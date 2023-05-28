<script>
  import { Router, Route } from "svelte-routing";
  import Home from "./pages/Home.svelte";
  import NotFound from "./pages/NotFound.svelte";
</script>

<Router>
  <Route path="/" component={Home} />
  <Route component={NotFound} />
</Router>
