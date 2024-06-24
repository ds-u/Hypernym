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
### Performed on Linux Ubuntu 22.04 using WSL. Server is made using FastAPI and run using uvicorn. Finally, the HTTP requests of fastAPI are deployed on AWS EC2

1) Navigate to 'task_03' directory.
2) Run the flaskapi HTTP server using 'uvicorn main:app'
3) In order to test the POST command, open the link and after it add '/docs'. The results are also shown below.
4) To implement this on AWS EC2, a new instance was launched, and then a .pem key was generated.
5) Next, the .pem key was made private and NGINX was used, in order to connect with the fastapi server.
6) Lastly, the ip of the EC2 instance was opened.
7) Changing 'https' to 'http' and adding '/docs' to the end of the link allowed access to the server using the ip. These results are also shown below.

#### Server running locally
![image](https://github.com/ds-u/Hypernym/assets/97378198/a6bda555-d24c-4bbf-ab19-3e690b01be67)

![WhatsApp Image 2024-06-23 at 23 45 39](https://github.com/ds-u/Hypernym/assets/97378198/40505b36-ce78-47c5-a16e-65597ecd4d4d)

![WhatsApp Image 2024-06-23 at 23 46 13](https://github.com/ds-u/Hypernym/assets/97378198/49f5f1ec-957f-43e6-8beb-e3016706d493)

![WhatsApp Image 2024-06-23 at 23 46 59](https://github.com/ds-u/Hypernym/assets/97378198/0bd4e722-b83e-4355-a8c6-a0e2d74fe3d2)

#### Running server on AWS EC2

![WhatsApp Image 2024-06-24 at 15 37 36](https://github.com/ds-u/Hypernym/assets/97378198/59aacef2-2b6a-4c4d-80f8-69ce8dd8c2f8)

![WhatsApp Image 2024-06-24 at 15 39 17](https://github.com/ds-u/Hypernym/assets/97378198/8b6eb4e1-a040-41c2-8b97-8ce147f229e8)


o Create a Python script to send HTTP POST requests to a cloud server
(e.g., using Flask or FastAPI).
o The server should receive and store JSON data sent from an IoT device.
