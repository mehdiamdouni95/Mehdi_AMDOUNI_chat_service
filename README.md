"# Mehdi_AMDOUNI_chat_service" 

Description :
a simple directed/targeted chat service using JavaScript , HTML & CSS , Express and socket.io
How to install :
1. Clone the project
2. Open the directory with command line and tap : npm install , to install the needed packages
3. Tap : node index.js to run the project
4. Open the web browser and open this link : http://localhost:8080/


Answers to the questions :


Once the implementation is done, think about an answer to the following questions:

● Which share of web users will this implementation address? Should it be increased and
how?

Answer: the application addresses all the clients already known by the service(connected to the server) , it could be increased by the possibility to send a message to a client who's not connected.

● How many users can connect to one server?

Answer: many , however it depends on how much the server support.

● How can the system support more systems?

Answer: The system can support more systems by being distribued on multiple machines.

● How to reduce the attack surface of the systems?

Answer :
 To reduce the attack surface we can : Eliminate complexity , visualize the vulnerabilities , control the endpoints and segment the Network , all this methodes allow us to avoid many type of attacks such as : Sql Injection , XSS attack , Ddos , CSS injection  ..

● Should an authentication mechanism be put in place and if yes, how?

Answer : Yes an we must put an authentication mechanism , by associating an id to each user(login and password).
