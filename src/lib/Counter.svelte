<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button
  on:click={increment}
  class="bg-gray-400 rounded-2xl p-2 focus:outline-purple-600 hover:border-purple-600"
>
  count is {count}
</button>
