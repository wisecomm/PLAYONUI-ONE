<script lang="ts">
  export let addClass: string
  export let label: string; // Button text
</script>

<!-- Button Class based on props -->
<button class={`btn ${addClass ? `${addClass}` : ''} `}>
  {label}
</button>
