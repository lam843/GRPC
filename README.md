## Systèmes Distribués avec GRPC 

### Objective:

+ First part : We want to create a client-server application based  on GRPC which exposes a service which makes it possible to consultbank accounts.
+ Second part : Create a GRPC chat server:

        1. Test the Chat server with a GRPC client like BloomRPC 
        2. Create Java GRPC Client 
        3. Create a Python GRPC Client 
                 
+ Third part : Create a GRPC GAME server :
At startup the server chooses a random number between 1 and 1000 Then the GRPC clients must guess the secret number in competition and the server responds each time with the following eventualities:

        1. Your number is greater
        2. Your number is smaller
        3. BRAVO you won and send the winner to customers
        4. Game over, the winner is ""Winner's number" 
        
        
===========================================================================================================================================================================

<details>
<summary>  First part:</summary>
                               
#### 1 ---> Test the Unary Model using BloomRPC:
![image](https://user-images.githubusercontent.com/78732216/235297645-5e95d16c-8f13-43c2-9063-a739000906b3.png)

#### ---> Test With client using blockingStub (mode synchrone):
![image](https://user-images.githubusercontent.com/78732216/235299617-ccd1184d-b291-4042-81f1-6abed8b9087d.png)

#### 2 ---> Test the Streaming Model using BloomRPC(count to 21):
![image](https://user-images.githubusercontent.com/78732216/235353370-1bbcb206-47c2-4fd8-b4ab-978808d15a73.png)

####   --->The client number 3 got an item every second (Server Streaming) :
![image](https://user-images.githubusercontent.com/78732216/235355666-c91e2164-a2b6-4667-ab7c-017fe70fe1da.png)

#### 3 ---> Streaming request from client and got response based on streamed requests (perform stream):
![image](https://user-images.githubusercontent.com/78732216/235357065-fe96331b-bfcb-406d-8a1d-a8481b16f540.png)

#### ---> Perform stream:
![image](https://user-images.githubusercontent.com/78732216/235367893-389ae7a0-b084-47c7-8f62-c4ac7606c9ec.png)
#### 4 ---> Bi-Directional (fullcurrencystream) send un recive a stream:
![image](https://user-images.githubusercontent.com/78732216/235368361-b16494db-108b-4a80-9cc9-7e80a983bbe8.png)
</details>
=======================================================================
<details>
           <summary>  Second part: </summary> 
typing user name BloomRPC:        
![image](https://user-images.githubusercontent.com/78732216/235484412-57a0fcab-97df-43e9-a4e1-fd3c54d47bce.png)
display who is on chat :
![image](https://user-images.githubusercontent.com/78732216/235484553-7d8fbf1b-de99-41ad-8233-b24eea5cb194.png)
sending message :
![image](https://user-images.githubusercontent.com/78732216/235484774-e50b4ed2-bd90-420a-86c1-d662587a85b7.png)

          
</details>

=======================================================================
<details>
           <summary>  Third part: </summary> 
</details>



