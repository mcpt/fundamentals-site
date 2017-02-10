+++
Title = "Conditionals"
date = "2017-01-06T21:30:33-05:00"
+++

<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<p>
				<i>Lesson created by Richard Yi</i>
			</p>
        	<p>
				Conditional statements, or "if statements", let you run a block of code only if a certain condition is true.
					<br/>
				The condition can check if 2 values are equal, if a value is less than another, if a value is more than another, or a mixture of conditions.
			</p>
			<p>If the condition is true, it will excecute the code in the block below</p>
            <p>For example, you can ask for the user's age and see if they're an adult.</p>
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
						var age : int
						
						put "Please enter your age: "
						get age
						
						if age < 18 then
							put "You are not an adult."
							%If age is less than 18, every line until "end if" will be excecuted
						end if
					</code>
				</pre>
                </div>
                <div id="python" class="tab-pane fade">
					<pre class="language-python line-numbers">
						<code>
							age = int(raw_input('Please enter your age: '))
							
							if age < 18:
								print('You are not an adult.')
								#If age is less than 18, every line on this indent level will be excecuted
						</code>
					</pre>
                </div>
                <div id="java" class="tab-pane fade">
					<pre class="language-java line-numbers">
						<code>
							BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
							
							System.out.print("Please enter your age: ");
							int age = Integer.parseInt(in.readLine());
							
							if (age < 18)
							{
								System.out.println("You are not an adult.");
								//If age is less than 18, every line until the } will be excecuted
							}
						</code>
					</pre>
                </div>
            </div>
        </div>
    </div>
</div>


<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12" style = "margin: 20px 0px 20px 0px">
			If you want a block of code to run if a condition is true, and want <b>another</b> block of code to run if that condition is <b>not true</b>, you can use an <b>else</b> along with the if statement
		</div>
	</div>
</div>


<div id = "Code" class = "container">
    <div class = "row">
        <div class = "col-md-12">
            <ul class="nav nav-tabs tabs-3" role="tablist">
                <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#turing2" role="tab">Turing</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python2" role="tab">Python</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#java2" role="tab">Java</a></li>
            </ul>

            <div class="tab-content">
                <div id="turing2" class="tab-pane fade in active">
					<pre class="language-turing line-numbers">
						<code>
							var age : int
							
							put "Please enter your age: "
							get age
							
							if age < 18 then
								put "You are not an adult."
								%If age is less than 18, every line until "else" will be excecuted
							else
								put "You are an adult."
								%If age is not less than 18, every line until "end if" will be excecuted
							end if
						</code>
					</pre>
                </div>
                <div id="python2" class="tab-pane fade">
					<pre class="language-python line-numbers">
						<code>
							age = int(raw_input('Please enter your age: '))
							
							if age < 18:
								print('You are not an adult.')
								#If age is less than 18, every line on this indent level will be excecuted
							else:
								print('You are an adult.')
								#If age is not less than 18, every line on this indent level will be excecuted
						</code>
					</pre>
                </div>
                <div id="java2" class="tab-pane fade">
					<pre class="language-java line-numbers">
						<code>
							BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
							
							System.out.print("Please enter your age: ");
							int age = Integer.parseInt(in.readLine());
							
							if (age < 18)
							{
								System.out.println("You are not an adult.");
								//If age is less than 18, every line until the } will be excecuted
							}
							else
							{
								System.out.println("You are an adult.");
								//If age is not less than 18, every line until the } will be excecuted
							}
						</code>
					</pre>
                </div>
            </div>
        </div>
    </div>
</div>


<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12" style = "margin: 20px 0px 20px 0px">
			<p>You can use <b>else if</b> (a.k.a. <b>elif</b> or <b>elsif</b>) to chain <b>if</b> statements together.</p>
			<p>
				If the condition in the <b>if</b> statement is not true, then it checks for the condition in the next <b>else if</b> statement, then the next, and so on.
					<br/>
				If none of the <b>if</b> or <b>else if</b> statements are true, it goes to the <b>else</b> block (if there is one).
			</p>
		</div>
	</div
</div>


<div id = "Code" class = "container">
    <div class = "row">
        <div class = "col-md-12">
            <ul class="nav nav-tabs tabs-3" role="tablist">
                <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#turing3" role="tab">Turing</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python3" role="tab">Python</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#java3" role="tab">Java</a></li>
            </ul>

            <div class="tab-content">
                <div id="turing3" class="tab-pane fade in active">
					<pre class="language-turing line-numbers">
						<code>
							var age : int
							
							put "Please enter your age: "
							get age
							
							if age < 14 then
								put "You have not started high school yet."
							elsif age < 18 then
								put "You are not an adult."
							elsif age > 200 then
								put "Uh..."
							else
								put "You are an adult."
							end if
						</code>
					</pre>
                </div>
                <div id="python3" class="tab-pane fade">
					<pre class="language-python line-numbers">
						<code>
							age = int(raw_input('Please enter your age: '))
							
							if age < 14:
								print('You have not started high school yet.')
							elif age < 18:
								print('You are not an adult.')
							elif age > 200:
								print('Uh...')
							else
								print('You are an adult.')
						</code>
					</pre>
                </div>
                <div id="java3" class="tab-pane fade">
					<pre class="language-java line-numbers">
						<code>
							BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
							
							System.out.print("Please enter your age: ");
							int age = Integer.parseInt(in.readLine());

							if(age < 14)
							{
								System.out.println("You have not started high school yet.");
							}
							else if(age < 18)
							{
								System.out.println("You are not an adult.");
							}
							else if(age > 200)
							{
								System.out.println("Uh...");
							}
							else
							{
								System.out.println("You are an adult.");
							}
						</code>
					</pre>
                </div>
            </div>
        </div>
    </div>
</div>


<div id = "Sample" class = "container">
	<div class = "row">
		<div class = "col-md-12">
			<h2> Sample Problem </h2>
			<p>
				Pick three random numbers from 1 to 10 and ask the user to enter a number between 1 and 10
					<br/>
				If the user guesses one of the three numbers you picked, tell they won, otherwise, tell them they lost.
			</p>
		</div>
	</div>
</div>
