## Allen Woodall
## Software Engineering
## Homework 11

1.  Stepwise refinement is the idea that you should handle all of the important issues of a problem/project first. Work out the details as far down the process as possible.
2. The primary difference I see is that with top-down development you look at the system as a whole and then refine it down to subsystems and so forth while with object-oriented analysis and design you're starting from the bottom in a way. If not the bottom, near it as the objects are essentially the subsystems or components of them at least. With OOAD you're designing the system by modules and how they interact (specific to general) while with top-down you're taking a more general to specific approach.
3. I really enjoyed this piece. I've never walked through such an extensive refinement and I see great value in it as an approach to problem solving. Breaking down a problem like this would result in a much more efficient solution than a spontaneous solution and perhaps more importantly, it would provide a better understanding of the problem and all potential solutions. It's another great method of planning a solution and further reason to not hastily sit down and program. 
4. An example of due diligence would be a company interested in entering the local embroidery market which is currently controlled by several small embroidery shops. The company wants to take over the market by acquiring one of these businesses and injecting funds for expansion. They analyze each business determining which would be the most effective use of their funds for their goals and act accordingly.  
5. Objects A and B would need to be decoupled somehow. Perhaps through notifications. Object A could send a notification for Object B to enact a particular method on an instance matching whatever criteria necessary.
6.  Attached
7. 
//The format is (target : dependencies)
//followed by a console command
//This examples recompiles files as needed

//default
all: hello

//hello depends on main.o, factorial.o, hello.o
hello: main.o factorial.o hello.o
// compile each dependency if hello has been changed
    g++ main.o factorial.o hello.o -o hello

//main.o depends on main.cpp
main.o: main.cpp
// compile the dependency if needed
    g++ -c main.cpp

//factorial.o depends on factorial.cpp
factorial.o: factorial.cpp
// compile the dependency if needed
    g++ -c factorial.cpp

//hello.o depends on hello.cpp
hello.o: hello.cpp
// compile the dependency if needed
    g++ -c hello.cpp

//this is a clean file to remove the object files
clean:
    rm *o hello