<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
  <style>
    /* Styles are the same as the previous example */
  </style>
</head>
<body>
  <div class="loading-screen">
    <div class="loading-spinner"></div>
  </div>

  <?php
    // Check if the user is logged in
    session_start();
    if (isset($_SESSION['username'])) {
      // Display the main screen
      echo '
        <div class="main-screen visible">
          <h1>Welcome to the Main Screen</h1>
          <p>You have successfully logged in or registered!</p>
        </div>
      ';
    } else {
      // Display the login or registration screen
      if (isset($_GET['action']) && $_GET['action'] === 'register') {
        // Display the registration screen
        echo '
          <div class="registration-screen">
            <div class="registration-form">
              <h2>Register</h2>
              <form method="post" action="index.php?action=register">
                <input type="text" id="reg-username" name="reg-username" placeholder="Username" required>
                <input type="email" id="reg-email" name="reg-email" placeholder="Email" required>
                <input type="password" id="reg-password" name="reg-password" placeholder="Password" required>
                <button type="submit">Register</button>
                <p>Already have an account? <a href="index.php">Login</a></p>
              </form>
            </div>
          </div>
        ';

        // Process the registration form
        if ($_SERVER['REQUEST_METHOD'] === 'POST') {
          $username = $_POST['reg-username'];
          $email = $_POST['reg-email'];
          $password = $_POST['reg-password'];

          // Here, you can add your registration logic, such as saving the user to a database
          echo "Registering user: $username, $email, $password";

          // Set the session and redirect to the main screen
          $_SESSION['username'] = $username;
          header('Location: index.php');
          exit;
        }
      } else {
        // Display the login screen
        echo '
          <div class="login-screen">
            <div class="login-form">
              <h2>Login</h2>
              <form method="post" action="index.php">
                <input type="text" id="username" name="username" placeholder="Username" required>
                <input type="password" id="password" name="password" placeholder="Password" required>
                <button type="submit">Login</button>
                <p>Don't have an account? <a href="index.php?action=register">Register</a></p>
              </form>
            </div>
          </div>
        ';

        // Process the login form
        if ($_SERVER['REQUEST_METHOD'] === 'POST') {
          $username = $_POST['username'];
          $password = $_POST['password'];

          // Here, you can add your login logic, such as checking against a database
          if ($username === 'admin' && $password === 'password') {
            // Set the session and redirect to the main screen
            $_SESSION['username'] = $username;
            header('Location: index.php');
            exit;
          } else {
            echo "Invalid username or password";
          }
        }
      }
    }
  ?>

  <script>
    // Loading Screen
    window.addEventListener('load', () => {
      const loadingScreen = document.querySelector('.loading-screen');
      loadingScreen.classList.add('hidden');
    });
  </script>
</body>
</html>
