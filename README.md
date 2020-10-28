# CloudMe-GolangExploit
CloudMe 1.11.2 - Buffer Overflow - Golang

CloudMe 1.11.2 - Buffer Overflow (PoC) translated to Golang due the service is scoping at 127.0.0.1, it cannot be accesible from outside and the machine doesnt have Python installed, so to avoid local port forwarding / tunnerling and that type of things I translated it to Golang so I can build a .exe and execute it from the machine.
To build a .exe execute on CMD: "go build poc.go"
Tested on Windows 10 64bits.
