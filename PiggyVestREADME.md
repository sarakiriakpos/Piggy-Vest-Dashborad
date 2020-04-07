<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <link rel="canonical" href="https://dashboard.piggyvest.com/register">
    <title>PiggyVest | Dashboard</title>

    <!--The CSS style sheet goes here-->
    <link rel="stylesheet" type="text/css" href="main.css">
    <!-- Mobile Friendliness -->
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="MobileOptimized" content="width">
    <meta name="HandheldFriendly" content="true">
</head>

<body>
  <div id="root">
<div style="float: center; width: 30%">
        <a href="https://www.piggyvest.com/">
        <img src="images/piggy-png_1_.png" alt="Piggybank Logo" class="mb-12">
        </a>
    </div>
    
    <div class="round">
        <!--this is the header-->
    <header>
    <h1>Create a Secure Account</h1>
    <p>Welcome to the future of Savings & Investments</p>
    </header>
        <form>
            <!--A form for users to register -->
            <div class="flex-1">
            <label for="username">Full Name:</label><br>
            <input type="text" id="username" name="username" placeholder="Full Name"><br></div>
            <div>
            <label for="email">Email Address:</label><br>
            <input type="text" id="email" name="email" placeholder="Email Address"><br></div>
            <div>
            <label for="phoneNo.">Phone Number:</label><br>
            <input type="text" id="phoneNo." name="phoneNo" placeholder="Phone Number"><br></div>
            <div>
            <label for="password">Password:</label><br>
            <input type="text" id="password" name="password" placeholder="Password"><br></div>
            <div>
            <label for="referrer">Referrer Phone or Promo Code (Optional):</label><br>
            <input type="text" id="password" name="password" placeholder="Referrer Phone Or Code"><br></div>
            <div>
            <label for="about">How Did You Hear About Us? (Optional):</label><br>
            <span class="datalist-arrow">
            <input list="select" id="about" name="about" placeholder="Click To Select">
            <datalist id="select" style="overflow: scroll; position: absolute; visibility: hidden; white-space: pre; "> 
            <option>Facebook</option>
            <option>Instagram</option>
            <option>Twitter</option>
            <option>Friend/Family/Coworker Referrer</option>
            <option>Google Search</option>
            <option>Google Playstore</option>
            <option>Online Blog</option>
            <option>Local Newspaper</option>
            <option>At an Event</option>
            <option>Other</option>
            </datalist>
            </span>
            </div>
            <input type="submit" value="CREATE ACCOUNT" class="submit" />
        </form>
        </div>
</div>
<div class="Log">
    <a href="https://dashboard.piggyvest.com/login" target="_blank">Already have an account? Log In</a>
</div>
</body>

</html>
