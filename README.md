# Ex.05 Design a Website for Server Side Processing
## Date:27/09/2025

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
BMi = W/H<sup>2</sup>
<br> BMI --> body mass index 
<br> H --> Height
<br> W --> Weight

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title>BMI Calculator</title>
</head>
<body bgcolor="lightblue">
    <center>
        <h2>BMI Calculator</h2>
        <form method="POST">
            {% csrf_token %}
            <label>Height (m):</label><br>
            <input type="text" name="height"><br><br>
            <label>Weight (kg):</label><br>
            <input type="text" name="weight"><br><br>
            <button type="submit">Calculate</button>
        </form>

        

        {% if BMI %}
            <h3>Your BMI is: {{ BMI }}</h3>
        {% endif %}
    </center>
</body>
</html>
```

## SERVER SIDE PROCESSING:
![alt text](<Screenshot 2025-09-27 162001.png>)

## HOMEPAGE:
![alt text](<Screenshot 2025-09-27 160307.png>)

## RESULT:
The program for performing server side processing is completed successfully.
