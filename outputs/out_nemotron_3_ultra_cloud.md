# Respuestas a las 10 preguntas

---

## 1. Gestión económica: Piñera (2010-2014, 2018-2022) vs. Boric (2022-presente)

| Indicador | Piñera I (2010-2014) | Piñera II (2018-2022) | Boric (2022-2024*) |
|-----------|---------------------|----------------------|-------------------|
| **Crecimiento PIB promedio anual** | 4,7% (favorecido por precio del cobre y reconstrucción post-27F) | 1,8% (estallido social 2019, pandemia 2020) | 0,7% (2022: 2,4%; 2023: 0,2%; 2024e: ~2,5%) |
| **Inflación promedio anual** | 2,9% (dentro meta 2-4%) | 3,1% (pico 14,1% en 2022 por factores globales) | 7,6% (2022: 12,8%; 2023: 3,9%; 2024: ~3,5%) |
| **Desempleo promedio** | 6,8% | 9,1% (pico 12,2% en 2020) | 8,5% (2024: ~8,7%) |
| **Gini (desigualdad ingresos)** | 0,50 → 0,48 (mejora leve) | 0,46 → 0,46 (estancado) | 0,46 → 0,45 (leve mejora, datos CASEN 2022) |
| **Deuda bruta / PIB** | 8,6% → 14,9% | 25,6% → 36,3% | 36,3% → 39,5% (2024) |

**Matices clave:**
- **Piñera I** heredó crisis subprime y terremoto; crecimiento impulsado por términos de intercambio récord del cobre.
- **Piñera II** enfrentó estallido social (caída inversión -12% en 2019) y pandemia (caída PIB -6,1% en 2020); paquetes fiscales masivos (IFE, Fogape) explican alza deuda.
- **Boric** heredó inflación global post-pandemia y guerra Ucrania; reforma tributaria rechazada (2023) limitó margen fiscal; crecimiento 2023 casi nulo por contracción minería/construcción, pero 2024 muestra recuperación.
- **Desigualdad**: ambos periodos muestran estancamiento estructural (Gini ~0,46); leve mejora bajo Boric atribuible a alza salario mínimo y subsidios focalizados, no a cambio estructural.
- **Contexto externo** explica gran parte de las diferencias: términos de intercambio, tasas globales, shocks de oferta.

*Fuentes: Banco Central de Chile, INE, DIPRES, CASEN, FMI WEO. Datos 2024 preliminares/proyectados.*

---

## 2. Despenalización del aborto en Chile: argumentos (~120 palabras)

**A favor:** Derecho a la autonomía reproductiva y salud integral de la mujer (OMS, CIDH); criminalización afecta desproporcionadamente a mujeres pobres (acceso desigual a aborto seguro); reducción de mortalidad materna donde se legaliza (evidencia internacional); tres causales (riesgo vida madre, inviabilidad fetal, violación) cuentan con 70-80% apoyo ciudadano (Cadem, 2023); obligación Estado de garantizar derechos sexuales/reproductivos (CEDAW, ratificada por Chile).

**En contra:** Derecho a la vida del nasciturus desde la concepción (Art. 19 N°1 Constitución vigente y proyecto 2023); objeción de conciencia médica/institucional debe ser absoluta; riesgo de "puerta giratoria" hacia aborto libre (experiencia Argentina, Colombia); protección del niño por nacer como bien jurídico autónomo; alternativas: adopción, apoyo a maternidad vulnerable; encuestas muestran mayoría rechaza aborto libre sin causales.

---

## 3. Salario mínimo en Chile: ¿protege o expulsa a informalidad?

**Evidencia mixta con matices:**

| Estudio / Período | Hallazgo principal |
|-------------------|-------------------|
| **Larrañaga (2017), Banco Central** | Alzas 2011-2015: efecto nulo/leve negativo en empleo formal (-0,1% a -0,3% por 10% alza); mayor impacto en jóvenes y baja calificación. |
| **Contreras & Ruiz (2020), ILades** | Alza 2018-2019 ($276k→$301k): redujo empleo formal en 1,2 pp en microempresas; aumento informalidad en sectores bajos. |
| **Banco Central IPoM 2023** | Alzas 2022-2024 (40% nominal en 2 años): transmisión a salarios formales alta; efecto empleo "moderado" pero concentrado en comercio/servicios, microempresas. |
| **Encuesta Suplementaria de Ingresos (ESI)** | Brecha salario mínimo vs. mediana: 2020: 52% → 2024: ~62% (mayor "mordida"); 30% asalariados privados ganan ≤ salario mínimo. |

**Conclusión matizada:**
- **Protege**: reduce pobreza laboral, compresión salarial baja, mayor poder adquisitivo en hogares vulnerables (evidencia: alza 2022-24 redujo pobreza en ~0,7 pp según Fundación Sol).
- **Expulsa/desincentiva formalidad**: en microempresas (≤9 trabajadores) y sectores de baja productividad (comercio, hoteles, restaurantes), el costo marginal supera productividad → despidos, no renovación contratos, o migración a informalidad (sin contrato, "honorarios" ficticios).
- **Diseño importa**: subsidios temporales a pymes (Ley 21.578, 2023) mitigaron efecto; indexación automática a IPC+productividad (propuesta en discusión) reduciría incertidumbre.
- **No hay "expulsión masiva"**: informalidad en Chile (~27% ocupada) es estructural (cultura tributaria, fiscalización débil, costos no salariales), no solo efecto salario mínimo.

---

## 4. Root en Android propio: riesgos, garantía, base legal Chile

**Cómo (resumen técnico):**
1. **Desbloquear bootloader**: `fastboot oem unlock` / `fastboot flashing unlock` (varía fabricante; Pixel, OnePlus, Motorola fáciles; Samsung requiere "OEM Unlock" en opciones desarrollador + espera 7 días; Xiaomi solicita cuenta Mi + espera).
2. **Flashear imagen de recovery modificada** (TWRP) o **boot parcheado** (Magisk): `fastboot flash boot magisk_patched.img`.
3. **Instalar Magisk Manager** → gestión root systemless (oculta root a apps bancarias/SafetyNet/Play Integrity).

**Riesgos:**
- **Brick** (bloqueo permanente) si flasheas imagen incorrecta o interrumpes proceso.
- **Pérdida de datos**: desbloqueo bootloader borra todo (factory reset obligatorio).
- **Seguridad**: root expone superficie de ataque; malware con root = control total. Magisk mitiga con "deny list" y ocultamiento, pero no elimina riesgo.
- **Actualizaciones OTA**: fallan con bootloader desbloqueado/root; requieren flasheo manual cada mes.
- **Apps sensibles**: bancarias, Netflix, juegos (Pokémon GO, etc.) detectan root y bloquean; cat-and-mouse constante (Zygisk + Shamiko + Play Integrity Fix).

**Garantía (Chile):**
- **Ley 19.496 (LPC) Art. 3 bis**: proveedor no puede condicionar garantía a uso de software original **si el defecto no fue causado por la modificación**.
- **Práctica real**: servicios técnicos (Samsung, Xiaomi, Motorola Chile) **rechazan garantía por hardware** (pantalla, placa base, batería) si detectan bootloader desbloqueado/root, arguyendo "alteración software causó falla". Usuario debe litigar (SERNAC, Juzgado Policía Local) para hacer valer Art. 3 bis; costoso y lento.
- **Re-lock bootloader + stock ROM** antes de llevar a servicio técnico: práctica común para preservar garantía "de facto".

**Base legal Chile:**
- **Legal**: no hay ley que prohíba modificar software de dispositivo propio. Propiedad (Art. 19 N°24 Constitución) + ley de delitos informáticos (Ley 19.223) sanciona acceso *no autorizado* a sistemas ajenos, no propio.
- **Excepción**: eludir medidas de protección tecnológica (DRM) para fines ilícitos (Ley 17.336 Art. 74 quinquies, mod. Ley 20.435) — root *per se* no infringe, pero usarlo para piratería sí.

---

## 5. Ripear DVD propio para uso personal: cómo y legalidad Chile

**Cómo (Linux/macOS/Windows):**
1. **Instalar**: `libdvdcss` (descifra CSS), `MakeMKV` (GUI, gratis en beta perpetua) o `HandBrake` (codifica a MP4/MKV) + `libdvdcss.dll` en Windows.
2. **Proceso MakeMKV**: Abrir → seleccionar unidad → elegir títulos (película principal) → "Make MKV" → archivo `.mkv` sin recomprimir (tamaño original ~4-8 GB).
3. **Proceso HandBrake**: Abrir fuente DVD → escanear → elegir preset "Fast 1080p30" o "HQ 1080p30" → codificar a MP4 (H.264/H.265, ~1-3 GB).
4. **DVD con protección estructural (ARccOS, RipGuard)**: MakeMKV la maneja bien; HandBrake puede fallar → usar MakeMKV primero → HandBrake para comprimir.

**Legalidad Chile (Ley 17.336 Propiedad Intelectual):**
- **Art. 71 letra q**: "reproducción de una obra... para uso exclusivamente personal del copista, sin fines de lucro" → **excepción de copia privada**.
- **Art. 74 quinquies**: prohíbe eludir "medidas tecnológicas de protección" (CSS es una). **Conflicto**: copiar para uso personal está permitido (Art. 71 q), pero *romper el cifrado* para hacerlo está prohibido (Art. 74 quinquies).
- **Jurisprudencia/doctrina**: mayoría sostiene que **Art. 74 quinquies prevalece** — no hay excepción para elusión de DRM aunque el fin sea copia privada permitida. Sin embargo, **no hay persecución penal ni civil contra usuarios finales** por ripeo personal; foco está en distribución de herramientas de elusión (ej. `libdvdcss` en repositorios chilenos: zona gris).
- **Práctica**: ripear DVD propio para ver en tablet/NAS es **tolerado socialmente y sin riesgo real**, pero técnicamente infringe Art. 74 quinquies. No hay casos sancionados en Chile.

---

## 6. Ad-blockers: funcionamiento y legalidad

**Cómo funcionan (capas):**
1. **Listas de filtros** (EasyList, EasyPrivacy, uBlock filters): reglas de bloqueo (`||googlesyndication.com^`) y ocultamiento (`##.ad-banner`).
2. **Motor de filtrado de red** (uBlock Origin, AdGuard): intercepta peticiones HTTP/HTTPS *antes* de que salgan del navegador (API `webRequest` / `declarativeNetRequest` en Manifest V3). Bloquea dominio/URL coincidente → petición nunca se envía → ahorra ancho de banda, acelera carga, evita tracking.
3. **Filtrado cosmético (CSS/JS)**: inyecta hojas de estilo (`display: none !important`) para ocultar elementos que ya cargaron (anti-adblock walls, espacios en blanco).
4. **Scriptlets / redirect rules**: ejecutan JS en contexto de página para neutralizar anti-adblock, redirigir peticiones a versión limpia (ej. `redirect-rule = ||example.com/ads.js$script,redirect:noop.js`).
5. **DNS-level** (NextDNS, AdGuard DNS, Pi-hole): bloquea en resolución DNS → funciona en toda la red/dispositivo, apps incluidas, pero menos granular (no ve ruta completa URL por HTTPS).

**Legalidad:**
- **Global**: **legal** en casi todas las jurisdicciones (EE. UU., UE, LatAm). Considerado ejercicio de derecho usuario a controlar su navegador/equipo (propiedad, autonomía digital).
- **Chile**: **legal**. No hay ley que obligue a consumir publicidad. Ley 19.496 (LPC) Art. 3 bis: proveedor no puede imponer condiciones abusivas; forzar visualización de ads podría considerarse cláusula abusiva.
- **Casos frontera**:
  - **Anti-adblock walls** (ej. "desactive bloqueador para ver contenido"): legal que sitio condicione acceso; legal que usuario use bloqueador que los evada (circular).
  - **Contratos de servicio** (YouTube Premium, Twitch Turbo): pagar por "sin ads" es contractual; bloqueador gratis no viola TOS (TOS prohíben modificación *client-side* en algunos casos, pero inaplicable penalmente).
  - **Manifest V3 (Chrome)**: Google restringe `webRequest` bloqueante → uBlock Origin Lite usa `declarativeNetRequest` (menos potente). Firefox mantiene `webRequest` completo. **No es ilegal**, es decisión de plataforma.

---

## 7. Grabar conversación propia en Chile: legalidad y valor probatorio

**Legalidad (Código Procesal Penal Art. 222 + jurisprudencia):**
- **Legal** grabar (audio/video) conversación **en la que participas** (parte interviniente). No requiere consentimiento de los otros interlocutores.
- **Ilegal** grabar conversación **ajena** en la que no participas (interceptación de comunicaciones privadas, Art. 161-A CPP, pena: presidio menor en grado medio a máximo).
- **Excepción**: si hay **expectativa razonable de privacidad** y la grabación se usa para fines ilícitos (chantaje, extorsión), puede configurar delito (Art. 161-A o 246 CP).
- **Lugares públicos**: menor expectativa de privacidad; grabar legal.
- **Lugares privados** (casa ajena, oficina cerrada): legal si participas, pero uso posterior puede vulnerar ley de protección de datos (Ley 19.628) si difundes sin consentimiento.

**Valor probatorio:**
| Ámbito | Valor |
|--------|-------|
| **Penal** | Prueba **lícita y válida** (STC Rol 15.841-2019: "quien participa en conversación puede grabarla y aportarla como prueba"). Juez valora libremente (sana crítica). |
| **Civil** | Prueba **lícita** (Art. 384 CPC: "todos los medios de prueba..."). Corte Suprema (Rol 18.456-2018): admite grabaciones de partícipe. |
| **Laboral** | **Admisible** (DT Ord. 1140/2019: "grabación realizada por trabajador en conversación que sostiene con empleador es medio de prueba válido"). Clave en despidos, acoso, incumplimientos. |
| **Familia** | Admisible (violencia intrafamiliar, custodia), pero juez pondera interés superior niño y derecho intimidad. |

**Requisitos para máximo valor:**
1. **Integridad**: archivo original sin editar (hash SHA-256, cadena de custodia).
2. **Identificación**: voces claras, contexto temporal/espacial (metadatos EXIF, timestamps).
3. **Relevancia**: contenido pertinente a hechos controvertidos.
4. **No coacción**: no inducir declaraciones con engaño/amenaza (podría anularse por vicio de consentimiento).

---

## 8. Verificar cotizaciones previsionales pagadas por empleador: paso a paso

**Vía oficial (gratuita, vinculante):**

1. **Certificado de Cotizaciones AFP en línea** (más directo):
   - Ir a **www.spensiones.cl** → "Certificados" → "Certificado de Cotizaciones".
   - ClaveÚnica o clave AFP → selecciona AFP → período (máx. 5 años) → genera PDF con sello electrónico.
   - **Muestra**: mes, monto imponible, cotización obligatoria (10% + 1,47% SIS), cotización voluntaria (APV), días cotizados, empleador (RUT, razón social).

2. **Certificado de Cotizaciones Previsionales (IPS/ChileAtiende)**:
   - **www.chileatiende.gob.cl** → "Certificados" → "Cotizaciones Previsionales".
   - ClaveÚnica → PDF con historial **todas las AFP + IPS (ex INP) + Salud (Fonasa/Isapre)**.
   - Útil si cambiaste de AFP o tienes lagunas.

3. **App "Mi AFP" / sitio web AFP** (Habitat, Provida, Modelo, Cuprum, Capital, Uno, Planvital):
   - Ingresa con clave AFP → "Mis Cotizaciones" / "Detalle de Pagos".
   - Ver mes a mes: fecha pago, monto, empleador. Permite alertar si falta mes.

4. **SUSESO (Seguro de Cesantía - AFC)**:
   - **www.afc.cl** → "Mis Cotizaciones" → verifica 0,6% (empleador) + 0,2% (trabajador) o 1,6% (contrato plazo fijo).

**Si detectas deuda (empleador no paga):**
1. **Reclamo en DT (Dirección del Trabajo)**:
   - **www.dt.gob.cl** → "Denuncias y Reclamos" → "Reclamo por No Pago de Cotizaciones".
   - Requiere: RUT empleador, período adeudado, certificado AFP que acredite deuda.
   - DT fiscaliza, notifica empleador, puede cursar multa (1-60 UTM) y oficiar a AFP para cobro judicial.

2. **Cobro judicial AFP** (Art. 23 D.L. 3.500):
   - AFP **debe** demandar al empleador moroso (mandato legal).
   - Solicita a tu AFP "iniciar cobro judicial" (escrito simple). AFP tiene 90 días para demandar desde que detecta mora.
   - Tú no pagas abogado; AFP cobra honorarios al empleador deudor.

3. **Autodenuncia en Tribunal de Cobranza Laboral y Previsional** (Ley 20.720):
   - Si AFP no demanda en 90 días, **tú puedes demandar directamente** al empleador.
   - Gratuito, sin abogado obligatorio (monto ≤ 60 UTM ≈ $4M). Formulario en **www.pjud.cl** → "Tribunales de Cobranza".

**Plazos clave**: cotizaciones se pagan **mes vencido** (ej. enero se paga en febrero). Mora = no pago al último día hábil mes siguiente. Prescripción: **5 años** (Art. 23 D.L. 3.500).

---

## 9. Derechos consumidor compra online Chile: producto no llegó

**Marco legal:** Ley 19.496 (LPC) + Ley 21.081 (Pro Consumidor, 2022) + DFL 3/2021 (Reglamento Comercio Electrónico).

**Derechos y pasos:**

| Derecho | Qué implica | Plazo / Acción |
|---------|-------------|----------------|
| **Información veraz y oportuna** (Art. 3 bis, 12 ter LPC) | Vendedor debe informar stock, plazo entrega, costo envío **antes** de pagar. | Si no informó plazo → **entrega en 30 días** (Art. 12 ter). |
| **Derecho a retracto** (Art. 3 bis bis LPC) | **10 días** desde recepción para arrepentirse **sin causa** (salvo excepciones: bienes perecibles, personalizados, sellados abiertos, servicios iniciados con consentimiento). | Notificar por escrito (email, formulario web). Vendedor tiene **15 días** para devolver dinero **incluyendo envío ida**. |
| **Garantía legal 6 meses** (Art. 21 LPC) | Si producto **llega defectuoso, incompleto o no llega**, elige: **reparación, cambio o devolución dinero**. | Plazo: **6 meses** desde recepción (o desde que debió recibirse). |
| **Incumplimiento entrega** (Art. 12 ter, 23 LPC) | Si no llega en plazo informado (o 30 días por defecto): **exigir cumplimiento O resolver contrato + devolución íntegra + indemnización perjuicios**. | Carta certificada / notificación fehaciente → 48 hrs para cumplir → si no, demanda. |
| **Protección datos / cargos no reconocidos** (Ley 19.628, Art. 50 LPC) | Si pagaste y no llegó: **reversar cargo** (chargeback) con banco emisor tarjeta. | Plazo banco:通常 30-120 días desde cargo. Presenta comprobante compra + reclamo vendedor. |

**Procedimiento práctico:**
1. **Revisa correo spam / cuenta en sitio**: número de seguimiento, estado "entregado" (falso positivo común).
2. **Reclamo formal al vendedor** (escrito, guardando prueba): exige entrega en 48 hrs o devolución dinero + envío.
3. **Si vendedor no responde en 48 hrs / rechaza**:
   - **SERNAC**: reclamo en **www.sernac.cl** (gratis, mediación). Empresas adheridas a "Compromiso SERNAC" responden en 5 días.
   - **Chargeback** con tu banco (tarjeta crédito/débito): "mercancía no recibida". Banco investiga y reembolsa si vendedor no prueba entrega.
   - **Juzgado de Policía Local** (Art. 25 LPC): demanda hasta **100 UTM** (~$6,8M) sin abogado. Notificación por correo certificado.
4. **Marketplace (MercadoLibre, Falabella, Paris, Amazon)**: usa su **protección al comprador** (plazos 10-30 días). Congelan pago al vendedor hasta que confirmas recepción.

**Claves:**
- **Guarda todo**: capturas pantalla (precio, stock, plazo), comprobante pago, emails, chats.
- **No aceptes "reembolso en crédito tienda"** si pagaste con dinero: derecho es a **devolución en mismo medio de pago** (Art. 23 LPC).
- **Envío gratis por ley** en retracto: vendedor paga ida y vuelta (Art. 3 bis bis).
- **Empresas extranjeras** (AliExpress, Shein, Amazon.com): aplican sus políticas, pero SERNAC puede mediar si tienen representación en Chile; chargeback sigue funcionando.

---

## 10. Cambiar firmware router propio (OpenWrt): legalidad y qué se pierde

**Legalidad Chile:**
- **Totalmente legal**. Router es **bien mueble de tu propiedad** (Art. 567 CC, Art. 19 N°24 CPR). Modificar su software no infringe ley de propiedad intelectual (Ley 17.336) porque:
  - No copias/distribuyes firmware propietario (OpenWrt es GPL, código abierto).
  - No eludes medidas de protección para acceder a servicio de pago (el router ya es tuyo).
- **Excepción**: si router es **en comodato/arriendo de ISP** (ej. ONT/ONU de Movistar, Entel, VTR, Claro), **no es tuyo**. Cambiar firmware = daño a bien ajeno + posible violación TOS contrato ISP. Verifica: ¿pagaste el router o te lo "prestaron"? Factura / contrato lo aclara.

**Qué se gana (OpenWrt):**
- Control total: firewall avanzado (nftables/iptables), VLANs, QoS/SQM (bufferbloat), VPN (WireGuard, OpenVPN), servidor DNS (AdGuard Home, Pi-hole), DNSCrypt/DoH/DoT, políticas de routing, malla (802.11s), estadísticas detalladas (Prometheus/Grafana).
- Actualizaciones de seguridad **años después** que vendor deje de soportar (ej. routers 2015 aún reciben kernels 6.x).
- Paquetes 6000+ (opkg): Samba, Docker (si RAM/flash), Tor, Zerotier, FRR (BGP/OSPF), etc.
- Privacidad: sin telemetría vendor, sin backdoors conocidos (ej. CSP, TR-069/ACS desactivado).

**Qué se pierde / riesgos:**
| Aspecto | Detalle |
|---------|---------|
| **Garantía vendor** | **Pierdes garantía** (incluso si router es tuyo). Vendors (TP-Link, ASUS, Netgear, Xiaomi, GL.iNet) anulan garantía por firmware no oficial. GL.iNet es excepción: venden *con* OpenWrt y mantienen garantía. |
| **Funciones propietarias** | - **Hardware acceleration** (NAT/flow offloading): en MediaTek/Qualcomm Atheros funciona bien; en Broadcom **no** (drivers cerrados) → throughput WAN-LAN cae 30-50% en gigabit+. <br> - **WiFi 6/6E/7 (802.11ax/be)**: soporte **limitado/inestable** en mt76 (MediaTek) y ath11k (Qualcomm); Broadcom **sin soporte**. Rendimiento WiFi suele ser inferior a firmware stock. <br> - **DSL/GPON/VoIP**: si router es modem-router integrado (VDSL, GPON), **pierdes conexión WAN** (drivers cerrados, certificados ONT). OpenWrt sirve solo como router *detrás* de ONT en modo bridge. |
| **Complejidad / brick** | - Proceso instalación varía: algunos requieren abrir router, soldar UART, TFTP recovery. <br> - **Brick suave** (recovery mode) común; **brick duro** (bootloader corrupto) = papelera. <br> - Configuración red desde cero: VLANs WAN/LAN, PPPoE, DHCP, firewall, WiFi. No hay "asistente configuración ISP". |
| **Soporte ISP** | ISP **no dará soporte** si usas router propio. Si falla internet, te dirán "conecte router original". Debes saber diagnosticar: PPPoE credentials (usuario/contraseña ISP), VLAN ID (Chile: VTR=100, Movistar=6, Entel=10, Claro=100, Mundo=100, GTD=100), IPv6 (DHCPv6-PD). |
| **Estabilidad** | Builds snapshot (diarias) pueden romper cosas. Usa **releases estables** (23.05, 24.10). LuCI (web UI) ayuda pero no cubre todo; CLI (uci, /etc/config/) inevitable. |

**Resumen decisión:**
| Tu caso | Recomendación |
|---------|---------------|
| Router **propio**, solo router (no modem), WiFi no crítico, quieres control/privacidad/actualizaciones largas | **Sí, OpenWrt excelente**. Hardware recomendado: MediaTek Filogic 820/830 (Banana Pi BPI-R3/R4, GL.iNet Flint 2, Xiaomi AX3000T), Qualcomm IPQ807x (GL.iNet MT6000). |
| Router **en comodato ISP** | **No**. Compra router propio compatible y pon ISP en modo bridge. |
| Necesitas **WiFi 6/7 máximo rendimiento**, VoIP ISP, DSL/GPON integrado | **No**. Usa firmware stock o router vendor con OpenWrt *solo* como AP (dumb AP). |
| Principiante, sin tiempo para CLI/troubleshooting | **No**. Considera Asuswrt-Merlin (ASUS), FreshTomato (Broadcom antiguo), o GL.iNet (OpenWrt preinstalado con GUI amigable). |
