<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Plans</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Our Pricing Plans</h1>
        <p>Choose the best plan for your needs</p>
    </header>

    <div class="pricing-container">
        <div class="pricing-card">
            <h2>Basic</h2>
            <p class="price">$10 / month</p>
            <ul>
                <li>1 User</li>
                <li>Basic Support</li>
                <li>Access to Essential Features</li>
            </ul>
            <button class="checkout-btn">Checkout</button>
        </div>

        <div class="pricing-card advantage">
            <h2>Advantage</h2>
            <p class="price">$25 / month</p>
            <ul>
                <li>Up to 5 Users</li>
                <li>Priority Support</li>
                <li>All Essential Features</li>
                <li>Extra Features</li>
            </ul>
            <button class="checkout-btn">Checkout</button>
        </div>

        <div class="pricing-card amaze">
            <h2>Amaze</h2>
            <p class="price">$50 / month</p>
            <ul>
                <li>Unlimited Users</li>
                <li>24/7 Support</li>
                <li>All Features</li>
                <li>Personalized Solutions</li>
            </ul>
            <button class="checkout-btn">Checkout</button>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    text-align: center;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
    margin-bottom: 30px;
}

h1 {
    font-size: 3rem;
}

.pricing-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin: 0 20px;
}

.pricing-card {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 250px;
    text-align: center;
}

h2 {
    margin-bottom: 15px;
    color: #333;
}

.price {
    font-size: 2rem;
    color: #28a745;
    margin-bottom: 20px;
}

ul {
    list-style-type: none;
    margin-bottom: 30px;
}

ul li {
    margin-bottom: 10px;
}

.checkout-btn {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.checkout-btn:hover {
    background-color: #0056b3;
}

footer {
    margin-top: 50px;
    background-color: #333;
    color: white;
    padding: 20px;
}
