# Méteo en direct
Permet de voir la météo d'une ville en direct via l'apel d'une API (openmeteo)

Principe de fonctionnement :

Le script envoie une requête HTTP GET à l'URL de l'API (ex: Open-Meteo) en passant des paramètres (latitude/longitude ou nom de la ville).

Le serveur répond avec une chaîne de texte structurée au format JSON.

Python convertit ce JSON en dictionnaire, extrait uniquement les clés qui t'intéressent (température, vitesse du vent) et les affiche proprement.

Outils / Modules : requests (à installer via pip install requests) et json.

Exécution : Exécution ponctuelle dans le terminal (ex: python meteo.py Lens), ou intégration dans un script de démarrage.
