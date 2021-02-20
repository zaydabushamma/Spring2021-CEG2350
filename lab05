Name: Zayd Abushamma
Email: abushamma.5@wright.edu
Part 1: Write Source Code (2 pts)
import java.util.Scanner;
class echo
{
    public static void main(String args[])
    {
        Scanner in = new Scanner(System.in);
        String s = in.nextLine();
        System.out.println(s);
    }
}
Part 2: Compile Source Code (4 pts)
1. which gcc
   /usr/bin/gcc
2. which java
   /usr/bin/java
3. /usr/bin/javac echo.java
4. /usr/bin/java echo
Part 3: Make that Makefile (3 pts)
3 Make file
compile_source:
        if [ -s echo.java ]; then \
                echo "compilling.."; \
                /usr/bin/javac echo.java; \
        fi
run:
        if [ -s echo.class ]; then \
                echo "running.."; \
                /usr/bin/java echo; \
        fi
clean:   
        if [ -s echo.class ]; then \
                echo "cleaning"; \
                rm echo.class; \
        fi
4. Part 4
   	Instruction Manual.
	1. To compile and run the echo.java file manually
        - /usr/bin/javac echo.java run this command from the directory containing the file
        - /usr/bin/java echo run this command from the same directory to run the complied program
	2. To compile and run the echo.java file with make command
        - run make command from the directory containing to compile the file
        - run make run to run the compiled file
        - run make clean to delete the compiled file
	
	Commands
	git add --all
	git commit -m "Lab05"
	git push origin master
Extra Credit (2 pt):
compile_source:
        if [ -s echo.java ]; then \
                echo "compilling.."; \
                /usr/bin/javac *.java; \
        fi
run:
        if [ -s echo.class ]; then \
                echo "running.."; \
                /usr/bin/java echo; \
        fi
clean:
        if [ -s echo.class ]; then \
                echo "cleaning"; \
                rm *.class; \
        fi


