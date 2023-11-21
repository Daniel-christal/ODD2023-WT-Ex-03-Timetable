Exp-03-WEB
Name:DANIEL.C
Reference no:23008937
AIM
Create a Django website with five users using function-based views. Two users are to be staff users (including admin) and the other three users are non-staff users.

Design Procedure
Step 1: To create a new project in django documents.

Step 2: Change file path with new project folder.

Step 3: include the login credentials using views.py.

Step 4: Create a template called "user_creation_success.html" in template folder.

Step 5: Add the necessary urls to the urls.py.

Step 6: Give command-"python manage.py makemigrations" and get no change detected as output.

Step 7: Give command-"python manage.py migrate" to get the file directories.

Step 8: Give command-"python manage.py runserver 8000" to sign in into django server.

Step 9: Enter given credentials to sign in into django server.

Output:
```
<html>
    <head>
        <title>
            Slot Timetable
        </title>
        <link rel="stylesheet" href="main.css" type="text/css">
    </head>
    <body>
        <br>
        <table align="center" width="500" cellspacing="2" cellpadding="4" border="5" bgcolor="pink">
            <caption><b>Slot Time Table-Jeshwanth 23002519</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>  
                <th bgcolor="yellow">Tuesday</th>  
                <th bgcolor="yellow">wednesday</th>  
                <th bgcolor="yellow">Thursday</th>  
                <th bgcolor="yellow">Friday</th>  
            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td>Engineering Designing and Modelling</td>
                <td>Engineering Mechanics and Product Development</td>
                <td>Python and Linear Algebra</td>
                <td>Fundamentals of Web Applications</td>
                <td>Communicative English</td>
            </tr>
            <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>No class</td>
            <td>Soft Skills</td>
            <td>Fundamentals of Web Applications</td>
            <td>Engineering Designing and Modelling</td>
            <td>Fundamentals of Web Applications</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td>Communicative English</td>
                <td>Python and Linear Algebra</td>
                <td>No class</td>
                <td>No class</td>
                <td>Python and Linear Algebra</td>
                
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td>Engineering Mechanics and Product Development</td>
                <td>No class</td>
                <td>No class</td>
                <td>Python and Linear Algebra</td>
                <td>No class</td>
            </tr>
        </table>
    </body>
</html>
```
#OUTPUT:
![image](https://github.com/Daniel-christal/ODD2023-WT-Ex-03-Timetable/assets/145742847/2e547ca5-8847-490c-bbe8-88c6693bbf15)

Result:
Hence the task was executed successfully.
