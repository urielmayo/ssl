**This is a simple hello world program**

To run this code execute the following comand:
```
gcc -std=c2x helloworld.c -o bin -Wall
./bin # this will print "Hello World!" in your terminal
```

If you want to execute this code and send the output to a .txt file run:
```./bin > output.txt```

To clen the unused files once done:
```./bin > rm -f -r bin *.txt```