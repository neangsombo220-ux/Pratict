# Pretict
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
    <style>
        body{
            font-family: Arial, sans-serif;
        }

        h2{
            text-align: center;
        }

        table{
            width: 650px;
            margin: auto;
            border-collapse: collapse;
        }

        td{
            border: 1px solid gray;
            padding: 12px;
        }

        .label{
            width: 150px;
            text-align: right;
            font-weight: bold;
        }

        input, textarea, select{
            padding: 5px;
        }

        .btn{
            text-align: center;
        }
    </style>
</head>
<body>

<h2>Student Registration Form</h2>

<form>
<table>
    <tr>
        <td class="label">Student ID</td>
        <td><input type="text"></td>
    </tr>

    <tr>
        <td class="label">First Name</td>
        <td><input type="text"></td>
    </tr>

    <tr>
        <td class="label">Last Name</td>
        <td><input type="text"></td>
    </tr>

    <tr>
        <td class="label">Gender</td>
        <td>
            <input type="radio" name="gender"> Male
            <input type="radio" name="gender"> Female
        </td>
    </tr>

    <tr>
        <td class="label">Date of Birth</td>
        <td><input type="date"></td>
    </tr>

    <tr>
        <td class="label">Email</td>
        <td><input type="email"></td>
    </tr>

    <tr>
        <td class="label">Phone</td>
        <td><input type="text"></td>
    </tr>

    <tr>
        <td class="label">Address</td>
        <td><textarea rows="4" cols="30"></textarea></td>
    </tr>

    <tr>
        <td class="label">Course</td>
        <td>
            <select>
                <option>Select Course</option>
                <option>Computer Science</option>
                <option>Business</option>
                <option>English</option>
            </select>
        </td>
    </tr>

    <tr>
        <td class="label">Photo</td>
        <td><input type="file"></td>
    </tr>

    <tr>
        <td colspan="2" class="btn">
            <input type="submit" value="Save">
            <input type="reset" value="Clear">
        </td>
    </tr>
</table>
</form>

</body>
</html>
