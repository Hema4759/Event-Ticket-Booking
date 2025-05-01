# style sheet
styles.css:
/* Basic Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
  color: #333;
}

header {
  background-color: #333;
  color: white;
  padding: 1rem 0;
}

nav ul {
  list-style-type: none;
  text-align: center;
}

nav ul li {
  display: inline-block;
  margin: 0 1.5rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 2rem;
}

.hero {
  text-align: center;
  background-color: #4CAF50;
  color: white;
  padding: 3rem;
}

.hero h1 {
  font-size: 3rem;
}

.btn {
  display: inline-block;
  padding: 1rem 2rem;
  background-color: #4CAF50;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 1rem;
}

.btn:hover {
  background-color: #45a049;
}

.about {
  background-color: #fff;
  padding: 2rem;
  margin-top: 2rem;
}

.events-list {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  margin-top: 2rem;
}

.event {
  background-color: white;
  padding: 1rem;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  width: 30%;
  text-align: center;
}

.contact-form form,
.booking-form form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

input, select, textarea {
  padding: 0.75rem;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 1rem;
  background-color: #4CAF50;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: white;
  position: fixed;
  width: 100%;
  bottom: 0;
}
