# UPWORK SWIFT TEST 2016

1. What is the name of the Xcode generated header file used to import Swift classes into an Objective-C Class given a product module named Example?  
  Answers:
  * ExampleSwift.h
  * Example.Swift.h
  * Example+Swift.h
  * **Example-Swift.h**

2. What does a retainCount represent in ARC?  
  Answers:
  * **The current number of strong references to an object. **
  * The current number of instances of an object.
  * The total number of objects currently being retained in memory.
  * The total number of times an object has been allocated.

3. Which of these statements is a valid way to extend the capabilities of our theoretical class, MyClass to conform to protocol MyProtocol?  
  Answers:
  * extension MyClass(MyProtocol) { }
  * extension MyClass, prot MyProtocol { }
  * **extension MyClass: MyProtocol { }**
  * extension MyClass, MyProtocol { }

4. Which one is the correct keyword for defining a constant in Swift? ( or To declare a constant in Swift you would use: )  
  Answers:
  * const
  * contant
  * final
  * **let** 
  * def

6. Which one of the below functions definitions is wrong considering Swift language?  
  Answers:
  * **func haveChar(#string: String, character: Character) -&gt; (Bool)**
  * func mean(numbers: Double...) -&gt; Double
  * func minMax(array: [Int]) -&gt; (min: Int, max: Int)?
  * func minMax(array: [Int]) -&gt; (min: Int?, max: Int?)

7. Which of these is a valid syntax for iterating through the keys and values of a dictionary?  
  `let dictionary = [keyOne : valueOne, keyTwo : valueTwo]`  
  Answers:
  * **for (key, value) in dictionary { println("Key: \(key) Value: \(value)") }**
  * for (key, value) in enumerate(dictionary) { println("Key: \(key) Value: \(value)") }
  * for (key, value) in (dictionary.keys, dictionary.values) { println("Key: \(key) Value: \(value)") }
  * **for (key, value) in dictionary.enumerate() { println("Key: \(key) Value: \(value)") }**

8. What is the name of the Swift language feature that Objective-C Blocks are translated into?  
  Answers:
  * Lambda
  * Callback
  * **Closure** 
  * Selector

9. Which one creates a dictionary with a key type of Integer and value of String?  
  Answers:
  * var dict:[Int: String] = ["one":1]
  * **var dict: [Int: String] = [1:"one"]**
  * var dict: [String: Int] = [1:"one"]
  * var dict = ["one":1]

10. Which of these is an appropriate syntax for dispatching a heavy operation to a background thread?  
  Answers:
  * dispatch_async(DISPATCH_QUEUE_PRIORITY_BACKGROUND), { self.heavyOperation() })
  * **dispatch_async(dispatch_get_global_queue(DISPATCH_QUEUE_PRIORITY_BACKGROUND, 0), { self.heavyOperation() })** 
  * DISPATCH_QUEUE_PRIORITY_BACKGROUND({ self.heavyOperation() })
  * dispatch_async({ self.heavyOperation() })

11. What is the name of the deinitializer in a Class declaration?  
  Answers:
  * **deinit** 
  * dealloc
  * release

12. Which of these is an appropriate syntax for declaring a function that takes an argument of a generic type?  
  Answers:
  * func genericFunction(argument: T&lt;Generic&gt;) { }
  * func genericFunction&lt;T&gt;(argument) { }
  * generic func genericFunction(argument: T) { }
  * **func genericFunction&lt;T&gt;(argument: T) { }**

13. Which of these is not a valid property declaration in Swift?  
  Answers:
  * final let x = 0
  * **final lazy let x = 0**
  * final lazy var x = 0
  * final var x = 0

14. Which  is the wrong definition of a protocol in Swift?  
  Answers:
  * protocol SomeProtocol { var first: Int{ get } }
  * **protocol SomeProtocol { var first: Int{ set } }**
  * protocol SomeProtocol { var first: Int { get set } }
  * protocol SomeProtocol { var first: Int { get set } var second: Int { get } }

15. Which of the following structures has both computed and stored properties?  
  Answers:
  * **`struct Rect { var origin = CGPointZero var center: CGPoint { get { // } set { // } } }`**
  * `struct Rect { var center: CGPoint { get { // } set { // } } }`
  * `struct Rect { let origin = CGPointZero }`
  * `struct Rect { var origin = CGPointZero var center: CGPointMake(0,0) }`

16. Considering var index = UInt8.max, which of the following operation results to the value of zero for var index?  
  Answers:
  * index = index &- 1
  * **index = index &+ 1**
  * index = index &* 1
  * index = index &/ 255

17. All Swift classes must inherit from which root class?  
  Answers:
  * **Swift classes do not require a root class.**
  * NSObject
  * @ObjC
  * Root

18. Which keyword is used on a function in an enumeration to indicate that the function will modify 'self'?  
  Answers:
  * modifier
  * **mutating**
  * mutable
  * mod
  * mut

19. Which is correct for Enumerations?  
  Answers:
  * **Enumerations can define initializers.**
  * Enumerations cannot conform to protocols.
  * Enumerations cannot conform to protocols.

20. Which of these is a valid definition of a generic function that incorporates inout parameters in Swift?  
  Answers:
  * **`func swap&lt;T&gt;(inout a: T, inout b: T) { let temp = a a = b b = temp }`**
  * `func swap&lt;U,T&gt;(inout a: U, inout b: T) { let temp = a a = b b = temp }`
  * `func swap&lt;U,T&gt;( a: U, b: T) { let temp = a a = b b = temp }`
  * `func swap&lt;T&gt;( a: T, b: T) { let temp = a a = b b = temp }`

21. If we have a class named MyClass with a nested enum called Status, declared like so:
  `class MyClass {
      enum Status {
          case On, Off
      }
  }`  
  How would one indicate that a variable is an enum of type Status outside the context of MyClass?
  Answers:
  * **`var status: MyClass.Status = .On`**
  * `var status: Status = .On`
  * `var status: MyClass&lt;Status&gt; = .On`
  * `var status: MyClass(Status) = .On`

22. Which of the following could be used to indicate the Function Type of the following function:
  `func joinStrings(stringOne: String, stringTwo: String) -&gt; String {
      return stringOne + stringTwo
  }`  
  Answers:
  * func(String, String -&gt; String)
  * **(String, String) -&gt; String**
  * {String, String} -&gt; String
  * {String, String}(String)

23. Which of the following statements could be used to determine if a given variable is of String type?  
  Answers:
  * if String.hierarchy(unknownVariable) { }
  * **if unknownVariable is String { }**
  * if unkownVariable: String { }
  * if (String)unknownVariable { }

24. Which of these could be an appropriate protocol declaration in Swift?  
  Answers:
  * **@objc protocol someProtocal { optional var first: Int { get } }**
  * @objc protocol someProtocal { optional var first: Int { set } }
  * protocol someProtocal { optional var first: Int { get } }
  * protocol someProtocal { var first: Int { set } }

25. In context of a Swift subscript, which of the following is correct?  
  Answers:
  * **`struct MyStruct { var myStr = [String]() subscript (index : Int) -&gt; String{ get{ return myStr[index] } set{ myStr[index] = newValue } } }`**
  * `struct MyStruct { var myStr = [String]() subscript (index : Int) -&gt; Int{ get{ return myStr[index] } set(newValue){ myStr[index] = newValue } } }`
  * `struct MyStruct { var myStr = [String]() subscript (index : Int) -&gt; String{ get(){ return myStr[index] } set(newValue){ myStr[index] = newValue } } }`
  * `struct MyStruct { var myStr = [String] subscript (index : Int) -&gt; String{ get(){ return myStr[index] } set(newValue){ myStr[index] = newValue } } }`

26. What is used to import Objective-C files into Swift?  
  Answers:
  * Objective-C classes are automatically imported.
  * Objective-C classes are imported in the Swift file using the class.
  * **Objective-C classes are imported via a Bridging Header.**
  * Objective-C classes import themselves by declare @SwiftImportable.

27. What keyword is used to indicate a custom operator that will appear in between two targets, similar to the addition operator in this example?  
  `var sum = 10 + 10`  
  Answers:
  * @inter
  * between
  * **infix**
  * @center

28. Which is correct regarding Swift enumeration members when they are defined?  
  Answers:
  * Members are assigned a default integer value.
  * Members are assigned a random default integer value.
  * **Members are not assigned default integer values.**

29. What type of object are Swift Structures?  
  Answers:
  * Reference Type
  * Memory Type
  * Abstract Type
  * **Value Type**

30. Which keyword in the context of a Switch statement is required to force the execution of a subsequent case?  
  Answers:
  * **fallthrough**
  * continue
  * break
  * return

31. What is the type of Swift Enumerations?  
  Answers:
  * Reference type
  * Class type
  * Collection type
  * **Value type**

32. Given that we have defined myChar like so :  
  `let myChar: Character = "b"`  
  Which code segment can be considered a complete Switch statement and will run without any error?  
  Answers:
  * switch myChar { case "a","A": println("The letter A") case "b","B": println("The letter A") }
  * switch myChar { case "a": println("The letter A") }
  * switch myChar { case "a": case "A": println("The letter A") default: println("Not the letter A") }
  * **switch myChar { case "a","A": println("The letter A") default: println("Not the letter A") }**

33. Can enumeration type have methods?  
  Answers:
  * **Enumerations can have methods associate with them.**
  * Enumerations can have only member values.

34. Which of the following declares a mutable array in Swift?  
  Answers:
  * var x = [Int]
  * let x = [Int]
  * **var x = &#91;Int&#93;&#40;&#41;**
  * let x = &#91;Int&#93;&#40;&#41;

35. Which keyword is used in Swift when we want a property of a class to initialize when it is accessed for the first time?  
  Answers:
  * let
  * var
  * const
  * **lazy**

36. Which is used for down casting?  
  Answers:
  * **as!**
  * is
  * is?
  * **as?**

37. What attribute can be used to allow a protocol to contain optional functions and to be used in ObjC?  
  Answers:
  * objective_bridge
  * ObjC
  * _objc
  * **@objc**

38. Which of the following types can be used use as raw value types for an enumeration?  
  Answers:
  * Bool
  * Array
  * **Int, String, Float**
  * Dictionary

39. Which keyword do you use to declare enumeration?  
  Answers:
  * var
  * **enum**
  * struct
  * case

40. When declaring an enumeration, multiple member values can appear on a single line, separated by which punctuation mark?  
  Answers:
  * Semi-colon
  * Colon
  * **Comma**
  * Slash
  * Point

41. How do closures capture references to variables by default?  
  Answers:
  * By weak reference
  * **By strong reference**
  * By unowned reference
  * By copy

44. To declare a function in swift you would use what keyword?  
  Answers:
  * function
  * new func
  * var
  * let
  * **func**

46. Which of the folowing could be used to indicate the Function Type of the folowing function:  
  >func joinStrings(stringOne: String, stringTwo: String) -&gt; String {
      return stringOne + stringTwo
  }
  
  Answers:
  * func(String, String -&gt; String)
  * **(String, String) -&gt; String**
  * {String, String} -&gt; String
  * {String, String}(String)

47. What is used in Swift to represent any kind of object?  
  Answers:
  * Ob
  * id
  * **AnyObject**
  * Nothing

48. What is the name of the Objective-C Bridging Header given a product module named Example?  
  Answers:
  * Example-Bridging-Swift.h
  * Example-Swift.h
  * Example-Bridging-ObjectiveC.h
  * **Example-Bridging-Header.h**

53. What is the name that represents a character in Swift?  
  Answers:
  * **Character**
  * Char
  * String
  * NSString

51. What is a muting instance method in Swift?  
  Answers:
  * When there is "muting" keyword in front of extension.
  * When extension can add new types to existing classes.
  * **When instance method without extension can modify itself.**
  * A method that modifies self.

56. Swift Extensions are similar to categories in Objective-C except:  
  Answers:
  * Swift extension might have a specific name
  * Swift extension doesn’t functionality to previously defined type.
  * Swift can override method from original type.
  * **Swift extensions are not named.**

57. Considering the following code, which statement is Correct:  
  `let array1 = ["A", "B", "C"]
  var array2 = array1
  array2.append("D")`  
  Answers:
  * array1 will be copied to array2 after the assignment
  * **Reference count of array1 won't change after the assignment**
  * array1 will change to [A, B, C, D] after appending D
  * Code will not compile, can not assign constant array1 to variable array2

63. How could we create a subclass of the Structure, CGRect?  
  Answers:
  * struct MyRect: CGRect {}
  * struct CGRect(MyRect) {}
  * **You can not subclass a Structure**
  * struct MyRect extends CGRect {}

16. Which is correct regarding optional form of the type cast operator (as?)?  
  Answers:
  * It will trigger a runtime error if you try to downcast to an incorrect class type.
  * This is used when you are sure that the downcast will always succeed
  * **Return value will be nil if the downcast was not possible**

17. How could one declare a Swift Array type that can store any type of class object?  
  Answers:
  * var arr: [id] = [ ]
  * **var arr: [AnyObject] = [ ]**
  * [AnyObject] arr = [ ]
  * var arr = NSArray&lt;AnyObject&gt;()

18. What is the return value of type check operator — is ?  
  Answers:
  * **true, false**
  * 0, 1
  * yes, no
  * 1, -1

19. How could we cast the following array into an NSArray that accesses the NSArray method:  
  `componentsJoinedByString() &lt; let arr = ["1", "2", "3"]`  
  Answers:
  * arr.toNSArray.componentsJoinedByString(",")
  * NSArray(arr).componentsJoinedByString(",")
  * **(arr as NSArray).componentsJoinedByString(",")**
  * (arr bridge NSArray).componentsJoinedByString(",")

21. What set of keywords is most commonly used to iterate over a collections of items?  
  Answers:
  * for each
  * switch case
  * do while
  * **for in**

22. How can we use optional binding to determine if the variable string is not nil?  
  Answers:
  * **if let str = string {…}**
  * if string {…}
  * if string as String {…}
  * if let string {…}

24. Choose the answer that declares an optional closure.  
  Answers:
  * var closureName: (parameterTypes) -&gt; (returnType)
  * typealias closureType = (parameterTypes) -&gt; (returnType)
  * **var closureName: ((parameterTypes) -&gt; (returnType))**
  * let closureName: closureType = { … }

25. Let’s assume "numbers" is an array of unsorted integers. Which of these could be used to sort numbers?  
  Answers:
  * numbers.sort({$0, $1 in $0 &gt; $1})
  * numbers.sort({s1 &gt; s2})
  * **numbers.sort({$0 &gt; $1})**
  * numbers.sort(){s1 &gt; s2}

26. What symbol is used like a tuple to access arguments in Abbreviated Swift Closure syntax?  
  Answers:
  * **$**
  * *
  * &
  * @
  * ~

27. How could you call the following function that takes a closure as an argument using trailing closure syntax:  
  >()) {
  // function body goes here
  }&gt;
  
  Answers:
  * funcWithClosure ({
  //closure’s body goes here
  })
  * funk funcWithClosure ({
  //closure’s body goes here
  })
  * **funcWithClosure() {
  //closure’s body goes here
  }**
  * funcWithClosure {
  //closure’s body goes here
  )

28. How could the following closure be rewritten to use shorthand arguments? s2 } ) > 
  Answers:
  * reversed = sorted(names, { $0 ,$1 in $0 &gt; $1 } )
  * **reversed = sorted(names, { $0 &gt; $1 } )**
  * reversed = sorted(names, { $0 ,$1 } )
  * reversed = sorted( { $0 &gt; $1 } )

29. What is a trailing closure?  
  Answers:
  * A closure expression that is called directly after another closure expression
  * **A closure expression that is written outside of (and after) the parentheses of the function call it supports.**
  * A closure expression that is declared within the scope of another closure expression.
  * A closure expression that is declared at the property of an object.

30. Which of the following statements is true regarding Swift closures and functions?  
  Answers:
  * Functions and Closures are not related
  * A Function is a Closure declared within the scope of a Class
  * **A Function is a named Closure**
  * Closures can’t be used as arguments, Functions can

33. What are the available arithmetic overflow operators in Swift?  
  Answers:
  * op+,op-,op*,op/,op%
  * **&+,&-,&*,&/,&%**
  * +,-,*,/,%
  * &, |, &&, ||

34. What specifies custom infix operator?  
  Answers:
  * **it is a binary operator, taking a left and right hand argument**
  * it is a unary operator written before its operand
  * it is a unary operator written after its operand
  * it is a reserved word that must be preceded with **

35. Which of following statements about functions is wrong?  
  Answers:
  * **In-out parameters might have a default value**
  * Function might have multiple return values
  * Function might not have return values
  * Function names might be the same with another but at least one parameter should be different

37. In the below text, what type of return does the function ‘area’ give?  
  >Class Square: NamedShape {  
  var sideLength: Double  
  func area() -&gt; Double {  
  return sideLength*sideLength  
  }   
  }  

  Answers:
  * Int
  * the area of a square
  * **Double**
  * area

38. In the below text, what is the class name?  
  >Class Square: NamedShape {  
  var sideLength: Double  
  func area() -&gt; Double {  
  return sideLength*sideLength  
  }  
  }  

  Answers:
  * NamedShape
  * **Square**
  * class
  * Double
  * sideLength

39. In the below text, what is the name of the class’s only method?  
  >Class Square: NamedShape {  
  var sideLength: Double  
  func area() -&gt; Double {  
  return sideLength*sideLength  
  }  
  }  

  Answers:
  * sideLength
  * **area**
  * Square
  * NamedShape
  * Double

40. What aspect of iOS development requires the use of NSOperation and/or Grand Central Dispatch (GCD)?  
  Answers:
  * **Multithreading**
  * serial task
  * None
  * Message Sending

41. Which Swift Type is used to group multiple values into a single compound value? For example:  
  >let compoundValue = (3, 5)
  
  Answers:
  * GroupObject
  * **Tuple**
  * Ordered
  * Struct

42. Swift can compile alongside what other language?  
  Answers:
  * **Objective C (Objective-C)**
  * Ruby
  * Scala
  * Erlang

43. What does Swift compile to?  
  Answers:
  * C
  * C++
  * Ruby
  * **Machine code**
  * Objective-C

44. Which of following expressions can be used to rewrite the following UITableView instantiation in Swift  
  >UITableView *myTableView = [[UITableView alloc] initWithFrame: CGRectZero style: UITableViewStyleGrouped];

  Answers:
  * let myTableView: UITableView = new UITableView(frame: CGRectZero, style: .Grouped);
  * let myTableView: UITableView = UITableView.alloc().init(frame: CGRectZero, style: .Grouped);
  * **let myTableView: UITableView = UITableView(frame: CGRectZero, style: .Grouped);**
  * let myTableView: UITableView = UITableView(frame: CGRectZero, style: UITableViewStyleGrouped)

45. Which of these operators is used to check whether or not two instances are identical?  
  Answers:
  * **==**
  * =
  * equalsTo
  * ===
  * identicalTo

46. In the bellow text, what is the super class name?  
  >class Square: NamedShape {  
  var sideLenght: Double  
  func area() -&gt; Double {  
  return sideLenght * sideLenght  
  }  
  }  

  Answers:
  * Square
  * Double
  * area
  * sideLenght
  * **NamedShape**

47. In the bellow text, what is the property name?  
  >class Square: NamedShape {  
  var sideLenght: Double  
  func area() -&gt; Double {  
  return sideLenght * sideLenght  
  }  
  }  

  Answers:
  * **sideLenght**
  * Square
  * NamedShape
  * area
  * NA

48. What will happen if you assign a value to a property within its own didSet observer?  
  Answers:
  * didSet will be called again
  * It will create an infinite loop
  * **The property will take on that value**
  * Code will not compile

49. Which of the following is correct to cube Integer?  
  Answers:
  * **extension Int {
  mutating func cube () {
  self = self*self*self
  }
  }**
  * extension Int {
  mutating func cube () {
  return self*self*self
  }
  }
  * extension Int {
  func cube () {
  self = self*self*self
  }
  }
  * extension Int {
  func cube () {
  return self*self*self
  }
  }

52. In what queue should all UI code be handled?  
  Answers:
  * BackgroundQueue
  * UIQueue
  * Any Queue
  * **MainQueue**

54. In what order will the following statements appear in the console?  
  >println("1")  
  dispatch_async(dispatch_get_global_queue(DISPATCH_QUEUE_PRIORITY_DEFAULT, 0), {println("2")});  
  println("3")  

  Answers:
  * **1/3/2**
  * 3/1/2
  * 1/2/3
  * 2, 1,2

55. When declaring a function, what symbol is used to indicate that an internal parameter name should also be used as an external parameter?  
  Answers:
  * _ **(right answer)**
  * @
  * :
  * #

56. What is the result of the following code?  
  >func potteryBarn (name: String, score: Int) -&gt; String { return "Hello (name)! Your score is (score)." }  
  potteryBarn ("Tom" , 2)

  Answers:
  * **Hello Tom! Your score is 2.**
  * name: Tom, score: 2
  * Hello Tom!
  * potteryBarn = "Hello Tom! Your score is 2."

57. What is the return type in the following declaration:  
  >func potteryBarn (name: String, score: Int) -&gt; String { return "Hello (name)! Your score is (score)." }
  
  Answers:
  * Integer
  * **String**
  * Function
  * Constant

58. What are the names of the input parameters in the following function:  
  >func potteryBarn (name: String, score: Int) -&gt; String {return "Hello (name)! Your score is (score)."}

  Answers:
  * String, Int
  * potteryBarn
  * **name, score**

60. Which is the correct optional form of a down cast operator?  
  Answers:
  * as
  * **as?**
  * as!
  * as.
  * as&gt;&gt;

79. To loop through a range of the numbers 1-9 without using 9, you would write…  
  Answers:
  * for i in 0…8
  * for i in 0&gt;..9
  * for i in 1&lt;..8
  * **for i in 1..&lt;9**

80. Which of these is an invalid constant or variable declaration?  
  Answers:
  * **let = 3.14159**
  * let &lt;pi&gt; = 3.14159
  * let = ""
  * let = "dogcow"

81. What is the correct way to compare the equality of two String type objects in Swift?  
  Answers:
  * equalsTo
  * **==**
  * isEqual
  * &gt;=&lt;

82. AnyObject can represent:  
  Answers:
  * **an instance of any class type.**
  * function types.
  * an instance of any type at all.

83. What is the name of the following function:  
  >func potteryBarn (name: String, score: Int) -&gt; String { return "Hello (name)! Your score is (score)." }

  Answers:
  * String
  * name: String, score: Int
  * **potteryBarn**
  * func

84. Which keyword do you use to define a function?  
  Answers:
  * **func**
  * function
  * procedure
  * let
  * extension

85. What is the type of Swift String, Dictionary, Array?  
  Answers:
  * **Class**
  * Union
  * Enum
  * Structure

86. What will be the final value of "a.data" and "b.data" after following codes are executed?  
  >struct A { var data: Int = 2 }  
  var a = A()  
  var b = a  
  var c = b  
  c.data = 10  
  a.data = 5  

  Answers:
  * a.data = 10 and b.data = 2
  * a.data = 2 and b.data = 5
  * a.data = 5 and b.data = 5
  * **a.data = 5 and b.data = 2**

87. How will ARC handle "Country" instance and "country2" reference when "country1" is set to "nil"?
  >class Country{  
  let name: String  
  init(name: String){  
  self.name = name  
  }  
  }  
  var country1: Country?  
  var country2: Country?  
  country1 = Country(name: "Bangladesh")  
  country2 = country1  

  Answers:
  * ARC will deallocate the Country instance but country2 will hold name it’s "Bangladesh"
  * ARC will not deallocate the Country instance but country2 will become "nil"
  * **ARC will not deallocate the Country instance and country2 will hold it’s name "Bangladesh"**
  * ARC will deallocate the Country instance and country2 will become "nil"

88. What is true about Memory management in Swift?  
  Answers:
  * Swift uses Non-ARC so we need to handle the references manually.
  * **Swift uses ARC but we still need to avoid reference cycles using weak and strong references etc.**
  * Swift uses ARC so we don’t need to care about memory management at all.
  * NA

89. To which of these types does ARC apply?  
  Answers:
  * **Class**
  * Structure
  * Enumeration
  * Basic types (String, Int, Bool)

90. Why are IBOutlets declared with a weak attribute by default?  
  Answers:
  * **IBOutlets are not declared with a weak attribute by default.**
  * To save memory
  * To increase loading speed
  * They are already retained by the view

91. How could we declare a custom protocol that inherits from Equatable?  
  Answers:
  * **protocol CustomEquatable: Equatable {…}**
  * protocol CustomEquatable, Equatable {…}
  * protocol CustomEquatable extends Equatable {…}
  * protocol CustomEquatable&lt;Equatable&gt; {…}

92. How can you use a nested type outside of its definition?  
  Answers:
  * **Prefix its name with the name of the type it is nested within.**
  * It’s impossible, nested types can’t be used outside of definition.
  * It can be used from anywhere in the same block.
  * Use generic type for definition.

93. Which is correct for the following codes?  
  >class Country{  
  let name: String  
  init(name: String){  
  self.name = name;  
  }  
  var city: City?  
  }  
  class City{  
  let name: String  
  init(name: String){  
  self.name = name;  
  }  
  var country: Country?  
  }  
  var bangladesh: Country?  
  var khulna: City?  
  bangladesh = Country( name: "Bangladesh" )  
  khulna = City( name: "Khulna" )  
  bangladesh?.city = khulna  
  khulna?.country = bangladesh  
  bangladesh = nil  
  khulna = nil  

  Answers:
  * **Neither Country, nor City will be deallocated.**
  * Both Country and City instance will be deallocated.
  * Only Country instance will be deallocated.
  * Only City instance will be deallocated.

94. Which keyword is used to declare an extension in Swift?  
  Answers:
  * extend
  * **extension**
  * typealias
  * mutating
  * subscript

95. Which of the following statements is true when talking about classes and structures in Swift?  
  Answers:
  * Both incorporate Inheritance
  * Both use reference counting
  * **Both can be extended**
  * Both are value types

96. How could we extend String to conform to protocol MyProtocol?
  Answers:
  * extension String(MyProtocol) { }
  * extension String, prot MyProtocol { }
  * **extension String: MyProtocol { }**
  * extension String, MyProtocol { }

98. Which keyword do you use to define a class?
  Answers:
  * **class**
  * method
  * var
  * property

1. What is the output of this segment of code:
  >var x = 0
  for index in 1...5 {
  ++x
  }
  print("\(x)")

  Answers:
  * 4
  * **5**
  * 6
  * None of this

2. Can Structures be type cast in Swift?  
  Answers:
  * Yes
  * **No**
  * Only those deriving from NSObject
  * Only when they conform to protocol TypeCast

3. Which keyword do you use to define a protocol?  
  Answers:
  * **protocol**
  * interface
  * struct
  * class

1. Which of these statements declares cityArray as a mutable array?                          
  Answers:                    
  * let cityArray = ["Portland","San Francisco","Cupertino"]
  * let cityArray = &#91;String&#93;&#40;&#41;
  * **var cityArray = ["Portland","San Francisco","Cupertino"]**
  * var cityArray = ["OR" : "Portland", "CA" : "San Francisco"]

2. Which of these collection types is not included by default in standard Swift?  
Answers:                     
  * Set
  * Array
  * Dictionary
  * **NA**

3. What happens when Swifts String, Array, and Dictionary objects are assigned to a new constant or variable?  
Answers:                     
  * **They are copied.**
  * They are always assigned and passed around as a reference to an existing instance.
  * They are assigned or copied according to the variable definition.

4. What is the most basic difference between Value and Reference types?  
  Answers:              
  * Copying Value type creates an shared instance where Reference type creates independent instance
  * Value type instance share a single copy of the data where Reference type instances keeps a unique copy of its data
  * **Assigning a Value type to a new variable copies its contents to a new instance, where Reference types do not.**
                                


