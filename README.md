# Ex02 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

'''<!DOCTYPE html>
{% load static %}
<html>
<head>
  <title>Slot Time Table</title>
  <style>
    body {
      font-family: "Times New Roman";
      background-color: #f9f9f9;
      text-align: center;
      margin: 20px;
    }

    h2 {
      color: #101011ff;
    }
    table {
      border-collapse: collapse;
      margin: 25px auto;
      width: 85%;
      background: white;
      box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.2);
      border-radius: 10px;
    }

    th, td {
      border: 1px solid #555;
      padding: 10px;
      text-align: center;
    }

    th {
      background-color: #c9fc8bff;
      color: black;
    }

    td {
      font-weight: bold;
    }

    tr:nth-child(even) {
      background-color: #f7faf0ff;
    }

    tr:hover {
      background-color: #88f5a3ff;
    }

    .sub-table {
      width: 60%;
      margin-top: 30px;
    }

    .sub-table th {
      background-color: #0c0c0cff;
      color: white;
    }

    p {
      margin-top: 20px;
      color: #0bff1bff;
    }
  </style>
</head>
<body>
  <img src={% static 'logo.png' %}>

  <h2>SLOT TIME TABLE - NITHILA R J (25010789)</h2>


  <table>
    <tr>
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>
    </tr>
    <tr>
      <td>8-10</td>
      <td>PYTHON</td>
      <td>FREE</td>
      <td>WEB</td>
      <td colspan="3">FREE</td>
    </tr>
    <tr>
      <td>10-12</td>
      <td>PYTHON</td>
      <td>WEB</td>
      <td colspan="2">F R E E</td>
      <td>Python</td>
      <td>FREE</td>
    </tr>
    <tr>
      <td>12-1</td>
      <td colspan="6">L U N C H</td>
    </tr>
    <tr>
      <td>1-3</td>
      <td>FREE</td>
      <td>Python</td>
      <td>MENTOR</td>
      <td>FREE</td>
      <td>Python</td>
      <td>FREE</td>
    </tr>
    <tr>
      <td>3-5</td>
      <td colspan="3">WEB</td>
      <td colspan="3">FREE</td>
    </tr>
  </table>

  <table class="sub-table">
    <tr>
      <th>Subject Code</th>
      <th>Subject Name</th>
    </tr>
    <tr>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
      <td>19AI301</td>
      <td>Python Programming</td>
    </tr>
  </table>

  <p>Prepared by: NITHILA R J  </p>

</body>
</html>'''
## OUTPUT
![WhatsApp Image 2025-12-08 at 11 57 46 AM](https://github.com/user-attachments/assets/d5fe8334-6db2-44bb-8a49-317f4d638654)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
