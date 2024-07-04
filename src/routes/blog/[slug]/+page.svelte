<script lang="ts">
    export let data;
</script>

<div>
  {#each data.content as { id, quantity } (id)}
    <div>{id} - {quantity}</div>
  {/each}
</div>