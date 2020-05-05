TARGET := hello

all:$(TARGET)

OBJS = \
	main.o

$(TARGET):$(OBJS)
	$(CXX) -O3 -o $@ $^ $(LDFLAGS)

%.o:%.cpp
	$(CXX) -c -O3 -o $@ $^ $ $(LDFLAGS)

%.o:%.c
	$(CXX) -c -O3 -o $@ $^ $ $(LDFLAGS)

clean:
	@rm -rf *.o $(TARGET)
