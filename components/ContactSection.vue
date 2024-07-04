<template>
  <section class="contact" id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <div class="contact-form">
        <h3>Send Me a Message</h3>
        <form>
          <div class="form-group">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>
          </div>
          <div class="form-group">
            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>
          </div>
          <div class="form-group">
            <label for="message">Your Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
          </div>
          <button type="submit" class="btn">Send</button>
        </form>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 50px 0;
  text-align: center;
}

.contact h2 {
  font-size: 2.5em;
  margin-bottom: 30px;
  color: #343a40;
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

.contact-form {
  background: #f8f9fa;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.contact-form h3 {
  font-size: 1.8em;
  margin-bottom: 20px;
  color: #343a40;
}

.form-group {
  margin-bottom: 20px;
}

.form-group label {
  font-size: 1.2em;
  display: block;
  margin-bottom: 5px;
  color: #495057;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 10px;
  font-size: 1em;
  border: 1px solid #ced4da;
  border-radius: 5px;
}

.form-group textarea {
  resize: vertical;
}

.btn {
  background-color: #007bff;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 1.2em;
  cursor: pointer;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #0056b3;
}
</style>
