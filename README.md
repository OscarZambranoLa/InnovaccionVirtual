# Recomendador de viajes

Encontrar un destino para vacacionar que se adapte a nuestro estilo de vida, presupuesto y gustos personales.​


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



## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
