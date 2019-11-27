# Create a simple Makefile for a program consisting of multiple files
# By: Nick from CoffeeBeforeArch

.PHONY : all
all : implementation simple_class

simple_class : simple_class.cpp implementation.o
	g++ -o simple_class simple_class.cpp implementation.o

implementation : implementation.cpp
	g++ -c implementation.cpp

.PHONY : clean
clean : 
	rm -rf *.o
	rm -rf simple_class
