<script>
    export let title = "Practice Fundamentals"
</script>

<div class="title">
    <img src="/joystick.svg" alt="site logo">
    <h1>{title}</h1>
</div>

<style>
   .title {
    display: flex;
   } 

   .title img {
    display: inline-block;
    filter: invert(99%) sepia(0%) saturate(0%) hue-rotate(264deg) brightness(106%) contrast(101%);
   }

   .title h1 {
    margin-left: 10px;
   }
</style>