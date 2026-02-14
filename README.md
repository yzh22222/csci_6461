CSCI6461 Assembler

This project implements an assembler for the CSCI6461 architecture. It converts .asm assembly source files into machine-readable output files.

Project Structure

CSCI6461_Assembler/ │ ├── *.java ├── Assembler.jar ├── tests/ │ └── filename.asm 

 How to Test the Assembler

Follow the steps below to compile and run the assembler:

Create a Test File

Create your assembly source file:
tests/filename.asm 

Replace filename.asm with your desired test file name.

Open Terminal (Mac Users)
Open Terminal
Navigate to the project directory:
cd path/to/CSCI6461_Assembler 

 Compile the Java Files

Compile all Java source files:
javac *.java 

 Create the Executable JAR File

Package the compiled classes into a JAR file:
jar cfe Assembler.jar Assembler *.class 

Run the Assembler
Execute the assembler with your test file:
java -jar Assembler.jar tests/filename.asm 

Output Files

Once execution is complete, the assembler will automatically generate two output files in the same directory:

filename.load — Machine code output file

filename.lst — Listing file (includes source code and translated instructions)

If the terminal displays “test completed”, the assembly process finished successfully.

Verifying Output

Open the generated files:

filename.load

filename.lst

Review them to verify:

Correct instruction translation

Proper memory addresses

Expected machine code output

🛠 Requirements

Java JDK installed

Terminal access (Mac/Linux) or Command Prompt (Windows)

To verify Java installation:
java -version javac -version 

Notes

Ensure your .asm file is placed inside the tests folder.

Make sure there are no syntax errors in your assembly file.

Recompile if you make changes to the Java source code. 👍
