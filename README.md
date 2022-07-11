<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentfinal_test</title>
    <style>
        *{
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #logo {
            width: 100px;
            height: 100px;
            margin-left: 0px;
            background-color: orangered;
            color: black;
            align-items: center;
            display: flex;
            justify-content: center;
            font-weight: bold;
            font-size: 30px;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        #header {
            width: 100%;
            height: 100px;
            display: flex;
            align-items: center;
            position: fixed;
            top: 0;
        }
        #buy_rogan {
            margin-left: 400px;
            color: orangered;
            font-size: 25px;
            text-decoration: none;
        }
        nav ul {
            list-style: none;
            display: flex;
            margin-left: 30px;
            justify-content: space-evenly;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            text-transform: uppercase;
            padding: 13px 20px;
            font-size: 20px;
            border-radius: 10px;
            transition: 0.65s;
        }
        nav ul li a:hover {
            background-color: orangered;
            color: black;
        }
        #big{
            color: rgb(56, 56, 130);
            font-size: 70px;
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        #box{
            margin-top: 200px;
        }
        #sale_box{
            color: rgb(91, 85, 85);
            background-color: rgb(206, 201, 201);
            width: 200px;
            height: 23px;
            border-radius: 20px;
            text-align: center;
        }
        #photo{
            margin-top: 150px;
            color: black;
        }
        #main{
            display: flex;
            justify-content: space-evenly;
        }
        #rule{
            color: rgb(91, 85, 85);
            font-size: 25px;
        }
        .footer{
            display: flex;
            justify-content: space-evenly;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <header id="header">
        <p id="logo">R</p>
        <nav>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Project</a></li>
                <li><a href="">Pages</a></li>
                <li><a href="">Elements</a></li>
                <li><a href="">Blog</a></li>
                <li><a href="">Shop</a></li>
                <li><a href="">Contact</a></li>
            </ul>
        </nav>
        <div ><a href="" id="buy_rogan">Buy Rogan &#x2192</a></div>
    </header>
    <div id="main">
        <div id="box">
            <p id="sale_box">
                <span style="color: orangered;">70% Off</span> for first 3 months
            </p>
            <div id="big">
                Digital Agency<br> With Excellence<br> Services.
            </div>
            <p id="rule">
                The 3 golden rules professional graphic designer don't.
            </p>
        </div>
        <div id="photo">
            <img src="https://crayonsdigital.com/wp-content/plugins/rogan-core/widgets/images/shape/banner-shape1.svg" alt="" height="500px" width="500px">
        </div>
    </div>
    <div class="footer">
        <h2 id="n">[Student Name]</h2>
        <h2 id="roll">[University Roll No]</h2>
        <h2 id="uni">Gla University,Mathura</h2>
        <h2 id="date"></h2>
    </div>
    <script>
        var n = document.getElementById("n");
        var roll = document.getElementById("roll");
        var date = document.getElementById("date");

        n.innerHTML = "Vishal Kumar Singh";
        roll.innerHTML = "201500793";

        var day = new Date();
        var d = day.getDate();
        var month = day.getMonth();
        var year = day.getFullYear();

        date.innerHTML = `${d}-${month}-${year}`;

    </script>
</body>
</html>
