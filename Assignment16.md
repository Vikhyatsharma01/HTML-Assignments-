student-registration-form.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
</head>
<body>

    <h1>Student Registration Form</h1>

    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob">
        <br><br>

        <p>Gender:</p>
        <input type="radio" id="male" name="gender" value="Male">
        <label for="male">Male</label>

        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label>
        <br><br>

        <label for="course">Select Course:</label>
        <select id="course" name="course">
            <option value="BCA">BCA</option>
            <option value="BCA AI">BCA Artificial Intelligence</option>
            <option value="BBA">BBA</option>
            <option value="BTech">B.Tech</option>
        </select>
        <br><br>

        <label for="address">Address:</label>
        <textarea id="address" name="address" rows="3" cols="25"></textarea>
        <br><br>

        <button type="submit">Register</button>
        <button type="reset">Reset</button>
    </form>

</body>
</html>
