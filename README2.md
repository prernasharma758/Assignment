# Question 16 : student-registration-form.html
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>

    <h1>Student Registration Form</h1>
    <p>Please fill in the following details.</p>

    <form>

        <h2>Personal Details</h2>

        <label>Full Name:</label>
        <input type="text" name="name" required>
        <br><br>

        <label>Email:</label>
        <input type="email" name="email" required>
        <br><br>

        <label>Phone Number:</label>
        <input type="number" name="phone">
        <br><br>

        <label>Date of Birth:</label>
        <input type="date" name="dob">
        <br><br>

        <label>Gender:</label>
        <input type="radio" name="gender"> Male
        <input type="radio" name="gender"> Female
        <input type="radio" name="gender"> Other

        <br><br>

        <h2>Academic Details</h2>

        <label>Course:</label>
        <select name="course">
            <option>Select Course</option>
            <option>BCA</option>
            <option>BCA (AI)</option>
            <option>BBA</option>
            <option>B.Tech</option>
        </select>

        <br><br>

        <label>College Name:</label>
        <input type="text" name="college">
        <br><br>

        <label>Previous Qualification:</label>
        <input type="text" name="qualification">
        <br><br>

        <h2>Address Details</h2>

        <label>Address:</label>
        <br>
        <textarea name="address" rows="4" cols="30"></textarea>

        <br><br>

        <label>City:</label>
        <input type="text" name="city">
        <br><br>

        <label>State:</label>
        <input type="text" name="state">
        <br><br>

        <h2>Interests</h2>

        <input type="checkbox" name="interest" value="Coding">
        Coding

        <input type="checkbox" name="interest" value="Sports">
        Sports

        <input type="checkbox" name="interest" value="Reading">
        Reading

        <br><br>

        <label>Upload Photo:</label>
        <input type="file" name="photo">

        <br><br>

        <input type="checkbox" required>
        I confirm that all the information is correct.

        <br><br>

        <input type="submit" value="Register">
        <input type="reset" value="Reset">

    </form>

</body>
</html>
