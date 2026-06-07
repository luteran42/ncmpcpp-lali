CXX := g++
CXXFLAGS += -std=c++0x -Wall -Wextra -Wshadow
CPPFLAGS += $(shell taglib-config --cflags)
LDFLAGS += $(shell taglib-config --libs)

artist_to_albumartist: artist_to_albumartist.cpp
	$(CXX) artist_to_albumartist.cpp -o artist_to_albumartist $(CXXFLAGS) $(CPPFLAGS) $(LDFLAGS)

clean:
	rm -f artist_to_albumartist

.PHONY: clean
