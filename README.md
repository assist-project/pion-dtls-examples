# pion-dtls-examples
Go PionDTLS example programs used to test DTLS client/server implementations. 
Currently, the only example included is a harness which can be configured to operate as a DTLS client or server.
In either case, the harness completes a handshake, echoes exactly one application message before terminating.

# Setting up

Install go version 1.13 or later which comes with support for modules, necessary to run PionDTLS.

Deploy the desired version of PionDTLS. The harness should be compatible with v2.0.2. 

> go get github.com/pion/dtls/v2@v2.0.2

Run the harness (to get the usage page).

> go run main/main.go

Alternatively, once PionDTLS is set up, you can compile and run the resulting binaries:

> go build -o piondtls-2.0.2 main/main.go 

> ./piondtls-2.0.2

