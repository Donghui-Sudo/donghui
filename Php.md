From now on, I will upadte a series of articles to introduce PHP language as this language will be used in my next stage of my work.
Today I will start on basic conception of PHP, like what is PHP, what can we do on PHP and so on.
 
Question 1: what is PHP.

The exist of HTML can let us look through lots of web pages as our brower in the computer need read the HTML file when it loads web pages.
And PHP can be embeded into HTML. For example:

            <html>
                <head>
                    <title>Example</title>
                </head>
                <body>

                    <?php
                        echo "Hi, I'm a PHP script!";
                    ?>

                </body>
            </html>

As you see, the PHP code is enclosed into special start and end instructions <?php and ?> that allow you jump into PHP mode.



What can PHP do?

PHP is mainly focused on server-side scripting language that means PHP code is executed on the server. It can do a lot of thing like other CGI programming, such as collect data in the web page, generate dynamic page content and send and receive cookies. For example, you can write the PHP code to be embeded into HTML to track users' action when they look through the web pages. This is one of method to collect data.

There are three main area where PHP script are used:

1. Server-side script: You need three thing to make this work: PHP Parser(server module), web server, web browser. Yoi can access PHP program without web browser, viewing web content. All these kind of thing can run on your home machine when you are experimenting with PHP programming.

2. Comamnd line script: you can run PHP code without any server and any browser. You only need PHP Parser to use it this way. In other words, PHP code is also executed on Linux or Unix..

3. Writing Desktop application.


What is Server in PHP area?

1. when you type URL in browsers' address bar, you are sending a message and asking it to send resusted HTML file. The web server respond by sending requested file. Your browser read the HTML file and display the web page..

2. you also requrire HTML file when you click the link in the web page that submit a form. In aadition, web server aslo process a file when you click the link. This procees is essentially the same when PHP is installed. you request a file, web server happnens to running PHP code., sending file back to web browser.
