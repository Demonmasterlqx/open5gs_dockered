# open5gs and ueransim 

5G end to end communication demo with open5gs and ueransim.


# Deployment NGC and 5g RAN

deploy the ngc core (open5gs) with:

```
docker compose -f 5gcore.yaml up -d
```

Register subscribers in ngc with `./register_subscriber.sh`.


# Deploy gnodeb

gnb1.yaml is configured to deploy 1 gnodeb (gnb1) and 1 ues:

```
docker compose -f ue1.yaml up -d
```

You can use gnb2.yaml to deploy a second gnodeb (gnb2) with 3 additional ues:

```
docker compose -f gnb2.yaml up -d
```


# Test

Follow [this](https://www.notion.so/open5gs-22c8fbd7ead480da932bc681bbd5811f)
