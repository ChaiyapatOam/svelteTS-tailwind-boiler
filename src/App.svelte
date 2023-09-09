<script lang="ts">
  import { Route, Router } from "svelte-routing";
  import Home from "./pages/Home.svelte";
  import NotFound from "./components/NotFound.svelte";
  import About from "./pages/About.svelte";
  export let url = "";
</script>

<Router {url}>
  <main>
    <Route path="/" component={Home} />
    <Route path="/about" component={About} />
    <Route component={NotFound} />
  </main>
</Router>
