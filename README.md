open linux terminal 
downlaod python using apt install python 
using command nano phish_check_gui.py
write scripting
run as python phish_check_gui.py
u get the output
# Phishing Detection Tool

A desktop application that analyzes URLs and identifies potential phishing attempts using a weighted scoring system across multiple security checks.

## Features
- Analyzes URLs against 8 distinct phishing indicators
- Weighted scoring system to calculate an overall risk score
- Simple desktop GUI for easy input and instant results
- Clear risk classification (safe / suspicious / high risk)

## Tech Stack
- **Language:** Python
- **GUI:** Tkinter

## How It Works
The tool checks a given URL against 8 weighted criteria (e.g. suspicious domain patterns, URL length, presence of special characters, HTTPS usage, and other common phishing indicators). Each check contributes a weighted score, which is combined into a final risk assessment shown to the user.

## Installation
```bash
git clone https://github.com/Gallasoumya/phishing-detection-tool.git
cd phishing-detection-tool
python main.py
