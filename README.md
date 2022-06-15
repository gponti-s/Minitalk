# Minitalk
The project consists of creating a communication program in the form of a client and a server. The server must be started first. After its launch, it has to print its PID. The client takes two parameters: the server PID and the string to send. The client must send the string passed as a parameter to the server. Once the string has been received, the server must print it. The server has to display the string pretty quickly (1 second to display 100 characters is way too much!).

# Allowed Functions
malloc
free
write
getpid
signal
sigemptyset & sigaddset
sigaction
pause
kill
sleep
usleep
exit
