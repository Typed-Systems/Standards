# Git setup

### Generate SSH key
- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

#### Ed algo
```
ssh-keygen -t ed25519 -C "<your_email@example.com>"
```

#### RSA algo
```
ssh-keygen -t rsa -b 4096 -C "<your_email@example.com>"
```