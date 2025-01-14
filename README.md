<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Cafe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #c9cdbe;
        }

        header {
            background-color: #151313;
            color: rgb(10, 223, 194);
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: rgb(187, 20, 20);
            text-decoration: none;
        }

        .menu-section {
            padding: 20px;
            text-align: center;
        }

        .menu-section h2 {
            margin-bottom: 20px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .menu-item {
            text-align: center;
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            border-radius: 10px;
        }

        .menu-item h3 {
            font-size: 18px;
            margin: 10px 0 5px;
        }

        .menu-item p {
            font-size: 14px;
            color: rgb(223, 9, 9);
        }

        .menu-item span {
            font-weight: bold;
        }

        .reservation {
            background-color: #939393;
            padding: 40px 20px;
            text-align: center;
        }

        .reservation form {
            display: flex;
            flex-direction: column;
            gap: 15px;
            max-width: 400px;
            margin: 0 auto;
        }

        .reservation input, .reservation button {
            padding: 10px;
            font-size: 16px;
        }

        .reservation button {
            background-color: #2841b1;
            color: rgb(0, 0, 0);
            border: none;
            cursor: pointer;
        }

        footer {
            background-color: #000000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer a {
            color: #ff6347;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        .menu-section {
            background-image: url('https://via.placeholder.com/1200x400?text=Delicious+Food');
            background-size: cover;
            background-position: center;
            color: rgb(145, 48, 48);
            padding: 40px 20px;
        }

        .menu-section h1 {
            color: #ea0909;
            background-color: rgba(255, 255, 255, 0.8);
            display: inline-block;
            padding: 20px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Restaurant Cafe</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#reservation">Reservations</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu-section" id="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="https://tse4.mm.bing.net/th?id=OIP.MPWL8vD4mUuHlvzfrNsxuwHaFj&pid=Api&P=0&h=180" alt="Pizza">
                <h3>Pizza</h3>
                <p>Delicious cheese pizza</p>
                <span>Rs-399/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse3.mm.bing.net/th?id=OIP.hbCx1juYjW051s8K4YsPTwHaD_&pid=Api&P=0&h=180" alt="Burger">
                <h3>Burger</h3>
                <p>Maharaja burger</p>
                <span>Rs-159/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse1.mm.bing.net/th?id=OIP.LGs2XyxVrqOuTohMA7xjmwHaIj&pid=Api&P=0&h=180" alt="Pasta">
                <h3>Pasta</h3>
                <p>Creamy Alfredo pasta</p>
                <span>Rs-249/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse4.mm.bing.net/th?id=OIP.0lRD9n_1Y0XpTVGlQ3qzvgHaE8&pid=Api&P=0&h=180" alt="Ice Cream">
                <h3>Ice Cream</h3>
                <p>Refreshing vanilla scoop</p>
                <span>Rs-129/.</span>
                
            </div>
        </div>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="https://tse1.mm.bing.net/th?id=OIP._rUusY-CQf6QwuhddG7OWAHaGN&pid=Api&P=0&h=180" alt="Pizza">
                <h3>Butter paneer</h3>
                <p>Butter Paneer Masala</p>
                <span>Rs-349/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse2.mm.bing.net/th?id=OIP.0R_peVioO6ry90_cz_VsCQHaGl&pid=Api&P=0&h=180" alt="Burger">
                <h3>Daal</h3>
                <p>Daal Makhani</p>
                <span>Rs-179/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse2.mm.bing.net/th?id=OIP.TNj20f3cQU3Wd2TvJk9ZRAHaE8&pid=Api&P=0&h=180" alt="Pasta">
                <h3>Paratha</h3>
                <p>Aloo Paratha</p>
                <span>Rs-119/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse1.mm.bing.net/th?id=OIP.ZmlXabGCLkgFUcl0PyqV9QHaD3&pid=Api&P=0&h=180" alt="Ice Cream">
                <h3>Chaat</h3>
                <p>Banarasi chhat</p>
                <span>Rs-49/.</span>
                
            </div>
        </div> <div class="menu-grid">
            <div class="menu-item">
                <img src="https://tse1.mm.bing.net/th?id=OIP.AJKbOIaLpDv1pQYgvoZkPQHaFy&pid=Api&P=0&h=180" alt="Pizza">
                <h3>Panipuri</h3>
                <p>Panipuri</p>
                <span>Rs-79/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse1.mm.bing.net/th?id=OIP.2PkBI0m1I9JPHHeWn-ErsQHaE0&pid=Api&P=0&h=180" alt="Burger">
                <h3>Frankie</h3>
                <p>Veg Frankie</p>
                <span>Rs-120/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse3.mm.bing.net/th?id=OIP.1NmSY68F190B2-emopWyewHaHa&pid=Api&P=0&h=180" alt="Pasta">
                <h3>Idli</h3>
                <p>Idli and Sambhar</p>
                <span>Rs-89/.</span>
            </div>
            <div class="menu-item">
                <img src="https://tse1.mm.bing.net/th?id=OIP.bOQiHhWLjgHYOBEC6S-XaQHaFj&pid=Api&P=0&h=180" alt="Ice Cream">
                <h3>munchurian</h3>
                <p>Veg Munchurian</p>
                <span>Rs-139/.</span>
                
            </div>
        </div>
    </section>

    <section class="reservation" id="reservation">
        <h2>Make a Reservation</h2>
        <form>
            <input type="text" placeholder="Name" required>
            <input type="email" placeholder="Email" required>
            <input type="tel" placeholder="Phone" required>
            <input type="date" required>
            <input type="time" required>
            <input type="number" placeholder="Number of Guests" required>
            <button type="submit">Reserve Now</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Restaurant Cafe. All Rights Reserved. <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
