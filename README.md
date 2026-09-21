# Gestion-de-identidad-bovedas-MFA-y-Passkeys
Práctica: Mi Bóveda y Contenedor Seguro

## Descripción
Configuré un entorno seguro para proteger mis accesos digitales y archivos sensibles combinando un gestor de contraseñas y cifrado de datos.

## Herramientas utilizadas
- Bitwarden: Gestor de contraseñas con cifrado de extremo a extremo
- VeraCrypt: Herramienta de cifrado para contenedores de archivos

## Paso 1 — Bóveda de contraseñas
- Creé la cuenta con una contraseña maestra tipo frase de 4 palabras
- Guardé 3 credenciales generadas automáticamente de 16+ caracteres
- Activé la autenticación en dos pasos (MFA) con aplicación autenticadora
- Guardé los códigos de recuperación en lugar seguro

## Paso 2 — Contenedor cifrado
- Creé un contenedor de 100 MB con algoritmos por defecto (AES, SHA-512)
- Usé una contraseña distinta a la de la bóveda
- Guardé la contraseña dentro de Bitwarden

## Paso 3 — Uso del volumen
- Monté el contenedor en la unidad Z:
- Creé el archivo aprendizajes.txt con los conceptos clave
- Desmonté el volumen para dejarlo protegido

## Capturas adjuntas
- captura_boveda.png — Lista de cuentas guardadas
- captura_mfa.png — MFA activado
- captura_veracrypt.png — Volumen montado en VeraCrypt

## Conclusiones
- Reutilizar contraseñas pone en riesgo todas las cuentas
- Las frases largas son más seguras y fáciles de recordar
- El MFA bloquea accesos aunque roben la contraseña
- El cifrado protege los archivos si pierdo el equipo
