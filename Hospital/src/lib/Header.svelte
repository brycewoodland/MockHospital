<script>
  export const title = 'Evercare Medical Center';
</script>

<header>
  <h1>{title}</h1>
  <nav>
    <img src="#" alt="logo">
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/about">About</a></li>
      <li><a href="/services">Services</a></li>
      <li><a href="/contact">Contact</a></li>
    </ul>
  </nav>
</header>

<style>
  header {
    box-sizing: border-box;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0,0,0,0.2);
  }
  nav ul {
    list-style-type: none;
    padding: 0;
  }
  nav ul li {
    display: inline;
    margin: 0 10px;
  }
  nav ul li a {
    text-decoration: none;
    color: #007bff;
  }
  nav ul li a:hover {
    text-decoration: underline;
  }
  h1 {
    color: #007bff;
    font-size: 2em;
  }
</style>

  
  





