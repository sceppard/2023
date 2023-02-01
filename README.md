# 2023
 <!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out this survey form to help us improve our service. Thank you for your time.</p>
    <form id="survey-form">
      <label for="name" id="name-label">Name:</label>
      <input type="text" id="name" name="name" required placeholder="Enter your name">
      <label for="email" id="email-label">Email:</label>
      <input type="email" id="email" name="email" required placeholder="Enter your email">
      
      <label for="number" id="number-label">Number:</label>
      <input type="number" id="number" name="number" min="1" max="10" placeholder="Enter a number between 1 and 10">
      
      <label for="dropdown">Choose an option:</label>
      <select id="dropdown" name="dropdown">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
      </select>
      
      <div>
        <input type="radio" id="radio1" name="radio" value="radio1">
        <label for="radio1">Radio 1</label>
        
        <input type="radio" id="radio2" name="radio" value="radio2">
        <label for="radio2">Radio 2</label>
      </div>
      
      <div>
        <input type="checkbox" id="checkbox1" name="checkbox1" value="checkbox1">
        <label for="checkbox1">Checkbox 1</label>
        
        <input type="checkbox" id="checkbox2" name="checkbox2" value="checkbox2">
        <label for="checkbox2">Checkbox 2</label>
      </div>
      
      <label for="comments">Additional comments:</label>
      <textarea id="comments" name="comments"></textarea>
      
      <button id="submit" type="submit">Submit</button>
    </form>
  </body>
</html>

