<script>
    export let src;
    export let caption;
</script>

<img src={src} alt={caption}>

<style>
    img {
        width: 18vw;
        height: 35vh;
        margin-bottom: 30px;
    }

    @media screen and (max-width: 725px) {
        img {
        width: 45vw;
        margin-bottom: 30px;
        }
    }
</style>