
# docker feature

 Play with network commands (ls/create/rm/inspect/…)
 • Play with options:
 •--driver <network-driver-name>
 •--subnet <subnet-CIDR-range>
 • Additional options for container command:
 •-p <host-port>:<container-port>
 •--network <network-name

![Screenshot 2024-10-25 160918](https://github.com/user-attachments/assets/5a564b8a-b453-43ad-b439-6e07ca411169)

![Screenshot 2024-10-25 160947](https://github.com/user-attachments/assets/7350bd1c-1850-4004-ad6a-e4c6a72803b1)


 Create a new volume
 • Mount the volume to a container named container_1 on /data/
 • Mount the volume to a container named container_2 on /data/
 • Create a file in /data/ inside each container with the container’s hostname
 • Mount the volume to a container named container_3 and run “ls /data/”, 
you should see two file

![Screenshot 2024-10-25 161431](https://github.com/user-attachments/assets/4cc77291-df04-457a-8786-04956fc733d7)

![Screenshot 2024-10-25 162440](https://github.com/user-attachments/assets/c13dd3f4-f647-4ec9-968f-372f1eb969c6)

![Screenshot 2024-10-25 162527](https://github.com/user-attachments/assets/1346b932-738c-4baa-bd76-919df78a8f31)
