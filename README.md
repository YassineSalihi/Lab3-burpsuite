# Lab3-burpsuite

## Objectifs Pédagogiques : 
- Vérification d’un navigateur Android envoie son trafic via Burp.
- Identification des éléments essentiels d’une requête.
(URL, methode, headers, cookie, paramètres)
- Expliquation de la différence HTTP vs HTTPS et le rôle d’un 
certificat CA en labo.
- Production une trace d’audit simple (preuves + contexte).

## Prérequis :

| Prérequis | Checked |
| -------------- | --------------- |
| Burpsuite installed | <ul><li>- [x]</li><li></ul> |
| Android Emulator | <ul><li>- [x]</li><li></ul> |
| Réseaux de lab | <ul><li>- [x]</li><li></ul> |

## Régles de sécurité :

 - Trafic intercepté uniquement pour des cibles autorisées.
 - Aucun compte personnel, aucune donnée sensible.
 - Le certificat de labo (si installé) doit être retiré à la fin.

## Étape 1 — Préparer Burp Suite

 Voilà la première interface :
 ![first interface of Burpsuite](https://github.com/user-attachments/assets/d5fa7058-8a39-4570-9bea-a9d57d44239f) 

 ![](https://github.com/user-attachments/assets/1b4f1ef4-4617-4cb9-b595-f347b5829e0a)
 ![](https://github.com/user-attachments/assets/44fcc728-84af-450d-a8e6-113c6d9c3fc3)

##  Étape 2 — Vérifier le Proxy Listener (adresse et port)

![](https://github.com/user-attachments/assets/f384736f-f292-4332-858a-bbf8c6b395fb)
![](https://github.com/user-attachments/assets/79a5204c-a4bb-4124-81d3-90248e33c182)

## Étape 3 — Identifier l’adresse réseau de la machine hôte

![](https://github.com/user-attachments/assets/246214df-b89a-4eeb-a81c-0bfba657d550)

## Configuration d'emulateur:
 ![](https://github.com/user-attachments/assets/814a0e01-e00d-48c6-a854-d0e773ba067f)

## Interception d'emulateur:

> [!NOTE]
> ajoute le port 8080 au regle ufw

![](https://github.com/user-attachments/assets/15b2151f-5285-4707-bf71-1954a9f5c737)

![](https://github.com/user-attachments/assets/c5e4c811-3195-41d2-9d90-73d89559a6f9)

![](https://github.com/user-attachments/assets/0cf166ca-bc4e-4ce1-8cbd-1b7d399e08a8)


