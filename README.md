<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TBs General Store</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; padding: 20px; text-align: center; }
        nav { background-color: #444; padding: 10px; }
        nav ul { list-style: none; padding: 0; text-align: center; }
        nav ul li { display: inline; margin: 0 15px; }
        nav a { color: white; text-decoration: none; }
        .container { max-width: 1200px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; }
        .products { display: flex; flex-wrap: wrap; justify-content: space-around; }
        .product { width: 30%; margin: 10px; text-align: center; border: 1px solid #ddd; padding: 10px; border-radius: 8px; }
        .product img { width: 100%; height: 200px; object-fit: cover; }
        footer { background-color: #333; color: white; text-align: center; padding: 10px; margin-top: 20px; }
        @media (max-width: 768px) { .product { width: 45%; } }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to TBs General Store</h1>
        <p>Your one-stop shop for everyday essentials!</p>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#groceries">Groceries</a></li>
            <li><a href="#household">Household</a></li>
            <li><a href="#electronics">Electronics</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="container" id="home">
        <h2>Featured Products</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Milk" alt="Milk">
                <h3>Fresh Milk</h3>
                <p>$2.50</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Bread" alt="Bread">
                <h3>Whole Wheat Bread</h3>
                <p>$1.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Soap" alt="Soap">
                <h3>Laundry Soap</h3>
                <p>$3.00</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Phone" alt="Phone">
                <h3>Basic Phone</h3>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Detergent" alt="Detergent">
                <h3>Floor Detergent</h3>
                <p>$4.50</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Lamp" alt="Lamp">
                <h3>Desk Lamp</h3>
                <p>$15.00</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>
    <div class="container" id="groceries">
        <h2>Groceries Section</h2>
        <p>Explore our wide range of fresh groceries.</p>
        <!-- Add more products here -->
    </div>
    <div class="container" id="household">
        <h2>Household Items</h2>
        <p>Everything you need for your home.</p>
        <!-- Add more products here -->
    </div>
    <div class="container" id="electronics">
        <h2>Electronics</h2>
        <p>Latest gadgets and appliances.</p>
        <!-- general_store_products = [
    # Grains & Pulses
    "Rice",
    "Wheat Flour",
    "Maize Flour",
    "Barley",
    "Lentils (Masoor Dal)",
    "Green Gram (Moong Dal)",
    "Chickpeas (Chana)",
    "Kidney Beans (Rajma)",

    # Cooking Essentials
    "Mustard Oil",
    "Sunflower Oil",
    "Ghee",
    "Salt",
    "Sugar",
    "Jaggery",
    "Baking Soda",
    "Vinegar",

    # Spices (Common in Kashmir)
    "Red Chilli Powder",
    "Turmeric Powder",
    "Cumin Seeds",
    "Coriander Powder",
    "Fennel Powder",
    "Garam Masala",
    "Dry Ginger Powder (Saunth)",
    "Cloves",
    "Cardamom",
    "Cinnamon",

    # Tea & Beverages
    "Kashmiri Kahwa Tea",
    "Green Tea",
    "Black Tea",
    "Coffee",
    "Soft Drinks",
    "Fruit Juice",

    # Dairy Products
    
    "Curd",
    "Butter",
    "Cheese",
    

    # Snacks & Biscuits
    "Biscuits",
    "Namkeen",
    

    # Dry Fruits (Popular in Kashmir)
    "Almonds",
    "Walnuts",
    "Raisins",
    "Cashews",
    "Dates",

    # Household Items
    "Detergent Powder",
    "Washing Soap",
    "Dishwash Liquid",
    "Floor Cleaner",
    "Toilet Cleaner",
    "Phenyl",

    # Personal Care
    "Bath Soap",
    "Shampoo",
    "Toothpaste",
    "Toothbrush",
    "Hair Oil",
    "Face Cream",

    # Stationery
    "Notebook",
    "Pen",
    "Pencil",
    "Eraser",
    "Sharpener",

    # Miscellaneous
    "Matchbox",
    "Candles",
    "Plastic Bags",
    "Batteries",
    "Mobile Recharge Coupons"
] -->
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: tufailbakshi091@gmail.com</p>
        <p>Phone: (7889390950)</p>
        <p>Address: Anantnag,gopalpora,kalan</p>
    </div>
    <footer>
        <p>&copy; 2023 TBs General Store. All rights reserved.</p>
    </footer>
</body>
</html>
