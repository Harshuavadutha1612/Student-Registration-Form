<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>
    <form action="#" method="post">
	    <h3>DevOps Lab</h3>
        <table border="1" cellpadding="10" cellspacing="0">
            <tr>
                <td><label for="name">Name:</label></td>
                <td><input type="text" id="name" name="name" required></td>
            </tr>
            <tr>
                <td><label for="email">Email:</label></td>
                <td><input type="email" id="email" name="email" required></td>
            </tr>
            <tr>
                <td><label for="mobile">Mobile No:</label></td>
                <td><input type="tel" id="mobile" name="mobile" pattern="[0-9]{10}" required></td>
            </tr>
            <tr>
                <td>Gender:</td>
                <td>
                    <input type="radio" id="male" name="gender" value="Male" required>
                    <label for="male">Male</label>
                    <input type="radio" id="female" name="gender" value="Female">
                    <label for="female">Female</label>
                </td>
            </tr>
            <tr>
                <td><label for="address">Address:</label></td>
                <td><textarea id="address" name="address" rows="4" cols="30" required></textarea></td>
            </tr>
            <tr>
                <td><label for="course">Course:</label></td>
                <td><input type="text" id="course" name="course" required></td>
            </tr>
            <tr>
                <td><label for="branch">Branch:</label></td>
                <td><input type="text" id="branch" name="branch" required></td>
            </tr>
            <tr>
                <td><label for="year">Year:</label></td>
                <td>
                    <select id="year" name="year" required>
                        <option value="">Select Year</option>
                        <option value="1">1st Year</option>
                        <option value="2">2nd Year</option>
                        <option value="3">3rd Year</option>
                        <option value="4">4th Year</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td colspan="2" style="text-align:center;">
                    <input type="submit" value="Register">
                </td>
            </tr>
        </table>
    </form>
</body>
</html># Student-Registration-Form
