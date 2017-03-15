+++
Title = "Strings"
date = "2017-02-11T21:30:33-05:00"

+++
<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<i>Lesson created by Vincent Macri</i>
			<p>Strings are variables that store sequences of characters. String manipulation is working with strings to turn an input into an output.</p>
		</div>
	</div>
</div>
<div id = "Code" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<ul class="nav nav-tabs tabs-3" role="tablist">
				<li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#turing" role="tab">Turing</a></li>
				<li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python" role="tab">Python</a></li>
				<li class="nav-item"><a class="nav-link" data-toggle="tab" href="#java" role="tab">Java</a></li>
			</ul>

			<div class="tab-content">
				<div id="turing" class="tab-pane fade in active">
					<pre class="language-turing line-numbers">
						<code>
							var myStr : string := "hello"

							put(myStr) % Print myStr.
							put(myStr(1)) % Print the first character in myStr.
							put(myStr(*)) % Print the last character in myStr.
							put(myStr(* - 1)) % Print the second last character in myStr.
						</code>
					</pre>
				</div>
				<div id="python" class="tab-pane fade">
					<pre class="language-python line-numbers">
						<code>
							myStr = "hello"

							print(myStr) # Print myStr.
							print(myStr[0]) # Print the first character in myStr.
							print(myStr[-1]) # Print the last character in myStr.
							print(myStr[-2]) # Print the second last character in myStr.
						</code>
					</pre>
				</div>
				<div id="java" class="tab-pane fade">
					<pre class="language-java line-numbers">
						<code>
							/*
							 * Strings in Java are objects.
							 * This will be explained further in later lessons.
							 * For now, just know that when you declare an object, the variable type is capitalized.
							 */
							String myStr = "hello";

							System.out.println(myStr); // Print myStr.
							System.out.println(myStr.charAt(0)); // Print the first character in myStr.
							System.out.println(myStr.charAt(myStr.length() - 1)); // Print the last character in myStr.
							System.out.println(myStr.charAt(myStr.length() - 2)); // Print the second last character in myStr.
						</code>
					</pre>
				</div>
			</div>
		</div>
	</div>
</div>
<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<p>When dealing with strings, you will often have to manipulate them. Reversing strings is a good exercise to practice doing this.</p>
		</div>
	</div>
</div>
<div id = "Code" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<ul class="nav nav-tabs tabs-3" role="tablist">
				<li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#turing" role="tab">Turing</a></li>
				<li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python" role="tab">Python</a></li>
				<li class="nav-item"><a class="nav-link" data-toggle="tab" href="#java" role="tab">Java</a></li>
			</ul>
			<div class="tab-content">
				<div id="turing" class="tab-pane fade in active">
					<pre class="language-turing line-numbers">
						<code>
							var original : string := "123" % This is the string we will reverse.
							var reversed : string := "" % Create an empty string. We will add the characters in reverse order next.

							for decreasing i : length (original) .. 1 % Loop through the original string backwards.
								reversed += original(i); % Add the characters one by one.
							end for

							put(original + " backwards is: " + reversed) % Print the final result.
						</code>
					</pre>
				</div>
				<div id="python" class="tab-pane fade">
					<pre class="language-python line-numbers">
						<code>
							original = "123" # This is the string we will reverse.
							reversedString = "" # Create an empty string. We will add the characters in reverse order next.

							for c in reversed(original): # Loop through the characters in the original string backwards.
								reversedString += c

							print (reversedString) # Print the final result.

							# This is another way to reverse string in Python.
							# While this method is faster, it make no sense unless you are familiar with Python.
							# This way also defeats the purpose of this exercise, which is to show the process of solving string manipulation problems.
							print (original[::-1])
						</code>
					</pre>
				</div>
				<div id="java" class="tab-pane fade">
					<pre class="language-java line-numbers">
						<code>
							String original = "123";
							String reversed = "";

							for (int i = original.length() - 1; i >= 0; i--) {
								reversed += original.charAt(i);
							}

							System.out.println(reversed);
						</code>
					</pre>
				</div>
			</div>
		</div>
	</div>
</div>
[//]:<> (CODE ENDS HERE)
[//]:<> (LESSON STARTS HERE)
<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<p>You can do a lot with strings, and will use them a lot throughout your programming. It is important that you understand and are comfortable with using and manipulating strings.</p>
		</div>
	</div>
</div>
[//]:<> (LESSON ENDS HERE)
[//]:<> (SAMPLE STARTS HERE)
<div id = "Sample" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<h2>Sample Problems</h2>
			<h3>Palindromes</h3>
			<p>One of the most basic string manipulation problems.</p>
			<p>Write a program that tells the user if a string they enter is a palindrome. Ignore spaces, punctuation, and capitalization.</p>
			<p>A palindrome is a string that is the same if you reverse it.</p>
			<p>Examples of palindromes are: "Anna", "A man, a plan, a canal, Panama!", and "taco cat".
			<h3>Capitalization</h3>
			<p>Write a program to fix the capitalization of sentences.</p>
			<p>If the user inputs: "this sentence is capitalized wrong. so is this! This one is right."</p>
			<p>Your program should output: "This sentence is capitalized wrong. So is this! This one is right."</p>
		</div>
	</div>
</div>
