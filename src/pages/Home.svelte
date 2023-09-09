<script lang="ts">
  import Counter from "../lib/Counter.svelte";
  import snorlax from "/images/snorlax.png";
  import { Link } from "svelte-routing";
  import Navbar from "@/components/Navbar.svelte";
</script>

<div class="flex justify-center place-content-center">
  <img src={snorlax} class="max-w-xs" alt="" />
</div>
<div class="flex flex-col justify-center items-center">
  <h1 class="font-bold text-2xl">SvelteTS + Tailwind</h1>
  <Link to="/about" class="text-blue-500 underline">About Page</Link>
  <Counter />
</div>
