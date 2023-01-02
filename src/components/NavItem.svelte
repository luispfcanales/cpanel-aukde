<script>
  import Fa from 'svelte-fa'
  export let uri = "";
  export let icon;
  export let size = 1.6
</script>

<div>
    <li>
      <a href="#/">
      <Fa 
        style={"min-width:80px;color:var(--icon-nav-light)"} 
        {icon} size={`${size}x`} />
      {uri}
      </a>
    </li>
</div>

<style>
  div,li{
    list-style:none;
    width:100%;
  }
  a {
    box-sizing:border-box;
    text-decoration:none;
    padding:1rem 0;
    color:var(--label-nav-light);
    width:100%;
    display: flex;
    font-weight:bold;
    font-size:1.2rem;
    transition:.5s;
  }

  a:hover{
    background-color:var(--hover-nav);
  }
</style>
