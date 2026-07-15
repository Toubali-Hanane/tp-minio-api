# TP MinIO Storage & Postman API

Ce projet présente la configuration d'un stockage objet local avec MinIO et la manipulation des objets via l'API S3 en utilisant Postman.

## 1. Création du Bucket (Interface MinIO & Postman)
* **Création du bucket via Postman:**
  ![Création Bucket](screenshots/1_creation_bucket_postman.png)

## 2. Upload de fichier `clients.json`
* **Upload via Postman (PUT):**
  ![Upload Postman](screenshots/2_upload_clients_postman.png)
* **Vérification de l'existence du fichier dans MinIO:**
  ![Vérification Upload MinIO](screenshots/2_bis_verification_upload_minio.png)

## 3. Lecture du fichier (GET)
* **Lecture du contenu de `clients.json` via Postman:**
  ![Lecture Postman](screenshots/3_lire_clients_postman.png)

## 4. Suppression du fichier (DELETE)
* **Suppression via Postman:**
  ![Suppression Postman](screenshots/4_supprimer_clients_postman.png)
* **Vérification du bucket vide dans MinIO:**
  ![Vérification Vide](screenshots/5_bucket_empty_verification.png)
