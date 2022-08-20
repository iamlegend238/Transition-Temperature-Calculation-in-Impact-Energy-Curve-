# Transition-Temperature-Calculation-in-Impact-Energy-Curve-
Here the T1, T3, T5 temperature are calculated using the values given. The values are impact energy (vs) temperature. 
The code also plots line + scatter of the points in the given data.    
In the first part of the code we convert the code we convert the txt file into an array.
Two array are created one for the x - axis values and other for the y - axis values. 
The values are then used for the calculation of the T1, T3 and T5 values.
T1 value is the temperature in the upper shelf of the impact energy curve having the highest imapct energy.
T5 value is the temperature in the lower shelf of the impact energy curve having the lowest imapct energy.
T3 is calculated by the following method.
  - We take 6 points from the upper shelf
  - We take 6 points from the lower shelf
  - Average of these 12 values is taken
  - The average is nothing but temperature average
