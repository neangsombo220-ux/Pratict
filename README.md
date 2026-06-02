<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>

<center>
    <h2><font color="blue">Student Registration Form</font></h2>
</center>

<form>
<table border="1" width="650" align="center" cellpadding="12">

    <tr>
        <td align="right">
            <font color="green">Student ID</font>
        </td>
        <td>
            <input type="text">
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="purple">First Name</font>
        </td>
        <td>
            <input type="text">
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="orange">Last Name</font>
        </td>
        <td>
            <font color="orange"></font>
            <input type="text">
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="brown">Gender</font>
        </td>
        <td>
            <input type="radio" name="gender"> Male
            <input type="radio" name="gender"> Female
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="black">Date of Birth</font>
        </td>
        <td>
            <input type="date">
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="gold">Email</font>
        </td>
        <td>
            <input type="email">
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="pink">Phone</font>
        </td>
        <td>
            <input type="text">
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="gray">Address</font>
        </td>
        <td>
            <textarea rows="4" cols="30"></textarea>
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="blue">Course</font>
        </td>
        <td>
            <select>
                <option>Select Course</option>
                <option>Computer Science</option>
                <option>Khmer Literature</option>
                <option>English</option>
                <option>Social Studies</option>
            </select>
        </td>
    </tr>

    <tr>
        <td align="right">
            <font color="gray">Photo</font>
        </td>
        <td>
            <input type="file">
        </td>
    </tr>

    <tr>
        <td colspan="2" align="center">
            <input type="submit" value="Save">
            <input type="reset" value="Clear">
        </td>
    </tr>

</table>
</form>

</body>
</html>
