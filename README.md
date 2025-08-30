# BMR & CPM Calculator 🔥

BMR & CPM Calculator is a simple web application that calculates your **Basal Metabolic Rate (BMR/PPM)** and **Total Daily Energy Expenditure (TDEE/CPM)**.  
The app lets you input your personal details, choose activity level, workout frequency, and your goal (weight loss, maintenance, or muscle gain).  

## Features ✨

- BMR calculation 🧮: Computes daily basal metabolic rate based on Mifflin–St Jeor formula.  
- TDEE calculation ⚡: Adjusts energy needs according to activity level, workouts, and goal.  
- Goal-based results 🎯: Weight loss, maintenance, or bulking with adjusted calorie needs.  
- Gender-specific formula 👩👨: Different equation for men and women.  
- Dynamic UI update 📊: Results appear instantly after form submission.  
- Error handling 🚨: Prevents form submission without required values.  
- Simple & responsive 💻📱: Works across browsers and devices.  

## Usage 🖱️

1. Select gender (male/female).  
2. Enter your weight (kg), height (cm), and age (years).  
3. Choose activity level and workout frequency.  
4. Select your goal:  
   - Lose weight  
   - Maintain weight  
   - Gain weight  
5. Submit the form and check your BMR (PPM) and CPM results.  

## Technologies used 💻

- Vanilla JavaScript (ES6+)  
- HTML5 (form inputs, selects, radio buttons)  
- CSS3 (basic styling, visibility toggle)  

## JavaScript skills used 🛠️

- DOM manipulation (`querySelector`, `innerHTML`, `classList`)  
- Form handling (`submit` event, `preventDefault`)  
- Conditional logic (`if/else`, `switch`)  
- Arithmetic calculations (Mifflin–St Jeor formula & multipliers)  
- String and number formatting (`Math.round`)  

## Code Structure 🏗️

- **Form submission handler**: Collects all input values and prevents page reload.  
- **BMR formula function**: Calculates PPM based on gender, weight, height, and age.  
- **TDEE calculation**: Adjusts PPM with activity level, workouts, and goal multipliers.  
- **UI update**: Dynamically shows calculated values and reveals results section.  

## License 📄

This project is open source and available under the MIT License.  

## 📦 Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-tracker.git
2. Navigate to the project directory::
   ```bash
   cd task-tracker
3. Open index.html in your browser.

No build tools or dependencies required – it’s 100% client-side!
