# OSWT-ATTACK

The tls.go, handshake_client.go, clientconn.go are responsible for launching DoS attacks with TLS handshakes.

The tls.go should replace the file fabric\vendor\google.golang.org\grpc\credentials\tls.go. 

The clientconn.go should replace the file fabric\vendor\google.golang.org\grpc\clientconn.go. 

The handshake_client.go should replace the file golang\src\crypto\tls\handshake_client.go. 

Re-compile the peer(client, DoS node). And then, the peer calls any command that requires a connection to another node to launch a DoS attack on that node.