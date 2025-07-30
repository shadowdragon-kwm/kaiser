
# Kaisar Provider CLI

Kaisar Provider CLI Linux Installation Tutorial

```
curl -O https://raw.githubusercontent.com/Kaisar-Network/kaisar-releases/main/kaisar-provider-setup.sh
```


```
chmod +x kaisar-provider-setup.sh
```

```
sudo ./kaisar-provider-setup.sh
```

Check Installation using this following command

```
kaisar
```

```
kaisar start          # Start the Provider App
kaisar create-wallet -e <your email> # Create Wallet
kaisar import-wallet -e <your email> -k <your private key> # Import your existed wallet
kaisar status         # Check node status
kaisar log            # Check details log of Provider App
```
