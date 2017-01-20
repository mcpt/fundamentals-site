+++
Title = "Variables"
date = "2016-11-30T21:30:33-05:00"

+++
[//]:<> (LESSON STARTS HERE)
<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12">
		<i>Lesson created by Vincent Macri</i>
		<p>Variables allow you to store values. They are one of the most important parts of programming, maybe even the most important.</p>
		<p>In this lesson, we will be focusing on the syntax of using variables.</p>
		</div>
	</div>
</div>
[//]:<> (LESSON STARTS HERE)
[//]:<> (CODE STARTS HERE)
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
							var firstName : string := "Vincent"
							var lastName : string := "Macri"
							var languages : int % In Turing, you can declare a variable, and give it a value later.
							languages := 3
							put(firstName + " " + lastName + " made this lesson. It teaches variables in " + intstr(languages) + " languages!")
						</code>
					</pre>
				</div>
				<div id="python" class="tab-pane fade">
					<pre class="language-python line-numbers">
						<code>
							firstName = 'Vincent'
							lastName = 'Macri'
							languages = 0 # Python doesn't let you declare variables without assigning them,
							languages = 3 # But you can always just assign a new value when you are ready.

							print(str.format("{} {} made this lesson. It teaches variables in {} languages!", firstName, lastName, languages))
						</code>
					</pre>
				</div>
				<div id="java" class="tab-pane fade">
					<pre class="language-java line-numbers">
						<code>
							String firstName = "Vincent";
							String lastName = "Macri";
							int languages; // In Java, you can declare a variable, and give it a value later.
							languages = 3;

							System.out.println(firstName + " " + lastName + " made this lesson. It teaches variables in " + languages + " languages!");
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
			<p>You may have noticed that Turing and Java use double quotes (" ") for strings, while Python uses single quotes (' '). In Turing and Java, double quotes are used for strings, while single quotes are used for single characters. In Python, you can use either double or single quotes, but Python programmers tend to prefer single quotes.</p>
			<p>For Turing and Java, we concatenated the variables with the string. Concatenate is a fancy word for put togther.</p>
			<p>In Python, we used the <code class=language-python>str.format()</code> command. It formats strings for us. We use {} in place of the variables, and then list the variables in order at the end.</p>
		</div>
	</div>
</div>
[//]:<> (LESSON STARTS HERE)
[//]:<> (SAMPLE STARTS HERE)
<div id = "Sample" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<h2> Sample Problems </h2>
			<p>Write a program where the user can enter their first name, lastName, and age, and then output "<i>firstName</i> <i>lastName</i> is <i>age</i> years old."</p>
			<p>Write a program where the user can enter two numbers, and then output the sum of the numbers.</p>
		</div>
	</div>
</div>
[//]:<> (SAMPLE ENDS HERE)
