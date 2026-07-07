# 🔐 Prácticas de Seguridad en Linux - RHEL 10
Este repositorio reúne las prácticas realizadas para la asignatura de Seguridad en Linux utilizando **Red Hat Enterprise Linux 10 (RHEL 10)**.

El objetivo es aplicar mecanismos de protección del sistema mediante herramientas ampliamente utilizadas en entornos empresariales, como GPG, iptables, firewalld, Snort y Google Authenticator.

---

## 🖥️ Entorno de Trabajo

- Sistema Operativo: Red Hat Enterprise Linux 10
- Máquina Virtual
- Acceso SSH
- Cliente Host para pruebas
- Privilegios de administrador (sudo/root)

---

# 📌 Práctica 1 - Cifrado con GPG2

## Objetivos

- Instalar GPG2.
- Configurar la herramienta.
- Crear archivos cifrados.
- Descifrar archivos.
- Verificar el contenido recuperado.

### Actividades

- Instalación de GPG2.
- Creación de un directorio de trabajo.
- Creación de un archivo de prueba.
- Cifrado del archivo.
- Intento de lectura del archivo cifrado.
- Descifrado del archivo.
- Verificación del contenido.

---

# 🔥 Práctica 2 - Administración del Firewall

## Objetivos

Administrar el acceso a los servicios mediante:

- iptables
- firewalld

### Servicios utilizados

- HTTP (80)
- FTP (21)
- SSH (22)

### Actividades

- Habilitación de servicios.
- Verificación de funcionamiento.
- Bloqueo mediante iptables.
- Verificación del bloqueo.
- Restauración del acceso.
- Bloqueo mediante firewalld.
- Restauración del acceso.

---

# 🛡️ Práctica 3 - IDS Snort

## Objetivos

Instalar y configurar el sistema de detección de intrusos Snort.

### Reglas implementadas

- Detección de tráfico ICMP.
- Detección de conexiones al puerto 21.
- Detección de conexiones al puerto 22.
- Detección de conexiones al puerto 80.

### Pruebas

Las pruebas fueron realizadas desde la máquina Host hacia la máquina virtual ejecutando:

- Ping
- SSH
- FTP
- HTTP

Se verificó que Snort detectara correctamente cada evento.

---

# 🔐 Práctica 4 - Autenticación de Dos Factores (2FA)

## Objetivos

Implementar autenticación multifactor para el servicio SSH utilizando Google Authenticator y PAM.

### Actividades

- Instalación de Google Authenticator.
- Configuración del usuario.
- Configuración de PAM.
- Configuración del servicio SSH.
- Validación del acceso remoto.

Durante la autenticación se solicita:

1. Usuario
2. Contraseña
3. Código temporal generado por Google Authenticator

---

# 📚 Herramientas Utilizadas

- GPG2
- iptables
- firewalld
- Snort
- OpenSSH
- PAM
- Google Authenticator

---

# 🎯 Competencias Desarrolladas

- Administración de servicios Linux.
- Cifrado de información.
- Gestión de firewall.
- Implementación de IDS.
- Seguridad en acceso remoto.
- Autenticación multifactor.

---


# 👨‍💻 Autor

**Víctor De Peña**

Prácticas desarrolladas en **Red Hat Enterprise Linux 10** como parte del laboratorio de Seguridad en Linux.

---

# 📄 Licencia

Repositorio con fines académicos.
