# Sentia-
Migration from private to public cloud - PoC

1) Web Service plan with Web App for our application probably the best solution in term of cost and scalability, reverse proxy installed on it

https://tomssl.com/create-your-own-free-reverse-proxy-with-azure-web-apps/
Azure App Service and Virtual Network Integration Options very cool video from JohnSavill
https://www.youtube.com/watch?v=5P14Q--Q9vE&ab_channel=JohnSavill

2) Storage Account with Blob Container 
3) Azure Cosmos with MongoDB - per tutorial which I have mentioned
4) Private Network in Azure and VM with bigger CPU with Elastic Search and Kibana on it.
5) Connection from VM to App to pull logs with some kind of script
6) VPN connection from each HQ to the private network in Azure 
7) I have found also an Azure front door that can be integrated and is security-wise maybe good addition but I have removed that option because of the cost.

This is my infrastructure PoC Diagram:

---------------------------


I spin up the infrastructure without connecting components and download the ARM template. 

----------------------------

I didn't put any time logs since it doesn't make sense, I was searching for a solution from Sunday till Friday for probably a couple of hours per day, searching, googling and watching youtube clips.

----------------------------![Infrastructure PoC for cloud migration](https://user-images.githubusercontent.com/50260662/114933413-ead33700-9e38-11eb-837f-aed7eb8d676c.jpg)



