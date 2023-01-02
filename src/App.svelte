<script>
  import { Router , Route } from "svelte-routing"
  import Login from "./routes/Login.svelte"
  import Cpanel from "./routes/Cpanel.svelte"
</script>

<Router>
  <Route path="/" component={Login}/>
  <Route path="cpanel" component={Cpanel}/>
</Router>

<style>

:root{
  --color1:#35DB77;
  --color2:#2A169D;
  --color3:#3D23C1;
  --back1:#195F73;
  --back-cpanel:#f5f5f5;
  --icon-nav-light:#fff;
  --label-nav-light:#fff;
  --hover-nav:#6498A6;
}
</style>
