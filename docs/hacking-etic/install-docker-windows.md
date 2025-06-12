# 📦 Tutorial d'Instal·lació de Docker i Verificació en Windows

Aquest document descriu el procés d'instal·lació de Docker en el sistema operatiu: **Windows**, així com una **prova ràpida** per verificar que Docker funciona correctament.

---

### 1. Descarregar Docker Desktop
Ves al lloc oficial:
👉 [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

### 2. Requisits

- Windows 10/11 Pro o Home
- Virtualització activada al BIOS
- WSL2 activat (s'instal·la automàticament si no ho està)

### 3. Instal·lació

- Executa .exe descarregat i segueix els passos
- Reinicia el sistema si és necessari

### 4. Verifica la instal·lació

```bash
docker --version
docker run hello-world
```

[Torna a la Unitat de Treball](UT1.md)