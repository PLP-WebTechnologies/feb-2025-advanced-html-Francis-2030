<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Advanced HTML5 Elements and Forms</title>
</head>
<body>
  <!-- Ordered list with Roman numerals -->
  <h2>Roman Numerals List</h2>
  <ol type="I">
    <li>First Item</li>
    <li>Second Item</li>
    <li>Third Item</li>
  </ol>

  <!-- External image -->
  <h2>External Image</h2>
  <img src="https://www.pexels.com/photo/example-image-url.jpg" alt="Beautiful Scenery from Pexels" width="500">

  <!-- Table of Contacts -->
  <h2>Contacts Table</h2>
  <table border="1">
    <thead>
      <tr>
        <th>Name</th>
        <th>Address</th>
        <th>Mobile</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>John Doe</td>
        <td>123 Main St, Nairobi</td>
        <td>+254700123456</td>
        <td>johndoe@example.com</td>
      </tr>
      <tr>
        <td>Jane Smith</td>
        <td>456 Elm St, Mombasa</td>
        <td>+254711234567</td>
        <td>janesmith@example.com</td>
      </tr>
      <tr>
        <td>Michael Kimani</td>
        <td>789 Oak St, Kisumu</td>
        <td>+254722345678</td>
        <td>mkimani@example.com</td>
      </tr>
      <tr>
        <td>Mary Wanjiku</td>
        <td>321 Pine St, Nakuru</td>
        <td>+254733456789</td>
        <td>mwanjiku@example.com</td>
      </tr>
      <tr>
        <td>Peter Otieno</td>
        <td>654 Birch St, Eldoret</td>
        <td>+254744567890</td>
        <td>potieno@example.com</td>
      </tr>
    </tbody>
  </table>

  <!-- Registration Form -->
  <h2>Registration Form</h2>
  <form action="#" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
    
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
    
    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required><br><br>
    
    <label for="gender">Gender:</label>
    <input type="radio" id="male" name="gender" value="Male">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="Female">
    <label for="female">Female</label><br><br>
    
    <label for="hobbies">Hobbies:</label>
    <input type="checkbox" id="reading" name="hobbies" value="Reading">
    <label for="reading">Reading</label>
    <input type="checkbox" id="traveling" name="hobbies" value="Traveling">
    <label for="traveling">Traveling</label>
    <input type="checkbox" id="sports" name="hobbies" value="Sports">
    <label for="sports">Sports</label><br><br>
    
    <label for="country">Country:</label>
    <select id="country" name="country" required>
      <option value="">--Select Your Country--</option>
      <option value="kenya">Kenya</option>
      <option value="uganda">Uganda</option>
      <option value="tanzania">Tanzania</option>
    </select><br><br>
    
    <button type="submit">Register</button>
  </form>
</body>
</html>
