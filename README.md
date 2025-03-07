<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VroomGo </title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Header Styles */
        header {
            background: #5271ff;
            color: white;
            padding: 15px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        /* Sections */
        section {
            padding: 40px;
        }

        #vehicles {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .vehicle {
            border: 1px solid #ccc;
            padding: 15px;
            width: 250px;
            text-align: center;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            background: #f9f9f9;
        }

        .vehicle img {
            width: 100%;
            height: 150px;
            border-radius: 5px;
        }

        .vehicle h3 {
            margin: 10px 0;
        }

        .vehicle button {
            background: #007BFF;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }

        .vehicle button:hover {
            background: #0056b3;
        }

        /* Contact Form */
        form {
            display: flex;
            flex-direction: column;
            width: 300px;
            margin: auto;
        }

        form input, form textarea {
            margin: 10px 0;
            padding: 8px;
            width: 100%;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        form button {
            background: #28a745;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }

        form button:hover {
            background: #218838;
        }

        /* Footer */
        footer {
            background: #204abe;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }

    </style>
    <title>Login</title>

</head>
<body>

    <header>
        <h1> YOURS FOR HOURS </h1><br>
    
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#vehicles">Vehicles</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <div class="search-container">
        <input type="text" id="search" placeholder="Search...">
        <button onclick="searchFunction()">
            🔍
        </button>
    </div>
    
    <style>
        .search-container {
            display: flex;
            align-items: center;
            justify-content: center;
            background:#204abe;
            padding: 10px;
        }
        .search-container input {
            width: 60%;
            padding: 8px;
            border: none;
            border-radius: 5px 0 0 5px;
        }
        .search-container button {
            padding: 8px 12px;
            border: none;
            background: #111111;
            color: white;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
        }
    </style>
    
    <script>
        function searchFunction() {
            let query = document.getElementById("search").value;
            alert("Searching for: " + query);
        }
    </script>

    <section id="home">
        <h2>Rent any Vehicle Easily</h2>
        <p>Choose from a variety of vehicles: Cars, Bikes, Tractors, JCBs, and more.</p>
    </section>

    <h2>For which vehicle are you looking for ?</h2>

    <section id="vehicles">
        <div class="vehicle">
            <img src="./76206a32257c0008a9076ede9fe4cb1a.jpg" alt="Car">
            <h3>Car</h3>
        
            <button>Book Now</button>
        </div>

        <div class="vehicle">
            <img src="./motocross-rider-action-vector-illustration-white-background_1142-140379.avif" alt="Bike">
            <h3>Bike</h3>
        
            <button>Book Now</button>
        </div>


        <div class="vehicle">
            <img src="./OIP.jpeg" alt="construction vehicle">
            <h3>Earthmover</h3>
            <button> Book now</button>

        </div>
        <div class="vehicle">
            <img src="./OIP (1).jpeg" alt="busses">
            <h3>Bus</h3>
            <button>Book now</button>
        

        </div>
    </section>
    <input type="referal code" placeholder="Referal code"/>
    <button > submit  </button>

    <footer>
        
        <div class="footer-container">
            <p>&copy; 2024 VroomGo. All rights reserved.</p>
            <p><a href="/privacy-policy">Privacy Policy</a> | <a href="/terms">Terms of Service</a></p>
        </div>
        <style>
            footer {
                background-color: #204abe;
                color: white;
                text-align: center;
                padding: 10px;
                position: relative;
                bottom: 0;
                width: 100%;
            }
            footer a {
                color: #f4a261;
                text-decoration: none;
                margin: 0 10px;
            }
            footer a:hover {
                text-decoration: underline;
            }
        </style>
        
    
    </footer>
    

</body>


</html>
