/* Estilos gerais */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

header {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

header h1 {
  margin-bottom: 0.5rem;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  padding: 20px;
  text-align: center;
}

section {
  margin-bottom: 2rem;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 1rem;
}

/* Responsividade */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  header, footer, main {
    padding: 10px;
  }
}

@media (max-width: 480px) {
  h1 {
    font-size: 1.5rem;
  }

  nav ul li {
    margin: 10px 0;
  }
}
