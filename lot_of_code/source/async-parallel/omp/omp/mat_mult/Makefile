# ZZZ: how add other kay for g++
#

SRCS = main.cpp matrixFirst.cpp
OBJS = main.o matrixFirst.o
CC = c++
# obj. files

all: main
# -lrt - ����� ��� ���������� � ���������
# -openmt - ���������������
main: $(OBJS) 
	$(CC)  -o main  $(OBJS)
$(OBJS): $(SRCS)
	$(CC)  -c $(SRCS)

# add
clean:
	rm -f $(OBJS) main.exe
run: 
	main.exe
