# intro-component-with-signup-form-main
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="css/style.css">
  
  <title>Frontend Mentor | Intro component with sign up form</title>
</head>
<body>
  <main>
    <div class="content">
      <h1>Learn to code by watching others</h1>
      <p>See how experienced developers solve problems in real-time. Watching scripted tutorials is great, 
  but understanding how developers think is invaluable.</p>
    </div>
    <div class="signup">
      <div class="signup__pricing">
        <p><strong>Try it free 7 days</strong> then $20/mo. thereafter</p>
      </div>
      <form action="#" class="signup__form">
        <input type="text" name="first-name" id="first-name" aria-label="First Name" placeholder="First Name" required>
        <input type="text" name="last-name" id="last-name" aria-label="Last Name" placeholder="Last Name" required>
        <input type="email" name="email" id="email" aria-label="Email Address" placeholder="Email Address" required>
        <input type="password" name="password" id="password" aria-label="Password" placeholder="Password" required>
        <input type="submit" value="Claim your free trial" aria-label="Submit">
        <span class="terms-notice">By clicking the button, you are agreeing to our <span>Terms and Services</span></span>
      </form>
    </div>
  </main>
  <footer>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="https://www.frontendmentor.io/profile/rngueco">Riyana Gueco</a>.
    </p>
  </footer>
</body>
<script src="js/validation.js"></script>
</html>
