<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experimental Study</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .nav {
            background-color: #333;
            padding: 10px;
        }
        .nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        .container {
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="nav">
        <a href="#background">Background Information</a>
        <a href="#company">Company Information</a>
        <a href="#questions">Questions</a>
    </div>
    
    <div class="container" id="background">
        <h1>Background Information</h1>
        <p>Provide details about the study here.</p>
    </div>
    
    <div class="container" id="company">
        <h1>Company Information</h1>
        <p>Provide details about the company here.</p>
    </div>
    
    <div class="container" id="questions">
        <h1>Questions</h1>
        <form>
            <label for="q1">Question 1:</label><br>
            <input type="text" id="q1" name="q1"><br><br>
            <label for="q2">Question 2:</label><br>
            <input type="text" id="q2" name="q2"><br><br>
            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>
