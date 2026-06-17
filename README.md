
## PowerShell Network Tools - Script de Red
Script interactivo en PowerShell con menú de herramientas de red para administración y diagnóstico.

📋 Descripción
Script con identificación de usuario que ofrece un menú con 10 herramientas de red para pruebas de conectividad y gestión de configuración IP.

⚙️ Funciones disponibles
Opción	Comando	Descripción
1	ping 127.0.0.1	Prueba de loopback
2	ipconfig	Configuración básica de red
3	ipconfig /all	Configuración completa de red
4	tracert	Rastreo de ruta a IP o dominio
5	ping 8.8.8.8	Prueba de conectividad a DNS de Google
6	ping google.com	Prueba de conectividad a Google
7	ipconfig /release	Liberar dirección IP
8	ipconfig /renew	Renovar dirección IP
9	ipconfig /flushdns	Limpiar caché DNS
10	Salir	Cerrar el script

🚀 Instalación y ejecución
Guarda el script como red.ps1

Abre PowerShell como administrador

Ejecuta: .\red.ps1

Si da error de ejecución:

powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

📁 Estructura del código
Identificación de usuarios

Menú principal con bucle

9 funciones de red independientes

Función de salida

👨‍💻 Autor
Hugo Arcones

📄 Licencia
MIT

📌 Requisitos
Windows 10/11

PowerShell 5.0 o superior

Permisos de administrador (opciones 7 y 8)


Si te fue Útil dale una estrella 
