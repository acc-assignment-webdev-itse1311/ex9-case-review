# Tutorial 9 - Review

## Instructions:
1. Use your editor to open the tny_july_txt.html and tny_timer_txt.js files from the html09 > review folder. Enter your name and the date in the comment section of each file, and save them as tny_july.html and tny_timer.js respectively
2. Go to the tny_july.html file in your editor. Directly above the closing </head> tag, insert a script element that links to the tny_timer.js file. Defer the loading of the script file until the web page loads
3. Take some time to study the content and structure of the file, paying close attention to the id attributes applied to different page elements. Save your changes to the document
4. Go to the tny_timer.js file in your editor. At the top of the file, insert a statement to tell the browser to apply strict usage of the JavaScript code in the file
5. Directly above the nextJuly4() function, insert a function named showClock() that has no parameters. Within the showClock() function, complete Steps i through vi. 
   1. Declare a variable named thisDay that stores a Date object containing the date May 19, 2018 at 9:31:27 a.m. 
   2. Declare a variable named localDate that contains the text of the date from the thisDay variable using local conventions. Declare another variable named localTime that contains the text of the time stored in the thisDay variable using local conventions.
   3. Within the inner HTML of the page element with the ID currentTime, write the following code <span>date</span><span>time</span> where date and time are the values of the localDate and localTime variables.
   4. Hector has supplied you with a function named nextJuly4() that returns the date of the next 4th of July. Call the nextJuly4() function using thisDay as the parameter value and store the date returned by the function in the j4Date variable.
   5. The countdown clock should count down to 9 p.m. on the 4th of July. Apply the setHours() method to the j4Date variable to change the hours value to 9 p.m. (Hint: Express the value for 9 p.m. in 24-hour time.)
   6. Create variables named days, hrs, mins, and secs containing the days, hours, minutes, and seconds until 9 p.m. on the next 4th of July. (Hint: Use the code from the tny_script.js file in the tutorial case as a guide for calculating these variable values.)
   7. Change the text content of the elements with the IDs "dLeft", "hLeft", "mLeft", and "sLeft" to the values of the days, hrs, mins, and secs variables rounded down to the next lowest integer

6. Directly after the opening comment section in the file, insert a command to call the showClock() function
7. After the command that calls the showClock() function, insert a command that runs the showClock() function every second
8. Document your work in this script file with comments
9. Save your changes to the file and then open the tny_july.html file in your browser. Verify that the page shows the date and time of May 19, 2018 at 9:31:27 a.m., and that the countdown clock shows that Summer Party fireworks will begin in 46 days, 11 hours, 28 minutes, and 33 seconds. The countdown clock will not change because the script uses a fixed date and time for the thisDay variable
10. Return to the tny_timer.js file in your editor. Change the statement that declares the thisDay variable so that it contains the current date and time rather than a specific date and time
11. Save your changes to the file and then reload the tny_july.html file in your browser. Verify that the countdown clock changes every second as it counts down the time until the start of the fireworks at 9 p.m. on the 4th of July