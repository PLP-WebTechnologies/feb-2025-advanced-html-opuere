# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Power Learn Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        table {
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Power Learn Project</h1>
    </header>
    <main>
        <section>
            <h2>Registration Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name"placeholder="your name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="phone">Password:</label>
                <input type="tel" id="Password" name="Password" required><br><br>
                <label for="date">Date:</label>
                <input type="date" id="date" name="dated" required><br><br>
                <p>Stay logged in: <input type="checkbox"></p>
			    <p>Under 18years: <input type="radio" name="age"></p>
			    <p>Above 18years: <input type="radio" name="age"></p>
                <input type="submit" value="Register">
            </form>
        </section>
        <section>
            <h2>Audio Element</h2>
            <audio controls>
                <source src="audio.mp3" type="audio/mp3">
                Your browser does not support the audio element.
            </audio>
        </section>
        <section>
            <h2>PLP Talent Department</h2>
            <video width="320" height="240" controls>
                <source src="PLP Talent Department_ What's Next after the #1MillionDevs4Africa Software Development Scholarship.mp4" type="video/mp4">
                 Your browser does not support the video element.
            </video>
        </section>
        <section>
            <h2>My picture</h2>
            <img src="Grace.png" alt="Example Image" width="300" height="200">
            <img src="https://images.pexels.com/photos/3180836/pexels-photo-3180836.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="External Image from Pexels" width="600" height="400">
        </section>
        <section>
            <h2>Table</h2>
            <table>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
                <tr>
                    <td>Irene Mwangi</td>
                    <td>45 Kofo road</td>
                    <td>+234 706 018 3450</td>
                    <td>irenemwangii@gmail.com</td>
                </tr>
                <tr>
                    <td>Akintoye Falabi</td>
                    <td>101 Sabo road</td>
                    <td>+234 703 217 0336</td>
                    <td>akintoyefalabi@yahoo.com</td>
                </tr>
                <tr>
                    <td>Bola James</td>
                    <td>New Courts road</td>
                    <td>+234 803 217 0764</td>
                    <td>bolajames@yahoo.com</td>
                </tr>
                <tr>
                    <td>Eno White</td>
                    <td>87 Smith road</td>
                    <td>+234 903 297 1136</td>
                    <td>Eno White@gmail.com</td>
                </tr>
                 <tr>
                    <td>Grace Falabi</td>
                    <td>4 Kent road</td>
                    <td>+234 806 098 5150</td>
                    <td>fopuere@gmail.com</td>
                </tr>
            </table>
        </section>
        <section>
            <h2>List of courses to learn</h2>
            <ol type="I">
                <li>Python Programming</li>
                <li>Software Development</li>
                <li>Database</li>
            </ol>
        </section>
    </main>
</body>
</html>
```
