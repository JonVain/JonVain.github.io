<script lang="ts">
    import {
        Button,
        Card,
        CardBody,
        CardFooter,
        CardHeader,
        CardSubtitle,
        CardText,
        CardTitle,
    } from "sveltestrap";
    import { Figure, Image } from "sveltestrap";
    import { Spotify } from "sveltekit-embed";
</script>

<h1>Tervetuloa</h1>
<p>Blogisivustolle</p>
<h2>Poiminnat..</h2>

<Card class="mb-3">
    <CardHeader>
        <CardTitle>Tammikuu 2023...</CardTitle>
    </CardHeader>
    <CardBody>
        <CardSubtitle>PAKKASTA!</CardSubtitle>
        <CardText>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat,
            sed atque? Nostrum velit atque magnam? Eaque suscipit nulla ut.
            Voluptates animi provident vero minima architecto consequuntur
            adipisci iusto suscipit natus.
        </CardText>
    </CardBody>
</Card>
<br />
<Card class="mb-3">
    <CardHeader>
        <CardTitle>Joulukuu 2022</CardTitle>
    </CardHeader>
    <CardBody>
        <CardSubtitle>Hyvää joulua</CardSubtitle>
        <CardText>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat,
            sed atque? Nostrum velit atque magnam? Eaque suscipit nulla ut.
            Voluptates animi provident vero minima architecto consequuntur
            adipisci iusto suscipit natus.
            <Figure caption="Hyvää joulua">
                <a
                    href="https://images.pexels.com/photos/4067188/pexels-photo-4067188.jpeg?"
                >
                    <Image
                        fluid
                        alt="Landscape"
                        src="https://images.pexels.com/photos/4067188/pexels-photo-4067188.jpeg?"
                        class="d-block vh-100 vw-25"
                        style="max-width:100%;height:auto;"
                    /></a
                >
            </Figure>
        </CardText>
    </CardBody>
</Card>
<br />
<h2>Viimeksi kuunnelluimmat</h2>
<Spotify
    spotifyLink="track/1rYP6R16sM0uSlxrqzR5pM?si=6f7211c56a034bc2"
    width="50%"
    height="180px"
/>
<Spotify
    spotifyLink="track/0KJAVizRhvcLNd2f8QxhdI?si=06c8b351da1244ff"
    width="50%"
    height="180px"
/>

<style>
    h1,
    p {
        text-align: center;
    }
</style>
