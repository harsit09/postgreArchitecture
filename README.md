# postgreArchitecture
Creating a listener on the backend application that accepts connections is simple. You listen on an address-port pair, connection attempts to that address and port will get added to an accept queue; The application accepts connections from the queue and start reading the data stream sent on the connection.
