<template>

    <div class="language">
        <a href="#" class="mb2">
            <img class="language_image" src="https://pbs.twimg.com/profile_images/683949209050046464/-MWyJCb1.png" alt="">
        </a>

        <p class="language_name mb2">Elixir</p>

        <div class="language_description">
            <p> Elixir is a dynamic, functional language designed for building scalable and maintainable applications.</p>
            <p> Elixir leverages the Erlang VM, known for running low-latency, distributed and fault-tolerant systems, while also being successfully used in web development and the embedded software domain.</p>
            <hr />
            <p class="language_more">READ MORE...</p>
        </div>
    </div>
    
</template>

<script>
export default {}
</script>

<style scoped>

.language {
    max-width: 200px;
    border: 20px solid darkcyan;
    padding: 16px;
    border-radius: 3px;
    box-shadow: 1px 2px 3px #bdddbd;
    text-align: center;
}

.language_image {
    width: 100px;
    height: 100px;
}

.language_name {
    font-size: 40px;
    color: rgb(163, 90, 125);
}

.language_description {
    font-size: 12px;
    color: #4f4f4f;
}

.language_more {
    color: orange;
}

.mb2 {
    margin-bottom: 16px;
}

hr {
    border: 1px groove rgb(211, 211, 211);
}

</style>