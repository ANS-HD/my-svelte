<script>
  import TailwindCss from './TailwindCSS.svelte';

  let name = '雷猴'

  function handleClick() {
    name = '鲨鱼辣椒'
  }
</script>
<TailwindCss />

<div class="bg-red-400">Hello {name}</div>
<button class="bg-gray" on:click={handleClick}>改名</button>
<span class="ml-3 text-red-500">ABC Company</span>

