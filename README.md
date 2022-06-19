<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
  <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

nav {
    background-color: #424646;
    padding: 0 60px;
    display: flex;
    justify-content: flex-end;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li a {
    display: inline-block;
    text-decoration: none;
    color: #fff;
    font-size: 14px;
    padding: 10px;
    transition: 0.4s ease;
}

nav ul li a:hover {
    color: rgb(255, 147, 24);
}

nav ul li:not(:last-child) {
    margin-right: 30px;
}


.active {
    background-color: white;
    color: #111;
}

/* Header Section Start */

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 60px;
}

header .logo {
    width: 130px;
}

.fa-cart-arrow-down {
    font-size: 30px;
}

.input__field {
    display: flex;
    align-items: center;
    width: 100%;
    padding: 0 80px;
}

.input__field input {
    width: 100%;
    padding: 12px;
    background-color: rgb(230, 225, 225);
    border: 0;
    border-top-left-radius: 6px;
    border-bottom-left-radius: 6px;
}

.fa-magnifying-glass {
    font-size: 24px;
    padding: 8px 20px;
    background-color: rgb(0, 0, 0);
    color: #fff;
    border: 0;
    border-top-right-radius: 6px;
    border-bottom-right-radius: 6px;
    cursor: pointer;
    transform: translateX(-50px);
    transition: 0.3s;
}

.fa-magnifying-glass:hover {
    background-color: gold;
}
  </style>
</head>

<body>
    <nav>
        <ul>
            <li>
                <a href="#">আজকেরডিলে সেল করুন</a>
            </li>
            <li>
                <a href="#">পরামর্শ / অভিযোগ</a>
            </li>
            <li>
                <a href="#">ডেলিভারি ট্র্যাক করুন</a>
            </li>
            <li>
                <a href="#">লগইন</a>
            </li>
            <li>
                <a class="active" href="#">বাংলা</a>
                <a href="#">ENG</a>
            </li>
        </ul>
    </nav>
    <header>
        <a href="#" class="Logo">
            <img class="logo" src="./ad-logo.svg">
        </a>
        <div class="input__field">
            <input type="text" placeholder="প্রোডাক্ট খুজুন">
            <i class="fa-solid fa-magnifying-glass"></i>
        </div>
        <i class="fa-solid fa-cart-arrow-down"></i>
    </header>
</body>

</html>
