## Reference sheet about Java ##

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

### OOP ###

Java support class and object, interfaces, abstract classes, simple inheritance between class.

### Methods ###

### Interfaces ###

### Abstract ###

### UML? ###


### Operator listed by precedence ###
Lower precedence means evaluted first. 

#### Precedence 0 ####
- `new`: Not officially an operator, as it is only used in one context, followed just after by  class name.

#### Precedence 1 #### 
- (prefix) ++: The preincrement operator (add 1)
- (prefix) --: The predecrement operator (substract 1)
- (unary) +
- (unary) -
- (unary) ~: Bitwise not for `int`
- (unary) !: Bolean not
- (cast): Not officially an operator, as multitude of purposes, all united under the term casting
- (postfix) ++: The postincrement operator (add 1)
- (postfix) --: The postdecrement operator (substract 1)

#### Precedence 2 ####
- *: Integer multiplication for `int` and floating point multiplication for `double`
- /: Integer division for `int` and floating point division for `double`
- %: Remainder operator (often miscalled the *modulus*)
#### Precedence 3 ####
- +: Integer addition for `int` and floating point addition for `double`. Is also the concatenation operator for `String`
- -: Integer substraction for `int` and floating point substraction for `double`
#### Precedence 4 ####
- <<: 
- >>:
- >>>:
#### Precedence 5 ####
#### Precedence 6 ####
#### Precedence 7 ####
#### Precedence 8 ####
#### Precedence 9 ####
#### Precedence 10 ####
#### Precedence 11 ####
#### Precedence 12 ####
#### Precedence 13 ####

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