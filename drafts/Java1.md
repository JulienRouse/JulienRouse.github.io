## Learning OOP with Java ##

### Basics ###

#### Hello world ####
#### Data Types ####

[DOC ORACLE on DATA TYPES](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)


Two types of data type in Java, that's a reason as why Java is not considered a truly Object language by purist.
There are primitives types
 - `byte` 8-bit signed two's complement integer. [-128;127] . default = 0
 - `short` 16-bit signed two's complement integer. [-32,768;32,767] . default = 0
 - `int` 32-bit signed two's complement integer. [-2^31;2^31-1] . default = 0 . In JavaSE >= 8, possibility to have unsigned int and support of unsigned int with the Integer class
 - `long` 64-bit signed two's complement integer. [-2^63;2^63-1] . default = 0L . In JavaSE >= 8, possibility to have unsigned long and support of unsigned long with the Integer class
 - `float` 32-bit IEEEE 754 floating points. default = 0.0f
 - `double` 64-bit IEEE 754 floating points. default = 0.0d
 - `boolean` true or false. default = false . One bit of information, but real size not precisely defined
 - `char` 16-bit Unicode character. ['\u0000';'\ufff'] . default = '\u0000'
 
String is a class but with special meaning. `String s = 'toto';` will do the same as `String s = new String('toto');`
 
#### Loop ####

There are several ways of looping in Java. We are going to print the numbers from 0 to 9 to show each looping construct.

##### For loop #####
A **for** loop:

    for(int i=0;i<10;i++)
	    System.out.println(i);

##### While loop #####
A **while** loop:

	int i = 0;
	while(i<10)
	{
		System.out.println(i);
		i++;
	}

##### Do...While loop #####
A **do..while** loop:

	int i = 0;
	do
	{
		System.out.println(i);
		i++;
	}while(i<10)

	
##### Bonus on loop #####
There are two keywords that interact with the flow of a loop, `break` and `continue`

#### Conditionnal statement ####

if then
if then else
switch
ternary operator

### Classes ###

### Methods ###

### Interfaces ###

### Abstract ###

### UML? ###

### Keywords ###

www.codejava.net/java-core/the-java-language/java-keywords
- abstract
- assert
- boolean
- break
- byte
- case
- catch
- char
- class
- const
- continue
- default
- do
- double
- else
- enum
- extends
- final
- finally
- float
- for
- goto
- if
- implements
- import
- instanceof
- int
- interface	
- long	
- native
- new
- package
- private
- protected
- public
- return	
- short	
- static
- strictfp
- super
- switch
- synchronized
- this
- throw
- throws
- transient
- try
- void
- volatile
- while

Some noteworthy points regarding Java keywords:

    - const and goto are resevered words but not used.
    - true, false and null are literals, not keywords.
    - all keywords are in lower-case.

### Conclusion ### 