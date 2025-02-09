[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/A04QAW6X)

# Índice - Proyecto

## 1. Sprint 1: Hardening de Ubuntu
### 1.1 Instalación de Ubuntu Advantage
- **1.1.1** Comandos de instalación de Ubuntu Advantage Tools

### 1.2 Instalación de Ubuntu Security Guide (USG)

### 1.3 Auditoría del `cis_level2_server`
- **1.3.1** Resultados y Comentarios de la Auditoría

### 1.4 Creación del Archivo `tailor.xml`

### 1.5 Modificación del Archivo `tailor.xml`

### 1.6 Corrección (fix) sobre el Archivo `tailor.xml`

### 1.7 Auditoría `cis_level2_server` con Cambios Aplicados

### 1.8 Configuraciones Globales según Seminario Incibe
- **1.8.1** Configuración del Arranque Grub
- **1.8.2** Establecer una Contraseña de Arranque
- **1.8.3** Establecer Permisos en el Fichero de Configuración de Arranque
- **1.8.4** Obligar al Uso de Contraseña en el Modo "single user"

### 1.9 Configuración de Usuario y Grupo

### 1.10 Comprobación de Cumplimiento Sobre las Actualizaciones

### 1.11 Última Auditoría del `cis_level2_server`

## 2. Sprint 2 - Copias de Seguridad
### 2.1 Instalación Duplicati
- **2.1.1** Problema y Solución Instalación Duplicati

### 2.2 Primera Copia de Seguridad (copia documentos)
- **2.2.1** Configuración Inicial
- **2.2.2** Conexión Google Drive-Duplicati
- **2.2.3** Continuación de la Configuración
- **2.2.4** Ejecución de la Copia de Seguridad
- **2.2.5** Restauración de la Copia de Seguridad
- **2.2.6** Comprobación de la Restauración

### 2.3 Segunda Copia de Seguridad (copia imágenes)
- **2.3.1** Configuración Copia
- **2.3.2** Ejecución de la Copia
- **2.3.3** Restauración de la Copia de Seguridad
- **2.3.4** Comprobación de la Restauración

## 3. Sprint 3 - Hardening Apache
### 3.1 Instalación de Apache

### 3.2. Configuraciones Globales Apache
- **3.2.1** Ficheros de configuraciones
- **3.2.2** Configuración de usuarios y grupos
- **3.2.3** Ocultación de versiones
- **3.2.4** Exposición mínima de módulos
- **3.2.5** Creación de VirtualHost con nombre y apellido
- **3.2.6** Configuración múltiple y de contexto: directiva options

### 3.3 Ficheros .htaccess

### 3.4 Hotlinking: Uso y Bloqueo

### 3.5 Configuración HTTPS y Redirección HTTP a HTTPS

### 3.6 Módulo mod_security

### 3.7 Descarga e Instalación de Kali Linux

### 3.8 Ataque DoS Mediante Metasploit (Slowloris)

### 3.9 Habilitar mod_security, Clonar e Instalar las reglas OWASP

### 3.10 Reglas para detectar SQLInjection

### 3.11 Realizar de nuevo el ataque DoS y comprobar que el servidor está accesible

## 4. Sprint 4 - Hardening SSH
### 4.1 Autenticación SSH (Clave Pública)

### 4.2 Cambio de Puerto Por Defecto

### 4.3 Comprobar Límite de la Vinculación IP (Deshabilitación Opcional)

### 4.4 Deshabilitar usuario ROOT para login

### 4.5 Limitar acceso SSH de los usuarios del sistema
- **4.5.1** Prueba de Limitación con Usuarios

### 4.6 Deshabilitar Inicio de Sesión Basado en Contraseña
- **4.6.1** Habilitar Inicio de Sesión Basado en Contraseña

### 4.7 Deshabilitar Contraseñas Vacías

### 4.8 Limitar Intentos de Autenticación Fallida

### 4.9 Limitar Conexiones Simultáneas No Autenticadas

### 4.10 Habilitar Banner de Advertencia para Usuarios de SSH

### 4.11 Configurar Intervalo de Tiempo de Espera de Cierre de Sesión Inactiva

### 4.12 Deshabilitar X11forwarding

## 5. Sprint 5 - Escaneo de vulnerabilidades
### 5.1 Descarga de mestasploitable2

### 5.2 Escaneo mediante la técnica SYN Scan
- **5.2.1** Comentario del Escaneo

### 5.3 Escaneo de los Principales Puertos UDP abiertos
- **5.3.1** Comentario del Escaneo

### 5.4 Escaneo lanzado el script vuln sobre metasploitable2 y servidor
- **5.4.1** Comentario del Escaneo

### 5.5 Escaneo Agresivo sobre metasploitable y servidor
- **5.5.1** Comentario del Escaneo

### 5.6 Escaneo de Descubrimiento de Equipos en la Red de Casa
- **5.6.1** Comentario del Escaneo

## 6. Sprint 6 - Seguridad perimetral con pfSense
### 6.1 Instalación y Configuración de pfSense

### 6.2 Preguntas previas a Configurar Reglas
- **6.2.1** ¿El servidor web y SSH es accesible desde el exterior?
- **6.2.2** ¿El servidor tiene acceso a internet?
- **6.2.3** ¿El equipo de los empleados tiene internet?
- **6.2.4** ¿El servidor web es alcanzable desde el equipo de los empleados? ¿Y viceversa?

### 6.3 Configuración de Reglas
- **6.3.1** El servidor tenga acceso a internet
- **6.3.2** Los empleados tengan acceso a internet
- **6.3.3** El servidor web sea accesible únicamente por el puerto 443 y redirija el tráfico del 80 al 443
- **6.3.4** El servidor SSH sea accesible únicamente desde el puerto que elegiste en el Sprint de Hardening SSH
- **6.3.5** Una regla que no permita el tráfico directo entre el servidor y los empleados, y al revés
- **6.3.6** Regla preparada para el bloqueo del tráfico
- **6.3.7** Regla contra ciberataque
- **6.3.8** Regla Propia

## 7. Sprint 7 - IDS, VPN y Análisis de Tráfico de Red con pfSense
### 7.1 Instalación IDS/IPS Suricata

### 7.2 Aplicación de Reglas Snort

### 7.3 Ataque DoS sobre Servidor Web

### 7.4 Habilitar IDS (Modo IPS [Legacy Mode])
- **7.4.1** Nuevo Ataque DoS
- **7.4.2** Revisión y Comprobación de Cambios
- **7.4.3** Comentario sobre Información del Log

### 7.5 Habilitar VPN en pfSense
- **7.5.1** Selección de Tecnología VPN
- **7.5.2** Instalación y Funcionamiento de OpenVPN o WireGuard

### 7.6 Instalación de ntopng
- **7.6.1** Comentario de ntopng
