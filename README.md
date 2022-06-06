# digital-clock
<p>Clocks are useful element for any UI if used in a proper way. Clocks can be used in sites where time is the main concern like some booking sites or some app showing arriving times of train, buses, flights, etc. Clock is basically of two types, Analog and Digital. We will be looking at making a digital one. </p>
<hr>
<p?<b>Approach:</b> The approach is to use the date object to get time on every second and then re-rendering time on the browser using the new time that we got by calling the same function each second.</p> 
<hr>
<h2>JavaScript Code: For JavaScript, follow the below given steps.</h2>
<pre>
Step 1: Create a function “showTime”.
Step 2: Create an instance of the Date object.
Step 3: Using the methods of Date object get “hours”, “minute” and “seconds”.
Step 4: Set AM/PM depending on the hour value. The Date object works on 24-hour format so we change hour back to 1 when it get’s larger than 12. The AM/PM also changes according to that.
Step 5: Now make a string using the same HH:MM:SS format changing the hour, minute, and second value with the values, we get from Date object methods.
Step 6: Now replace the string variable in the “div” using innerHTML property.
Step 7: To call the function every second use setInterval() method and set time-interval as 1000ms which is equal to 1s.
Step 8: Now call the function at the end to start function at exact reloading/rendering time as setInterval() will call first after 1s of rendering.
</pre>
<hr>
<p> I am using some CSS also to style my page.</p>
<hr>
<h2>OUTPUT</h2>
![Screenshot (211)](https://user-images.githubusercontent.com/92047366/172159798-80c2edce-887a-4e6c-9032-26cd2a72cef9.png)
