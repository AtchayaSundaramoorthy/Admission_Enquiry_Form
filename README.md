# Admission_Enquiry_Form
## Date:

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body>

    <div align="center">
        <h1>Admission Enquiry Form</h1>

        <form action="#" method="post">
            <table>
                <tr>
                    <td><label for="fullName">Full Name:</label></td>
                    <td><input type="text" id="fullName" name="fullName" required></td>
                </tr>
                <tr>
                    <td><label for="email">Email Address:</label></td>
                    <td><input type="email" id="email" name="email" required></td>
                </tr>
                <tr>
                    <td><label for="mobile">Mobile Number:</label></td>
                    <td><input type="tel" id="mobile" name="mobile" required></td>
                </tr>
                <tr>
                    <td><label>Gender:</label></td>
                    <td>
                        <input type="radio" id="male" name="gender" value="Male">
                        <label for="male">Male</label>
                        <input type="radio" id="female" name="gender" value="Female">
                        <label for="female">Female</label>
                        <input type="radio" id="other" name="gender" value="Other">
                        <label for="other">Other</label>
                    </td>
                </tr>
                <tr>
                    <td><label for="dob">Date of Birth:</label></td>
                    <td><input type="date" id="dob" name="dob" required></td>
                </tr>
                <tr>
                    <td><label for="department">Department Interested:</label></td>
                    <td>
                        <select id="department" name="department" required>
                            <option value="">--Select--</option>
                            <option value="CSE">CSE</option>
                            <option value="ECE">ECE</option>
                            <option value="MECH">MECH</option>
                            <option value="EEE">EEE</option>
                            <option value="CIVIL">CIVIL</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td><label for="qualification">Academic Qualification:</label></td>
                    <td><textarea id="qualification" name="qualification" rows="3" cols="30" required></textarea></td>
                </tr>
                <tr>
                    <td><label for="address">Address:</label></td>
                    <td><textarea id="address" name="address" rows="3" cols="30" required></textarea></td>
                </tr>
                <tr>
                    <td><label>Preferred Mode of Contact:</label></td>
                    <td>
                        <input type="checkbox" id="contactEmail" name="contactMode" value="Email">
                        <label for="contactEmail">Email</label>
                        <input type="checkbox" id="contactPhone" name="contactMode" value="Phone">
                        <label for="contactPhone">Phone</label>
                    </td>
                </tr>
                <tr>
                    <td colspan="2" align="center">
                        <input type="submit" value="Submit">
                    </td>
                </tr>
            </table>
        </form>
    </div>

</body>
</html>
```

## Output:

![image](https://github.com/user-attachments/assets/ba094a84-d834-45bd-bad0-0d8b9bb4c01c)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
