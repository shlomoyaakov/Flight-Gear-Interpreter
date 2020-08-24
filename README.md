# ex3
  Interpreter for flight gear simulator in C++.
  The program interprets the fly.txt and fly_with_func.txt, that contain a sequence of an autopilot commands,
  to a flight gear simulator code that makes the airplane fly.
  In order to change the autopilot commands, you can edit the fly.txt and the fly_with_func.txt files
  according to the "generic_small.xml" file.
  You can compile this program with the command -
  "g++ -std=c++11 *.cpp -Wall -Wextra -Wshadow -Wnon-virtual-dtor -pedantic -o a.out -pthread"
  and run it with the command "./a.out file_name" when file_name is the name of the text file you
  want to interpret, for example fly_with_func.txt.
  Make sutre to reside the text files along side the main.cpp file (and all the others)
  and you should also reside the "generic_small.xml" file in the protocol folder under data of 
  the simulator code (wherever you downloaded it to).
  please make sure that you open the program before enter the simulator to enable right connection flow.
  enjoy!
