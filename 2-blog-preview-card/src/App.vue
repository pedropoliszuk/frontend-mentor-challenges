<script setup></script>

<template>
  <div class="container">
    <article class="card">
      <img class="card__image" src="./images/illustration-article.svg" alt="Illustration Article" />
      <span class="card__tag">Learning</span>
      <time>Published 21 Dec 2023</time>
      <h2>HTML & CSS foundations</h2>
      <p>
        These languages are the backbone of every<br />website, defining structure, content, and<br />
        presentation.
      </p>
      <div class="card__footer">
        <img src="./images/image-avatar.webp" alt="Avatar" />
        <p>Greg Hooper</p>
      </div>
    </article>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100%;
}

.card {
  display: flex;
  flex-direction: column;
  background-color: hsl(0, 0%, 100%);
  border: 1px solid hsl(0, 0%, 7%);
  border-radius: 18px;
  font-family: 'Figtree', sans-serif;
  padding: 22px;
  gap: 16px;
  color: hsl(0, 0%, 7%);
  box-shadow: 8px 8px hsl(0, 0%, 7%);

  p {
    color: hsl(0, 0%, 42%);
    line-height: 22px;
    font-weight: 500;
  }

  time {
    font-size: 14px;
  }
}

.card__image {
  max-width: 100%;
  border-radius: 18px;
}

.card__tag {
  display: inline-block;
  padding: 6px 10px;
  background-color: hsl(47, 88%, 63%);
  font-weight: bold;
  border-radius: 4px;
  width: 84px;
}

.card__footer {
  display: flex;
  align-items: center;
  gap: 8px;

  img {
    width: 32px;
  }

  p {
    font-weight: bold;
    font-size: 14px;
    color: hsl(0, 0%, 7%);
  }
}
</style>
