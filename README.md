# First-Makefile
Ian Martin Ajzenszmidt first attempt at a simple Makefile for linux.
ian@ian-Latitude-E7440:~$ make
gcc hello.c -o hello
ian@ian-Latitude-E7440:~$ ./hello

Ian Ajzenszmidt's first Makefile testian@ian-Latitude-E7440:~$ make
gcc hello.c -o hello
ian@ian-Latitude-E7440:~$ ./hello
Ian Ajzenszmidt's first Makefile test
ian@ian-Latitude-E7440:~$ cat Makefile
firstmake: hello.c
	gcc hello.c -o hello
ian@ian-Latitude-E7440:~$ cat hello.c
    #include <stdio.h>
    int main(){
	    printf("%s\n","Ian Ajzenszmidt's first Makefile test");
			    }
ian@ian-Latitude-E7440:~$ 
