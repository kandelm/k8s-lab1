# k8s-lab1

1- How many pods exist on the system?
![alt text](image.png)

2- How many Nodes exist on the system?
![alt text](image-1.png)

3- Create a new pod with the nginx image.
    Image name: nginx
![alt text](image-2.png)

4- Which nodes are these pods placed on?
the pods are placed in node01
![alt text](image-3.png)

5- Create pod from the below yaml using kubectl apply command
![alt text](image-4.png)

6- How many containers are part of the pod webapp?
only 2 containers >> nginx and agentx
![alt text](image-5.png)

7- What images are used in the new webapp pod?
nginx and agentx
![alt text](image-5.png)

8- What is the state of the container agentx in the pod webapp
![alt text](image-6.png)

9- Why do you think the container agentx in pod webapp is in error?
The container agentx in pod webapp is in error because the image agentx is not found 
![alt text](image-7.png)

10- Delete the webapp Pod.
![alt text](image-8.png)

11- Create a new pod with the name redis and with the image redis123.
•	Name: redis
•	Image Name: redis123
![alt text](image-9.png)

12- Now change the image on this pod to redis.
Once done, the pod should be in a running state.
![alt text](image-10.png)

13- Create a pod called my-pod of image nginx:alpine
![alt text](image-11.png)

14- Delete the pod called my-pod
![alt text](image-12.png)




