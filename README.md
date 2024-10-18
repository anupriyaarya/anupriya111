<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Application Form</title>
</head>
<body>
    <h1>Application Form</h1>
    <p>Note: Form is to be completed at least 21 days prior to date</p>
    
    <form>
        <h2>Personal Details</h2>
        
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Enter name here"><br>
        
        <label for="address">Address:</label>
        <input type="text" id="address" placeholder="Enter address here"><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter email here"><br>
        
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" placeholder="Enter 10 digit number"><br>
        
        <label for="iq">IQ:</label>
        <input type="number" id="iq" placeholder="Enter IQ here"><br>
        
        <h3>Gender</h3>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br>
        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label><br>
        
        <label for="date">Date of Proposed Outing:</label>
        <input type="date" id="date"><br>
        
        <h3>Check All That Apply</h3>
        <input type="checkbox" id="tattoos">
        <label for="tattoos">I have tattoos and/or piercings</label><br>
        <input type="checkbox" id="older">
        <label for="older">I am more than 2 years older than my daughter</label><br>
        <input type="checkbox" id="van">
        <label for="van">I own a panel van or V8 ute</label><br>
        <input type="checkbox" id="fulltime">
        <label for="fulltime">I work full-time</label><br>
        <input type="checkbox" id="rich">
        <label for="rich">My parents are rich</label><br>
        <input type="checkbox" id="public">
        <label for="public">Is the date at a well lit public location</label><br>
        
        <label for="politics">Political Persuasion:</label>
        <select id="politics">
            <option value="left">Left Wing</option>
            <option value="right">Right Wing</option>
            <option value="center">Center</option>
        </select><br>
        
        <label for="education">Education Level Completed:</label>
        <select id="education">
            <option value="highschool">High School</option>
            <option value="college">College</option>
            <option value="university">University</option>
        </select><br>
        
        <h3>Essay Section</h3>
        <textarea rows="4" cols="50" placeholder="Enter your essay here"></textarea><br>
        
        <input type="submit" value="Submit">
    </form>
</body>
</html>
