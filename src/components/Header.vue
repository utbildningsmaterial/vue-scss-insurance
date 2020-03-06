<template>
    <header id="header">
        <section class="hello">
            <h1>Weve got you covered!</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam molestiae ipsa quo expedita earum eligendi voluptate impedit nobis vitae, atque deleniti voluptatem voluptatum aliquam consequatur harum natus consectetur, ex hic?</p>
            <button>Join now</button>
        </section>
        <section class="learn">
            <p class="argument">What do we have to offer?</p>
            <h2>Learn more</h2>
        </section>
        <section class="join">
            <p class="argument">What are you waiting for?</p>
            <h2>Join today</h2>
        </section>
    </header>    
</template>
<script>
export default {
    name: 'Header'
}
</script>
<style lang="scss" >
@import './../assets/scss/variables';

#header {

    .argument {
        font-size: .8rem;
        margin: 0;
        opacity: .8;
    } 

    .hello {
        background: $blue;
        @extend %center;
        padding: 2rem;

        h1, p {
            max-width: 20rem;
        }

    }

    .learn {
        background: $orange;
        @extend %center;
    }

    .join { 
        background: $yellow;
        @extend %center;
  }
}

</style>