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
</script>

<h1>Stories</h1>

<Card class="mb-3">
    <CardHeader>
        <CardTitle>Maaliskuu 2023</CardTitle>
    </CardHeader>
    <CardBody>
        <CardSubtitle>Hiihtoloma lähenee</CardSubtitle>
        <CardText>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat,
            sed atque? Nostrum velit atque magnam? Eaque suscipit nulla ut.
            Voluptates animi provident vero minima architecto consequuntur
            adipisci iusto suscipit natus.
        </CardText>
    </CardBody>
</Card>
<Card class="mb-3">
    <CardHeader>
        <CardTitle>Helmikuu 2023</CardTitle>
    </CardHeader>
    <CardBody>
        <CardSubtitle>Kallista sähköä!</CardSubtitle>
        <CardText>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat,
            sed atque? Nostrum velit atque magnam? Eaque suscipit nulla ut.
            Voluptates animi provident vero minima architecto consequuntur
            adipisci iusto suscipit natus.
        </CardText>
    </CardBody>
</Card>
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
                <Image
                    fluid
                    alt="Landscape"
                    src="https://images.pexels.com/photos/4067188/pexels-photo-4067188.jpeg?"
                    class="d-block vh-100 vw-25"
                    style="max-width:100%;height:auto;"
                />
            </Figure>
        </CardText>
    </CardBody>
</Card>
<Card class="mb-3">
    <CardHeader>
        <CardTitle>Syksy 2022</CardTitle>
    </CardHeader>
    <CardBody>
        <CardSubtitle>Lehdet putoaa</CardSubtitle>
        <CardText>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat,
            sed atque? Nostrum velit atque magnam? Eaque suscipit nulla ut.
            Voluptates animi provident vero minima architecto consequuntur
            adipisci iusto suscipit natus.
            <Figure caption="Synkkä syksy">
                <Image
                    fluid
                    alt="Landscape"
                    src="https://images.pexels.com/photos/1542857/pexels-photo-1542857.jpeg?"
                    class="d-block vh-100 vw-25"
                    style="max-width:100%;height:auto;"
                />
            </Figure>
        </CardText>
    </CardBody>
</Card>
