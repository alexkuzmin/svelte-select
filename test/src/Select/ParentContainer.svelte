<script>
  import Select from '../../../src/Select.svelte';

  export let value;
  export let items;
</script>

<div class="container">
  <Select bind:value {items}></Select>

  <p class="result">{value.label}</p>
</div>
