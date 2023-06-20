# Titre

## Création d'un workspace sur gitpod

1- Connectez vous avec votre comptre gitpod. Vous aurez l'interface suivante:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/85698b90-9bdf-4724-ac19-bec9e797d04a)

2- Créez un workspace en choisissant un repository github dans lequel vous allez travailler et choisissez une machine `Large`:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/7e396e45-0283-4aac-99db-85d87b14eebb)

3- Vous aurez l'interface suivante sur laquelle vous allez travailler: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/edaa34a5-01f8-4222-847e-18add577f3c3)


## Installation DataHub

1- Dans votre terminal, tapez les commandes suivantes pour installer `Docker Compose v2`: 

```
sudo rm /usr/local/bin/docker-compose

sudo curl -L "https://github.com/docker/compose/releases/download/v2.0.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

docker-compose --version
```
![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/cb4c7100-6fba-458a-8a4a-c3d4e7514821)

2- Tapez les commandes suivantes pour installer `Datahub`

```
python3 -m pip install --upgrade pip wheel setuptools

python3 -m pip install --upgrade acryl-datahub

```

3- Vérifiez que Datahub est bien installé avec les commandes suivantes: 
```
which datahub

datahub version
```

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/97ea1b9d-a300-4b71-ac7f-896b881d49aa)

4- Pour déployer une instance DataHub, exécutez la commande CLI suivante depuis votre terminal.

```
datahub docker quickstart
```

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/04d9cc32-ba7e-4ef4-b01a-881ff075c9c1)

5- Pour ingérer les métadonnées d'exemple, exécutez la commande suivante depuis votre terminal.

```
datahub docker ingest-sample-data
```


![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/1ec06131-104c-448c-bf38-0fc7857890ba)





