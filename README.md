<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
        }

        /* Add a black background color to the top navigation */
        .topnav {
            background-color: #1D1D1D;
            overflow: hidden;
            border-radius: 100px;
            text-align: center;
            display: flex;
            justify-content: right;
            background-image: url("./fromsoftware.png");
            outline-color: white;
            outline-style: solid;
            outline-width: 0.5px;
            transition: box-shadow 0.3s;
            box-shadow: 0px 0px 0px 0px black;
            
        }

        .topnav:hover {
            box-shadow: 0px 2px 10px 2px black;

        }

        /* Style the links inside the navigation bar */
            .topnav a {
                float: left;
                color: white;
                padding: 14px 16px;
                text-decoration: none;
                font-size: 25px;
                font-family: Arial, Helvetica, sans-serif;
            }

        /* Change the color of links on hover */
                .topnav a:hover {
                    background-color: #696969;
                    color: whitesmoke;
                    font-family: Arial, Helvetica, sans-serif;
                }

        /* Add a color to the active/current link */
                .topnav a.active {
                    background-color: #505050;
                    color: white;
                    font-family: Arial, Helvetica, sans-serif;
                }

        /* Background image*/
        body 
        {
            background-image: url("./games.png");
        }

        .text-box {
            color:white;
            display: flex;
            background-color: #1D1D1D;
            margin-top: 100px;
            padding-top: 50px;
        }
    </style>
</head>
<body>
    <div class="topnav">
        <a class="active" href="/index">Home</a>
        <a href="/gamesinfo">Games</a>
        <a href="/news">News</a>
        <a href="#about">Contact</a>
    </div>
    <div class="text-box">
        <div style="width: 50%;">
            Hello I am text
        </div>
        <div>
            I am over here
        </div>
    </div>
</body>
</html>
