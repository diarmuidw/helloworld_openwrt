hello:hello.o
	$(CXX) $(LDFLAGS) hello.o -o hello
hello.o:hello.cpp
	$(CXX) $(CXXFLAGS) -c hello.cpp


# remove object files and executable when user executes "make clean"
clean:
	rm *.o hello



