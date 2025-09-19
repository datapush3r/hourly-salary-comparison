# **Australian Salary Comparison Calculator**

A comprehensive, single-page web application to realistically compare a contract role's take-home pay against a full-time employee's salary package in Australia.  
This tool goes beyond simple conversions by accounting for the hidden costs of contracting and providing detailed tax calculations. It allows contractors and permanent employees to make truly informed financial decisions.

## **Features**

* **Side-by-Side Comparison:** Directly compare a **Contract Role** (based on hourly/daily rate) with a **Full-time Role** (based on annual salary).  
* **Realistic Contractor Adjustments:**  
  * **Unpaid Leave:** Option to factor in 4 weeks of annual leave and 2 weeks of personal leave, showing the impact on a contractor's billable year.  
  * **Public Holidays:** Automatically subtracts the correct number of public holidays from a contractor's billable days based on the selected state or territory.  
* **Advanced Tax Options:**  
  * **HECS/HELP Debt:** Includes a toggle to add compulsory student loan repayments to the tax calculation based on official ATO thresholds.  
  * **Medicare Levy Surcharge (MLS):** Includes a toggle for the MLS for high-income earners without private health insurance.  
* **Detailed Income Breakdown:** View your estimated take-home pay broken down by yearly, quarterly, monthly, fortnightly, weekly, daily, and hourly rates for both roles.  
* **Clear Final Summary:** A dedicated section shows the exact monetary difference in yearly take-home pay, highlighting which role is more lucrative after all adjustments and taxes.  
* **Real-Time Calculations:** All financial figures update instantly as you type.  
* **Self-Contained & Responsive:** The entire application is a single, easy-to-run HTML file with a clean, modern interface that works on all devices.

## **How to Use**

1. Download the salary-calculator.html file.  
2. Open the file in any modern web browser.  
3. In the **Comparison Adjustments** section, select your state and toggle the options for unpaid leave, HECS/HELP, and MLS to match your personal circumstances.  
4. Enter your rate into the **Contract Role** column or your salary into the **Full-time Role** column to see the live results.

## **Tech Stack**

* **HTML:** For the structure of the application.  
* **Tailwind CSS:** For all styling and layout, loaded via a CDN.  
* **JavaScript (ES6):** For all the calculation logic and DOM manipulation.

## **Disclaimer**

This calculator is intended for estimation and informational purposes only. The tax calculations are based on standard 2024-2025 ATO rates and do not account for all individual circumstances (e.g., specific tax offsets, family tax benefits, etc.). Always consult with a certified financial advisor for professional advice tailored to your situation.
