# BlueMesh apt repository

```bash
echo 'deb [trusted=yes] https://raw.githubusercontent.com/salimkt/parser-apt/main ./' | sudo tee /etc/apt/sources.list.d/bluemesh.list
sudo apt update
sudo apt install bluemesh-parser
```

Flat, unsigned repository (`trusted=yes`) — see scripts/publish_apt.sh for why.
Older versions are retained so a pinned install keeps working.
