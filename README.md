# EmSys: Lab1 logbook 

### Secret Word
> Answer the following:

> 1. What was the secret word begin transmitted via UART on your device? __[1 mark]__
> 2. What pin was it transmitting on? __[1 mark]__ 
> 3. What was the baud rate it was transmitting at? __[1 mark]__

--------------------------------

### Hello World
> Complete the following:

> 1. Commit a sketch [HelloWorld/HelloWorld.ino](HelloWorld/HelloWorld.ino) that prints a message of your choice __[1 mark]__
> 2. Include a screenshot of your message caputred on ``pulseview`` __[1 mark]__ 

--------------------------------

### Square Wave Generator
> Answer/Complete the following:

> __Part one:__
> 1. What is the highest frequency possible with ```digitalWrite()```? Commit your code in [SquareWaveGen/Task1/Task1.ino](SquareWaveGen/Task1/Task1.ino)  __[1 mark]__
> 2. Was there anything unsual about the output? If there was, speculate/discuss what it might be? __[3 marks]__
> 3. What is the maximum frequency possible generating two square waves with ```digitalWrite()```? Commit your code in [SquareWaveGen/Task1/Task2.ino](SquareWaveGen/Task1/Task2.ino) __[1 mark]__
> 4. How has the maximum frequency changed and why? __[2 marks]__
> 5. Estimate how long ```digitalWrite()``` takes to execute and the loop overheads. Include screenshots from ``pulseview`` to support your answer. __[3 marks]__  
> 6. Use your measurements from 5 calculate an estimate for the max frequency when generating three square waves. __[2 marks]__
> 7. Measure the maximum frequency when generating three square waves with ```digitalWrite()```, report it in your logbook, include ``pulseview`` screenshots, and commit the code in [SquareWaveGen/Task3/Task3.ino](SquareWaveGen/Task3/Task3.ino). How did the actual measurement compare to your estimated one? __[2 marks]__ 


> __Part two:__
> 1. What is the maximum frequency single square wave you can generate when directly writing to hardware registers? Include ``pulseview`` screenshots. Commit your code in [SquareWaveGen/Task4/Task4.ino](SquareWaveGen/Task4/Task4.ino). __[3 marks]__

> 2. Modify the code in the point above to generate 6 square waves with the maximum frequency. What is the new maximum frequency you can measure? Include ``pulseview`` screenshots. Commit your code in [SquareWaveGen/Task5/Task5.ino](SquareWaveGen/Task5/Task5.ino) __[3 marks]__
> 3. Modify the code again to generate 8 square waves with the highest frequency possible using direct hardware register manipulation. Report the new maximum frequency, include ``pulseview`` screenshots, and commit your code to [SquareWaveGen/Task6/Task6.ino](SquareWaveGen/Task6/Task6.ino). __[3 marks]__ 
> 4. Compare the maximum frequency generated for 6 and 8 square waves and comment on if they are the same or different and why. __[2 marks]__

----------------------------
### dotDevice 
> Answer/Complete the following:

> __Part one:__
> 1. Make your dotDevice say something. Include a screenshot and commit the code to [dotDevice/Task1/Task1.ino](dotDevice/Task1/Task1.ino) __[2 marks]__
> 2. Make your dotDevice dance. Commit the code to [dotDevice/Task2/Task2.ino](dotDevice/Task2/Task2.ino) __[2 marks]__
> 3. Make your dotDevice change colour periodically. Commit the code to [dotDevice/Task3/Task3.ino](dotDevice/Task3/Task3.ino) __[2 marks]__
> 4. Make your dotDevice change size. Commit the code to [dotDevice/Task4/Task4.ino](dotDevice/Task4/Task4.ino) __[2 marks]__
> 5. Add some discussion on difficulties and debugging strategies __[2 marks]__

>__Part two:__
> 1. Use the dotDevice on-board memory to load commands to perform actions similar to part one. Commit your code to [dotDevice/Task5/Task5.ino](dotDevice/Task5/Task5.ino) __[6 marks]__
> 2. Discuss the differences between using the on-board dotDevice programmable command memory vs continuously sending commands. What are the tradeoffs? __[6 marks]__ 

