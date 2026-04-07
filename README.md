# WALMART-Predictive-Maintenance-
AIM

To compute the equipment health score using sensor data for predictive maintenance.

PROCEDURE
Initialize temperature (T) and vibration (V) values
Apply the formula: Health = 100 − (0.4T + 1.1V)
Substitute the given values
Compute the health score
Display the result
CODE
# Input values
T = 80   # temperature
V = 10   # vibration

# Health calculation
health = 100 - (0.4 * T + 1.1 * V)

# Output
print("Health Score:", health)
OUTPUT

Health Score: 56

RESULT

The health score is 56, indicating moderate equipment condition and the need for maintenance planning.
