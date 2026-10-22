# Francisco Escalante

**Fundador y arquitecto de CyberScan Sovereign** · Evaluación externa de riesgo cibernético para empresas en México

Diseño y construyo software de extremo a extremo —producto, motores, entregables e infraestructura de producción— para el mercado empresarial mexicano. Prefiero resolver en la raíz antes que acumular parches, y no publico una cifra que no pueda reconstruir desde la evidencia.

---

## CyberScan Sovereign

Evaluación externa y no intrusiva de la superficie web de una organización —sin credenciales ni acceso interno— que traduce hallazgos técnicos al lenguaje que necesitan la dirección y el área jurídica.

No compite por encontrar más, sino por poder sostener lo que afirma:

- **Un hallazgo técnico no es una infracción.** El informe separa tres niveles: el hallazgo técnico (lo determina el escaneo), el riesgo de cumplimiento (lo estima la metodología) y la infracción legal (solo la determina la autoridad competente).
- **Evidencia observada vs. inferencia.** Cada hallazgo declara si se verificó sobre un artefacto observado o si es una inferencia.
- **Relevancia normativa.** Los hallazgos se relacionan con los artículos aplicables de la LFPDPPP 2025.
- **Integridad del entregable.** Validaciones de consistencia antes de emitir y sello ECDSA sobre el contenido del informe.
- **Menos falsos positivos.** Identifica dominios detrás de CDN/WAF y confirma servicios por banner antes de reportarlos.

**Stack:** Python · Flask · Gunicorn · Nginx · ModSecurity · Cloudflare · DigitalOcean · Linux · ReportLab · Three.js  
**Modelado cuantitativo:** simulación Monte Carlo · VaR / CVaR

---

## Plataforma SaaS clínica · en producción

SaaS multi-tenant para consulta de nutrición, en operación con una clínica real: expediente, planes alimentarios, citas, chat en tiempo real, notificaciones push y app instalable (PWA).

- Aislamiento por clínica con Row-Level Security en PostgreSQL y cifrado por campo AES-256-GCM.
- Notificaciones Web Push sin datos clínicos en el contenido y asistente de IA con seudonimización de los datos del paciente.
- Respaldos diarios cifrados con restauración probada de extremo a extremo.

**Stack:** FastAPI · Python · PostgreSQL · Redis · Next.js · TypeScript · WebSockets · Caddy · contenedores

> El código de ambos proyectos es privado. Demostración disponible bajo solicitud.

---

## Seguridad de aplicaciones web

Formación práctica en OWASP Top 10 con laboratorios en DVWA y PortSwigger Web Security Academy: SQLi, XSS, inyección de comandos, CSRF, path traversal, control de acceso y lógica de negocio.

**Herramientas:** Burp Suite · Nmap · SQLMap · John the Ripper · Git · Parrot OS  
**En preparación:** Burp Suite Certified Practitioner (BSCP)

---

## Contacto

[LinkedIn](https://www.linkedin.com/in/francisco-escalante-cyberscan) · fco.escalanted@cyberscansovereign.com

<sub>**EN —** Founder & architect of CyberScan Sovereign: external, non-intrusive cyber-risk assessment for companies in Mexico that keeps technical findings separate from legal conclusions under Mexico's data-protection law (LFPDPPP 2025). Also building a multi-tenant clinical SaaS in production. Background in web application security (OWASP Top 10, PortSwigger labs).</sub>
