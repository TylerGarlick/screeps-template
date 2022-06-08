# Screeps Template

## Getting Started

```bash
docker pull yz89122/screeps

```


### Run
```bash
docker run -it --rm -v "$PWD/screeps-data:/app" screeps npx screeps init
```


### Start
```bash
docker run -d -v "$PWD/screeps-data:/app" -p "21025:21025" screeps
```



// "screeps:init": "docker run -it --rm -v `$PWD/screeps-data:/app` screeps npx screeps init",
    // "screeps:start": "npx screeps start --logdir ./logs --port 21025 --steam_api_key 8D9C6AFD0CFB8803DA9AABBB519CCC65"
