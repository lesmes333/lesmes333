# Luis Alberto Lesmes Hernández

**Técnico en Ciberseguridad Jr.** · Departamento de Ciberseguridad de Zunder · Palencia, España

[![Email](https://img.shields.io/badge/Email-lesmes.luisber%40gmail.com-555?style=flat&logo=gmail&logoColor=white)](mailto:lesmes.luisber@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Luis%20Alberto%20Lesmes-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-alberto-lesmes-hern%C3%A1ndez-03207838b)
[![GitHub](https://img.shields.io/badge/GitHub-lesmes333-181717?style=flat&logo=github&logoColor=white)](https://github.com/lesmes333)

---

## Sobre mí

Técnico Superior en Administración de Sistemas Informáticos en Red (ASIR) con especialización práctica en ciberseguridad, adquirida en el departamento de Ciberseguridad de Zunder. Mi trabajo se centra en la seguridad defensiva: investigación y mitigación de vulnerabilidades en Linux, protección del puesto de trabajo con Microsoft Defender, inteligencia de amenazas y despliegue de infraestructura segura en la nube.

Me interesa especialmente la parte operativa de la defensa: entender cómo se explota una vulnerabilidad para saber cómo detectarla y cerrarla.

---

## Experiencia

**Zunder · Técnico en Ciberseguridad Jr.** · abril 2026 – actualidad

- Investigación, validación y mitigación de vulnerabilidades críticas del kernel de Linux en la infraestructura corporativa (CVE-2026-31431 "Copy Fail", CVE-2026-43284 "Dirty Frag", CVE-2026-46333 "ssh-keysign-pwn").
- Operación de Microsoft Defender for Endpoint y Defender for Office 365: triaje de alertas y protección del parque corporativo.
- Inteligencia de amenazas: análisis de IOC, triaje de phishing y malware, ajuste de detecciones y threat hunting.
- Diseño y despliegue de políticas de Microsoft Purview DLP: control de dispositivos USB, sesiones RDP y Windows 365, y gobierno del almacenamiento en la nube.
- Auditoría de aplicaciones web y API REST con OWASP ZAP, Burp Suite y Postman.
- Despliegue de una plataforma corporativa de simulación de phishing (GoPhish) en Google Cloud Platform, con Docker, Nginx como proxy inverso, TLS 1.2/1.3 con Let's Encrypt, y protección perimetral con Fortinet 100F, VPC, WAF y VPN.
- Hardening de Linux en infraestructura cloud y documentación técnica de informes y pruebas de concepto.

---

## Proyectos

### [OSINT-Prototype](https://github.com/lesmes333/OSINT-Prototype)

Suite de inteligencia de fuentes abiertas escrita en Python para el reconocimiento pasivo de un dominio. Descubre los activos expuestos (subdominios, DNS, WHOIS), identifica las tecnologías en uso, correlaciona vulnerabilidades (CVE) y exploits públicos, integra los avisos de INCIBE-CERT y vigila la dark web a través de Tor. Ejecuta las fases en paralelo y genera informes en JSON, CSV, Markdown y HTML.

Trabaja únicamente con fuentes públicas indexadas, sin interacción intrusiva con el objetivo. Uso exclusivamente defensivo, en auditorías autorizadas y con fines educativos.

`Python` · `OSINT` · `Threat Intelligence` · `CVE` · `INCIBE-CERT` · `Tor`

### Plataforma corporativa de simulación de phishing

Plataforma desplegada en un entorno corporativo real para campañas de concienciación en ciberseguridad.

| Componente | Tecnología |
|---|---|
| Aplicación | GoPhish 0.12.1 |
| Ejecución | Docker 29.3 + Compose |
| Nube | Google Cloud Platform (Compute Engine, VPC Firewall, Cloud WAF) |
| Proxy | Nginx 1.24 con TLS 1.2/1.3 |
| Certificados | Let's Encrypt + Certbot 3.x |
| Correo | SPF, DKIM y DMARC |
| Perímetro | Fortinet 100F NGFW, acceso por túnel SSH sobre VPN corporativa |

### Laboratorio personal de ciberseguridad

Entorno propio para investigación, pentesting práctico y defensa, virtualizado sobre Proxmox VE 8 con almacenamiento ZFS, máquinas en clúster y copias de seguridad de contenedores. Herramientas habituales: Nmap, OWASP ZAP, Burp Suite Community, Wireshark, Hydra y Kali Linux, con entornos aislados en Docker.

---

## Competencias técnicas

| Área | Herramientas y tecnologías |
|---|---|
| Sistemas | Linux (Debian, Ubuntu, Kali), Bash, PowerShell, Windows, Active Directory, OpenLDAP |
| Seguridad defensiva | Microsoft Defender (Endpoint y Office 365), Microsoft Purview DLP, Fortinet, pfSense |
| Inteligencia de amenazas | MITRE ATT&CK, Shodan, VirusTotal, OSINT, Tor |
| Auditoría | Nmap, OWASP ZAP, Burp Suite, Wireshark, Hydra, GoPhish |
| Infraestructura | Docker, Nginx, Proxmox VE, Google Cloud Platform, OpenSSL, Let's Encrypt |
| Desarrollo | Python, PHP, HTML, CSS, JavaScript, MySQL, REST API, Git |

---

## Formación

**Grado Superior en Administración de Sistemas Informáticos en Red (ASIR)** · C.I.F.P. Camino de la Miranda, Palencia · 2024 – 2026
Formación en Centro de Trabajo (FCT) en Zunder: "Diseño, despliegue y operación de plataforma de simulación de phishing para concienciación en Ciberseguridad".

**Grado Medio en Sistemas Microinformáticos y Redes (SMR)** · Centro IMPLIKA, Valladolid · 2020 – 2022

**Certificación en curso:** eJPTv2 (eLearnSecurity Junior Penetration Tester, INE Security).

---

## Actualmente aprendiendo

- KQL y Microsoft Sentinel (SIEM)
- Threat hunting e ingeniería de detección
- Triaje de malware y fundamentos de DFIR

---

## Contacto

Abierto a contactos profesionales y colaboración en proyectos de seguridad defensiva.

- Correo: [lesmes.luisber@gmail.com](mailto:lesmes.luisber@gmail.com)
- LinkedIn: [Luis Alberto Lesmes Hernández](https://www.linkedin.com/in/luis-alberto-lesmes-hern%C3%A1ndez-03207838b)
