# MalBucket

MalBucket is a website developed in Django which let you manage your Malware Samples with interesting features.


## Not just management

With MalBucket you can:

- Upload Samples
- Create html/pdf report with informations from various sandbox
- Search a sample by:
  - Sha256
  - ImpHash
  - Tag
- Hunt the samples with YARA Rules (Retro Hunting)
- Export the data tables from the searchs in various formats
- Live Hunting
  -- Manage you YARA Rules
  -- Receive the results in real time in your email
- Search with queries and visualize the results in a network graph
- Charts
- Login / Register

## Screenshots

### Home
![image](https://user-images.githubusercontent.com/52568048/130370400-bf2af1fa-ff9f-43b6-be8a-9c771b012630.png)

### Dashboard
![image](https://user-images.githubusercontent.com/52568048/130370429-a14fc282-3176-4652-b46e-774d52e11764.png)

### Search
![image](https://user-images.githubusercontent.com/52568048/130371647-794cbf72-e556-487d-b0bb-968042bff5a8.png)

![image](https://user-images.githubusercontent.com/52568048/130371669-b7de2b2d-1e05-490b-bfaf-59ee95ee0fb5.png)

#### Queries
![image](https://user-images.githubusercontent.com/52568048/130372270-28a0d50b-e28f-4648-bbeb-c3a64632c7bd.png)


#### Network Graph
![image](https://user-images.githubusercontent.com/52568048/130371708-48e05783-5628-4b34-8085-094a0edd9dc3.png)

### Samples
![image](https://user-images.githubusercontent.com/52568048/130371725-de90adae-4c99-4e2f-b758-b5957d087445.png)

![image](https://user-images.githubusercontent.com/52568048/130371734-467b332a-8ead-4d3a-bf99-1e729fbc55d2.png)

### Settings
![image](https://user-images.githubusercontent.com/52568048/130371955-4165e3d7-cee1-4fb4-9726-0d1c1b5d3caa.png)

![image](https://user-images.githubusercontent.com/52568048/130371970-3a7b7a64-a9e1-4576-84d9-d2724cc11d39.png)


## Supported Sandbox Services

- MalwareBazaar
- HatchingTriage
- OtxAlienVault
- HybridAnalysis
- MalShare
- CAPE (To avoid abuse, the api requests must be sent to a local hosted CAPE, not to the online verion, if you want to host CAPE, please see this [guide](https://github.com/Finch4/Malware-Analysis-Reports/blob/master/CAPEv2Setup.MD), you can obviously just change the url and send these requests to the online version, but I don't recommend that)
- VirusTotal (free API Key)

## To do

- [ ] Add more sandbox services
- [ ] Add more charts
- [ ] Add more search queries

## Important Notes

The project will be uploaded when all the features (without the to-do) will be functional.

