# Automator


## Feature

| Name                                        |     Status      |
|---------------------------------------------|-----------------|
|     Auto Create Post On Group               |        ON       | 
|---------------------------------------------|-----------------|

## Alert

For First installation you need to extract data.rar and put group list on list.json

## Group list

for getting group list 
1.go to https://developers.facebook.com/tools/explorer
2.make app
3.create access token 
4.go to https://graph.facebook.com/me/groups?access_token={Your ACCESS TOKEN}
5.copy all and pas to list.json

## Run Locally

Clone the project

```bash
  git clone https://github.com/IkuzaDev/Automator
```

Go to the project directory

```bash
  cd Automator
```

Install dependencies

```bash
  pip3 install -r requirements.txt
```

```

Start the bot

```bash
  python3 main.py
```

## Update from previous version

Pull the latest version

```bash
  git pull
```

Install new dependencies

``` bash
  pip3 install -r requirements.txt
```

Run the bot

```bash
  python3 main.py
```
