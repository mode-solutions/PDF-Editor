<script>
  import Portal from "./Portal.svelte";
</script>

<Portal>
  <div class="fixed z-20 top-0 left-0 right-0 h-20">
    <slot />
  </div>
</Portal>
