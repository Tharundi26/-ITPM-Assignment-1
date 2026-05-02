# ITPM Assignment 1 - Option 1 
 
## Student Registration Number 
IT23578432 
 
## How to Run Tests 
 
### Prerequisites 
```bash 
pip install playwright openpyxl 
playwright install 
``` 
 
### Run Automation 
```bash 
python test_automation.py --excel "it23578432.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 
``` 
 
## Test Cases Summary 
- Total Test Cases: 52 
- Positive Test Cases: Pos_Fun_0001 to Pos_Fun_0044 
- Negative Test Cases: Neg_Fun_0001 to Neg_Fun_0014
