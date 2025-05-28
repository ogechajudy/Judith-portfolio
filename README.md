body {
  font-family: sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

header {
  background: #333;
  color: white;
  padding: 2rem;
  text-align: center;
}

section {
  padding: 2rem;
  max-width: 800px;
  margin: 0 auto;
}

.project-card {
  background: white;
  padding: 1rem;
  margin-bottom: 1rem;
  border-left: 5px solid #0077cc;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.project-card a {
  color: #0077cc;
  text-decoration: none;
  font-weight: bold;
}

.project-card a:hover {
  text-decoration: underline;
}

#skills ul {
  list-style: square;
  padding-left: 2rem;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  body {
    padding: 1rem;
  }

  .project-card {
    margin-bottom: 1.5rem;
  }

  header, footer {
    text-align: center;
  }
}
