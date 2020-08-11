<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            text-decoration: none;
            list-style: none;
            box-sizing: border-box;
        }
        nav{
            height: 80px;
            width: 100%;
        }
        img{
            width: 170px;
            height: auto;
            margin: 10px;
        }
        nav ul{
            float: right;
            margin-right:20px ;
            background-color: white;
        }
        nav ul li{
            display: inline-block;
            line-height: 80px;
            margin: 0 5px;
        }
        nav ul li a{
            color: black;
            font-size:17px;
            padding: 7px 13px;
            border-radius: 3px;
            text-transform: uppercase;
        }
        a.active{
            background-color: blue;
            color: white;
            padding: 10px;
        }
        .checkbtn{
            font-size: 30px;
            float:right;
            line-height:80px;
            margin-right: 40px;
            cursor: pointer;
            display: none;
        }
        #check{
            display: none;
        }
        .coin-top{
            background-color:blue;
            color:white;
            margin-top:50px;
            opacity: 0.8;
        }
        .divs{
            display:inline-block;
            padding:20px;
            margin-left: 150px;
            font-size:17px;
        }
        .divs1{
            display:inline-block;
            padding:20px;
            margin-left: 100px;
            font-size: 17px;
        }
        .divs2{
            display:inline-block;
            padding:20px;
            margin-left: 100px;
            font-size: 17px;
        }
        .divs3{
            display:inline-block;
            padding:20px;
            margin-left:100px;
            font-size: 17px;
        }
        .divs4{
            display:inline-block;
            padding:20px;
            margin-left: 100px;
            font-size:17px;
        }
        .top h3{
            margin-top: 30px;
            margin-left: 140px;
            font-size: 25px;
        }
        .top a{
            float:right;
            margin-right:225px;
            margin-top: -30px;
            padding:10px;
            background-color: gainsboro;
            border:1px solid gainsboro;
            border-radius: 15px;
            color:black;
        }
        .butt1{
            padding:30px;
            background-color:rgb(47, 248, 255) ;
            color:white;
            width: 120px;
            height:100px;
            margin-left: 200px;
            font-size:16px;
            margin-top: 30px;
            border:1px solid rgb(47, 248, 255);
            border-radius: 15px;
            display: inline-block;
        }
        .butt2{
            padding:30px;
            background-color: green;
            color:white;
            width: 120px;
            height:100px;
            margin-left: 50px;
            font-size:16px;
            margin-top: 30px;
            border:1px solid green;
            border-radius: 15px;
            display: inline-block;
        }
        #icon{
            margin: 0;
            padding: 0;
            color:white;
            font-weight:bold;
            transform:rotate(45deg);
        }
        table{
            margin-left: 200px;
        }th{
            padding:27px;
            color: blue;
        }
        td{
            padding: 27px;
            color:blue;
            font-weight: bold;
            font-size:20px;
        }
        @media (max-width:952px){
            img{
                width: 130px;
                height: 50px;
                padding-left: 50px;
            }
            nav ul li a{
                font-size:16px;
            }
        }
        @media (max-width:852px){
            img{
                width: 150px;
                height: 50px;
            }
            .checkbtn{
                display: block;
            }
            ul{
                position: fixed;
                width: 100%;
                height: 100vh;
                top: 80px;
                left: -100%;
                transition: all .5s ease;
            }
            nav ul li{
                display: block;
                margin: 50px 0;
                line-height: 30px;
                text-align: center;
            }
            nav ul li a{
                font-size: 20px; 
            }
            #check:checked ~ ul{
                left: 0;
            }
            .divs{
                margin: 0;
            }
            .divs1{
                margin: 0;
            }
            .divs2{
                margin: 0;
            }
            .divs3{
                display: none;
            }
            .divs4{
                display: none;
            }
            .top h3{
                margin-top: 20px;
                margin-left: 15px;
            }
            .top a{
                margin-top: -30px;
                margin-right: 20px;
                padding:10px;
                font-size:17px;
            }
            .butt1{
                margin-top: 22px;
                margin-left: 10px;
            }
            .butt2{
                position:fixed;
                top:34%;
                margin: 0;
            }
            .bt{
                display: none;
            }
            table{
                margin: 0;
            }
            th{
                font-size:17px;
                padding: 10px;
            }
            td{
                font-size: 17px;
                padding: 10px;
            }
            th:nth-child(5){
                display: none;
            }
            th:nth-child(6){
                display: none;
            }
            th:nth-child(7){
                display: none;
            }
            th:nth-child(8){
                display: none;
            }
            .mk1{
                display: none;
            }
            .mk2{
                display: none;
            }
            .mk3{
                display: none;
            }
            .mk4{
                display: none;
            }
        }
    </style>
</head>
<body>
    <nav>
        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
            <i class="fa fa-bars"></i>
        </label>
        <img src="images/logo.jpg" alt="">
        <ul>
            <li><a href="#" class="active">Home</a></li>
            <li><a href="#">ICO's</a></li>
            <li><a href="#">Airdrops</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Guide</a></li>
            <li><a href="#">Hire Experts</a></li>
            <li><a href="#">Login</a></li>
        </ul>
    </nav>
    <section>
        <div class="row" style="background-color: blue; color: white;">
            <div class="divs">
                <h4>BTC/USD</h4>
                <span>$9120.78</span>
            </div>
            <div class="divs1">
                <h4>Cryptocurrencies</h4>
                <span>1554</span>
            </div>
            <div class="divs2">
                <h4>24h volume</h4>
                <span>$137.7 B</span>
            </div>
            <div class="divs3">
                <h4>AltCoin M.cap</h4>
                <span>$100.5 B</span>
            </div>
            <div class="divs4">
                <h4>total M.cap</h4>
                <span>$277.7 B</span>
            </div>
        </div>
    </section>
    <section>
        <div class="row top">
            <h3>Top Viewed</h3>
            <a href="#">View All</a>
        </div>
        <div class="row">
            <div class="butt1">
                <h5>BitCoin</h5>
                <span>$9,120.78</span>
                <span class="fa fa-angle-double-up" id="icon"></span> 4.46%
            </div>
            <div class="butt2 " style="margin-left: 90px;" >
                <h5>BitCoin</h5>
                <span>$9,120.78</span>
                <span class="fa fa-angle-double-up" id="icon"></span> 4.46%
            </div>
            <div class="butt1 bt" style="margin-left: 90px;background-color:indianred">
                <h5>BitCoin</h5>
                <span>$9,120.78</span>
                <span class="fa fa-angle-double-up" id="icon"></span> 4.46%
            </div>
            <div class="butt1 bt" style="margin-left: 90px;background-color:tan;">
                <h5>BitCoin</h5>
                <span>$9,120.78</span>
                <span class="fa fa-angle-double-up" id="icon"></span> 4.46%
            </div>
            <div class="butt1 bt" style="margin-left: 110px;background-color:yellowgreen;">
                <h5>BitCoin</h5>
                <span>$9,120.78</span>
                <span class="fa fa-angle-double-up" id="icon"></span> 4.46%
            </div>
        </div>
        <table>
            <tr>
                <th>#</th>
                <th>NAME<i class="fa fa-angle-up"></i></th>
                <th>CHANGE<i class="fa fa-angle-up"></i></th>
                <th>PRICE<i class="fa fa-angle-down"></i></th>
                <th>24HR CHANGE<i class="fa fa-angle-up"></i></th>
                <th>GRAPH</th>
                <th>COINS<i class="fa fa-angle-up"></i></th>
                <th>MARKET CAP<i class="fa fa-angle-down"></i></th>
            </tr>
            <tr>
                <td>1</td> 
                <td><span class="fa fa-btc" style="margin:0;padding: 0;color: orangered;font-weight: bold;font-size:20px;"></span>Bitcoin</td>
                <td><span class="fa fa-angle-double-up" id="icon"></span> 4.46%</td>
                <td>$9,120.78</td>
                <td class="mk1"><span class="fa fa-angle-double-up" id="icon"></span> $9,120.78</td>
                <td class="mk2">...</td>
                <td class="mk3">18.25 M</td>
                <td class="mk4">$166.5 B</td>
            </tr>
            <tr>
                <td>2</td> 
                <td><span class="fa fa-diamond" style="margin:0;padding: 0;color: black;font-weight: bold;font-size:20px;"></span>Ethereum</td>
                <td><span class="fa fa-angle-double-up" id="icon"></span> 3.49%</td>
                <td>$230.91</td>
                <td class="mk1"><span class="fa fa-angle-double-up" id="icon"></span> $248.98</td>
                <td class="mk2">...</td>
                <td class="mk3">109.97 M</td>
                <td class="mk4">$25.39 B</td>
            </tr>
            <tr>
                <td>3</td> 
                <td>Ripple</td>
                <td><span class="fa fa-angle-double-up" id="icon"></span> 4.46%</td>
                <td>$9,120.78</td>
                <td class="mk1"><span class="fa fa-angle-double-up" id="icon"></span> $9,120.78</td>
                <td class="mk2">...</td>
                <td class="mk3">18.25 M</td>
                <td class="mk4">$166.5 B</td>
            </tr>
        </table>
    </section>
</body>
</html>
