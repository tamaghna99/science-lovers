<!-- Full Multi-Page Website: Science Lovers -->

<!-- ========== index.html (HOME PAGE) ========== -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Science Lovers - Home</title>
  <style>
    body { font-family: Arial; margin: 0; padding: 0; background: #f2f2f2; }
    header { background: #222; color: white; padding: 15px; display: flex; justify-content: space-between; align-items: center; }
    header a { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; }
    .hero { text-align: center; padding: 40px; background: #4CAF50; color: white; }
    .content { padding: 20px; font-size: 20px; }
  </style>
</head>
<body>
  <header>
    <div>SCIENCE LOVERS</div>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="worksheets.html">Worksheets</a>
      <a href="mocktests.html">Mock Tests</a>
      <a href="contact.html">Contact</a>
      <a href="register.html">Register</a>
      <a href="login.html">Login</a>
    </nav>
  </header>
  <div class="hero">
    <h1>Welcome to Science Lovers</h1>
    <p>Learn science in a different way. Learn by your reflection, but advanced!</p>
  </div>
</body>
</html>


<!-- ========== about.html ========== -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>About - Science Lovers</title>
  <style> body { font-family: Arial; padding: 20px; } </style>
</head>
<body>
  <h1>About Me</h1>
  <p>I am a science student, <b>Tamaghna Bhattacharya</b>, advanced in science but still reading in school.</p>
  <p>What made me advanced?</p>
  <ul>
    <li>VVM (Vidyarthi Vigyan Manthan) Level 2 Passed</li>
    <li>Participated in IMO</li>
    <li>SPACE-E-FIC participant</li>
  </ul>
  <p>Don't hesitate to contact or ask something!</p>
  <p><b>Email:</b> tamaghnabhattacharya013@gmail.com</p>
  <p><b>Phone:</b> 6289443697</p>
</body>
</html>


<!-- ========== contact.html ========== -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Contact - Science Lovers</title>
  <style> body { font-family: Arial; padding: 20px; } </style>
</head>
<body>
  <h1>Contact</h1>
  <p>Phone: 6289443697</p>
  <p>Email: tamaghnahattacharya@gmail.com</p>
</body>
</html>


<!-- ========== worksheets.html ========== -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Worksheets</title>
</head>
<body>
  <h1>Worksheets</h1>
  <p>Coming soon...</p>
</body>
</html>


<!-- ========== mocktests.html ========== -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Mock Tests</title>
  <style> body { font-family: Arial; padding: 20px; } </style>
</head>
<body>
  <h1>Mock Tests</h1>
  <h2>Select Your Class</h2>
  <ul>
    <li><a href="mocktest6.html">Class 6 Mock Tests</a></li>
    <li><a href="mocktest7.html">Class 7 Mock Tests</a></li>
    <li><a href="mocktest8.html">Class 8 Mock Tests</a></li>
  </ul>
</body>
</html>


<!-- ========== mocktest6.html ========== -->
<!DOCTYPE html>
<html><head><meta charset="UTF-8"><title>Class 6 Mock Test</title></head>
<body>
  <h1>Class 6 Mock Test</h1>
  <p>Download File:</p>
  <a href="class6_test.pdf" download>Click to Download Class 6 Mock Test</a>
</body></html>


<!-- ========== mocktest7.html ========== -->
<!DOCTYPE html>
<html><head><meta charset="UTF-8"><title>Class 7 Mock Test</title></head>
<body>
  <h1>Class 7 Mock Test</h1>
  <a href="class7_test.pdf" download>Download Class 7 Test</a>
</body></html>


<!-- ========== mocktest8.html ========== -->
<!DOCTYPE html>
<html><head><meta charset="UTF-8"><title>Class 8 Mock Test</title></head>
<body>
  <h1>Class 8 Mock Test</h1>
  <a href="class8_test.pdf" download>Download Class 8 Test</a>
</body></html>


<!-- ========== register.html ========== -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Register</title>
  <style> body { font-family: Arial; padding: 20px; } input { display: block; margin: 10px 0; padding: 8px; }</style>
</head>
<body>
  <h1>Register</h1>
  <form action="payment.html">
    <input type="text" placeholder="Full Name" required>
    <input type="email" placeholder="Email" required>
    <input type="number" placeholder="Phone" required>
    <button type="submit">Next Step</button>
  </form>
</body>
</html>


<!-- ========== payment.html ========== -->
<!DOCTYPE html>
<html>
<head><meta charset="UTF-8"><title>Payment</title></head>
<body>
  <h1>Payment Step</h1>
  <p>After payment you will be automatically registered.</p>
  <a href="registered.html">Simulate Payment</a>
</body>
</html>


<!-- ========== registered.html ========== -->
<!DOCTYPE html>
<html>
<head><meta charset="UTF-8"><title>Registered</title></head>
<body>
  <h1>You Are Successfully Registered!</h1>
  <p>Your class timings will appear after login.</p>
</body>
</html>


<!-- ========== login.html ========== -->
<!DOCTYPE html>
<html>
<head><meta charset="UTF-8"><title>Login</title></head>
<body>
  <h1>Login</h1>
  <input placeholder="Email">
  <input placeholder="Password" type="password">
  <button>Login</button>
</body>
</html>
