# BMI_Calculator
This is a basic JavaScript implementation for calculating Body Mass Index (BMI) based on user input for height (in centimeters) and weight (in kilograms).

# 🚀 Overview

The script listens for a form submission, validates the input values, calculates the BMI using the standard formula, and displays the result.

# ⚙️ Logic & Formula

The calculation uses the standard BMI formula, assuming:

Height is provided in centimeters (cm).

Weight is provided in kilograms (kg).

$$\text{BMI} = \frac{\text{Weight (kg)}}{\text{Height (cm)}^2} \times 10,000$$

The calculation uses the parseInt() method to ensure inputs are treated as whole numbers before calculating the BMI.

# 📝 Key Features

**Input Validation**: Ensures height and weight are numerical, positive, and non-empty.

**BMI Calculation**: Converts centimeter height to meters for the final calculation.

**Categorization**: Provides an interpretation of the BMI score:

- Less than 18.6: Underweight

- 18.6 - 24.9: Normal Range

- Greater than 24.9: Overweight
