# Html
Html simple codes
<!DOCTYPE html>
<html>
<head>
	<title>nav test</title>
	<meta charset="utf-8">
  	<meta http-equiv="x-ua-compatible" content="ie=edge">
  	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
  	<link rel="stylesheet" href="assets/css/styles.css">
  	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <script src="assets/js/new.js"></script>
    <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
    <style type="text/css">
    	 {
            box-sizing: border-box;
            padding: 0;
            margin: 0;
        }

        body {
            font-family: 'Josefin Sans', sans-serif;
        }

        .navbar {
            font-size: 18px;
            background-image: linear-gradient(260deg, #2376ae 0%, #c16ecf 100%);
            border: 1px solid rgba(0, 0, 0, 0.2);
            padding-bottom: 10px;
        }

        .main-nav {
            list-style-type: none;
            display: none;
        }

        .nav-links,
        .logo {
            text-decoration: none;
            color: rgba(255, 255, 255, 0.7);
        }

        .main-nav li {
            text-align: center;
            margin: 15px auto;
        }

        .logo {
            display: inline-block;
            font-size: 22px;
            margin-top: 10px;
            margin-left: 20px;
        }

        .navbar-toggle {
            position: absolute;
            top: 10px;
            right: 20px;
            cursor: pointer;
            color: rgba(255, 255, 255, 0.8);
            font-size: 24px;
        }

        .active {
            display: block;
        }

        @media screen and (min-width: 768px) {
            .navbar {
                display: flex;
                justify-content: space-between;
                padding-bottom: 0;
                height: 70px;
                align-items: center;
            }

            .main-nav {
                display: flex;
                margin-right: 30px;
                flex-direction: row;
                justify-content: flex-end;
            }

            .main-nav li {
                margin: 0;
            }

            .nav-links {
                margin-left: 40px;
            }

            .logo {
                margin-top: 0;
            }

            .navbar-toggle {
                display: none;
            }

            .logo:hover,
            .nav-links:hover {
                color: rgba(255, 255, 255, 1);
            }
}
    </style>
</head>
<body>
<nav class="navbar">
        <span class="navbar-toggle" id="js-navbar-toggle">
            <i class="fas fa-bars"></i>
        </span>
        <a href="#" class="logo">logo</a>
        <ul class="main-nav" id="js-menu">
            <li>
                <a href="#" class="nav-links">Home</a>
            </li>
            <li>
                <a href="#" class="nav-links">Products</a>
            </li>
            <li>
                <a href="#" class="nav-links">About Us</a>
            </li>
            <li>
                <a href="#" class="nav-links">Contact Us</a>
            </li>
            <li>
                <a href="#" class="nav-links">Blog</a>
            </li>
        </ul>
</nav>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<a href="#" class="crunchify-top">↑</a>

<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
</script>
 
<script type="text/javascript">
	let mainNav = document.getElementById('js-menu');
let navBarToggle = document.getElementById('js-navbar-toggle');

navBarToggle.addEventListener('click', function () {
  mainNav.classList.toggle('active');
});
</script>

</body>
</html>
