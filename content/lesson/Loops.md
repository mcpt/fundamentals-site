+++ Title = "Loops" date = "2016-11-30T21:30:33-05:00"

+++ [//]:<> (LESSON STARTS HERE)

Lesson created by [Abdul Arif]
This is a sample file to show you how to create a proper lesson page. Here you would explain the topic, and teach them what they would need to know. Feel free to edit this section with subheadings, etc.

There are two types of loops: counted loops and conditional loops

[//]:<> (COUNTED LOOPS STARTS HERE) [//]:<> (COUNTED LOOPS STARTS HERE)

Counted Loops

Counted loops execute a predetermined number of times.

The following provides an overview of counted loops:


[//]:<> (COUNTED LOOPS ENDS HERE)


[//]:<> (LESSON STARTS HERE) [//]:<> (CODE STARTS HERE)

Turing
Python
Java
                        for i : startValue .. endValue
					% code
					% code
					end for

                    
                     for iteratingVariable in sequence:
				#code
				#code
   
				for (initial condition; condition; increment){
				//code
				//code
					}

                    

                    
[//]:<> (CODE ENDS HERE) [//]:<> (LESSON CONTINUES HERE)

But, what if we wanted to increment by a number other than one?  For example, to output all the multiples of 3 from 1 to 14, we could iterate from 1 to 14 and use conditionals to check for multiplicity.  However, we can achieve the same result using loops as follows.  (We know that the first number will be 3)

[//]:<> (LESSON STARTS HERE) [//]:<> (CODE STARTS HERE)

Turing
Python
Java
                        for i : 3..14 by 3
					print i


                    
                     for (initial condition; condition; increment){
				//code
				//code
					}
				
				for (int i = 3; i <=14; i+=3){
					System.out.println (i);
				}


                    

                    
[//]:<> (CODE ENDS HERE) [//]:<> (LESSON CONTINUES HERE)


[//]:<> (LESSON STARTS HERE) [//]:<> (SAMPLE STARTS HERE)

Sample Problems

Here is where you show a sample problem, a very simple one. You will then explain how to solve it and redirect them to a more difficult (still simple) problem.

[//]:<> (SAMPLE ENDS HERE)