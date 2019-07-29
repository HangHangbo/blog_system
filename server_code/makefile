FLAG=-std=c++11 -L/usr/lib64/mysql -lmysqlclient -ljsoncpp -lpthread

.PHONY:all
all:blog_server

blog_server:blog_server.cc
	g++ blog_server.cc -o blog_server $(FLAG)

.PHONY:clean
clean:
	rm  blog_server