Useful snippets for fast prototyping in Sublime text editor
-----------------------------------------------------------

* _Image placeholder_ HTML (imgplaceholder.sublime-snippet)
    description:    put an image placeholder using the placehold.it service.
    trigger:        "place"[tab]
    output:         ``` html <img src="http://placehold.it/580x350" alt="" /> ```
    tab steps:      width|height|alt

* _HTML5 skeleton_ (html5-skeleton.sublime-snippet)
    description:    create a basic HTML5 skeleton with Twitter bootstrap (local), html5shim (CDN) and jQuery (CDN + local fallback) links.
    trigger:        "skeleton"[tab]
    output:
    ``` html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title></title>
        <meta charset="utf-8" />
        <meta name="description" content="" />
        <meta name="keywords" content="" />
        <meta name="author" content="" />
        <meta name="viewport" content="width=device-width" />
        <link rel="stylesheet" href="libs/css/bootstrap.min.css" />
        <link rel="stylesheet" href="libs/css/common.css" />
        <!--[if lt IE 9]>
          <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
        <![endif]-->
    </head>
    <body class="container">

        <footer>&copy; 2012</footer>
        <!-- Load jQuery from Google's CDN + local fallback-->
        <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
        <script>!window.jQuery && document.write(unescape('%3Cscript src="libs/js/jquery-1.7.1.min.js"%3E%3C/script%3E'))</script>
    </body>
    </html>
    ```
    tab steps: |lang|title|description|keywords|author|css link 1|css link 2|jQuery version (CDN)|jQuery version (local)|body>