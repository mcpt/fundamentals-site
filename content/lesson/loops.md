+++
Title = "Loops"
date = "2016-11-30T21:30:33-05:00"

+++
[//]:<> (LESSON STARTS HERE)
<div id = "Description" class = "container">
    <div class = "row">
        <div class = "col-md-12">
		        <i>Lesson created by Abdul Arif</i>
            <p>There are two types of loops: counted loops and conditional loops.</p>
            <h2>Counted Loops</h2>
            <p>Counted loops execute a predetermined number of times. The following provides an overview of counted loops:</p>
        </div>
    </div>
</div>


[//]:<> (COUNTED LOOPS STARTS HERE)
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
                        <code>for i : startValue .. endValue
                          % code
                          % code
                        end for
                        </code>
                    </pre>
                </div>
                <div id="python" class="tab-pane fade">
                    <pre class="language-python line-numbers">
                        <code>for iteratingVariable in sequence:
                          #code
                          #code
                        </code>
                    </pre>
                </div>
                <div id="java" class="tab-pane fade">
                    <pre class="language-java line-numbers">
                        <code>for (initial condition; condition; increment){
                            //code
                            //code
                        }
                        </code>
                    </pre>
                </div>
            </div>
        </div>
    </div>
</div>
[//]:<> (COUNTED LOOPS ENDS HERE)


<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12" style = "margin: 20px 0px 20px 0px">
      The following example will make the use of these loops clearer.  Let's say we wanted to print "Hello World!" 5 times.  We could accomplish this as follows:
		</div>
	</div>
</div>

[//]:<> (CONDITIONAL LOOPS STARTS HERE)
<div id = "Code" class = "container">
    <div class = "row">
        <div class = "col-md-12">
            <ul class="nav nav-tabs tabs-3" role="tablist">
                <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#turing2" role="tab">Turing</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python2" role="tab">Python</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#java2" role="tab">Java</a></li>
            </ul>

            <div class="tab-content">
                <div id="turing3" class="tab-pane fade in active">
                    <pre class="language-turing line-numbers">
                        <code>for i : 1 .. 5
			               put ("Hello World!")
			            end for

                          </code>
                    </pre>
                </div>
                <div id="python3" class="tab-pane fade">
                    <pre class="language-python line-numbers">
                        <code>for i in range (1, 5):
			              print "Hello World!"

                        </code>
                    </pre>
                </div>
                <div id="java3" class="tab-pane fade">
                    <pre class="language-java line-numbers">
                        <code>for (int i = 0; i < 5; i++){
			               System.out.println("Hello World!");
				        }

                        </code>
                    </pre>
                </div>
            </div>
        </div>
    </div>
</div>
[//]:<> (CONDITIONAL LOOPS ENDS HERE)



<div id = "Description" class = "container">
	<div class = "row">
		<div class = "col-md-12" style = "margin: 20px 0px 20px 0px">
      But, what if we wanted to increment by a number other than one?  For example, to output all the multiples of 3 from 1 to 14, we could iterate from 1 to 14 and use conditionals to check for multiplicity.  However, we can achieve the same result using loops as follows.  (We know that the first number will be 3)
		</div>
	</div>
</div>

[//]:<> (CONDITIONAL LOOPS STARTS HERE)
<div id = "Code" class = "container">
    <div class = "row">
        <div class = "col-md-12">
            <ul class="nav nav-tabs tabs-3" role="tablist">
                <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#turing4" role="tab">Turing</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#python4" role="tab">Python</a></li>
                <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#java4" role="tab">Java</a></li>
            </ul>

            <div class="tab-content">
                <div id="turing4" class="tab-pane fade in active">
                    <pre class="language-turing line-numbers">
                        <code>for i : 3..14 by 3
			               put i
				        end for
                          </code>
                    </pre>
                </div>
                <div id="python4" class="tab-pane fade">
                    <pre class="language-python line-numbers">
                        <code>for i in range (1, 5):
			               print i
                        </code>
                    </pre>
                </div>
                <div id="java4" class="tab-pane fade">
                    <pre class="language-java line-numbers">
                        <code>for (int i = 3; i <=14; i+=3){
			               System.out.println (i);
				        }
                        </code>
                    </pre>
                </div>
            </div>
        </div>
    </div>
</div>
[//]:<> (CONDITIONAL LOOPS ENDS HERE)



[//]:<> (LESSON STARTS HERE)
<div id = "Description" class = "container">
    <div class = "row">
        <div class = "col-md-12">
		 <h3>Challenge Problem</h3>
            <p>Use counted loops to output a 5 by 5 times table as follows:</p>
			<p>1   2    3    4    5</p>
			<p>2   4    6    8    10</p>
			<p>3   6    9    12   15</p>
			<p>4   8    12   16   20</p>
			<p>5   10   15   20   25</p>
        </div>
    </div>
</div>



[//]:<> (SAMPLE STARTS HERE)
<div id = "Sample" class = "container">
    <div class = "row">
        <div class = "col-md-12">
            <h2> Conditional Loops </h2>
            <p> Conditional Loops execute until a specific condition is met.  For example, a program may ask the user to keep entering a password until it is correct.  An additional control variable is also required with these types of loops.
</p>
		<p>If we needed to find the number of times we need to divide the number 10 by 2 to get a value less than 1, we could do this as follows:
</p>
        </div>
    </div>
</div>
[//]:<> (SAMPLE ENDS HERE)


[//]:<> (CONDITIONAL LOOPS STARTS HERE)
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
                        <code>var value: int := 10
						var numDivides: int := 0
						loop
							value = value / 2
							numDivides := numDivides +1
							exit when value <1
						end loop
						put (numDivides)


                          </code>
                    </pre>
                </div>
                <div id="python2" class="tab-pane fade">
                    <pre class="language-python line-numbers">
                        <code>value = 10
						numDivides = 0
						while (true):
							value = value / 2
							numDivides ++
							if (value < 1): break
						print numDivides

						OR

						value = 10
						numDivides = 0
						while (value >= 1):
							value = value / 2
							numDivides ++
						print numDivides

                        </code>
                    </pre>
                </div>
                <div id="java2" class="tab-pane fade">
                    <pre class="language-java line-numbers">
                        <code>int value = 10;
						int numDivides = 0;
						while (true){
							value = value / 2;
							numDivides ++;
							if (value <1)
								break;
						}
						System.out.println(numDivides)

						OR

						int value = 10;
						int numDivides = 0;
						while (value >= 1){
							value = value / 2;
							numDivides ++;
						}
						System.out.println(numDivides)


                        </code>
                    </pre>
                </div>
            </div>
        </div>
    </div>
</div>
[//]:<> (CONDITIONAL LOOPS ENDS HERE)

[//]:<> (LESSON STARTS HERE)
<div id = "Description" class = "container">
    <div class = "row">
        <div class = "col-md-12">
		 <h3>Challenge Problem</h3>
            <p>Use a conditional loop to output the first 10 numbers in the Fibonacci Sequence.  </p>
        </div>
    </div>
</div>
