# Ngnix installing and curl Test
## Task
Installing nginx and verify it using `curl localhost`.

---

## Installation
```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
curl localhost
