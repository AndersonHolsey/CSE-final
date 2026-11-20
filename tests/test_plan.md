Test 1: Normal Temperature
Test:
Enter a temperature of 72°F.
Expected Result:
The system displays NORMAL and the LED remains OFF.
Actual Result:
The system displayed NORMAL and the LED remained OFF.
Test 2: High Temperature
Test:
Enter a temperature of 80°F.
Expected Result:
The system displays WARNING and the LED turns ON.
Actual Result:
The system displayed WARNING and the LED turned ON.
Test 3: Low Temperature
Test:
Enter a temperature of 65°F.
Expected Result:
The system displays WARNING and the LED turns ON.
Actual Result:
The system displayed WARNING and the LED turned ON.
Test 4: Change Temperature Range
Test:
Change the acceptable range from 68°F-76°F to 70°F-75°F.
Expected Result:
The program updates the range and uses the new values for temperature checks.
Actual Result:
The acceptable temperature range was successfully updated.
Test 5: Average Temperature Calculation
Test:
Enter temperatures of 70°F and 74°F.
Expected Result:
The average temperature displayed is 72°F.
Actual Result:
The program correctly calculated and displayed an average of 72°F.
Test 6: Data Logging
Test:
Enter a temperature reading and check temperature_log.csv.
Expected Result:
The temperature, status, LED state, and average are saved to the CSV file.
Actual Result:
The data was successfully written to temperature_log.csv.
Test 7: Status File Update
Test:
Enter a temperature of 80°F and check status.txt.
Expected Result:
The file contains WARNING.
Actual Result:
The file was updated with WARNING.
Test 8: Program Exit
Test:
Select menu option 3.
Expected Result:
The program exits and the LED turns OFF.
Actual Result:
The program closed successfully and the LED turned OFF.
