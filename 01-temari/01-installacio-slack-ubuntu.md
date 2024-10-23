# Slack - instal.lació

## 1. Afegeix la clau GPG de Slack

Aquesta clau s'utilitza per verificar la integritat dels paquets descarregats des del repositori oficial.

Obre una terminal i executa:

```bash
sudo apt update
sudo apt install curl apt-transport-https
curl -fsSL https://packagecloud.io/slacktechnologies/slack/gpgkey | sudo tee /etc/apt/trusted.gpg.d/slack.asc
```

## 2. Afegeix el repositori de Slack a la llista de fonts

Afegeix el repositori oficial de Slack perquè puguis instal·lar-lo i mantenir-lo actualitzat automàticament:

```bash
echo "deb https://packagecloud.io/slacktechnologies/slack/debian/ jessie main" | sudo tee /etc/apt/sources.list.d/slack.list
```

## 3. Actualitza el repositori de paquets

Actualitza la informació del sistema sobre els paquets disponibles:

```bash
sudo apt update
```

## 4. Instal·la Slack

Instal·la l'aplicació Slack:

```bash
sudo apt install slack-desktop
```

## 5. Inicia Slack

Després de la instal·lació, pots iniciar Slack des del menú d'aplicacions o simplement executant el següent comandament a la terminal:

```bash
slack
```
