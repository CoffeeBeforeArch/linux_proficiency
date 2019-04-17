# Create a simple Makefile for a program consisting of multiple files
# By: Nick from CoffeeBeforeArch

.PHONY : all
all: implementation.o simple_class

implementation.o : implementation.cpp
	g++ -c implementation.cpp

simple_class : simple_class.cpp implementation.o
	g++ -o simple_class simple_class.cpp implementation.o

.PHONY : clean
clean : 
	rm *.o
	rm simple_class
