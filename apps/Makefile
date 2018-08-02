FLAGS := -I/home/zilong/WorkSpace/disk0/dbus/libs/include/dbus-1.0/ \
         -I/home/zilong/WorkSpace/disk0/dbus/libs/lib/dbus-1.0/include \
         -L/home/zilong/WorkSpace/disk0/dbus/libs/lib 
all: server client
	@:

server:
	gcc $(FLAGS) -o server dbus-server.c -ldbus-1

client:
	gcc $(FLAGS) -o client dbus-client.c -ldbus-1
