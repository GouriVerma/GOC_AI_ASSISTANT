
# AI-Powered Tax Assistant - ITR Selection & Filing
The solution is not built completely, this is the overview of solution

## Overview
The AI-Powered Tax Assistant is a Chrome extension designed to simplify the process of filing Income Tax Returns (ITR) in India. It provides an intuitive questionnaire to help users determine the correct ITR form, automates complex tax calculations, and assists with pre-filling data on the ITR website. This tool empowers individuals to file their taxes accurately and independently without requiring external assistance.

## Features
- **ITR Selection Questionnaire**: Step-by-step guided questionnaire to determine the appropriate ITR form (ITR-1 to ITR-7).
- **Automated Tax Calculations**: Handles complex income calculations, including salary, house property, mutual funds, and business income.
- **Document-Based Autofill**: Extracts data from uploaded PDFs (salary slips, Form 16, bank statements) to pre-fill tax forms.
- **Query Resolution**: Provides explanations and guidance on tax-related queries using verified sources.
- **Presumptive Taxation Support**: Identifies eligibility under Sections 44AD and 44ADA for small businesses and professionals.

## How It Works
### **Step 1: Identify Taxpayer Type**
- Individual → Proceed to Step 2
- HUF → Proceed to Step 2
- Partnership Firm → Likely ITR-5
- Company → Likely ITR-6
- Trust → Likely ITR-7

### **Step 2: Determine Residential Status**
- Resident → Proceed to Step 3
- Non-Resident → ITR-2 or ITR-3 required

### **Step 3: Identify Primary Source of Income**
- Salary → Proceed to Step 4
- Business/Profession → Proceed to Step 10

### **Step 4-9: Salaried Individuals**
- **Income Check**: Determines if total annual income is above ₹50 lakh (ITR-2 required).
- **Presumptive Income Check**: Identifies applicability of ITR-4 for small businesses/professionals.
- **House Property Income**: Determines ITR-1 (single house) or ITR-2 (multiple properties).
- **Investment Income**: Identifies capital gains from stocks, mutual funds, and crypto trading.
- **Special Income Conditions**: Checks for lottery income, foreign assets, director status, etc.

### **Step 10-13: Business/Profession Taxpayers**
- **Presumptive Taxation Check**: Determines eligibility for ITR-4.
- **Capital Gains Check**: Identifies ITR-3 for stock trading.
- **Additional Conditions**: Flags complex cases requiring ITR-3.

### **Final ITR Form Selection**
- ✅ **ITR-1**: Salaried individuals, single house, no capital gains.
- ✅ **ITR-2**: Multiple properties, capital gains, high income, foreign income/assets.
- ✅ **ITR-3**: Business/profession with detailed accounting, directors, foreign income.
- ✅ **ITR-4**: Presumptive taxation for small businesses & professionals.

## Installation
1. Download the Chrome extension package.
2. Install it from the Chrome Web Store (or load unpacked in Developer Mode).
3. Open the ITR filing website and let the extension assist you.

## Benefits
- **Simplifies tax filing**: No need for external help.
- **Reduces errors**: Automated calculations minimize mistakes.
- **Saves time**: Prefilling and guided assistance streamline the process.
- **Educates users**: Provides insights on tax benefits and deductions.


