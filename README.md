# tcp_client_server
Starter code example for tcp (socket) client-server system

#### Compilation instructions

```shell
csgcc utils.c tcp_server.c -o server
gcc -o client tcp_client.c utils.c
```

#### Here is a typical command line, run each in its own terminal

Open a terminal and run: 

```shell
./server
```

Open four terminals and in each one run: 

```shell
./client <external index> <initial temperature>
```

##### Example: 

```shell
./client 1 100
```

```shell
./client 2 200
```

```shell
./client 3 300
```

```shell
./client 4 400
```

![Screenshot_TCP_Running](https://user-images.githubusercontent.com/108601032/230708179-28d71f70-2114-4587-99f4-1d25088f549c.PNG)

