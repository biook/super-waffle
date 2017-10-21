# super-waffle
html
<html>
<head>
<title> Filmes</title>
<meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <link href="css/estilos.css" rel="stylesheet">
</head>
<body bgcolor="Black">

    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="index.html">Site de filmes</a>
            </div>
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">

                    <li>
                        <a href="index.html">Home</a>
                    </li>
                    <li class="dropdown">
                    <a href="index.html" class="dropdown-toggle" data-toggle="dropdown">Fimes<b class="caret"></b></a>
                    <ul class="dropdown-menu">
                        <li><a href="ami.html">Amityville: o despertar</a></li>
                        <li><a href="wick.html">John Wick 2: Pacto de Sangue</a></li>
                        <li><a href="feito.html">Feito na América</a></li>
                        <li><a href="lei.html">Polícia Federal: A Lei É para Todos</a></li>
                        <li><a href="mae.html">Mãe!</a></li>
                        <li><a href="iti.html">It: A Coisa</a></li>

                    </ul>
                    </li>
                    <li>
                        <a href="contato.html">Entre em contato </a>
                    </li>

                     
                    <div class="container">
                        <a class="navbar-brand navbar-right" href="http://www.facebook.com"><img src="images/Facebook.jpg" height="35px"></a>
                        <a class="navbar-brand navbar-right" href="http://www.twitter.com"><img src="images/Twitter.jpg" height="35px"/></a>
                        
                </ul>
            </div>
        </div>
    </nav>
    <center>

        <div class="container">
        
        <div class="row">
            <div class="col-lg-12 text-center">
                <h1>Filmes</h1>
            </div>
        </div>
        
        <section id="sliderhome">
            <div id="meuSlider" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#meuSlider" data-slide-to="0" class="active"></li>
                    <li data-target="#meuSlider" data-slide-to="1"></li>
                    <li data-target="#meuSlider" data-slide-to="2"></li>
                    <li data-target="#meuSlider" data-slide-to="3"></li>
                    <li data-target="#meuSlider" data-slide-to="4"></li>
                    <li data-target="#meuSlider" data-slide-to="5"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="item active"><img src="images/ami.jpg" width="500 px" Height=" 500 px" alt="Slider 1" /></div>
                    <div class="item"><img src="images/jonh.jpg"  width="500 px" Height=" 500 px" alt ="Slide 2" /></div>
                    <div class="item"><img src="images/feito.jpg" width="500 px" Height=" 500 px" alt="Slide 3" /></div>
                    <div class="item"><img src="images/lei.jpg" width="500 px" Height=" 500 px" alt="Slide 4" /></div>
                    <div class="item"><img src="images/mae.jpg" width="500 px" Height=" 500 px" alt="Slide 5" /></div>
                    <div class="item"><img src="images/iti.jpg" width="500 px" Height=" 500 px" alt="Slide 6" /></div>                    
                </div>
                <a class="left carousel-control" href="#meuSlider" data-slide="prev"><span class="glyphicon glyphicon-chevron-left"></span></a>
                <a class="right carousel-control" href="#meuSlider" data-slide="next"><span class="glyphicon glyphicon-chevron-right"></span></a>
            </div>
        </section>
</center>
	 
<center>
    <TABLE width="50%" border="0"><center>
    <tfoot>
        <tr>    
        <tbody>
    <tr>
         <td><A HREF="ami.html" target="_blank"><img src="images/ami.jpg"width="300" title="amityville: o despertar" height="500" ></A></td> </center>
        <br>
        <td><A HREF="wick.html" target="_blank"><img src="images/wick.jpg"width="300" title="John Wick 2: Pacto de Sangue" height="500" ></A></td>
        <br>
        <td><A HREF="feito.html" target="_blank"><img src="images/feito.jpg"width="300" title="Feito na América" height="500" ></A></td>
    
    </tr> 
    <br>
    <tr>
        <center><td><A HREF="lei.html" target="_blank"><img src="images/lei.jpg"width="300" title="Polícia Federal: A Lei É para Todos" height="500"></A></td>
        <br>
        <td><A HREF="mae.html" target="_blank"><img src="images/mae.jpg"width="300" title="Mãe!" height="500"></A></td>
        <br>
        <td><A HREF="iti.html" target="_blank"><img src="images/iti.jpg"width="300" title="It: A Coisa" height="500" ></A></td>
        <br>
    </tr>
</center>    
</TABLE>
</center>

        

    </div>

    <script src="js/jquery.js"></script>
    <script src="js/bootstrap.js"></script>
    <br>

</body>
</html>
