# Sowndaryam-Collections-
Welcome to Sowndaryam Collections 
/* File: style.css */

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fdfcfb;
  color: #333;
}

header {
  background-color: #b89d62;
  padding: 1rem;
  text-align: center;
  color: white;
}

nav a {
  margin: 0 10px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 2rem;
  background-color: #f1e9da;
}

.hero h2 {
  font-size: 2rem;
}

.btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 10px 20px;
  background-color: #a4753b;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

footer {
  background-color: #b89d62;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

section {
  padding: 2rem;
}

.checkout-form label,
.checkout-form input,
.checkout-form textarea,
.checkout-form select {
  display: block;
  width: 100%;
  max-width: 500px;
  margin: 10px auto;
}

.checkout-form button {
  display: block;
  margin: 20px auto;
  padding: 10px 30px;
  background-color: #a4753b;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
}

.product-detail {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  align-items: center;
  justify-content: center;
}

.product-detail img {
  max-width: 300px;
  border-radius: 10px;
}

.product-info {
  max-width: 400px;
}

.product-info .price {
  font-size: 1.5rem;
  color: #a4753b;
  margin-bottom: 10px;
}

.product-info .btn {
  margin-top: 1rem;
}

@media (max-width: 600px) {
  .product-detail {
    flex-direction: column;
  }
}
