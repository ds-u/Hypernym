# HyperNym Tasks

## 1. MQTT Communication 
### Performed on Linux Ubuntu 22.04 using WSL.

1) Navigate to the directory with the name 'task_01'
2) Open a terminal and run the publisher.py script using 'python3 publisher.py'. This script publishes data.
3) Open a separate terminal and run the subscriber.py script. This script subscribes and then prints the recieved data.

#### Publisher output:
![publisher_output](https://github.com/ds-u/Hypernym/assets/97378198/4daf8853-7523-413b-a027-7f8b527373e5)

#### Subscriber output:
![subscriber_output](https://github.com/ds-u/Hypernym/assets/97378198/c88b3960-9054-42ee-a4d1-3c0f6ee885e7)



## 2. TCP Communication
### Performed on Linux Ubuntu 22.04 using WSL.

1) Navigate to the directory with the name 'task_02'
2) Open a terminal and first run server.py script using 'python3 server.py'. This will make the tcp server online, awaiting for any connections to be made.
3) In a separate terminal, run the client.py file using 'python3 client.py'. The client will send data to the server and the server will display the output.
#### Server online:
![image](https://github.com/ds-u/Hypernym/assets/97378198/a61ed2fc-468b-4217-b718-ff9e09e71efe)

#### Server recieving data from Client:
![image](https://github.com/ds-u/Hypernym/assets/97378198/dcfb474f-2ed9-4d05-bb98-181ff53ec3ce)



## 3. HTTP Communication
### Performed on Linux Ubuntu 22.04 using WSL.

1) 

o Create a Python script to send HTTP POST requests to a cloud server
(e.g., using Flask or FastAPI).
o The server should receive and store JSON data sent from an IoT device.
