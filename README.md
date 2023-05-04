Download Link: https://assignmentchef.com/product/solved-cs520-week-3-assignment
<br>
CS520 Week 3 AssignmentGeneral Rules for Homework Assignments• You are strongly encouraged to add comments throughout the program. Doingso will help your facilitator to understand your programming logic and gradeyou more accurately.• You must work on your assignments individually. You are not allowed to copythe answers from the others. However, you are encouraged to discuss theapproaches to the homework assignments with your section mates and thefacilitator in your section via the discussion board.• Each assignment has a strict deadline. However, you are still allowed to submityour assignment within 2 days after the deadline with a penalty. 15% of thecredit will be deducted unless you made previous arrangements with yourfacilitator and professor. Assignments submitted 2 days after the deadline willnot be graded.• When the term lastName is referenced in an assignment, please replace it withyour last name.You are strongly encouraged to add comments into your program!Create a new Java Project in Eclipse named HW3_lastName and complete thefollowing two parts.Part 1 (40 Points) – Strings &amp; ExceptionsCreate a package named cs520.hw3.part1. Using this package, create the classStringTest and implement the specified functionality in its main method.a. Ask the user, through a single input dialog, for the name, age, and theircity in the formatName,Age,Cityb. Trim the user’s input, in case spaces were entered at the beginning or atthe end.c. Display the trimmed data to the console. Do the following operationsusing this trimmed string.d. Find the index of the first comma in the input using the indexOf method.Using this value, extract name part of the input using the substringmethod.e. Display the position of the first comma, the name, and the length of thename to the console.f. Find the index of the second comma in the input using the indexOfmethod. Using this value, extract the age part of the input using thesubstring method.g. Display the position of the second comma, and the age to the console.Convert the value to an integer. Display to the console their age in 10years.h. Extract the city using the substring method. Display to the console thecity and the length of the city to the console.i. Now, examine the code for all possible exceptions that could occur.Handle all the different exceptions explicitly and print out the appropriateexception message to the console.Sample Input:Sample Output:Also, test the following inputs where exceptions will occur and your programhandles them gracefully — when Cancel is clicked, when only the name isentered, when only the name and the age are entered, and when all thethree values are specified but the age is not an integerPart 2 (60 Points) – StringTokenizer and File InputCreate a package named cs520.hw3.part2. Using this package, create the followingclasses.1. Create a class named Senator as follows.a. The instance (or member) private variables – name, party, state (String),and yearsInOffice (integer).b. A single constructor with name as its argument.c. The public get and set methods for the instance variables.d. Override the toString method to return the string representation of thisobject in the format “&lt;name&gt; (&lt;party&gt;) from &lt;state&gt; has beenthe senator for &lt;yearsInOffice&gt; years”.2. Create a Test class to test the following functionality in its main method.a. Use the BufferedReader class to read the data.txt file. Thecontents of the file are shown below. Create the data.txt file inHW3_lastName folder.b. Read the contents of the text file one line at a time using a loop.The program should work for any number of input lines. Invoke theprocessInputData method for each line read.c. Write a private method processInputData which processes its stringinput argument as follows.1. Tokenize the string argument using the StringTokenizer classusing the comma as the delimiter.2. Extract the name token. Create a Senator object and assignto the variable currentSenator.3. Read the rest of the tokens one token at a time. Use thecorresponding set method on the currentSenator object toset the instance value.4. If the yearsInOffice is not a valid number, i.e., throws anexception when parsed, set the value as -99 in the exceptionhandling part.5. Display the string representation of the currentSenator objectto the console.Sample Input data.txt file:Al Franken,8,Democrat,MinnesotaAmy Klobuchar,10,Democrat,MinnesotaAngus King,4,Independent,MaineBen Cardin,10,Democrat,MarylandBen Sasse,2,Republican,NebraskaBernie Sanders,10,Independent,VermontSample Output:Submission:Create an archive of your Eclipse project using the following steps. Select theHW3_lastName project in the Eclipse IDE’s Package Explorer or the Navigatorwindow.Click File-&gt;Export. Select the General-&gt;Archive File option. Click Next.Specify the “To archive file:” entry as say, C:TempHW3_lastName.zip.The zip file will be created and stored in the C:Temp folder.Submit this zip file as an attachment in the Assignment Section.