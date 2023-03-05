<script lang="ts">
    import {
        Carousel,
        CarouselControl,
        CarouselIndicators,
        CarouselItem,
        Styles,
    } from "sveltestrap";

    const items = [
        "https://images.pexels.com/photos/2607544/pexels-photo-2607544.jpeg?",
        "https://images.pexels.com/photos/11560540/pexels-photo-11560540.jpeg?",
        "https://images.pexels.com/photos/5072405/pexels-photo-5072405.jpeg?",
        "https://images.pexels.com/photos/2215380/pexels-photo-2215380.jpeg?",
        "https://images.pexels.com/photos/3140204/pexels-photo-3140204.jpeg?",
        "https://images.pexels.com/photos/1870376/pexels-photo-1870376.jpeg?",
        "https://images.pexels.com/photos/1693095/pexels-photo-1693095.jpeg?",
    ];
    let activeIndex = 0;
</script>

<h1>Galleria</h1>

<Carousel {items} bind:activeIndex>
    <CarouselIndicators bind:activeIndex {items} />

    <div class="carousel-inner">
        {#each items as item, index}
            <CarouselItem bind:activeIndex itemIndex={index}>
                <img
                    src={item}
                    class="d-block vh-100 vw-100"
                    alt={`${item} ${index + 1}`}
                    style="max-width:100%;height:auto;"
                />
            </CarouselItem>
        {/each}
    </div>

    <CarouselControl direction="prev" bind:activeIndex {items} />
    <CarouselControl direction="next" bind:activeIndex {items} />
</Carousel>

<style>
    h1 {
        text-align: center;
    }
</style>
