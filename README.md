# codsoft
here is my all code of web devlopment intern in this repo
Landing Page 
Task 1 Codsoft Internship
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Landing Page</title>
  <style>
    /* Reset default styles */
    body, h1, p, ul, li {
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f9f9f9;
    }

    /* Header styles */
    header {
      background-color: #3498db;
      color: white;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 36px;
    }

    /* Main content styles */
    main {
      padding: 40px;
    }

    .hero-section {
      text-align: center;
      padding: 80px 20px;
      background-color: #f1c40f;
      color: #333;
    }

    .hero-section h2 {
      font-size: 32px;
    }

    .hero-section p {
      font-size: 18px;
    }

    /* Features section styles */
    .features-section {
      display: flex;
      justify-content: space-around;
      padding: 40px 0;
    }

    .feature {
      text-align: center;
      max-width: 300px;
      padding: 20px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    .feature h3 {
      font-size: 24px;
    }

    .feature p {
      font-size: 16px;
    }

    /* Call-to-action styles */
    .cta-section {
      text-align: center;
      padding: 40px 0;
    }

    .cta-button {
      display: inline-block;
      padding: 15px 30px;
      background-color: #3498db;
      color: white;
      font-size: 18px;
      text-decoration: none;
      border-radius: 5px;
    }

    /* Footer styles */
    footer {
      text-align: center;
      padding: 20px;
      background-color: #222;
      color: white;
    }

    footer a {
      color: white;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Landing Page</h1>
  </header>

  <main>
    <section class="hero-section">
      <h2>Welcome to My Website</h2>
      <p>Discover amazing products and services that will make your life better.</p>
    </section>

    <section class="features-section">
        <div class="feature">
          <h3>Feature 1: Personalized Recommendations</h3>
          <p>Receive personalized product recommendations based on your preferences and interests. Our smart algorithm ensures you get exactly what you need.</p>
        </div>
        <div class="feature">
          <h3>Feature 2: Seamless Integration</h3>
          <p>Enjoy a seamless experience with our services that effortlessly integrate with your existing tools and systems. No technical expertise required!</p>
        </div>
        <div class="feature">
          <h3>Feature 3: 24/7 Customer Support</h3>
          <p>Rest assured, our dedicated customer support team is available 24/7 to assist you with any questions or issues you may have. Your satisfaction is our priority!</p>
        </div>
      </section>

    <section class="cta-section">
      <a href="#" class="cta-button">Get Started</a>
    </section>
  </main>

  <footer>
    <p>Contact us at: <a href="mailto:contact@mylandingpage.com">contact@mylandingpage.com</a></p>
  </footer>
</body>
</html>
