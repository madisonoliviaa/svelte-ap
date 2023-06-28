<script>
  let name = "madison";
  import Component2 from "./component2.svelte";
</script>

<h1>Madisons first svelte component</h1>

<p class="links">Hello world!</p>

<div class="links">
  <a href="https://twitter.com/madisonoliviaa_">Link to my twitter</a>
</div>

<Component2 />

<style>
  :global(h1) {color: rebeccapurple; animation: zoom 30s infinite;}
  :global(p) { font-size: 44px; }
  .links {text-align: center;}
@keyframes -global-zoom {
  0%, 100% {transform: scale(3)}
  50% {transform: scale(0.5)}
}
  
</style>
