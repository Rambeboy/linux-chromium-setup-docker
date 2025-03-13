# CHROMIUM ON YOUR VPS USING DOCKER

That `setup.sh` file is for installing Chromium with UI on your VPS.
Run it with
```
[ -f setup.sh ] && rm setup.sh; wget https://raw.githubusercontent.com/Rambeboy/linux-chromium-setup-docker/refs/heads/main/setup.sh && sudo chmod +x setup.sh && ./setup.sh
```

After running that command, check if the container running using
```
docker ps
```
if you don't see chromium container running, try
```
cd ~/chromium
docker compose up -d
```

---
