
### How to use this apt

```bash
sudo curl https://raw.githubusercontent.com/lazywalker/apt/refs/heads/master/debian/key.asc -o /etc/apt/trusted.gpg.d/lazywalker.asc
echo "deb https://raw.githubusercontent.com/lazywalker/apt/refs/heads/master/debian/ stable main" | sudo tee /etc/apt/sources.list.d/lazywalker.list
```

for raspberrypi OS(trixie arm64):
```bash
sudo curl https://raw.githubusercontent.com/lazywalker/apt/refs/heads/master/debian/key.asc -o /etc/apt/trusted.gpg.d/lazywalker.asc
echo "deb [arch=arm64] https://raw.githubusercontent.com/lazywalker/apt/refs/heads/master/debian/ stable main" | sudo tee /etc/apt/sources.list.d/lazywalker.list
```
