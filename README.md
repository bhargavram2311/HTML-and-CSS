# HTML-and-CSS
HTML (HyperText Markup Language) is used to structure and organize content on web pages using tags for text, images, and links. CSS (Cascading Style Sheets) adds style and design to those pages by controlling colors, fonts, spacing, and layout, making websites visually appealing and well-structured.
**CODE:**
<!DOCTYPE html>
<html>
    <head>
        <title>Registration Form</title>
    </head>
    <body bgcolor="orange">
        <h2 align="center">Student Registration Form</h2>
        <form action="#" method="post">
            <table border="1" align="center" cellpadding="10" cellspacing="0">
                <tr>
                    <td><label for="fname">First Name:</label></td>
                    <td><input type="text" id="fname" name="fname" required></td>
                </tr>
                <tr>
                    <td><label for="lname">Last Name:</label></td>
                    <td><input type="text" id="lname" name="lname" required></td>
                </tr>
                 <tr>
                    <td><label for="password">Password:</label></td>
                    <td><input type="password" id="password" name="password" required></td>
                </tr>
                 <tr>
                    <td><label for="age">Age:</label></td>
                    <td><input type="number" id="age" name="age" min="0" max="100"></td>
                </tr>
                 <tr>
                    <td><label for="dob">D.O.B:</label></td>
                    <td><input type="date" id="dob" name="dob"></td>
                </tr>
                <tr>
                    <td>Gender:</td>
                    <td>
                        <input type="radio" id="male" name="gender" value="Male">
                        <label for="male"> Male</label>
                        <input type="radio" id="female" name="gender" value="Female">
                        <label for="female">Female</label>
                    </td>
                </tr>
                <tr>
                    <td>Languages Known:</td>
                    <td>
                        <input type="checkbox" id="english" name="language" value="English">
                         <label for="english"> English</label>
                         <input type="checkbox" id="telugu" name="language" value="Telugu">
                        <label for="telugu"> Telugu</label>
                        <input type="checkbox" id="hindhi" name="language" value="Hindhi">
                        <label for="hindhi"> Hindhi</label>
                    </td>
                </tr>
                <tr>
                    <td><label for="course">Course:</label></td>
                    <td>
                        <select id="course" name="course">
                        <option value="">--Select--</option>
                        <option value="B.Tech">B.Tech</option>
                        <option value="M.Tech">M.Tech</option>
                        <option value="MCA">MCA</option>
                        <option value="MBA">MBA</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td><label for="address">Address:</label></td>
                    <td><textarea id="address" name="address" rows="4" cols="30"></textarea></td>
                </tr>
                <tr>
                    <td colspan="2" align="center">
                        <input type="submit" value="Submit">
                        <input type="reset" value="Reset"
                    </td>
                </tr>
            </table>
        </form>
    </body>
</html>
