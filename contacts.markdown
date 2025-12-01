---
layout: default
title: Contact Me
---

<style>
.contact-container {
  max-width: 500px;
  margin: 60px auto;
  padding: 30px;
  border-radius: 10px;
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  font-family: "Helvetica Neue", Arial, sans-serif;
}

.contact-container h1 {
  text-align: center;
  margin-bottom: 10px;
}

.contact-container p {
  text-align: center;
  font-size: 14px;
  color: #666;
}

.contact-container label {
  font-weight: 600;
  margin-top: 15px;
  display: block;
}

.contact-container input,
.contact-container textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  margin-top: 5px;
  border-radius: 5px;
  font-size: 15px;
}

.contact-container button {
  margin-top: 20px;
  width: 100%;
  padding: 12px;
  font-size: 16px;
  border: none;
  background: #333;
  color: white;
  border-radius: 5px;
  cursor: pointer;
}

.contact-container button:hover {
  background: #000;
}
</style>


<div class="contact-container">
  <h1>Contact Me</h1>
  <p>Have a project? Let's talk.</p>

  <form action="https://formspree.io/f/xkgnwjrv" method="POST">
    <label>Your Name</label>
    <input type="text" name="name" required>

    <label>Your Email</label>
    <input type="email" name="_replyto" required>

    <label>Your Message</label>
    <textarea name="message" rows="5" required></textarea>

    <button type="submit">Send Message</button>
  </form>
</div>
