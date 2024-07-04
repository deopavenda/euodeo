<template>
  <section class="about-me"id="about">
    <div class="container">
      <h2>About Me</h2>
      <div class="about-content">
        <p>
          Hi, I have recently entered the world of technology with great enthusiasm to learn and grow. With a strong background, I feel challenged to delve deeper into the field of programming and master the technical skills required. I am very enthusiastic about learning programming and web design, as well as exploring new ways to deliver innovative solutions in the digital world.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutMe'
}
</script>

<style scoped>
.about-me {
  background-color: #f8f9fa;
  padding: 50px 0;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}

.about-me h2 {
  font-size: 2.5em;
  margin-bottom: 30px;
  color: #343a40;
}

.about-content {
  background-color: white;
  border-radius: 10px;
  padding: 30px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: left;
}

.about-content p {
  font-size: 1.2em;
  margin-bottom: 20px;
  color: #6c757d;
  line-height: 1.6;
}
</style>
