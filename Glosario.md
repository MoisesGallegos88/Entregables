### 🔸 **1. Inyección**

Técnicas que introducen datos maliciosos en formularios o entradas para modificar el comportamiento del sistema.

- **SQL Injection**: Técnica que permite ejecutar consultas SQL no autorizadas.
    
- **Inyección de código SQL**: Inserta código SQL malicioso en formularios o URLs.
    
- **Inyección de comandos**: Permite ejecutar comandos del sistema operativo desde una app vulnerable.
    
- **Inyección de datos**: Inserta datos maliciosos que modifican la lógica de una aplicación.
    
- **Injection flaws**: Errores que permiten ejecutar código no deseado mediante entradas manipuladas.
    
- **Command injection**: Ejecución remota de comandos en el servidor por entradas no validadas.
    
- **XML External Entity (XXE)**: Explotación de entidades externas definidas en XML para leer archivos o hacer peticiones.
    
- **Host header injection**: Manipula la cabecera Host para redirigir usuarios o explotar rutas internas.
    
- **Header injection**: Inserta contenido malicioso en cabeceras HTTP, a menudo para phishing o redirección.
    
- **Parameter pollution**: Envío de múltiples parámetros con el mismo nombre para alterar la lógica del servidor.
    

---

### 🔸 **2. XSS y ataques web**

Ataques a aplicaciones web orientados a manipular scripts o vulnerar la lógica de interacción.

- **Cross-Site Scripting (XSS)**: Inyección de scripts en páginas web para atacar a usuarios.
    
- **Reflected XSS**: El script se refleja en la respuesta del servidor inmediatamente.
    
- **Stored XSS**: El script malicioso se guarda en la base de datos y se ejecuta al visitar la página.
    
- **Open redirect**: Redirige al usuario a una URL controlada por el atacante.
    
- **Clickjacking**: Truco visual que hace clic al usuario en botones invisibles o disfrazados.
    
- **CSRF**: Fuerza al usuario autenticado a ejecutar acciones no deseadas.
    
- **Cookie theft**: Robo de cookies para suplantar sesiones de usuarios.
    
- **User-agent spoofing**: Falsificación del agente de usuario para engañar sistemas o registros.
    
- **Content spoofing**: Manipulación del contenido mostrado para engañar al usuario.
    
- **HTTP response splitting**: Inyección de cabeceras para dividir respuestas HTTP y alterar el contenido.
    
- **IDOR**: Acceso indebido a recursos por identificación directa sin autorización.
    
- **Login sin autenticación**: Acceso a cuentas o paneles sin verificación de identidad.
    
- **Session fixation**: Fijación de una sesión conocida para secuestrar la sesión de un usuario.
    

---

### 🔸 **3. Evasión y ocultación**

Técnicas usadas para evitar la detección por parte de sistemas de defensa o análisis.

- **Técnicas de evasión**: Métodos para evitar la detección por firewalls o antivirus.
    
- **Escaneo sigiloso**: Escaneo que intenta pasar desapercibido usando técnicas como fragmentación.
    
- **Fragmentación de paquetes**: Divide los paquetes para evitar detección en redes.
    
- **Puerto fuente no estándar**: Uso de puertos inesperados para evadir filtros.
    
- **Intervalos de paquetes**: Manipula tiempos entre paquetes para evitar correlación.
    
- **Código ofuscado**: Código difícil de entender para ocultar su propósito real.
    
- **Esteganografía**: Oculta datos dentro de archivos aparentemente normales.
    
- **Encapsulation**: Encierra datos maliciosos dentro de protocolos válidos.
    
- **Tunneling**: Envía tráfico a través de protocolos como HTTP o DNS para evadir controles.
    
- **Redirección maliciosa**: Envía al usuario a un sitio falso o infectado.
    
- **Cache poisoning**: Manipula cachés para entregar contenido malicioso.
    
- **Verbose error**: Errores detallados que revelan información del sistema.
    

---

### 🔸 **4. Escaneo y reconocimiento**

Actividades destinadas a identificar información sobre el sistema o red objetivo.

- **Enumeración**: Proceso de obtención de información del sistema o red.
    
- **Banner grabbing**: Extrae información de servicios mediante sus mensajes iniciales.
    
- **OS fingerprinting**: Identifica el sistema operativo a partir de respuestas de red.
    
- **Reconocimiento pasivo**: Obtiene información sin interactuar directamente con el objetivo.
    
- **Reconocimiento activo**: Realiza peticiones directas para descubrir detalles del objetivo.
    
- **DNS enumeration**: Identifica registros DNS y subdominios.
    
- **Subdomain enumeration**: Lista subdominios del dominio objetivo.
    
- **Service enumeration**: Detecta servicios activos en un sistema.
    
- **SNMP enumeration**: Obtiene datos mediante el protocolo SNMP.
    
- **SMB enumeration**: Descubre recursos compartidos por SMB.
    
- **Anonymous login**: Acceso sin autenticación en servicios mal configurados.
    
- **Null session**: Sesión sin credenciales para acceder a recursos compartidos.
    
- **ICMP scan**: Usa mensajes ICMP para detectar hosts activos.
    
- **Ping scan**: Envía paquetes ping para descubrir dispositivos conectados.
    
- **SYN scan**: Envía paquetes SYN para ver qué puertos responden.
    
- **TCP handshake**: Proceso de conexión entre cliente y servidor TCP.
    
- **Solicitudes TCP SYN**: Paquetes usados para iniciar una conexión TCP.

### 🔸 **5. Fuerza bruta**

Ataques que buscan adivinar contraseñas o credenciales.

- **Fuerza bruta**: Intenta todas las combinaciones posibles de contraseñas.
    
- **Ataque de diccionario**: Usa una lista de contraseñas comunes.
    
- **Cracking de contraseñas**: Rompe contraseñas cifradas.
    
- **Login bypass**: Evita autenticación con manipulación de entrada.
    
- **Credential stuffing**: Usa credenciales filtradas en varios servicios.
    
- **Token reuse**: Reutiliza tokens de sesión para acceder sin login.
    
- **Two-factor bypass**: Elude la verificación en dos pasos.
    
- **Captura de credenciales**: Intercepta contraseñas por sniffing o phishing.
    
- **Brute force distribuido**: Ataque desde múltiples IPs para evadir bloqueos.
    
- **Ataque de sesión**: Secuestra sesiones para obtener acceso continuo.
    

---

### 🔸 **6. Vulnerabilidades**

Errores que pueden ser aprovechados para obtener acceso o ejecutar código.

- **Vulnerabilidad**: Fallo en el sistema explotable por un atacante.
    
- **CVE**: Identificador estándar de vulnerabilidades conocidas.
    
- **Zero-day**: Vulnerabilidad no descubierta públicamente aún.
    
- **Exploit**: Código usado para explotar una vulnerabilidad.
    
- **Buffer overflow**: Desbordamiento de memoria que ejecuta código arbitrario.
    
- **Race condition**: Conflicto de procesos que causa errores de seguridad.
    
- **Deserialización insegura**: Procesa objetos manipulados con código malicioso.
    
- **Path traversal**: Accede a rutas no permitidas.
    
- **Privilege escalation**: Gana privilegios mayores al usuario original.
    
- **RCE**: Ejecuta comandos de forma remota por una falla.
    

---

### 🔸 **7. Sniffing y red**

Técnicas para interceptar, espiar o alterar tráfico de red.

- **Sniffing**: Captura datos que circulan por la red.
    
- **Intercepción de paquetes**: Lee datos en tránsito.
    
- **ARP Spoofing**: Suplanta direcciones en red local para desviar tráfico.
    
- **Man-in-the-middle**: Interfiere en la comunicación entre dos partes.
    
- **DNS Spoofing**: Devuelve direcciones falsas al resolver nombres.
    
- **DHCP Spoofing**: Asigna IPs falsas en una red.
    
- **MAC flooding**: Satura la tabla del switch para escuchar tráfico.
    
- **SSL stripping**: Quita cifrado HTTPS y lo convierte en HTTP.
    
- **Captura de tráfico**: Registra el tráfico de una red.
    
- **Sniffing activo**: Alteración directa de red para recopilar datos.
    

---

### 🔸 **8. Reconocimiento (OSINT)**

Obtención de datos públicos del objetivo antes de un ataque.

- **Reconocimiento (OSINT)**: Recolección de información abierta.
    
- **Footprinting**: Identifica activos, dominios, IPs del objetivo.
    
- **Google Dorking**: Búsqueda avanzada de información expuesta con operadores.
    
- **TheHarvester**: Extrae correos y subdominios de fuentes públicas.
    
- **Metadatos**: Información oculta en archivos como autores o rutas.
    
- **Scraping**: Extrae contenido automatizado de páginas web.
    
- **Web Crawling**: Navega sistemáticamente sitios para indexarlos.
    
- **Análisis WHOIS**: Muestra datos técnicos y legales de dominios.
    
- **Geolocalización de IP**: Asigna coordenadas aproximadas a direcciones IP.
    
- **DNS lookup**: Recolecta información DNS como subdominios o registros.