<script>
    import { base } from "$app/paths";
</script>
<section class="hero">
    <div class="hero__left">
        <h1 class="hero__left__title">Calm stays in a warm countryside setting</h1>
        <p class="hero__left__bio">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores accusantium obcaecati adipisci 
            debitis nihil nam totam cumque ipsa pariatur libero!
        </p>
        <div class="hero__left__actions">
            <a href="{base}/" class="btn btn-primary">Book a stay</a>
            <a href="{base}/" class="btn btn-secondary">Discover the place</a>
        </div>
    </div>
    <div class="hero__right">
        <div class="hero__right__image-container">
            <img
                class="hero__right__image-container__image"
                src="{base}/les-gites-de-la-robertie.png" 
                alt="les gites de la robertie"
            />
            <div class="hero__right__image-container__badge">Visit and relax.</div>
        </div>
    </div>
</section>
<section class="section">
    <div class="section__title-container">
        <h2 class="section__title-container__title">What are important aspects of this cottage?</h2>
        <p class="section__title-container__bio">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt pariatur, id ex sint eum assumenda.
        </p>
    </div>
    <div class="section__cards">
        <article class="section__cards__card">
            <h3>Aspect 1</h3>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt pariatur, id ex sint eum assumenda.
            </p>
        </article>
        <article class="section__cards__card">
            <h3>Aspect 2</h3>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt pariatur, id ex sint eum assumenda.
            </p>
        </article>
        <article class="section__cards__card">
            <h3>Aspect 3</h3>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt pariatur, id ex sint eum assumenda.
            </p>
        </article>
    </div>
    <div class="cta">
        <div class="cta__text-container">
            <h3 class="cta__text-container__title">Feeling interested? Read more.</h3>
            <p class="cta__text-container__bio">
                All the information you need will be here documented so you can read all about it.
            </p>
        </div>
        <a href="{base}/" class="btn btn-secondary">View details</a>
    </div>
</section>