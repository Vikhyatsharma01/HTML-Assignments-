job-application-form.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Application Form</title>
</head>
<body>

    <h1>Job Application Form</h1>

    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone">
        <br><br>

        <label for="position">Job Position:</label>
        <select id="position" name="position">
            <option value="developer">Web Developer</option>
            <option value="designer">Web Designer</option>
            <option value="intern">Software Intern</option>
        </select>
        <br><br>

        <p>Skills:</p>
        <input type="checkbox" id="html" name="skills" value="HTML">
        <label for="html">HTML</label>

        <input type="checkbox" id="css" name="skills" value="CSS">
        <label for="css">CSS</label>

        <input type="checkbox" id="java" name="skills" value="Java">
        <label for="java">Java</label>
        <br><br>

        <label for="resume">Upload Resume:</label>
        <input type="file" id="resume" name="resume">
        <br><br>

        <label for="message">Why should we hire you?</label>
        <br>
        <textarea id="message" name="message" rows="4" cols="30"></textarea>
        <br><br>

        <button type="submit">Apply Now</button>
        <button type="reset">Reset</button>
    </form>

</body>
</html>
