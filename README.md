## Systèmes Distribués avec GRPC 

### Objective:
We want to create a client-server application based  on GRPC which exposes a service which makes it possible to consultbank accounts.

#### 1 Test the Unary Model using BloomRPC:
![image](https://user-images.githubusercontent.com/78732216/235297645-5e95d16c-8f13-43c2-9063-a739000906b3.png)
#### Test With client using blockingStub (mode synchrone):
![image](https://user-images.githubusercontent.com/78732216/235299617-ccd1184d-b291-4042-81f1-6abed8b9087d.png)

#### 2 Test the Streaming Model using BloomRPC(count to 21):
![image](https://user-images.githubusercontent.com/78732216/235353370-1bbcb206-47c2-4fd8-b4ab-978808d15a73.png)
#### every second the client number 3 got an item (Server Streaming) :
![image](https://user-images.githubusercontent.com/78732216/235355666-c91e2164-a2b6-4667-ab7c-017fe70fe1da.png)




