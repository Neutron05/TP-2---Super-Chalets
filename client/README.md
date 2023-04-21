Client

Rôle:
Permet d'interagir avec le serveur pour aller chercher les informations de réservations

Requis fonctionnels:
Permet d'effectuer les opérations CRUD d'un point de vue client
GET /reservation/{reservationId}: Retourne l'information sur la réservation
GET /reservations/{utilisateur}: Retourne toutes les réservations de l'utilisateur
POST /reservation: Ajoute une réservation
PUT /reservation/{reservationId}: remplace la réservation
DELETE /reservation/{reservationId}: Supprime la réservation
POST /utilisateur: Ajoute un utilisateur
GET /reservations: si administrateur, renvoyé toutes les réservations triées par ordre de reservationId
Créer le code client permettant d'effectuer les opérations avec le serveur
Voir le README.md du serveur pour le format JSON entre le client et le serveur