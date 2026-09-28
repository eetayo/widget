# widget


On this page you will find everything you need to display the widget on a website.


The ul.html file shows an example of integration.


1) widgetfeedback_ul.css : Here are all styles of widget (colors , shapes, sizes , etc )


2) widgetfeedback_ul.js : This part is all the logic for creating the widget and its behavior.
    Very important: The first few lines of the file are the ones you have to redefine:
        var user = "insert user id " ;
        var page = "insert page id " ;
        var urlserverGlobal = "insert urlserver";


3 ) The required files for the integration of the widget are:

       <link href="css/widgetfeedback_ul.css" rel="stylesheet"> 
        <script src="https://code.jquery.com/jquery-2.1.4.min.js"></script> 
        <script src="js/widgetfeedback_ul.js"></script>

