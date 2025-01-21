<template>
  <div class="contact">
    <h1>Contact Us</h1>

    <p>
      We’d love to hear from you! Whether you have questions, need advice, or want a free, no-obligation quote, feel free to get in touch with us.
    </p>

    <div class="contact-info">
      <p>📞 Call us today:</p>
      <ul>
        <li><a href="tel:07933491431">07933 491431</a></li>
        <li><a href="tel:07736749306">07736 749306</a></li>
      </ul>
    </div>

    <p>
      Alternatively, reach out to us via email or through our social media channels. We’re here to help!
    </p>
  </div>
</template>

<style>
.contact {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
}

.contact h1 {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
  color: #2c3e50;
}

.contact p {
  font-size: 1.2rem;
  margin-bottom: 1rem;
  color: #34495e;
}

.contact-info {
  font-size: 1.2rem;
  margin: 1rem 0;
}

.contact-info ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.contact-info li {
  margin: 0.5rem 0;
}

.contact-info a {
  color: #3498db;
  text-decoration: none;
  font-weight: bold;
}

.contact-info a:hover {
  text-decoration: underline;
  color: #2980b9;
}
</style>
