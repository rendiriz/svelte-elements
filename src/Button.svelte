<svelte:options tag="rrr-button" />

<script lang="typescript">
  export let name: string
</script>

<button>
  <slot />
</button>

<style lang="scss">
  button {
    display: inline-block;
    font-weight: $btn-font-weight;
    color: $body-color;
    text-align: center;
    background-color: transparent;
  }
</style>
