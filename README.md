# Week3-assignment-web

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: rgb(62, 199, 199);
            font-family: 'Courier New', Courier, monospace;
        }
        header{
            text-align: center;
            padding: 20px;
            color: white;
            background-color: rgb(87, 33, 33);
        }
        img{
            height: auto;
            max-width: 100px;
        }
        
        .navbar{
            background-color: rgb(74, 1, 134);
            padding: 5px;
        }
        ol{
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .container{
            display: flex;
            background-color: rgb(104, 129, 212);
            flex-wrap: wrap;
            justify-content: space-around;
            min-height: 400px;
        }
        .box{
            flex: 1 1 30%;
            color: rgb(8, 42, 48);
            background-color: rgb(27, 74, 145);
            max-width: 49%;
        }
        footer{
            background-color: blue;
            width: 100%;
            height: 50px;
        }
    </style>
</head>
<body>
    <header>
        <img src="a.jpeg" alt="image"> <h1>ZEEZCO GRAPHICS WORLD</h1>
    </header>
    <div class="navbar">
        <ol>
            <ul>Home</ul>
            <ul>contact</ul>
            <ul>Home</ul>
            <ul>contact</ul>
        </ol>
    </div>
    <section class="container">
        <div class="box"><h1>Welcome to this Page</h1></div>
        <div class="box"></div>
    </section>
    <footer>
        <div></div>
    </footer>
</body>
</html>
