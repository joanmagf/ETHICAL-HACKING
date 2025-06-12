# 📦 Tutorial d'Instal·lació de Docker i Verificació en Linux (Ubuntu / Debian)

Aquest document descriu el procés d'instal·lació de Docker en el sistema operatiu: **Linux**, així com una **prova ràpida** per verificar que Docker funciona correctament.

---

### 1. Preparar el sistema
```bash
sudo apt update
sudo apt install ca-certificates curl gnupg lsb-release
```

### 2. Afegir la clau GPO oficial de Docker
```bash
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | \
sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
```

### 3. Afegir el repositori oficial
```bash
echo \
  "deb [arch=$(dpkg --print-architecture) \
  signed-by=/etc/apt/keyrings/docker.gpg] \
  https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```

### 4. Instal·lar Docker
```bash
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io
```

### 5. Afegir l'usuari al grup docker (Opcional)
```bash
sudo usermod -aG docker $USER
```

### 6. Verificar la instal·lació
```bash
docker --version
docker run hello-world
```

[Torna a la Unitat de Treball](UT1.md)