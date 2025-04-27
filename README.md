<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Maison Gourmet | Your Kitchen, My Passion</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #333;
      height: 100%;
    }
    header {
      background: url('https://images.unsplash.com/photo-1556910103-1e15f3fdd40b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 56px;
      margin-bottom: 15px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
    }
    header p {
      font-size: 24px;
      margin-top: 0;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.6);
    }
    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
      background: #fff;
    }
    h2 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #b8895a;
    }
    p {
      font-size: 18px;
      line-height: 1.6;
    }
    form {
      display: flex;
      flex-direction: column;
      margin-top: 30px;
    }
    input, textarea {
      margin-bottom: 20px;
      padding: 14px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }
    button {
      padding: 15px;
      font-size: 18px;
      background-color: #b8895a;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #9c6d44;
    }
    .contact-details {
      margin-top: 30px;
      font-size: 18px;
      color: #555;
    }
    .contact-details p {
      margin: 8px 0;
    }
    .contact-details a {
      color: #b8895a;
      text-decoration: none;
    }
    .contact-details a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #eee;
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>

<header>
  <h1>Maison Gourmet</h1>
  <p>Your kitchen, my passion.</p>
</header>

<section>
  <h2>About Me</h2>
  <p>Welcome to Maison Gourmet — where exquisite dining meets the comfort of your own home. I am a passionate chef dedicated to crafting unforgettable meals tailored to your tastes. Whether it’s a romantic dinner, a lively gathering, or a special celebration, let me bring the luxury of fine dining right to your table.</p>
</section>

<section>
  <h2>Book or Contact Me</h2>
  <form action="mailto:stevebennettchef@yahoo.co.uk" method="POST" enctype="text/plain">
    <input type="text" name="Name" placeholder="Your Name" required>
    <input type="email" name="Email" placeholder="Your Email" required>
    <textarea name="Message" rows="5" placeholder="Tell me about your event..." required></textarea>
    <button type="submit">Send Message</button>
  </form>

  <div class="contact-details">
    <p><strong>Email:</strong> <a href="mailto:stevebennettchef@yahoo.co.uk">stevebennettchef@yahoo.co.uk</a></p>
    <p><strong>Phone:</strong> <a href="tel:07815483204">07815483204</a></p>
  </div>
</section>

<footer>
  &copy; 2025 Maison Gourmet. All rights reserved.
</footer>

</body>
</html
