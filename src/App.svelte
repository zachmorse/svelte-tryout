<script>
  export let name;
</script>

<style>
  .tr {
    width: 100%;
    margin: auto;
    height: 100%;
    position: relative;
    /* border: 3px solid saddlebrown; */
    overflow: hidden;
  }

  .tr:before {
    content: "";
    position: absolute;
    top: 0;
    left: 20%;
    width: 100%;
    height: 100vh;
    background: #0079c6;
    transform-origin: 0 100%;
    transform: rotate(45deg);
  }
</style>

<div class="tr">
  <div class="interior" />
</div>
