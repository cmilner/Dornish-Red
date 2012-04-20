all:	run

run:	build
	./dornish 12345 Ned:

build:
	g++ -pthread -o dornish main.cpp RSA.cpp RsaHacker.cpp  Server.cpp

clean:
	rm dornish