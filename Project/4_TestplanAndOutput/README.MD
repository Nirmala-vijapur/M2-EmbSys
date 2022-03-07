|NO|Test case|Test case Objective                                                   |prerequisite |Input data        |Expected Result           |Actual Result            |status|
|:-|:--------|:---------------------------------------------------------------------|:------------|:-----------------|:-------------------------|:------------------------|:-----|
|1 |TC-1     |set the tempareture value at 0 and display the result on LCD display  |temp,fanspeed|0 degree celsius  |temp:0, fanspeed:0        |temp:0,fanspeed:0        |Pass  |
|2 |TC-2     |set the tempareture value at 24 and display the result on LCD display |temp,fanspeed|24 degree celsius |temp:24, fanspeed:0       |temp:24,fanspeed:5       |Fail  |
|3 |TC-3     |set the tempareture value at 42 and display the result on LCD display |temp,fanspeed|42 degree celsius |temp:42, fanspeed:20      |temp:42,fanspeed:20      |Pass  |
|4 |TC-4     |set the tempareture value at 67 and display the result on LCD display |temp,fanspeed|67 degree celsius |temp:67, fanspeed:46      |temp:67,fanspeed:46      |Pass  | 
|5 |TC-5     |set the tempareture value at 85 and display the result on LCD display |temp,fanspeed|85 degree celsius |temp:85,fanspeed:53,LEDON |temp:85,fanspeed:53,LEDON|Pass  | 
|6 |TC-6     |set the tempareture value at 111 and display the result on LCD display|temp,fanspeed|111 degree celsius|temp:111,fanspeed:83,LEDON|temp:111,fanspeed:83,LEDON|Pass |   
