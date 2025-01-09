CXX = g++
CXXFLAGS = -Wall

BUILD_DIR := build-out

default all $(BUILD_DIR)/lib/hello.a: hello.cpp hello.h
	rm -rf $(BUILD_DIR)/lib
	mkdir -p $(BUILD_DIR)/lib
	$(CXX) $(CXXFLAGS) -o $(BUILD_DIR)/lib/hello.o -c hello.cpp
	ar rcs $(BUILD_DIR)/lib/hello.a $(BUILD_DIR)/lib/hello.o


