// Basic Reset
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

// Body
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

// Header
header {
  background: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

header h1 {
  margin: 0;
}

// Hero Section
.hero {
  background: #f4f4f4;
  padding: 2rem;
  text-align: center;
}

.hero h1 {
  margin-bottom: 0.5rem;
}

// Posts
.posts {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.posts article {
  margin-bottom: 1.5rem;
  max-width: 600px;
  width: 100%;
}

.posts h2 a {
  color: #007bff;
  text-decoration: none;
}

.posts h2 a:hover {
  text-decoration: underline;
}

// Footer
footer {
  background: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
}
