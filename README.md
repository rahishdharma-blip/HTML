# HTML
A STUDENT REGISTRATION FORM IN HTML
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>

    <h2>Student Registration Form</h2>
 <form>
        <label>First Name:</label><br>
        <input type="text" name="firstname" required><br><br>

  <label>Last Name:</label><br>
        <input type="text" name="lastname" required><br><br>

  <label>Email:</label><br>
        <input type="email" name="email" required><br><br>

  <label>Phone Number:</label><br>
        <input type="tel" name="phone" required><br><br>

  <label>Date of Birth:</label><br>
        <input type="date" name="dob"><br><br>

  <label>Gender:</label><br>
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
        <input type="radio" name="gender" value="Other"> Other
        <br><br>

   <label>Course:</label><br>
        <select name="course">
            <option value="">Select Course</option>
            <option value="B.Tech">B.Tech</option>
            <option value="BCA">BCA</option>
            <option value="B.Sc">B.Sc</option>
            <option value="B.Com">B.Com</option>
        </select>
        <br><br>

   <label>Address:</label><br>
        <textarea name="address" rows="4" cols="30"></textarea>
        <br><br>

  <input type="submit" value="Register">
        <input type="reset" value="Clear">

</form>

</body>
</html>
