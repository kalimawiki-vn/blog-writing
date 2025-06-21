---
title: "Liên Hệ"
date: ""
type: "page"
author: " "
showBreadCrumbs: false
showDate: false
showReadingTime: false
---

<style>
  .form-field {
    width: 100%;
    padding: 0.6rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    margin-bottom: 1rem;
    font-size: 1rem;
  }
  .form-button {
    background-color: #007bff;
    color: white;
    padding: 0.6rem 1.2rem;
    border: none;
    border-radius: 4px;
    font-weight: bold;
    cursor: pointer;
  }
  .form-button:hover {
    background-color: #0056b3;
  }
</style>

<form action="https://formspree.io/f/mgvyyzqo" method="POST" style="max-width: 500px; margin-top: 1rem;">
  <label for="name">Tên:</label><br>
  <input type="text" name="Tên" required class="form-field"><br>

  <label for="email">Email:</label><br>
  <input type="email" name="_replyto" required class="form-field"><br>

  <label for="message">Nội dung:</label><br>
  <textarea name="message" rows="5" required class="form-field"></textarea><br>

  <button type="Gửi thông tin" class="form-button">Send</button>
</form>

