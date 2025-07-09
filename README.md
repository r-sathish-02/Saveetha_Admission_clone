# Saveetha_Admission_clone
## Date:

## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
<!DOCTYPE html>
<html>
    <head>
        <title>Saveetha Engineering College</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>

        <div class="bg-img">
        <form class="form-box">
                <h2>Admissions Open 2025</h2>
                <br>
                <input type="text" placeholder="Enter Name *" required>
                <br> <br>
                <input type="email" placeholder="Enter Email Address *" required>
                <br><br>
                <input type="tel" placeholder="Enter Mobile Number *" required>
                <br><br>
                <input type="password" placeholder="Any Password of Your Choice *" required>
                <br><br>
                
                <select required>
                    <option value="" disabled selected>State *</option>
                    <option>Tamil Nadu</option>
                    <option>Karnataka</option>
                    <option >Kerala</option>
                    <option>Andhra Pradesh</option>
                </select>
                <select required>
                    <option value="" disabled selected>City *</option>
                    <option>Chennai</option>
                    <option>Coimbatore</option>
                </select>
                
                <br><br>
                
                <select required>
                    <option value="" disabled selected>Course *</option>
                    <option>CSE</option>
                    <option>AIDS</option>
                    <option>AIML</option>
                    <option>ECE</option>
                </select>
                <select required>
                    <option value="" disabled selected>Specialization *</option>
                    <option>VLSI</option>
                    <option>Cyber Security</option>
                    <option>IOT</option>
                </select>
                <br><br>
                <div class="right-side">
                <input class="checkbox" type="checkbox" id="terms" name="terms" required>
                <label for="terms">
                    I authorise Saveetha Engineering College & its representatives to contact me with updates and notifications via Email/SMS/What'sApp/Call. This will override DND/NDNC *
                </label>
                </div>
                <br><br>
                <button>APPLY NOW <span style='font-size:15px;'>&#10095;</span></button>
                <br><br>
                <p>Already have an Account? <a href="index.html">Login</a></p>
                <br>
                <p>Resend Verification Email</p>
        </form>
        </div>
    </body>
</html>

## CSS Code:
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html, body {
  height: 100%;
  font-family: Arial, sans-serif;
}

.bg-img {
  background-image: url("bg.jpg");
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding: 20px;
}

.form-box {
  width: 500px;
  padding: 16px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
  background-color: rgba(0, 0, 0, 0.6); 
  overflow-y: auto;
  max-height: 90vh; 
}

input, select {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  border: none;
}

select {
  width: 49%;
}

label, p, h2 {
  color: white;
  font-size: 13px;
}

h2 {
  text-align: center;
}

.right-side {
  display: flex;
  align-items: flex-start;
  gap: 10px;
  color: white;
  font-size: 13px;
}

.checkbox {
  margin-top: 3px;
}

button {
  width: 100%;
  padding: 10px;
  background-color: #e28743;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
p{
  text-align: center;
}
a{
  color: white;
}
## Output:
![image](https://github.com/user-attachments/assets/e6630822-7e20-4665-b057-6d1527970cd8)

## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.
