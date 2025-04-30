# Como instalar o Kali Linux no Subsistema Windows para Linux(WSL)

### Etapa 1: Instale o WSL

```
wsl –install
```
### Etapa 2: Lista de Sistemas
veja se está online o linux que você pretende instalar

```
wsl --list --online
```

### Etapa 3: instalar o Sistema
irei baixar o ubuntu mais baixe o sistema que queira

```
wsl –install -d kali-linux
```

### Etapa 4: Atualizar o kali linux
```
sudo apt update -y && apt full-upgrade -y
```

### Etapa 5: Instalar kali full
Quando você instalar o kali linux pelo WSL ele vem com uma versão limitada, use esse comando para instalar o kali full
```
sudo apt install -y kali-linux-large
```

Script em Breve...

### Etapa 6: Instalar o Kex

```
sudo apt install kali-win-kex -y
```

### Etapa 7:Iniciar o Kali Linux com Interface Grafica

```
kex –win -s
```

