# This Makefile assumes that you have GLFW libraries and headers installed on,
# which is commonly available through your distro's package manager.
# On Debian and Ubuntu, GLFW can be installed via `apt install libglfw3-dev`.

COMMON=-O2 -I../include -L../lib -std=c++11 -pthread -Wl,-rpath,'$$ORIGIN'/../lib

all:
#	$(CXX) $(COMMON) testxml.cc    -lmujoco             -o ../bin/testxml
#	$(CXX) $(COMMON) testspeed.cc  -lmujoco             -o ../bin/testspeed
#	$(CXX) $(COMMON) compile.cc    -lmujoco             -o ../bin/compile
#	$(CXX) $(COMMON) derivative.cc -lmujoco -fopenmp    -o ../bin/derivative
#	$(CXX) $(COMMON) basic.cc      -lmujoco -lGL -lglfw -o ../bin/basic
#	$(CXX) $(COMMON) record.cc     -lmujoco -lGL -lglfw -o ../bin/record
#	$(CC) -c -O2 -I../include uitools.c
	$(CXX) $(COMMON) uitools.c simulate.cc -lmujoco -lGL -lglfw -o ../bin/simulate
#	$(CXX) $(COMMON) uitools.c inverted_pendulum.cc      -lmujoco -lGL -lglfw -o ../bin/inverted_pendulum
#	$(CXX) $(COMMON) uitools.c flywheel_inverted_pendulum.cc      -lmujoco -lGL -lglfw -o ../bin/flywheel_inverted_pendulum
#	$(CXX) $(COMMON) uitools.c acrobot_2link.cc      -lmujoco -lGL -lglfw -o ../bin/acrobot_2link
#	rm *.o
