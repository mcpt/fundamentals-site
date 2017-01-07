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
            <h3>Counted Loops</h3>
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
      But, what if we wanted to increment by a number other than one?  For example, to output all the multiples of 3 from 1 to 14, we could iterate from 1 to 14 and use conditionals to check for multiplicity.  However, we can achieve the same result using loops as follows.  (We know that the first number will be 3)
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
                <div id="turing2" class="tab-pane fade in active">
                    <pre class="language-turing line-numbers">
                        <code>for i : 3..14 by 3
                          print i
                          </code>
                    </pre>
                </div>
                <div id="python2" class="tab-pane fade">
                    <pre class="language-python line-numbers">
                        <code>for (initial condition; condition; increment){
                            #code
                        }
                        </code>
                    </pre>
                </div>
                <div id="java2" class="tab-pane fade">
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


[//]:<> (SAMPLE STARTS HERE)
<div id = "Sample" class = "container">
    <div class = "row">
        <div class = "col-md-12">
            <h2> Sample Problems </h2>
            <p> Here is where you show a sample problem, a very simple one. You will then explain how to solve it and redirect them to a more difficult (still simple) problem. </p>
        </div>
    </div>
</div>
[//]:<> (SAMPLE ENDS HERE)
