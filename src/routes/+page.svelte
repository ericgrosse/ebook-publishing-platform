<div class="main">
  <header>
    <div class="container header-content">
      <h1>Ebook Publishing Platform</h1>
      <div class="sign-in">
        <a href="#">Sign In</a>
        <a href="#">Log Out</a>
      </div>
    </div>
  </header>

  <section class="auth-panel">
    <div class="container">
      <h2>Sign in with:</h2>
      <div class="auth-buttons">
        <button class="auth-google">Sign in with Google</button>
        <button class="auth-facebook">Sign in with Facebook</button>
        <button class="auth-twitter">Sign in with Twitter</button>
      </div>
    </div>
  </section>

  <section class="main-content">
    <div class="container">
      <!-- Main content goes here -->
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2023 Eric Grossé</p>
    </div>
  </footer>
</div>

<style>
  /* Set the display property of the main container to flex */
  .main {
    display: flex;
    flex-direction: column;
  }

  /* Set the display property of the auth-buttons container to flex */
  .auth-buttons {
    display: flex;
    flex-direction: column;
    gap: 16px;
  }

  /* Style the buttons using Material UI */
  button {
    color: white;
    background-color: #1976d2;
    border-radius: 4px;
    padding: 12px 24px;
    border: none;
    cursor: pointer;
    font-weight: 600;
  }

  /* Set the margin and padding of the container */
  .container {
    padding: 0 24px;
  }

  .header-content {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
  }

  /* Style the header */
  header {
    background-color: #f5f5f5;
    padding: 16px;
  }

  header h1 {
    margin: 0;
    font-size: 24px;
  }

  /* Style the sign-in container */
  .sign-in {
    display: flex;
    gap: 4px;
  }

  .sign-in a {
    color: #1976d2;
    font-weight: 600;
    text-decoration: none;
  }

  .sign-in a:hover {
    text-decoration: underline;
  }

  /* Style the main content */
  .main-content {
    flex: 1;
    padding: 16px;
  }

  /* Style the footer */
  footer {
    background-color: #f5f5f5;
    padding: 16px;
    margin-top: auto;
  }
</style>