+++
Title = "Time"
date = "2016-11-30T21:30:33-05:00"

+++
[//]:<> (LESSON STARTS HERE)
<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<i>Lesson created by Vincent Macri</i>
			<p>The universe was created on January 1st, 1970.</p>
			<p>This lesson will teach you how to keep track of time. The general idea is to get the difference between the current time, and when the timer started.</p>
		</div>
	</div>
</div>
[//]:<> (LESSON STARTS HERE)
[//]:<> (CODE STARTS HERE)
<div id = "Code" class = "container">
	<div class = "row">
		<div class = "col-md-4">
			<h3>Turing</h3>
			<pre class="language-turing line-numbers">
				<code>var startTime, endTime : int % Declare the two variables to keep track of time.
startTime := Time.Sec % Set startTime to the number of seconds since the start of the universe (1970).
% Do stuff
delay(5000) % Wait 5 seconds, for demonstration purposes.
endTime := Time.Sec % Set endTime to the number of seconds since the start of the universe (1970).
put(endTime - startTime) % Output the difference between startTime and endTime.

% Note: Turing rounds passed time somewhat unpredictably. It's accurate enough for most purposes, however.
</code>
			</pre>
		</div>
		<div class = "col-md-4">
			<h3>Python</h3>
			<pre class="language-python line-numbers">
				<code>import time # Import the time module, so we can use the time functions.
startTime = time.time() # Set startTime to the number of seconds since the start of the universe (1970).
time.sleep(5); # Wait 5 seconds, for demonstration purposes.
endTime = time.time() # Set endTime to the number of seconds since the start of the universe (1970).
print(endTime - startTime) # Output the difference between startTime and endTime.

# Note: In Python, time.time() returns the time since the start of the universe in seconds as a float. The precision can vary between machines however. It is not guaranteed to be more precise than 1 second.</code>
			</pre>
		</div>
		<div class = "col-md-4">
			<h3>Java</h3>
			<pre class="language-java line-numbers">
				<code>long startTime = System.currentTimeMillis(); // Set startTime to the number of milliseconds since the start of the universe (1970).

	// Delays in Java are more verbose than in other languages.
	try {
		Thread.sleep(5000); // Wait for 5 seconds.
	} catch(InterruptedException e) { // Catch an error that can (but almost never does) occur when using Thread.sleep().
		e.printStackTrace(); // If there is an error (which there shouldn't be), print the error message.
	}


	endTime = System.currentTimeMillis(); // Set endTime to the number of milliseconds since the start of the universe (1970).
	System.out.println(endTime - startTime); // Output the difference between startTime and endTime.

	long timeNow = System.currentTimeMillis();</code>
			</pre>
		</div>
	</div>
</div>
[//]:<> (CODE ENDS HERE)
[//]:<> (LESSON STARTS HERE)
[//]:<> (SAMPLE STARTS HERE)
<div id = "Sample" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<h2> Sample Problem </h2>
			<p>Write a program that waits five seconds without using delay.</p>
		</div>
	</div>
</div>
[//]:<> (SAMPLE ENDS HERE)
