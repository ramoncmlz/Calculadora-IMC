🇺🇸 English | 🇧🇷 [Português](README.pt-Br.md)

# 📱 BMI Calculator (Android)

A simple Android application for calculating BMI (Body Mass Index), developed in Kotlin. The app allows users to enter their weight, adjust their height using a slider, and quickly get the result.

---

## 🚀 Features

* Weight input via text field
* Height selection using a `SeekBar` (in centimeters)
* Dynamic display of selected height
* Automatic BMI calculation
* Result formatted to two decimal places
* Input validation:

  * Warning for invalid weight
  * Warning for invalid height
* Button to **clear all inputs**
* Simple and intuitive interface

---

## 🧮 Formula Used

The BMI is calculated using the standard formula:

```
BMI = weight / (height * height)
```

> Height is converted from centimeters to meters before the calculation.

---

## 🖥️ Interface

The app includes the following components:

* Weight input field
* Height slider (SeekBar)
* Text displaying selected height
* **Calculate** button
* **Clear** button
* Result display area

---

## ⚠️ Error Handling

The app handles common input errors to improve user experience:

* If the weight field is empty or invalid → shows a `Toast`
* If the height is zero → shows a `Toast`
* Prevents crashes using `try/catch`

---

## 🧹 Clear Button

When the **Clear** button is pressed, the app:

* Clears the weight input
* Resets height to 0
* Hides the height value
* Hides the BMI result

---

## 🛠️ Technologies Used

* Kotlin
* Android SDK
* XML (layouts)
* Android components:

  * `EditText`
  * `SeekBar`
  * `TextView`
  * `Button`
  * `Toast`

---

## 📌 Notes

* Height is selected in centimeters and internally converted to meters
* The result is displayed in the format: `BMI: XX.XX`
* The interface is designed for simplicity and quick usage

---

## 📄 License

This project is free to use and modify for learning purposes.

---
