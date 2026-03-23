<script>
import Router from "svelte-spa-router";

import Loading from "./lib/Loading.svelte";
import LoginEmailPage from "./lib/LoginEmailPage.svelte";

const routes = {
  "/": Loading,
  "/login": LoginEmailPage,
};
</script>

<Router {routes} />