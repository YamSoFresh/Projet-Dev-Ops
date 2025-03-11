# Utilisaton d'une image Python officielle
FROM python:3.10

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier les fichiers nécessaires
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

# Copier le dossier app dans le conteneur
COPY app /app

# Exposer le port utilisé par flask
EXPOSE 5000

# Définir la commande pour démarrer l'application
CMD ["python", "app.py"] 

