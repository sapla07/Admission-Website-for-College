# Admission-Website-for-College
Website consist of different forms which student have to fill before taking admission into the college and also they have to upload their documents and submit to college database 

<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Meta tags -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta charset="utf-8" />
    <!-- CSS -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet" type="text/css" />
    <link href="../../css/jquery.smartmenus.bootstrap.css" rel="stylesheet" type="text/css">
    <link href="../../css/template.css" rel="stylesheet" type="text/css" />
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css?family=Roboto:400,700italic,700,400italic" rel="stylesheet" type="text/css" />
    <title>Admission Portal</title>
</head>

<body>
    <header class="container-fluid" role="banner">
        <img class="img-responsive" src="../../images/header.png" alt="header" />
    </header>
    <nav class="navbar navbar-inverse" role="navigation">
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class="sr-only">Toggle Navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
            </div>
            <div class="collapse navbar-collapse" id="theNavbar">
                <ul class="nav navbar-nav">
                    <li><a href="intro.html">Home</a></li>
                    <li><a href="http://dte.org.in/">DTE</a></li>
                    <li>
                        <a href="#">Sindhi Admissions <span class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="../admission-rules.html">Admission Rules</a></li>
                            <li>
                                <a href="#">Eligibility Criteria <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="../eligibility/fe.html">F. E.</a></li>
                                    <li><a href="../eligibility/dse.html">D. S. E.</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">List of Documents <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="../documents/fe.html">F. E.</a></li>
                                    <li><a href="../documents/dse.html">D. S. E.</a></li>
                                    <li><a href="../documents/mca.html">M. C. A.</a></li>
                                    <li><a href="../documents/me.html">M. E.</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">Fee Structure <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="../fee-structure/fe.html">F. E.</a></li>
                                    <li><a href="../fee-structure/dse.html">D. S. E.</a></li>
                                    <li><a href="../fee-structure/mca.html">M. C. A.</a></li>
                                    <li><a href="../fee-structure/me.html">M. E.</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">Admission Schedule <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="../admission-schedule/fe.html">F. E.</a></li>
                                    <li><a href="../admission-schedule/dse.html">D. S. E.</a></li>
                                    <li><a href="../admission-schedule/mca.html">M. C. A.</a></li>
                                    <li><a href="../admission-schedule/me.html">M. E.</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">Admission Procedure <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="../admission-procedure/fe.html">F. E.</a></li>
                                    <li><a href="../admission-procedure/dse.html">D. S. E.</a></li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <a href="#">CAP Admissions <span class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="#">E-CAP</a></li>
                            <li>
                                <a href="#">List of Documents <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="#">F. E.</a></li>
                                    <li><a href="#">D. S. E.</a></li>
                                    <li><a href="#">M. C. A.</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">Fee Structure <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="#">F. E.</a></li>
                                    <li><a href="#">D. S. E.</a></li>
                                    <li><a href="#">M. E.</a></li>
                                    <li><a href="#">M. C. A.</a></li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">Admission Schedule <span class="caret"></span></a>
                                <ul class="dropdown-menu">
                                    <li><a href="#">F. E.</a></li>
                                    <li><a href="#">M. C. A.</a></li>
                                    <li><a href="#">M. E.</a></li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <a href="#">Online Application <span class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="../forms/fe.html">F. E.</a></li>
                            <li><a href="../forms/dse.html">D. S. E.</a></li>
                        </ul>
                    </li>
                    <li><a href="../contact-us.html">Contact Us</a></li>
                </ul>
                <ul class="nav navbar-nav navbar-right">
                    <li>
                        <a href="#">Login <span class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="#">Admin</a></li>
                            <li><a href="#">Student</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <main class="container-fluid">
    </main>
    <footer class="container-fluid text-center" role="footer">
        <span class="glyphicon glyphicon-copyright-mark"></span>&nbsp;&nbsp;Brought to you by <a href="http://vesit.edu/">VESIT</a>
    </footer>
    <!-- Scripts -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
    <script src="../../js/jquery.smartmenus.min.js"></script>
    <script src="../../js/jquery.smartmenus.bootstrap.min.js"></script>
</body>

</html>
