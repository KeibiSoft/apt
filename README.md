# KeibiDrop APT Repository

Install KeibiDrop on Debian/Ubuntu:

```bash
curl -fsSL https://keibisoft.github.io/apt/gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/keibidrop.gpg
echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/keibidrop.gpg] https://keibisoft.github.io/apt stable main" | sudo tee /etc/apt/sources.list.d/keibidrop.list
sudo apt update
sudo apt install keibidrop
```
