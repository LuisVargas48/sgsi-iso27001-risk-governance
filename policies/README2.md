# Catálogo Corporativo de Políticas de Seguridad de la Información

Marco regulatorio interno compuesto por 25 políticas formales diseñadas para mitigar las brechas operativas y normativas identificadas en la organización:

### 1. Políticas de Seguridad de Software
1. **Protección de Endpoints:** Sustitución de antivirus gratuitos por EDR corporativo en 15,000 equipos.
2. **Gestión de Actualizaciones de SO:** Calendario mandatorio mensual y aplicación de parches en periodos < 7 días.
3. **Mantenimiento y Parches de BD:** Parcheo trimestral y soporte de fabricante para motores Oracle, DB2 y SQL Server.
4. **Control de Instalación de Software:** Restricción de privilegios y prohibición de software de internet no autorizado.
5. **Gestión y Auditoría de Licencias:** Adopción de Software Asset Management (SAM) y auditoría de derechos de uso.

### 2. Políticas de Seguridad de Hardware
6. **Ciclo de Vida de Red:** Prohibición de operar switches/routers Cisco con más de 5 años de antigüedad y actualización semestral de firmware.
7. **Mantenimiento Preventivo de Servidores:** Ventanas de mantenimiento limitadas a < 4 horas y esquemas de Alta Disponibilidad.
8. **Inventario y Control de Activos:** Registro digitalizado en tiempo real; prohibición de conexión para activos no etiquetados.
9. **Sustitución y Renovación:** Reemplazo por ciclo de vida útil (4 años para laptops, 5 años para servidores).
10. **Integridad Física de Equipos:** Prohibición de manipulación de componentes internos sin supervisión de TI.

### 3. Políticas de Información Confidencial
11. **Control de Acceso Basado en Roles (RBAC):** Eliminación del "Full Access" generalizado y aplicación de mínimo privilegio con MFA.
12. **Clasificación de la Información:** Estructura de 4 niveles (Pública, Uso Interno, Confidencial y Restringida).
13. **Seguridad para Acceso Remoto:** Conectividad exclusiva vía túneles VPN industriales con autenticación multifactor (2FA).
14. **Cifrado de Bases de Datos:** Cifrado de datos en reposo (AES-256) y en tránsito para proteger la propiedad intelectual.
15. **Respaldos de Información:** Cumplimiento de la estrategia 3-2-1 con réplica off-site para asegurar el 100% de los datos críticos.

### 4. Políticas de Seguridad Ambiental y Física
16. **Respuesta ante Sismos:** Plan de evacuación y Hot Site alterno para el centro de diseño en zona sísmica (Múnich).
17. **Vigilancia y Monitoreo Físico:** Cobertura del 100% operativa en CCTV e inspecciones quincenales.
18. **Gestión de Residuos Electrónicos:** Destrucción y reciclaje certificado de hardware en desuso para prevenir fuga de datos.
19. **Seguridad en Centros de Datos:** Restricción física de acceso a salas de mainframes e inspección de UPS y enfriamiento.
20. **Protección de Activos en Tránsito:** Protocolo de cadena de custodia para prototipos y hardware automotriz premium.

### 5. Políticas de Recursos Humanos y Cultura
21. **Control de Visitantes:** Registro obligatorio en recepción, porte de gafetes y acompañamiento permanente.
22. **Concientización y Capacitación:** Programa trimestral mandatorio para los 35,000 colaboradores con simulaciones de phishing.
23. **Uso Aceptable de Activos (AUP):** Reglas disciplinarias ante descargas no autorizadas o uso recreativo de estaciones de trabajo.
24. **Acuerdos de No Divulgación (NDA):** Obligatoriedad legal para salvaguardar secretos industriales post-empleo.
25. **Revocación de Accesos por Baja:** Procedimiento conjunto RH/TI para revocación lógica total en un plazo máximo de 2 horas.
