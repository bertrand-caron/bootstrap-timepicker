# Making the project compliant with Bootstrap V3

## To do : 

* Rewrite demos
    * `class='input-append'` => `class='input-group'`
    * `class='add-on'` => `class='input-group-addon'`

```
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <link type="text/css" href="css/bootstrap.min.css" />
        <link type="text/css" href="css/bootstrap-timepicker.min.css" />
        <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
        <script type="text/javascript" src="js/bootstrap-2.2.2.min.js"></script>
        <script type="text/javascript" src="js/bootstrap-timepicker.min.js"></script>
    </head>
    <body>
        <div class="input-group bootstrap-timepicker">
            <input id="timepicker1" type="text" class="input-small">
            <span class="input-group-addon"><span class="glyphicon glyphicon-time"></span></span>
        </div>
 
        <script type="text/javascript">
            $('#timepicker1').timepicker();
        </script>
    </body>
</html>
```

```
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <link type="text/css" href="css/bootstrap.min.css" />
        <link type="text/css" href="css/bootstrap-timepicker.min.css" />
        <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
        <script type="text/javascript" src="js/bootstrap-2.2.2.min.js"></script>
        <script type="text/javascript" src="js/bootstrap-timepicker.min.js"></script>
    </head>
    <body>
        <div class="input-append bootstrap-timepicker">
            <input id="timepicker1" type="text" class="input-small">
            <span class="add-on"><i class="icon-time"></i></span>
        </div>
 
        <script type="text/javascript">
            $('#timepicker1').timepicker();
        </script>
    </body>
</html>
```

* Minify the 'js' files

## Done
