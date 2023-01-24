Description of your approach in the github url link

The approach used in the java program is:

As I am required to create a file copy program that works exactly like a windows file copy

Firstly the program asks the user to enter the file name that needs to be copied
I used Scanner class for that to store the input

I use File class to check if the input file exist, by creating a File object using the name entered by the user (fileName) and calling the exist() method on it

If the input file does not exist the program prints an error message that "Sorry the file you named does not exist"

if the input file exist the program generates the output file name as per windows naming convention by appending -Copy to the oroginal file name.
Again if user enter same file name the program checks that the file exist or not by calling exist() method and if exist it will increment the copy number as copy(n)

this program uses FileInputStream and FileOutputStream classes to read and write the file respectively.

finally at last the program closes by printing messsage "yay!!! Your file is sucessfully copied to....." indicating that the file has been copied sucessfully
