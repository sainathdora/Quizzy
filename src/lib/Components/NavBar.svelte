<!-- src/components/Navbar.svelte -->
<script>
    
  </script>
  
  <nav>
    <div class="logo">Quizzy</div>
    <div class="menu" class:open={menuOpen}>
      <a href="/">Home</a>
      <a href="/about">About</a>
      <a href="/contact">Contact</a>
    </div>
    <button >
      Attend Quiz
    </button>
  </nav>
  
  <style lang="scss">
    nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1rem;
      background-color: #333;
      color: white;
    }
  
    .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }
  
    .menu {
      display: flex;
      gap: 1rem;
    }
  
    .menu a {
      color: white;
      text-decoration: none;
    }
  
    button {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.4);
    cursor: pointer;
    border: 2px solid white;
    &:hover {
    background-color: #555;
  }
  }

  
  </style>
  