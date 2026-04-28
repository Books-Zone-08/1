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

<!-- LOGIN PAGE -->
<div id="loginPage" class="login-box">
    <h2>🔐 تسجيل الدخول</h2>

    <input type="text" id="username" placeholder="اسم المستخدم"><br>
    <input type="password" id="password" placeholder="كلمة السر"><br>

    <button onclick="login()">دخول</button>

    <p>جرب: user / 1234</p>
</div>

<!-- MAIN SITE -->
<div id="site" class="hidden">

<header>
    📚 books
</header>

<nav>
    <a href="#">Home</a>
</nav>

<h2>Available Books</h2>

<div class="book">
    <img src="images/005.jpg" />
    <h3>History Book</h3>
    <p>A boy discovers he is a wizard</p>
    <button>Buy</button>
</div>

<div class="book">
    <img src="images/harry.jpg" />
    <h3>Harry Potter and the Sorcerer's Stone</h3>
    <p>A boy discovers he is a wizard</p>
    <button>Buy</button>
</div>

<div class="book">
    <img src="images/hobbit.jpg" />
    <h3>The Hobbit</h3>
    <p>An adventure in Middle-earth</p>
    <button>Buy</button>
</div>

<div class="book">
    <img src="images/dracula.jpg" />
    <h3>Dracula</h3>
    <p>A terrifying vampire story</p>
    <button>Buy</button>
</div>

<div class="book">
    <img src="images/paulo.jpg" />
    <h3>The Alchemist</h3>
    <p>A journey to find personal destiny</p>
    <button>Buy</button>
</div>

<div class="book">
    <img src="images/lord.jpg" />
    <h3>The Lord of the Rings</h3>
    <p>An epic journey to destroy a powerful ring</p>
    <button>Buy</button>
</div>

<div class="book">
    <img src="images/jane.jpg" />
    <h3>Jane Eyre</h3>
    <p>A strong woman's life story</p>
    <button>Buy</button>
</div>

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
