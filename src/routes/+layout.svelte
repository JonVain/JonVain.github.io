<script>
    import pico from "@picocss/pico";
    import { base } from "$app/paths";
</script>

<nav class="layout">
    <li>
        <a prefetch href="{base}/">Etusivu</a>
    </li>
    <li>
        <a prefetch href="{base}/gallery">Galleria</a>
    </li>
    <li>
        <a prefetch href="{base}/music">Musiikki</a>
    </li>
    <li>
        <a prefetch href="{base}/stories">Tarinat</a>
    </li>
    <li>
        <a prefetch href="{base}/contact">Yhteystiedot</a>
    </li>
</nav>

<main>
    <slot />
</main>

<footer class="layout">
    <div class="social-links">
        <div class="row">
            <div class="small-6 medium-3 columns text-center mobile-stack">
                <a href="https://www.facebook.com/"
                    ><i class="fa fa-facebook" aria-hidden="true" />Facebook</a
                >
            </div>
            <div class="small-6 medium-3 columns text-center mobile-stack">
                <a href="https://www.instagram.com/?hl=en"
                    ><i
                        class="fa fa-instagram"
                        aria-hidden="true"
                    />Instagram</a
                >
            </div>
            <div class="small-6 medium-3 columns text-center mobile-stack">
                <a href="https://www.pinterest.com/"
                    ><i
                        class="fa fa-pinterest-p"
                        aria-hidden="true"
                    />Pinterest</a
                >
            </div>
            <div class="small-6 medium-3 columns text-center mobile-stack">
                <a href="https://twitter.com/?lang=en"
                    ><i class="fa fa-twitter" aria-hidden="true" />Twitter</a
                >
            </div>
        </div>
    </div>
</footer>

<style>
    nav {
        background: rgba(0, 0, 0, 0.4);
        padding-top: 1rem;
        padding-bottom: 1rem;
    }

    nav,
    footer {
        text-transform: uppercase;
        font-size: 0.7rem;
        letter-spacing: 0.1px;
        font-weight: 500;
    }

    :global(html) {
        background: rgb(20, 20, 40);
        /* scrollbar-gutter: stable; */
        overflow-y: scroll;
    }

    :global(.layout) {
        --width: 700px;
        padding-left: max(1rem, calc(calc(100vw - var(--width)) / 2));
        padding-right: max(1rem, calc(calc(100vw - var(--width)) / 2));
    }

    main {
        margin-bottom: 5rem;
        margin-top: 5vw;
    }

    footer {
        text-align: center;
        margin: 3rem 0;
        color: rgba(255, 255, 255, 0.4);
    }
</style>
