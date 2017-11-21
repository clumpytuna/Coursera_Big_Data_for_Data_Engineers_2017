# Unix command line interface

There are some useful command group by theme


### Processes
1. Displays the total amount of free and used memory
```
free [options]
```
2. Provides a dynamic real-time view of a running system
```
top [options]
```
3. Send a signal to a process
```
kill [-s][-l]%pid
```
4. Runs a command with a modified scheduling priority
```
nice [OPTION][COMMAND[ARG]...]
```

5. Gets snapshot of the status of currently running processes
```
top [options]
```

### Web
1. Tool to transfer data from or to a server.
```
curl <address> -o <filename>
```
- -o  Flag saves output to a file "filename"
- -i, --include  Flags include the HTTP response headers in the output
- -L, --location  If the server reports that the requested page has moved to a different location (indicated with a Location: header and a 3XX response code), this option will make curl redo the request on the new place.
