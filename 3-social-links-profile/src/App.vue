<script setup></script>

<template>
  <div class="container">
    <article class="card">
      <img class="profile__img" src="./images/avatar-pedro.jpeg" alt="Pedro Poliszuk" />
      <h2>Pedro Poliszuk</h2>
      <h5 class="location">Sorocaba, São Paulo</h5>
      <p>"Desenvolvedor Front-end e cinéfilo."</p>
      <button class="social__links">
        <a href="https://github.com/pedropoliszuk" target="_blank">Github</a>
      </button>
      <button class="social__links">
        <a href="https://www.frontendmentor.io/profile/pedropoliszuk" target="_blank"
          >Frontend Mentor</a
        >
      </button>
      <button class="social__links">
        <a href="https://www.linkedin.com/in/pedropoliszuk/" target="_blank">LinkedIn</a>
      </button>
      <button class="social__links">
        <a href="https://www.instagram.com/pedro_poliszuk/" target="_blank">Instagram</a>
      </button>
    </article>
  </div>
  <footer>
    Challenge by
    <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded
    by <a href="#">Pedro Poliszuk</a>
  </footer>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', sans-serif;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100%;
  text-align: center;
}

.card {
  background-color: hsl(0, 0%, 12%);
  max-width: 360px;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  color: hsl(0, 0%, 100%);
  padding: 30px;
  border-radius: 12px;

  .location {
    margin-top: 16px;
  }

  p {
    margin: 30px 0;
    font-size: 14px;
  }
}

.profile__img {
  height: 160px;
  border-radius: 50%;
  margin: 20px;
}

.location {
  color: hsl(75, 94%, 57%);
}

.social__links {
  background-color: hsl(0, 0%, 20%);
  padding: 10px;
  width: 100%;
  border: none;
  color: hsl(0, 0%, 100%);
  font-weight: bold;
  border-radius: 8px;
  margin-bottom: 16px;
  cursor: pointer;
}

.social__links a {
  text-decoration: none;
  color: inherit;
}

.social__links a:visited {
  color: inherit;
}

.social__links a:hover,
.social__links a:focus {
  color: inherit;
  text-decoration: none;
}
</style>
