<template>
    <section id="customers">
        <article class="safety">
            <h1>Your personal safety net online.</h1>
            <button>Join now</button>
        </article>
        <article class="info">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur animi nulla distinctio obcaecati, harum quas aliquam, amet, beatae aperiam fugiat deleniti tempora. Praesentium, ex excepturi. Nisi perferendis voluptate enim libero.</p>
        </article>
        <footer>
            <article class="card">Card 1</article>
            <article class="card">Card 2</article>
            <article class="card">Card 3</article>
        </footer>
    </section>
</template>
<script>
export default {
    name: 'Customers'
}
</script>
<style lang="scss">
@import './../assets/scss/variables';

#customers {
    background: $grey;

    footer {
        display: flex;
        justify-content: center;

        .card {
            max-width: 14rem;
            width: 100%;
            height: $baseline * 4;
            background: $white;
            border-radius: $round;
            margin: 1rem;
            box-shadow: 0 0 2rem rgba(0,0,0,.2);
            transform: translateY( ($baseline * 3) / 2 );
        }

    }

}

</style>
