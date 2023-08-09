<b>Greet</b><br>
In the greet folder, Make a simple Flask app that responds to these routes with simple text messages:

<br>/welcome
<br>Returns “welcome”
<br>/welcome/home
<br>Returns “welcome home”
<br>/welcome/back
<br>Return “welcome back”
<br>Once you’ve finished this, run the tests for it:

<p>$ python3 -m unittest test.py</p>

<p><b>Calc</b></p>
Build a simple calculator with Flask, which uses URL query parameters to get the numbers to calculate with.

Make a Flask app that responds to 4 different routes. Each route does a math operation with two numbers, a and b, which will be passed in as URL GET-style query parameters.

<br>/add
<br>Adds a and b and returns result as the body.
<br>/sub
<br>Same, subtracting b from a.
<br>/mult
<br>Same, multiplying a and b.
<br>/div
<br>Same, dividing a by b.

<p>For example, a URL like http://localhost:5000/add?a=10&b=20 should return a string response of exactly 30.</p>

<p>Write the routes for this but don’t hardcode the math operation in your route function directly. Instead, we’ve provided helper functions for this in the file operations.py:</p>

<p>Import and use these in your routes.</p>

<p>After you’ve tried out your app, run the unit tests:</p>
<br>$ python3 -m unittest test.py
