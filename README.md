# 🚩 RETO SOC: Operación "Robo Silencioso"

¡Bienvenido al equipo de respuesta ante incidentes! 🛡️

El profesor Paco ha reportado que han aparecido notas modificadas en el sistema. Sospechamos que alguien ha robado su cuenta. Tu misión es reconstruir el ataque usando los registros (logs) del sistema.

### 📝 El Desafío
Debes actuar como un **Analista SOC L1**. Tu objetivo es responder a las "5 preguntas de la sintaxis forense":

1. **Sujeto (¿Quién?):** ¿Qué IP externa tuvo éxito al entrar? ¿Qué IP interna se usó para descargar los exámenes?
2. **Tiempo (¿Cuándo?):** ¿En qué ventana horaria ocurrió el robo?
3. **Modo (¿Cómo?):** ¿Qué técnica usaron contra la cuenta de Paco? (Fuerza bruta, robo de sesión...).
4. **Lugar (¿A qué afectó?):** ¿Qué archivo crítico fue exfiltrado (descargado)?
5. **Mensaje Oculto:** El atacante dejó una "firma" en el log de acceso en formato Base64. ¿Qué dice?

### 🛠️ Herramientas recomendadas:
* [AbuseIPDB](https://www.abuseipdb.com/) para verificar IPs.
* [CyberChef](https://gchq.github.io/CyberChef/) para decodificar mensajes.
* `Ctrl + F` para buscar dentro de los archivos.

