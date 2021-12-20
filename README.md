# Recomendador de viajes

![alt text](https://raw.githubusercontent.com/OscarZambranoLa/InnovaccionVirtual/main/Img/Pink%20Gradient%20Blog%20Banner%20.png)

Encontrar un destino para vacacionar que se adapte a nuestro estilo de vida, presupuesto y gustos personales.​


## ¿Cómo usamos Azure?

![alt text](https://raw.githubusercontent.com/OscarZambranoLa/InnovaccionVirtual/main/Img/Usuario%20(1080%20x%20700%20px)%20(1080%20x%20500%20px)%20(1).png)


## Tecnologías a utlizar
- Azure Bot Service​
- Azure SQL Database​
- Azure App Service​
- Azure DDOS Protection



## Comandos a usar en Azure

```sql
CREATE DATABASE estados

CREATE TABLE cancun (id INT PRIMARY KEY IDENTITY (1,1), lugar VARCHAR(100), tipo(40))

INSERT INTO cancun (lugar, tipo) VALUES ('Cenote dos ojos', 'playa')

ALTER TABLE cancun ADD imagenBlobId VARCHAR(120)


```
## TCO


| Service type                   | Custom name | Region           | Description                                                                                                                                                                                                                                                                                                                                                                 | Estimated monthly cost             | Estimated upfront cost |
|--------------------------------|-------------|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------|------------------------|
| Storage Accounts               |             | South Central US | Block Blob Storage, General Purpose V2, LRS Redundancy, Hot Access Tier, 20 GB Capacity - Pay as you go, 1 x 10,000 Write operations, 1 x 10,000 List and Create Container Operations, 10 x 10,000 Read operations, 100,000 Archive High Priority Read, 1 x 10,000 Other operations. 1,000 GB Data Retrieval, 1,000 GB Archive High Priority Retrieval, 1,000 GB Data Write | $0.51                              | $0.00                  |
| Storage Accounts               |             | Central US       | Block Blob Storage, General Purpose V2, LRS Redundancy, Cool Access Tier, 2 GB Capacity - Pay as you go, 1 x 10,000 Write operations, 1 x 10,000 List and Create Container Operations, 0 x 10,000 Read operations, 100,000 Archive High Priority Read, 1 x 10,000 Other operations. 1 GB Data Retrieval, 1,000 GB Archive High Priority Retrieval, 2 GB Data Write          | $0.18                              | $0.00                  |
| App Service                    |             | South Central US | Basic Tier; 1 B1 (1 Core(s), 1.75 GB RAM, 10 GB Storage) x 730 Hours; Windows OS                                                                                                                                                                                                                                                                                            | $54.75                             | $0.00                  |
| Azure SQL Database             |             | East US          | Single Database, vCore, RA-GRS Backup Storage, General Purpose, Provisioned, Standard-series (Gen 5), Local Redundancy, 1 - 8 vCore instance(s) x 730 Hours, 32 GB Storage, 0 GB Backup Storage                                                                                                                                                                             | $1,476.43                          | $0.00                  |
| Azure DDoS Protection          |             |                  | Protection for 100 resources                                                                                                                                                                                                                                                                                                                                                | $2,943.55                          | $0.00                  |
| Azure Bot Services             |             | West US          | S1 tier, 0 messages in Premium Channels                                                                                                                                                                                                                                                                                                                                     | $0.00                              | $0.00                  |
| Azure Kubernetes Service (AKS) |             | West US          | 1 D2 v3 (2 vCPUs, 8 GB RAM) x 730 Hours (Pay as you go), Linux; 0 managed OS disks – S4, 0 clusters                                                                                                                                                                                                                                                                         | $85.41                             | $0.00                  |
| Support                        |             |                  | Support                                                                                                                                                                                                                                                                                                                                                                     | $0.00                              | $0.00                  |
|                                |             |                  | Licensing Program                                                                                                                                                                                                                                                                                                                                                           | Microsoft Customer Agreement (MCA) |                        |
|                                |             |                  | Billing Account                                                                                                                                                                                                                                                                                                                                                             |                                    |                        |
|                                |             |                  | Billing Profile                                                                                                                                                                                                                                                                                                                                                             |                                    |                        |
|                                |             |                  | Total                                                                                                                                                                                                                                                                                                                                                                       | $4,560.83                          | $0.00                  |


|Categoría|Costo
|---|----|
|Compute|USD 4,162.80|
|Data Center|USD 0.00|
|Networking|USD 0.12|
|Storage|USD 28,438.48|
|IT Labor|USD 0.00|
|**Total**|**USD 32,601.00***|

## Nivel de acuerdo de sevicio

| Servicio                 | SLA     |
|--------------------------|---------|
| Azure Bot Service        | 99,90%  |
| Azure DDoS Protection    | 99,99%  |
| Azure Kubernetes Service | 99,95%  |
| App Service              | 99,95%  |
| Azure SQL Database       | 99,995% |
| Azure Blob Storage       | 99,90%  |
| Total                    | 99,685% |

### Créditos
Construido con esfuerzo en un fin de semana por:

Atziry Denisse González              
César Augusto Flores                   
Jorge Pérez Sánchez                    
Oscar Zambrano                           
Osiel Alejandro Rubio                  

​

## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
