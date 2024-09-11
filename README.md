"dinky";

// Basic Reset
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

// Body
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

// Header
header {
  background: #004d99;
  color: #fff;
  padding: 1rem 2rem;
  text-align: center;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 1000;
}

header h1 {
  margin: 0;
  font-size: 2rem;
}

header nav ul {
  list-style: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 1rem;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

header nav ul li a:hover {
  text-decoration: underline;
}

// Hero Section
.hero {
  background: url('/assets/images/hero-background.jpg') no-repeat center center/cover;
  color: #fff;
  padding: 4rem 2rem;
  text-align: center;
  margin-top: 70px; // Adjust based on header height
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.hero p {
  font-size: 1.25rem;
}

// Main Content
main {
  padding: 2rem;
}

.posts {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.posts article {
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  margin-bottom: 2rem;
  padding: 1.5rem;
  max-width: 600px;
  width: 100%;
}

.posts h2 {
  margin-bottom: 0.5rem;
}

.posts a {
  color: #007bff;
  text-decoration: none;
}

.posts a:hover {
  text-decoration: underline;
}

// Footer
footer {
  background: #004d99;
  color: #fff;
  padding: 1rem 2rem;
  text-align: center;
}

footer p {
  margin: 0;
}

// Responsive Design
@media (max-width: 768px) {
  header {
    padding: 1rem;
  }

  .hero {
    padding: 2rem 1rem;
  }

  .posts {
    padding: 0 1rem;
  }
}
