<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>TASK  1</title>
</head>
<body>

    <form>
        <label for="firstName">First Name</label>
        <input type="text" id="firstName" name="firstName" required ><br>

        <label for="lastName">Last Name:</label>
        <input type="text" id="lastName" name="lastName" required  ><br>

        <label for="city">City:</label>
        <input type="text" id="city" name="city"  required ><br>
    
        <label for="zipCode">Zip Code:</label>
        <input type="text" id="zipCode" name="zipCode" maxlength="4" pattern="\d{4}" inputmode="numeric" required>
        <br>

        <label for="dob">Date of Birth:</label>
        <input type="text" id="dob" name="dob" placeholder="dd/mm/yy" pattern="^(0[1-9]|[12][0-9]|3[01])/(0[1-9]|1[0-2])/\d{2}$" required>
        <br>

        <input type="submit" value="Submit" />
    </form>

</body>
</html>
