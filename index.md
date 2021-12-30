
<!DOCTYPE html>
<html>
<head>
    <title>Cafe Unlimited - Home</title>

    <script>
        function bigger(){
            document.getElementById('body').style.fontSize='x-large';
        }
        function smaller(){
            document.getElementById('body').style.fontSize='medium';
        }
    </script>
    <style>
        h1 {
            font-family: fantasy;
            color: slategray;
        }
        p {
            font-family: sans-serif;
            color: rgb(0, 0, 128);
        }

        li {
            font-family: sans-serif;
            color: #000080;
        }
    </style>

</head>
<body id="body" style="background-image:url(images/background.png)">

<!-- Banner -->
<p>
    <img src="images/banner.png" alt="Cafe Unlimited - Banner">
</p>

<!-- Navigation links -->
<p style="background:slategray;font-weight: bolder;">
    <a href="index.html">Home</a>
    <a href="breakfast.html">Breakfast</a>
</p>

<!-- Breakfast photos -->
<p>
    <img src="images/pancakes.jpg" alt="Pancakes">
    <img src="images/muffin.jpg" alt="Muffin" >
</p>

<!--Javascript -->
<button type="button" onclick="bigger()">Bigger</button>
<button type="button" onclick="smaller()">Smaller</button>

<h1>Welcome</h1>
<p>Welcome to Cafe Unlimited. We serve award-winning breakfasts and lunches,
    with unlimited coffee, tea, and soft drinks.
    Freshly baked muffins, signature omelets, healthy salads, delicious burgers
    and hearty sandwiches are just some of the delicious items on our menu.

    We were voted the
    <span style="color:red;font-style:italic">
        the #1 Breakfast and Lunch restaurant
    </span>
    downtown!
</p>
<p>We want to make you
    <span style="color:red;font-style:italic">feel at home</span>
    from the minute you walk in the door.

    Be part of the Cafe Unlimited family! Have a great meal, relax, socialize, and come back again soon!</p>
<p>We offer delivery on <a href="http://ubereats.com" target="_blank">UberEats</a>. Download the app and place your order today. Please contact us about catering services.</p>

<p>We are located at 20 Channel Center Street in Boston, MA.</p>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2948.8366673124624!2d-71.05369318489703!3d42.346005543982265!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89e37a7de82a1251%3A0xb79b53cf96e26c94!2s20+Channel+Center+St%2C+Boston%2C+MA+02210!5e0!3m2!1sen!2sus!4v1543445329233" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
<p>    We are open:</p>

<ul>
    <li>Saturday and Sunday, 7 am to 2 pm</li>
    <li>Monday through Friday, 6 am to 2 pm</li>
</ul>
<p>Visit our contact page for directions and contact information.</p>
<h1>Find Us, Follow Us</h1>
<p>Follow us on <a href="http://facebook.com" target="_blank">Facebook</a> and
    <a href="http://twitter.com" target="_blank">Twitter</a>.
    Check out our reviews on <a href="http://yelp.com" target="_blank">Yelp.</a>
</p>
<p>Find us in Channel Center.</p>
<p>Cafe Unlimited<br>
617-555-1234<br>
    cafeunlimited@example.com</p>
</body>
</html>

