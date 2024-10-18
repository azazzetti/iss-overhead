# iss-overhead
Sends an email notification when the ISS passes overhead and it is nighttime using location-based logic and API integration.


English Description
International Space Station (ISS) Overhead Notifier

This Python script sends an email notification when the International Space Station (ISS) passes directly overhead and it's nighttime. It utilizes two APIs: one to get the current location of the ISS and another to determine the local sunrise and sunset times based on your coordinates.

Features:
API Integration: The script fetches data from the Open Notify ISS API to track the position of the ISS and the Sunrise-Sunset API to determine if it’s nighttime.
Email Notifications: When the ISS is overhead and it is nighttime, the script sends an email to notify the user to look up and spot the ISS.
Location-based Logic: It compares the user's location with the ISS position and checks if it’s within a 5-degree margin to trigger a notification.

Technologies:
	Python: Main language for the script.
	Requests: Used to fetch data from the APIs.
	Smtplib: Sends email notifications using Gmail's SMTP server.

APIs:
	Open Notify ISS API
	Sunrise-Sunset API



_____________________________________________________________________________________________________________________________________________________________________________________


Descripción en Castellano
Notificador del Paso de la Estación Espacial Internacional (ISS)

Este script en Python envía una notificación por correo electrónico cuando la Estación Espacial Internacional (ISS) pasa directamente sobre tu ubicación y es de noche. Utiliza dos APIs: una para obtener la posición actual de la ISS y otra para determinar los horarios locales de salida y puesta del sol según tus coordenadas.

Funcionalidades:
Integración con APIs: El script obtiene datos de la API de Open Notify ISS para rastrear la posición de la ISS y de la API Sunrise-Sunset para determinar si es de noche.
Notificaciones por Correo Electrónico: Cuando la ISS pasa por encima y es de noche, el script envía un correo electrónico notificando al usuario que mire hacia el cielo.
Lógica Basada en la Ubicación: Compara la ubicación del usuario con la posición de la ISS y verifica si está dentro de un margen de 5 grados para activar una notificación.

Tecnologías:
	Python: Lenguaje principal del script.
	Requests: Para realizar solicitudes a las APIs.
	Smtplib: Para enviar notificaciones por correo electrónico usando el servidor SMTP de Gmail.

APIs:
	API de Open Notify ISS
	API Sunrise-Sunset
