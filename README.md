# homework-r1
> print("hello, world")
[1] "hello, world"
> 2+3
[1] 5
> 456/90
[1] 5.066667
> print("hello, world")
[1] "hello, world"
> 2+3
[1] 5
> 
> 
> 
> print("hello, world")
[1] "hello, world"
> y=2+3!y
Error: unexpected '!' in "y=2+3!"
> y=2+3
> y
[1] 5
> y=2+3
> y
[1] 5
> b<-19
> b
[1] 19
> x<-2+3
> x
[1] 5
> y=x**4
> y
[1] 625
> (y=x**4)
[1] 625
> (a+9)
Error in a + 9 : non-numeric argument to binary operator
> a+9
Error in a + 9 : non-numeric argument to binary operator
> 5*9 = a
Error in 5 * 9 = a : target of assignment expands to non-language object
> (a+9)
Error in a + 9 : non-numeric argument to binary operator
> 5*9 = a
Error in 5 * 9 = a : target of assignment expands to non-language object
> (a+9)
Error in a + 9 : non-numeric argument to binary operator
> 5*9 -> a
> a+9
[1] 54
> 5*9 -> a
> (a+9)
[1] 54
> nummy <- c(2,3,4)
> nummy_int <- c(1L,2L,3L)
> typeof(nummy)
[1] "double"
> typeof(nummy_int)
[1] "integer"
> is.numeric(nummy)
[1] TRUE
> is.numeric(nummy_int)
[1] TRUE
> is.numeric(nummy)
[1] TRUE
> lengthy(nummy)
Error in lengthy(nummy) : could not find function "lengthy"
> nummy <- c(2,3,4,bgf)
Error: object 'bgf' not found
> nummy_int <- c(1L,2L,3L)
> typeof(nummy)
[1] "double"
> typeof(nummy_int)
[1] "integer"
> is.numeric(nummy)
[1] TRUE
> nummy <- c(2,3,4,"bgf")
> nummy_int <- c(1L,2L,3L)
> typeof(nummy)
[1] "character"
> length(nummy)
[1] 4
> #type casting#
> money_in-char <- ("20","30","33")
Error: unexpected ',' in "money_in-char <- ("20","
> #type casting#
> money_in-char <- c("20","30","33")
Error in money_in - char <- c("20", "30", "33") : 
  object 'money_in' not found
> 
> #type casting#
> money_in_char <- c("20","30","33")
> typeof(money_in_char)
[1] "character"
> money_money <- as.numeric(money_in_char)
> money_money
[1] 20 30 33
> typeof(money_money)
[1] "double"
> is.numeric(money_money)
[1] TRUE
> is.numeric(money_in_char)
[1] FALSE
> as.logical(money_money)
[1] TRUE TRUE TRUE
> abhishek<- as.logical(money_money)
> as.logical(abhishek)
[1] TRUE TRUE TRUE
> as.logical(c(20,20,0))
[1]  TRUE  TRUE FALSE
> c(2,4,"hello",TRUE)
[1] "2"     "4"     "hello" "TRUE" 
> c(2,4,TRUE)
[1] 2 4 1
> c(2,4,FALSE)
[1] 2 4 0
> mahek<-c(2,4,TRUE)
> mahek
[1] 2 4 1
> as.logical(mahek)
[1] TRUE TRUE TRUE
> month.abb
 [1] "Jan" "Feb" "Mar" "Apr" "May" "Jun" "Jul" "Aug" "Sep" "Oct" "Nov" "Dec"
> month.abb[3]
[1] "Mar"
> month.name
 [1] "January"   "February"  "March"     "April"     "May"       "June"     
 [7] "July"      "August"    "September" "October"   "November"  "December" 
> 1:10
 [1]  1  2  3  4  5  6  7  8  9 10
> month.name[2:7]
[1] "February" "March"    "April"    "May"      "June"     "July"    
> month.name(seq(1,12,2))
Error in month.name(seq(1, 12, 2)) : could not find function "month.name"
> month.name[1,12,2]
Error in month.name[1, 12, 2] : incorrect number of dimensions
> month.name[c(1,12,2)]
[1] "January"  "December" "February"
