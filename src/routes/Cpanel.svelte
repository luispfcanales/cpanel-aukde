<script>
  import NavItem from "../components/NavItem.svelte"
  import {faUsers,faUser,faMicrochip,faBook} from "@fortawesome/free-solid-svg-icons"
</script>
<div>
  <div>
    <h1> cabecera</h1>
  <NavItem uri={"Usuarios"} icon={faUser}/>
  <NavItem uri={"Clientes"} icon={faUsers}/>
  <NavItem uri={"Dispositivos"} icon={faMicrochip}/>
  <NavItem uri={"Reportes"} icon={faBook}/>
  </div>
</div>


<style>
  div{
    width:100vw;
    height:100vh;
    background-color:var(--back-cpanel);
  }
  div div {
    max-width: 300px;
    background-color:var(--back1);
  }
</style>
