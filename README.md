# BMI Calculator

A simple and interactive **Body Mass Index (BMI)** Calculator built using **React.js**. This tool helps users determine their BMI based on their height and weight, providing a classification (e.g., underweight, normal, overweight, or obese).

---

## Features

- **Real-Time Calculation**: Automatically calculates BMI as the user enters height and weight.
- **Responsive Design**: Works seamlessly across desktops, tablets, and mobile devices.
- **Categorization**: Provides BMI categories based on the calculated value.
- **Clear Inputs**: Reset button to clear all inputs and results.

---

## Live Demo

Check out the live demo here: [BMI Calculator Demo](#)

---

## Installation

Follow these steps to run the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/bmi-calculator.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd bmi-calculator
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start the development server**:
   ```bash
   npm start
   ```

5. Open your browser and go to: `http://localhost:3000`

---

## Usage

1. Enter your **weight** in kilograms (kg).
2. Enter your **height** in centimeters (cm).
3. The BMI will be calculated automatically and displayed along with the category.
4. Use the **Reset** button to clear all inputs and results.

---

## Technologies Used

- **React.js**: Frontend library for building the user interface.
- **CSS**: Styling for responsive and clean design.
- **JavaScript**: Core logic for BMI calculations.

---

## Formula for BMI

BMI is calculated using the formula:

\[ \text{BMI} = \frac{\text{weight (kg)}}{(\text{height (m)})^2} \]

To convert height from centimeters to meters:

\[ \text{Height (m)} = \frac{\text{Height (cm)}}{100} \]

---

## Folder Structure

```
.
├── public
│   └── index.html
├── src
│   ├── components
│   │   └── BMICalculator.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── package.json
└── README.md
```

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.
---
## Acknowledgements

- Inspired by the idea of promoting health awareness through simple tools.

---



