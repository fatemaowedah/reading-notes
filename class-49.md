### Message Queues
#### Rooms and Namespaces
Socket.IO allow you to namespace your sockets which mean assigning different endpoints or paths, it is minimize the number of TCP connections and seperate concerns within application,by sepaeation comumunication channels, the default namespace `/` it connected to by default, ypu can use custom namespace you can call the of function on the server-side, you can also define channels that sockets can join and leave by using `socket.join` or socket.leave `socket.leave` and disconnect the channels, the default room we define it by random unique identifier, you can sending message from outside world you need to use emit events you can use `socket.io-redis`, `socket.io-emitter`.
#### Message Queues
queue server runs independnt and it tasked with routing events and messaging between clients, any client can publish a message to server, any client subscribe to receive messages by type, queue have ability to se which client are connected which event are subscribed, the message is package of information, it categorized by queue general bucket does the message belong, and event what is event has happend, payload it is data associated with the event.
#### Real Time vs Queued Messaging
real time when the message come to server the server broadcast out to subscibers, when any subscriber lose the connection with the server in this time the massage will be missed by the client, BUT Queue it track the delivery status of message this mean if the subscribers not recived the message it will be in queue until can be deliverd to subscribers.
#### Use Case
An API server responds to a POST request
User’s access rights are confirmed,The data is analyzed and normalized,The data is sent to the database for saving,The database “publishes” a message into the queue, Queue: DB,Event: CREATE,Payload: JSON Object containing the created record
The API server sends information back to it’s client as normal.

