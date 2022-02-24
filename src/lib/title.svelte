<script>
    export let title = "Ninja Gaming";
</script>

<div class="title">    
    <img src="/controller.svg" alt="site logo">
    <h2>{title}</h2>
</div>

<style>
    .title{
        display: flex;

    }

    .title img {
        display: inline-block;
        filter:invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%);
        width: 40px;
        padding: 10px;
    }

    .title h1{
        margin-left: 10px;
    }
</style>