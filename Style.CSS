/* style.css */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

:root {
  --bg-color: #121212;
  --primary-color: #00bcd4;
  --text-color: #ffffff;
  --accent-color: #1f1f1f;
  --shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  scroll-behavior: smooth;
}

body {
  background-color: var(--bg-color);
  color: var(--text-color);
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 2rem 0;
}

.nav {
  background: var(--accent-color);
  padding: 1rem 0;
  box-shadow: var(--shadow);
  position: sticky;
  top: 0;
  z-index: 100;
}

.nav .logo {
  font-size: 1.5rem;
  font-weight: 600;
  color: var(--primary-color);
}

.nav .nav-links {
  list-style: none;
  display: flex;
  gap: 2rem;
  justify-content: flex-end;
}

.nav .nav-links li a {
  color: var(--text-color);
  text-decoration: none;
  transition: color 0.3s;
}

.nav .nav-links li a:hover {
  color: var(--primary-color);
}

.section {
  padding: 4rem 0;
}

.hero {
  text-align: center;
  padding: 6rem 0 4rem;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: var(--primary-color);
}

.btn {
  display: inline-block;
  background: var(--primary-color);
  color: var(--text-color);
  padding: 0.75rem 1.5rem;
  border: none;
  border-radius: 5px;
  margin-top: 1rem;
  text-decoration: none;
  transition: background 0.3s;
}

.btn:hover {
  background: #0097a7;
}

.projects .project-list {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

.project {
  background: var(--accent-color);
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: var(--shadow);
  transition: transform 0.3s;
}

.project:hover {
  transform: translateY(-5px);
}

.contact form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 500px;
  margin: auto;
}

.contact input,
.contact textarea {
  padding: 0.75rem;
  background: #1c1c1c;
  border: none;
  border-radius: 5px;
  color: var(--text-color);
}

.footer {
  background: #1c1c1c;
  text-align: center;
  padding: 2rem 0;
  margin-top: 4rem;
  color: #aaa;
}

.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeIn 1s ease-out forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
    transform: none;
  }
}

@media (max-width: 768px) {
  .nav .nav-links {
    flex-direction: column;
    align-items: center;
  }
  .hero h2 {
    font-size: 2rem;
  }
}
