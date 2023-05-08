Download Link: https://assignmentchef.com/product/solved-solvedcomputer-science-221-program-4
<br>
Learningobjectives:

Write a Javaclass with multiple constructors.

Write a Javaclass with more complex methods.

Assignment:

Define a class named MyString whose objects simulate JavaStrings. The class must have two instance variables, one of type int for the lengthand one of type char[] for the contents of thestring. You may not use any Java String variables orvalues in this program, except as specified below.

Write two public constructors. One has a JavaString parameter. It converts the String to an array of char by the method toCharArray(). This is the only String method that youare allowed to use in this program. The other has a MyString parameter, andmakes a new MyString with the same contents.

Write the following methods. It is stronglysuggested that you write them in this order, and test each method after youhave written it. Remember that after you write a constructor or method you may(and should) use it to write further methods.

StringtoString() returns the String representation of the MyString object. Thismust meet all the usual requirements of a toString() method. Pass thechar[] array to a String constructor. Ifthe array is named s, this looks like newString(s). This is the only String constructor thatyou are allowed to use in this program.

intlength() returns the length of the MyString object.

charcharAt(int i) returns the character at position i of the MyString object.

At this point write a private constructor. It has a char[] parameter, andmakes a new MyString with the same contents.

Continuing with methods. Be prepared to do some arithmetic in some ofthese methods.

MyStringclone()makes a copy of the MyString object.

booleanequals(MyString s) returns true or false as this and s are equal ornot.

MyStringconcat(MyString s) returns a MyString object that begins with thecontents of this to which the contents of m are appended.

intindexOf(char c, int i) returns the position of the first occurrence of c in this, at or after theith position of this. Returns -1 if c does not occurin this.

MyStringsubstring(int i, int j) returns a MyString object thatbegins with the ith position of this and ends withthe (j-1)th position of this.

intindexOf(MyString s, int i) returns the position of the first occurrence of s in this, at or after theith position of this. Returns -1 if s does not occurin this.

MyStringreplace(MyString oldPart, MyString newPart) returns a MyString object that islike this except that the substring oldPart within this is replaced bythe substring newPart. newPart may be longer orshorter than oldPart, so the resulting MyString may be longer orshorter than this.

Write a program TestMyString to test your MyString class. Wereserve the right to replace your TestMyString with our own.

Submissioninstructions:

Upload the files MyString.java and TestMyString.java to “Program 4”.Do not submit class files or any of the BlueJ control files. Be sure to pressthe submit button.

Policies:

The policies given on WebCT are in effect for this and all assignments.

You may submit on WebCT multiple times, so there is no excuse for notsubmitting partial solutions.