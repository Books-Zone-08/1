<!DOCTYPE html>
<html>
<head>
    <title>Book Store</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background-color: #12121f;
            color: white;
            text-align: center;
        }

        /* LOGIN */
        .login-box {
            margin-top: 120px;
        }

        input {
            padding: 10px;
            margin: 5px;
            width: 200px;
        }

        button {
            padding: 10px;
            background-color: #00ffcc;
            border: none;
            cursor: pointer;
            font-weight: bold;
            margin-top: 10px;
        }

        /* HEADER */
        header {
            background: #00ffcc;
            color: black;
            padding: 15px;
            font-size: 22px;
            font-weight: bold;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
        }

        /* BOOKS */
        .book {
            background-color: #1f1f33;
            margin: 20px;
            padding: 15px;
            border-radius: 10px;
            display: inline-block;
            width: 220px;
        }

        .book img {
            width: 100%;
            border-radius: 8px;
        }

        .hidden {
            display: none;
        }
    </style>
</head>

<body>


</div>

<!-- MAIN SITE -->
<div id="site" class="hidden">

<header>
    📚 books
</header>

<nav>
    <a href="#"home</a>
</nav>

<h2>available books</h2>

<div class="book">
    <img src="images/005" />
    <h3<005 history</h3>
    <p>a boy discovers he is a wizard</p>
    <button/<buy/button>
</div>

<div class="book">
    <img src="images/harry p" />
    <h3<harry potter qnd the sorcerer stone</h3>
    <p>a boy discovers he is a wizard</p>
    <button/<buy/button>
</div>

<div class="book">
    <img src="images/hobbit" />
    <h3>the hobbit</h3>
    <p>an  adventure in middle-earth</p>
    <button>buy</button>
</div>

<div class="book">
    <img src="images/dracula" />
    <h3< dracula</h3>
    <p>  a terrifying vampire story</p>
    <button>buy</button>

<div class="book">
    <img src="images/paulo" />
    <h3>the alchemist</h3>
    <p>a journey to find personal destiny</p>
    <button>buy</button>

<div class="book">
    <img src="images/lord" />
    <h3>the lord of the rings </h3>
    <p>an epic journey to destroy a powerful ring</p>
    <button>buy</button>

<div class="book">
    <img src="images/jane" />
    <h3>jane eyre</h3>
    <p>a strong woman life story</p>
    <button>buy</button>
</div>

<script>
function login() {
    let user = document.getElementById("username").value;
    let pass = document.getElementById("password").value;

    if(user === "user" && pass === "1234") {
        document.getElementById("loginPage").style.display = "none";
        document.getElementById("site").classList.remove("hidden");
    } else {
        alert("❌ معلومات خاطئة");
    }
}
</script>

</body>
</html>
