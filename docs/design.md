
The Smart Classroom Comfort Monitor allows users to enter classroom temperature readings in Fahrenheit.
The program compares each temperature to a user-defined acceptable range (default 68°F to 76°F).
If the temperature is within the range:
Status = NORMAL
LED = OFF
If the temperature is outside the range:
Status = WARNING
LED = ON
Each temperature reading, status, LED state, and running average are saved to temperature_log.csv.
The current status is written to status.txt.
The program runs through a menu that allows users to:
Enter a temperature reading.
Change the acceptable temperature range.
Exit the program.
