# contact
contact.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Ticketing System</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="events.html">Events</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="book-tickets.html">Book Tickets</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact-form">
    <h2>Contact Us</h2>
    <p>If you have any questions or need assistance, feel free to reach out to us!</p>

    <form id="contact-form" action="#">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Event Ticketing System. All rights reserved.</p>
  </footer>
</body>
</html>
