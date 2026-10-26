# Building Electricity Calculator

A simple web app that splits a building's electricity bill between apartments using each apartment's sub-meter readings, replacing the monthly manual calculation.

**App link:** https://saja-saeed.github.io/kahraba/

<img src="screenshot.png" alt="App screenshot" width="320">

## Features

- Calculates each apartment's consumption from the previous and current meter readings.
- Two billing methods:
  - **Split the bill:** divides the main meter's bill between apartments in proportion to each one's consumption.
  - **Fixed rate:** multiplies consumption by a price per kWh, with an option to add 15% VAT.
- Adds a monthly meter fee per apartment, either on top of the bill or deducted from it.
- Saves each month, and the next month starts from the last saved readings.
- Copies a ready-to-send message for each tenant with their amount and readings.
- Works offline after the first visit.

## Install on your phone

**iPhone:** open the link in Safari → tap Share → Add to Home Screen

**Android:** open the link in Chrome → tap the three-dot menu → Install app

## How to use

The app's interface is in Arabic. Button names are given below with their meaning.

1. On first use, tap «امسحها وابدأ» (Clear and start) to remove the example numbers.
2. Under «إدارة الشقق» (Manage apartments), add your apartments and tenant names.
3. Choose the billing method and enter the meter fee.
4. Each month, enter each apartment's current reading and the bill amount, then tap «حفظ الشهر» (Save month).
5. Tap «نسخ» (Copy) next to each apartment and send it to the tenant.

## Data and privacy

All data is stored only on the device and is never sent anywhere. Deleting the app or clearing the browser's data erases it, so use «تنزيل نسخة احتياطية» (Download backup) regularly, and «استرجاع من ملف» (Restore from file) when moving to a new phone.

## Files

| File | Purpose |
|---|---|
| `index.html` | The app |
| `manifest.webmanifest` | App name, icons and install settings |
| `sw.js` | Service worker for offline use |
| `icon-*.png`, `apple-touch-icon.png` | App icons |
