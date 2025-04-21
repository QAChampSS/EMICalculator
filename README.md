# 📊 EMI Calculator (Java)

This is a simple Java-based **EMI (Equated Monthly Installment) Calculator** that allows users to compute their monthly loan payments based on the principal amount, interest rate, and tenure.

---

## 🧾 Features

- Accepts loan input from the user: amount, interest rate, and duration.
- Calculates monthly EMI using standard EMI formula.
- Displays the calculated EMI in a user-friendly format.

---

## 🧮 Formula Used

The EMI is calculated using the following standard formula:

\[
\text{EMI} = P \times r \times \frac{(1 + r)^n}{(1 + r)^n - 1}
\]

Where:  
- `P` = Principal loan amount  
- `r` = Monthly interest rate (Annual Rate / 12 / 100)  
- `n` = Loan tenure in months (Years × 12)

---

## 🚀 How to Run

1. **Clone the repository or copy the code** into a file named `EMICalculator.java` inside a folder named `day4`.

2. **Compile the code:**
   ```bash
   javac day4/EMICalculator.java
   ```

3. **Run the program:**
   ```bash
   java day4.EMICalculator
   ```

4. **Follow the prompts** to enter the loan amount, interest rate, and tenure.

---

## 🛠 Requirements

- Java Development Kit (JDK) 8 or higher
- A terminal or command prompt to run the program

---

## 📂 Project Structure

```
EMICalculator/
└── day4/
    └── EMICalculator.java
```

---

## 📌 Example

```
Enter loan amount in USD
10000
Enter annual interest rate (in %)
10
Enter loan tenure in years
2
Your monthly EMI is: 461.45
```

---

## 📄 License

This project is released under the MIT License.

---
