## What is it

You can use clonehub to clone other's all images(with all tags) in his repo to your own repo. Have fun ! 

## Usage

- require jq

example for ubuntu
```
apt install jq
```

- require docker

- need docker login first

```
docker login
>> username
>> password
```

- Set the UNAME && UPASS && UREPO && TARGET in run.sh

```
UNAME=""    # your docker hub username
UPASS=""    # your docker hub password
UREPO=""    # repo you want to clone
TARGET = "" # your own target repo
```

- Run it !!

```
chmod +x run.sh
./run.sh
```
