# UPWORK JAVA TEST V3 2016

1. Consider the following code:  
  `public class Jam {
     public void apple(int i, String s) {   
     }    
     //ABC    
  }`  
  Choose possible valid code replacements of «//ABC» among the choices:  
  Answers:
  * __public void apple(String s, int i) {}__
  * public int apple(int i, String s) {}
  * public void apple(int i, String mystring) {}
  * public void Apple(int i, String s) {}  

2. Which of these is not an event listener adapter defined in the java.awt.event package?  
  Answers:
  * __ActionAdapter__
  * MouseListener
  * WindowAdapter
  * FocusListener  

3. Which distributed object technology is most appropriate for systems that consist of objects written in different languages and that execute on different operating system platforms?  
  Answers:
  * RMI
  * __CORBA__
  * COBRA
  * DCOM
  * COM  

4. The transaction attribute of a bean is set to ‘TX_REQUIRES_NEW’. What can be inferred about its behavior?  
  Answers:
  * It initiates a new transaction only when the previous one is concluded.
  * It initiates a new transaction without waiting for the previous one to conclude.
  * It sends the request to the EJB container for initiating a new bean.
  * __The bean manages its own transaction.__

5. Which of the following is a well-known HTTP port?  
  Answers:
  * 21
  * 25
  * 8080
  * __80__
  * 137

6. Which of the following methods can be used for reporting a warning on a Connection object, Statement object & ResultSet object?  
  Answers:
  * __getWarnings()__
  * getWarned()
  * getWarning()
  * getError()
  * getErrors()

7. The principal finder method that must be implemented by every entity bean class is:  
  Answers:
  * __findByPrimaryKey()__
  * ejbGetByPrimaryKey()
  * ejbFindPrimayKey()
  * getPrimaryKey()
  * getFinder()

8. How does the set collection deal with duplicate elements?  
  Answers:
  * Duplicate values will cause an error at compile time.
  * A set may contain elements that return duplicate values from a call to the equals method.
  * An exception is thrown if you attempt to add an element with a duplicate value.
  * __The add method returns false if you attempt to add an element with a duplicate value.__

9. Why can’t a string’s compareTo method be overridden?  
  Answers:
  * __The String class is final, therefore its methods can’t be overridden.__
  * The String class doesn’t have a compareTo method.
  * A compareTo method isn’t built-in; it has to be manually implemented.

10. Which class contains a method to create a directory?  
  Answers:
  * __File__
  * DataOutput
  * Directory
  * FileDescriptor
  * FileOutputStream

11. Which of these interfaces is the most applicable when creating a class that associates a set of keys with a set of values?
  Answers:
  * Collection
  * Set
  * __Map__
  * SortedSet

12. Assuming the servlet method for handling HTTPGET requests is doGet(HttpServletRequest req, HTTPServletResponse res), how can the request parameter in that servlet be retrieved?
  Answers:
  * String value=req.getInitParameter(10);
  * String value=req.getInitParameter(«product»);
  * __String value=res.getParameter(«product»)__;
  * __String value=req.getParameter(«product»);

13. Which of the following is the correct syntax for suggesting that the JVM perform garbage collection?  
  Answers:
  * System.setGarbageCollection();
  * System.out.gc();
  * __System.gc();__
  * System.free();

14. Which of the following methods should be invoked by the container to get a bean back to its working state?  
  Answers:
  * EJBPassivate()
  * __EJBActivate()__
  * EJBRemove()
  * EJBOpen()
  * EJBActivation()

15. What is the output of the given program?  
  `public class Test89 {`  
  `  public static void main(String[] args) {`  
  `    T x = new T(«X», null); x.start();`  
  `    T y = new T(«Y», x); y.start();`  
  `    T z = new T(«Z», y); z.start();`  
  `  }`  
  `}`  
  `class T extends Thread {`  
  `  private Thread predecessor;`  
  `  private String name;`  
  `  public T(String name, Thread predecessor) {`  
  `    this.predecessor = predecessor;`  
  `    this.name = name;`  
  `  }`  
  `  public void run() {`  
  `    try {`  
  `      Thread.sleep((int)(Math.random()*89));`  
  `      System.out.print(name);`  
  `    } catch (InterruptedException ie) {`  
  `      ie.printStackTrace();`  
      `}`  
    `}`  
  `}`  
  Answers:
  * always XYZ
  * always ZYX
  * **any of the following: XYZ, XZY, YXZ, YZX, ZXY, ZYX**
  * any of the following: XYZ, ZYX

16. Which of the following require explicit try/catch exception handling by the programmer?  
  Answers:
  * Accessing a method in another class
  * **Attempting to open a network socket**
  * **Attempting to open a file**
  * Traversing each member of an array

17. What protocol is used by the DatagramSocket class?  
  Answers:
  * STCP
  * **UDP**
  * TCP
  * FTP
  * None of the above

18. What should be the replacement of «//ABC» in the following code?  
  `class Krit {`  
  `  String str= new String(«OOPS !!! JAVA»);`  
  `  public void KritMethod(final int iArgs) {`  
  `    int iOne;`  
  `    class Bicycle {`  
  `      public void sayHello() {`  
  `        //ABC`  
  `      }`  
  `    }`  
  `  }`  
  `  public void Method2() {`  
  `    int iTwo;`  
  `  }`  
  `}`  
  Answers:
  * **System.out.print(str);**
  * System.out.print(iOne);
  * System.out.print(iTwo);
  * System.out.print(iArgs);

19. What is the output of the given program?  
  `public class Test117 {`  
  `  {`  
  `  System.out.print("_INIT");`  
  `  }`  
  `  static {`  
  `  System.out.print("_STATIC");`  
  `  }`  
  `  Test117() {`  
  `  System.out.print("_CONST");`  
  `  }`  
  `  public static void main(String[] args) {`  
  `    System.out.print("_MAIN");`  
  `    new Test117();`  
  `  }`  
  `}`  
  Answers:
  * **_STATIC_MAIN_INIT_CONST**
  * _STATIC_MAIN_CONST_INIT
  * _INIT_STATIC_CONST_MAIN
  * _STATIC_INIT_CONST_MAIN

20. Assuming the tag library is in place and the tag handler is correct, which of the following is the correct way to use a custom tag in a JSP page?  
  Answers:
  * `<yourLibrary="whatColorlslt" color="red"/>`
  * **`<yourLibrary:whatColorlslt color="red"/>`**
  * `<yourLibrary color="red"/>`
  * `<yourLibrary.whatColorlslt color="red"/>`
  
21. Why would the following code snippet not compile successfully?  
  `if (mangoList instanceof List<Mango>) { System.out.println("true"); }`  
Answers:
  * It is unknown whether mangoList is a List type.
  * **Generic types are erased before runtime.**
  * The instanceof keyword only works on primitive types.

22. Choose all valid forms of the argument list for the FileOutputStream constructor shown below:  
Answers:
  * **FileOutputStream( FileDescriptor fd )**
  * **FileOutputStream( String n, boolean a )**
  * FileOutputStream( boolean a )
  * FileOutputStream()
  * **FileOutputStream( File f )**

23. Which of the following are wrapper classes?  
  Note: There may be more than one right answer.  
  Answers:
  * java.lang.Math
  * **java.lang.Boolean**
  * **java.lang.Long**
  * **java.lang.Float**

24. Which of the following illustrates correct synchronization syntax?  
Answers:
  * public synchronized void Process(void){}
  * public void Process(){ synchronized(this){ } }
  * public void synchronized Process(){}
  * **public synchronized void Process(){}**

25. With regard to the destroy lifecycle method, identify the correct statements about its purpose or about how and when it is invoked.
  Note: There may be more than one right answer.  
Answers:
  * **It gives the servlet an opportunity to clean up resources.**
  * Like try-catch, it is called upon an exception.
  * It is rarely used but can be called to remove a servlet from memory.
  * It isn’t called if the server crashes.

26. Which of these interfaces are used by implementations of models for JTable?  
  Answers:
  * **TableModel**
  * TableColumnModel
  * TableSelectionModel
  * ListModel

27. Which of the following is the correct syntax for creating a Session object?  
  Answers:
  * HttpSession ses=request.getSession(true);
  * HttpSession ses=getSession(true);
  * **HttpSession ses=request.getSession();**
  * HttpSession ses=request.getSessionObject(true);
  * HttpSession ses=response.getSession(true);

28. Which of the following symbols are metacharacters supported by the java.util.regex API?  
  Answers:
  * **.** (right answer)
  * \
  * @
  * #

29. Which of the following code snippets will correctly convert from one time zone to another time zone?  
  Note: There may be more than one right answer.  
  Answers:
  * **`DateFormat formatter = new SimpleDateFormat(«dd/MM/yyyy HH:mm:ss»);
  formatter.setTimeZone(TimeZone.getTimeZone(«GMT-8»));
  Date date = formatter.parse(«01/01/2012 05:00:00»);
  System.out.println(formatter.format(date));
  formatter.setTimeZone(TimeZone.getTimeZone(«GMT+5»));
  System.out.println(formatter.format(date));`**
  * **`DateFormat formatter = new SimpleDateFormat(«dd/MM/yyyy HH:mm:ss»);
  formatter.setTimeZone(TimeZone.getTimeZone(«PST»));
  Date date = formatter.parse(«01/01/2012 05:00:00»);
  System.out.println(formatter.format(date));
  formatter.setTimeZone(TimeZone.getTimeZone(«IST»));
  System.out.println(formatter.format(date));`**
  * `DateFormat formatter = new SimpleDateFormat(«dd/MM/yyyy HH:mm:ss»);
  formatter.setTimeZone(new TimeZone(«PST»));
  Date date = formatter.parse(«01/01/2012 05:00:00»);
  System.out.println(formatter.format(date));
  formatter.setTimeZone(new TimeZone(«IST»));
  System.out.println(formatter.format(date));`
  * `DateFormat formatter = new SimpleDateFormat(«dd/MM/yyyy HH:mm:ss»);
  formatter.setTimeZone(new TimeZone(«GMT-8»));
  Date date = formatter.parse(«01/01/2012 05:00:00»);
  System.out.println(formatter.format(date));
  formatter.setTimeZone(new TimeZone(«GMT+5»));
  System.out.println(formatter.format(date));`

30. Select all true statements:  
  Note: There may be more than one right answer.  
  Answers:
  * **Threads exist within a process.**
  * **Every process has at least one thread.**
  * Processes exist within a thread.
  * A thread may belong to more than one process.

31. Which code snippet will check for the existence of the file «text.txt» in the current location?  
  Note: There may be more than one right answer.  
  Answers:
  * **`File f = new File(«text.txt»);
  System.out.println(f.exists());`**
  * `File f = new File(); f.setName(«text.txt»);
  System.out.println(f.exists());`
  * `File f = new File(«text.txt»);
  System.out.println(f.equals(f));`

32. Which of the following is true regarding sleep() and wait() in threaded environments?  
  Answers:
  * Both can take time in milliseconds as a parameter and will execute when the time is expired.
  * Both will wait for another thread’s notify() method before it can execute.
  * The wait() method will wait for a specific time (in milliseconds) and continue execution afterwards, while sleep() will wait for another thread’s notify() method before it will execute.
  * **The sleep() method will wait for a specific time (in milliseconds) and continue execution afterwards, while wait() will wait for another thread’s notify() method before it will execute.**

33. Choose the right syntax for preparedStatement using ? as a placeholder for values, namely CUSTOMER_ID,PRICE, to be substituted while inserting values in the table ORDER:  
  `PreparedStatement ps=con.prepareStatement(«INSERT INTO ORDER (CUSTOMER_ID ,PRICE) VALUES(?,?)»);`  
  Answers:
  * ps.clearParameters(); ps.setInt(1,3); ps.setDouble(2,790.50); ps.executeUpdate(sql);
  * **ps.clearParameters(); ps.setInt(1,3); ps.setDouble(2,790.50); ps.executeUpdate();**
  * ps.clear(); ps.setInt(1,3); ps.setDouble(2,790.50); ps.executeUpdate(sql);
  * ps.clearParameters(); ps.setInt(1,3.09); ps.setDouble(2,790.50); ps.execute(sql);
  * ps.clearParameters(); ps.setInt(1,3.09); ps.set(2,790.50); ps.execute(sql);

34. Given a method declared as:  
  `public static <E extends Number> List<E> process(List<E> nums)`  
  A programmer wants to use the method like this:  
  *// INSERT DECLARATIONS HERE*  
  `output = process(input);`  
  Which pair of declarations could be placed at *// INSERT DECLARATIONS HERE* to allow the code to compile? (Choose all that apply.)  
  Note: There may be more than one right answer.  
  Answers:
  * `ArrayList<Integer> input = null;
  ArrayList<Integer> output = null;`
  * **`ArrayList<Integer> input = null;
  List<Integer> output = null;`**
  * **`List<Integer> input = null;
  List<Integer> output = null;`**

35. Which is the right syntax of a javadoc comment for parameter of the method test(int)?  
  `public class Test125 {
  public static void main(String[] args) {
  new Test125().test(125);
  }
  public void test(int a) {
  for (int i=0; i<a; System.out.println(i++));
  }
  }`  
  Answers:
  * **@param a Description**
  * @parameter int a Description
  * @param Description
  * @parameter a Description

36. What will be the output when this code is compiled and run?  
  `public class Test {
  static int x = 10;
  public Test() {
  Bar b = new Bar();
  Bar b1 = new Bar();
  update(b);
  update(b1);
  }
  private void update(Bar bar) {
  bar.x = ++x;
  System.out.println(bar.x);
  }
  public static void main(String args[]) {
  new Test();
  }
  private class Bar {
  public int x = 10;
  }
  }`  
  Answers:
  * The code will fail to compile.
  * **11 12**
  * 11 11
  * 12 12

37. Which line of code will produce output «base», if inserted instead of the comment in the given code?  
  `public class Test9 {
  public static void main(String[] args) {
  new Child9().printBase();
  }
  }
  class Parent9 {
  public void printSgnt() {
  System.out.println(«base»);
  }
  }
  class Child9 extends Parent9 {
  public void printSgnt() {
  System.out.println(«—-«);
  }
  public void printBase() {
  // !!! INSERT A CODE LINE HERE !!!
  }
  }`  
  Answers:
  * **super.printSgnt();**
  * this.printSgnt();
  * printSgnt();
  * printBase();

38. Choose the correct declarations for the main() method which will allow the class to be run as a standalone program:  
  Note: There may be more than one right answer.  
  Answers:
  * public void main(String str[])
  * **static public void main(String str[])**
  * public static int main(String str[])
  * **public static void main(String str[])**

39. What is the central abstraction of the Java Servlet API?  
  Answers:
  * **The Servlet interface**
  * The GenericServlet
  * The HttpServlet
  * The Servlet package
  * The Servlet object

40. What will be the output of the following code?  
  `import java.util.*;
  public class Test {
  public static void main(String args[]) throws Exception {
  List l = new ArrayList();
  int a = (int) (3 * 2.5);
  for (int i = 0; i &lt; 10; i++)
  l.add(i);
  String s = «Hello»;
  l.add(a, s.getBytes(«UTF-8»)[2]);
  System.out.println(l);
  }
  }`  
  Answers:
  * [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
  * **[0, 1, 2, 3, 4, 5, 6, 108, 7, 8, 9]**
  * [0, 1, 2, 3, 4, 5, 6, 108, 8, 9, 10]
  * The code won’t compile.

41. What is true regarding the User Datagram Protocol (UDP)?  
  Note: There may be more than one right answer.  
  Answers:
  * A message is never partial.
  * Messages order is guaranteed.
  * Messages are not guaranteed to arrive at destination.
  * UDP is MTU independent.
  * **None of these.**

42. Which statements, when inserted at the indicated position in the following code, will cause a runtime exception when attempting to run the program?  
  `class A {
  }
  class B extends A {
  }
  class C extends A {
  }
  public class X {
  public static void main(String args[]) {
  A x = new A();
  B y = new B();
  C z = new C();
  // insert statement here
  }
  }`  
  Note: There may be more than one right answer.  
  Answers:
  * x = y;
  * z = x;
  * y = (B)x;
  * **y = (A)y;**

43. Which of the following will programmatically throw an exception?  
  Answers:
  * **throw new Exception();**
  * throws new Exception();
  * throw Exception();
  * It is not possible to throw an exception programmatically.

44. Which of the following statements are true regarding declaring a servlet instance in a deployment descriptor?  
  Answers:
  * **The tags are nested within &lt;web-app&gt; tags**
  * The tags do not define parameters
  * The tags are &lt;servlet-instance&gt;&lt;/servlet-instance&gt;
  * **It specifies the fully qualified class name of the servlet**

45. Which of the following options is a valid declaration?  
  Answers:
  * **`<%! String name="Patricia" %>`**
  * `<%! String name="Patricia"; %>`
  * `<% String name="Devyn" %>`
  * `<% public String name="Devyn"; %>`

47. What is the return type of the method ceil(double) from the Math class  
  Answers:
  * int
  * float
  * **double**
  * Integer
  * Double

48. What would happen on trying to compile and run the following code?  
  `class ExThread extends Thread
  {
  public native String getTime();
  }
  public class ThMulti implements Runnable
  {
  boolean Stop;
  public static void main(String argv[])
  {
  ThMulti m = new ThMulti();
  m.go();
  }
  public void go()
  {
  ExThread ts = new ExThread(this);
  ts.start();
  Stop=true;
  }
  public void run()
  {
  if(Stop==true)
  {
  return;
  }
  System.out.println(«Thread is running»);
  }
  }`  
  Answers:
  * **The code will not compile.**
  * The code will compile but will give a Runtime error.
  * The code will compile and will print ‘Thread is running’.
  * The code will compile and will print nothing on the screen.

49. What will happen to the running session beans if the EJB container crashes or restarts?  
  Answers:
  * **They will get destroyed (They will be destroyed)**
  * They will keep on running
  * Their execution will be halted temporarily
  * None of the above

50. With regard to the servlet context listener, which of the following methods is valid?  
  Answers:
  * contextListenerEvent
  * **contextListenerInitialized**
  * contextInitialized
  * contextListenerDestroyed

52. What would be the result of the following code?  
  
  >public class Quest  
  {  
  int i=0;  
  public static void main(String argv[]) {  
  }  
  Quest()  
  {  
  top:  
  while(i &lt; 2) {  
  System.out.println(i);  
  i++;  
  continue top;  
  }  
  }  
  }  
  
  Answers:
  * **The code will compile but will not output anything at runtime**
  * The code will compile and output 0
  * The code will compile and output 0 followed by 1
  * The code will not compile as a target label cannot appear before the corresponding continue or break statement

53. Which of the following code snippets will generate five random numbers between 0 and 200?  
  Answers:
  * Random r = new Random(); for (int i = 0; i &lt; 5; i++) { System.out.println(r.nextInt(0,200)); }
  * Random r = new Random(200); for (int i = 0; i &lt; 5; i++) { System.out.println(r.nextInt()); }
  * **Random r = new Random(); for (int i = 0; i &lt; 5; i++) { System.out.println(r.nextInt(200)); }**
  * Random r = new Random(200); for (int i = 0; i &lt; 5; i++) { System.out.println(r.nextInt(0)); }

54. Which of the following statements is true of the HashMap class?  
  Answers:
  * **It stores information as key/value pairs.**
  * Elements are returned in the order they were added.
  * It does not permit null keys.
  * It does not permit null values.

55. Which statement is true regarding ServletContext Initialization Parameters in the deployment descriptor?  
  Answers:
  * **They are accessible by all servlets in a given web application.**
  * They are accessible by all servlets in a given session.
  * They are accessible by all servlets in a given HTTP request.
  * They are accessible by all servlets in a given container.

56. Which distributed object technology is most appropriate for systems that consist entirely of Java objects?  
  Answers:
  * **RMI**
  * CORBA
  * DCOM
  * COM
  * JDBC

57. Which of the following transaction modes are supported by Enterprise Java Beans?  
  Answers:
  * TX_NOT_SUPPORTED
  * TX_BEAN_MANAGED
  * TX_REQUIRED
  * TX_MANDATORY
  * **All of the above**

58. How many objects are created in the given code?  
  `Object x, y, z;
  x = new Object();
  y = new Object();`  
  Answers:
  * 0
  * 1
  * **2** (right answer)
  * 3

59. Which method in the HttpServlet class corresponds to the HTTPPUT method?  
  Answers:
  * put
  * **doPut**
  * httpPut
  * putHttp

60. Which of the following is the name of the cookie used by Servlet Containers to maintain session information?  
  Answers:
  * SESSIONID
  * SERVLETID
  * **JSESSIONID**
  * CONTAINERID

61. Which of the following are valid ways to define a thread in Java?  
  Answers:
  * **Create a subclass of java.lang.Thread class**
  * Create a class that implements java.lang.Runnable
  * Define method run() in a class
  * Define method call() in a class

62. Which of the following are the methods of the Thread class?  
  Answers:
  * stay()
  * go()
  * **yield()**
  * **sleep(long millis)**

63. Which option could be used to see additional warnings about code that mixes legacy code with code that uses generics?  
  Answers:
  * **-Xlint:unchecked**
  * -Xlint:-unchecked
  * -Xswitchcheck or -Xlint:fallthrough depending on the version of Java
  * -classpath or -cp

64. The JDK comes with a special program that generates skeleton and stub objects that is known as:  
  Answers:
  * java.rmi.Remote
  * rmi
  * **rmic**
  * rmijava
  * javac

65. Which design pattern reduces network traffic by acting as a caching proxy of a remote object?  
  Answers:
  * DataAccess Object
  * Model-View-Controller
  * **Value Object**
  * Business Delegate

66. In which class is the notify method defined?  
  Answers:
  * Thread
  * Applet
  * Runnable
  * **Object**

67. Which of the following methods are members of the Vector class and allow you to input a new element?  
  Answers:
  * addItem
  * append
  * insert
  * **addElement**

68. Why can’t a Graphics object be created using the following statement?  
`Graphics g = new Graphics();`  
  Answers:
  * The Graphics class is a final class.
  * **The Graphics class is an abstract class.**
  * The constructor of the Graphic class needs a color object to be passed as a parameter, e.g Graphics g = new Graphics(new Color());.

69. Which of the following is false?  
  Answers:
  * A scrollable ResultSet can be created in JDBC 2.0 API.
  * The cursor is moved forward using next().
  * The cursor is moved backward using previous().
  * A while loop can be used because next() & previous() methods return false beyond the resultset.
  * **A while loop can be used because next () & previous () methods return -1 beyond the resultset.**

70. Which of the following interfaces makes it possible for Java to save an object to a file and turn it into a data stream?  
  Answers:
  * java.io.Serialization
  * java.net.Serializable
  * java.net.Serialization
  * **java.io.Serializable**
  * java.net.io.Serializable

71. As part of the type erasure process, when compiling a class or interface that extends a parameterized class or implements a parameterized interface, the compiler may need to create a synthetic method, called a _________.  
  Answers:
  * **bridge method**
  * helper method
  * stub method
  * raw method

72. What is the output of the given console application?  
>public class Test31 {  
>public static void main(String[] args) {  
>test();  
>}  
>public static void test() {  
>try {  
>System.out.print(«-try»);  
>return;  
>} catch (Exception e) {  
>System.out.print(«-catch»);  
>} finally {  
>System.out.print(«-finally»);  
>}  
>}  
>}  
  
  Answers:
  * -try
  * -try-catch
  * **-try-finally**
  * -try-catch-finally

1. Which of the following methods will cause a thread to stop?  

  Answers:
  * Invoking the interrupt() method of the thread.
  * Invoking the sleep() method of the thread.
  * When execution of the run() method ends.
  * None of these.

2. What will be the output when this code is compiled and run?  
>public class Test {  
>
>public Test() {  
>Bar b = new Bar();  
>Bar b1 = new Bar();  
>update(b);  
>update(b1);  
>b1 = b;  
>update(b);  
>update(b1);  
>}
>
>private void update(Bar bar) {  
>bar.x = 20;  
>System.out.println(bar.x);  
>}
>
>public static void main(String args[]) {  
>new Test();  
>}
>
>private class Bar {  
>int x = 10;  
>}
>}  

  Answers:
  * The code will fail to compile.
  * 10 10 10 10
  * 20 20 20 20
  * 10 20 10 20

3. Select the correct option based upon the following sample code:  
>public class Test {  
>static int a;  
>int b;  
>public Test() {  
>int c;  
>c = a;  
>a++;  
>b += c;  
>System.out.println("one”);  
>}
>
>public void Test() {  
>int c;  
>c = a;  
>a++;  
>b += c;  
>System.out.println("two”);  
>}
>
>public static void main(String args[]) {  
>Test t = new Test();  
>}  

  Answers:
  * The code will fail to compile because there is a method with the same name as the class name.
  * The code will fail to compile because there are 2 constructors with the same names and parameters.
  * The code will fail to compile because the constructor is trying to access a static variable.
  * The code will compile but will fail when run.
  * The code will compile and run successfully. It will print "one".
  * I The code will compile and run successfully. It will print "two”.

4. What will be written to the standard output when the following program is run?
>public class X {  
>public static void main(String args[]) {
>System.out.println(11 ^ 2);  
>}  
>}  

  Answers:
  * 10
  * 9
  * 11
  * 13
  * 121

5. An online shop employs a stateless session bean (named 'Eshop') to process the requests. Eshop' uses a declarative transaction management system. The following code is from the XML deployment descriptor file of the bean:  
  >1. <ejb-jar>
  2. (enterprise-beans)
  3. <session>
  4. <ejb-name>Eshop</ejb-name>
  5. <home>com.solution.Eshopflome</home>
  6. <remote>com.solution.Eshop</remote>
  7. <local-home>com.solution.EshopLocalHome<llocal-home>
  8. <local>com.solution.EshopLocal</local>
  9. <ejb-class>com.solution.EshopBean</ejb-class>
  10.
  11.
  12. </session>
  13. </enterprise-beans>
  14. </ejb-jar>  

The session and transaction attributes are to be coded in the lines numbered 10 and 11.
Which of the following options should be used to make the bean work as expected?  
  Answers:
  * <session>Stateless<lsession>
  <transaction>Container</transaction>
  * <session>Stateful<lsession>
  <transaction>Bean</transaction>
  * <session-type>Stateless<lsession-type>
  <transaction-type>Container</transaction-type>
  * <session-type>Stateful</session-type>
  <transaction-type>Bean</transaction-type>
  * <session-type>Stateless<lsession-type>
  <transaction>Container</transaction>

6. Which of the following code snippets will take transform input string "2012/06/05" to output string "05 - 06 - 2012"?  
  Answers:
  * String dateString = "2012/06/05";
  Date date = new SimpleDateFormat("yyyy/MM/dd").parse(dateString);
  SimpleDateFormat sdf = new SimpleDatePormat(“dd - MM - yyyy“);
  System.out.println(sdf.format(date));
  * String dateString = "2012/06/05";
  Date date = new SimpleDateFormat("yyyy/MM/dd").format(dateString);
  SimpleDateFormat sdf = new SimpleDatePormat(“dd - MM - yyyy“);
  System.out.println(sdf.parse(date));
  * String dateString = "2012/06/05";
  Date date = new SimpleDateFormat("dd - MM - yyyy").format(dateString);
  SimpleDateFormat sdf = new SimpleDatePormat(“yyyy/MM/dd”);
  System.out.println(sdf.parse(date));
  * String dateString = "2012/06/05";
  Date date = new SimpleDateFormat("dd - MM - yyyy").parse(dateString);
  SimpleDateFormat sdf = new SimpleDatePormat(“yyyy/MM/dd”);
  System.out.println(sdf.format(date));




















