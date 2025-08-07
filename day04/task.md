<!-- # Creating a form 

# In tommorow have to create any form from scratch
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form>
        <label for="name" >NAME:</label>
        <input type="text" placeholder="Enter your name" required name="name" id="name">
        <br><br><br>
        <label for="age"  >AGE:</label>
        <input type="number" placeholder="Enter your age" required name="age" id="age" min="18" max="100" required>
        <br><br><br>
        <label for="email"   >E-MAIL:</label>
        <input type="email" placeholder="Enter your email" required id="email" name="email">
        <br><br><br>
        <label for="gender">GENDER:</label><br>
        <input type="radio" value="Female" id="gender" name="gender">Female<br>
        <input type="radio" value="Male" id="gender" name="gender">Male<br>
        <input type="radio" value="Other" id="gender" name="gender">Other<br><br><br>


        <button type="submit">submit form</button>
    </form>
</body>
</html> -->