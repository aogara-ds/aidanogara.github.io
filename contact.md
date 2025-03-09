---
layout: page
title: Contact
permalink: /contact/
---

Feel free to reach out to me through any of the following channels:

- **Email:** [example@email.com](mailto:example@email.com)
- **GitHub:** [github.com/aidanogara](https://github.com/aidanogara)
- **LinkedIn:** [linkedin.com/in/aidanogara](https://linkedin.com/in/aidanogara)

Or use the form below to send me a message:

<form action="#" method="post" class="contact-form">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required>
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" required>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>
  <button type="submit">Send Message</button>
</form>

<style>
  .contact-form {
    max-width: 600px;
    margin: 2rem 0;
  }
  
  .form-group {
    margin-bottom: 1.5rem;
  }
  
  label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: bold;
  }
  
  input, textarea {
    width: 100%;
    padding: 0.5rem;
    font-family: inherit;
    font-size: 1rem;
    border: 1px solid #ddd;
    border-radius: 4px;
  }
  
  button {
    background-color: #555;
    color: white;
    border: none;
    padding: 0.75rem 1.5rem;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 4px;
    transition: background-color 0.3s ease;
  }
  
  button:hover {
    background-color: #333;
  }
</style>