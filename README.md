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
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header, nav, main, footer {
            padding: 20px;
        }
        header {
            background: #333;
            color: white;
            text-align: center;
        }
        nav {
            background: #555;
            color: white;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        main {
            background: white;
            padding: 20px;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>
    
    <!-- Navigation Section -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <!-- Main Content Section -->
    <main>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>HTML Basics</li>
            <li>CSS Styling</li>
            <li>JavaScript Essentials</li>
            <li>Responsive Design</li>
            <li>Web Accessibility</li>
        </ol>
        
        <h2>External Image</h2>
        <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Sample Image from Pexels" width="600">
        
        <h2>Contact Table</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Street, City</td>
                <td>+123456789</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Avenue, City</td>
                <td>+987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>789 Road, City</td>
                <td>+112233445</td>
                <td>michael@example.com</td>
            </tr>
            <tr>
                <td>Emily White</td>
                <td>101 Highway, City</td>
                <td>+556677889</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>David Green</td>
                <td>202 Lane, City</td>
                <td>+998877665</td>
                <td>david@example.com</td>
            </tr>
        </table>
        
        <h2>Registration Form</h2>
        <form>
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br><br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            
            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male"> Male
            <input type="radio" id="female" name="gender" value="female"> Female
            <br><br>
            
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
                <option value="australia">Australia</option>
            </select>
            <br><br>
            
            <label>Interests:</label>
            <input type="checkbox" name="interests" value="coding"> Coding
            <input type="checkbox" name="interests" value="design"> Design
            <input type="checkbox" name="interests" value="gaming"> Gaming
            <br><br>
            
            <button type="submit">Register</button>
        </form>
    </main>
    
    <!-- Footer Section -->
    <footer>
        <p>Contact us at: info@example.com</p>
    </footer>
</body>
</html>
