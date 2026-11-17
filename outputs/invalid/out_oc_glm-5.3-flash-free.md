# Respuestas

## 1. Piñera vs. Boric (economía)

**Crecimiento del PIB real (promedio del mandato):**
- Piñera I (2010–2014): ~5,4% — ayuda de base baja post-crisis 2009 y superciclo del cobre.
- Piñera II (2018–2022): ~2,4–2,5% — con trayectoria muy irregular: 4,0% (2018), 2,3% (2019, estallido), −6,1% (2020, pandemia) y 11,3% (2021), impulsado por los retiros de fondos previsionales (US$ ~50 mil millones) y estímulo fiscal récord, no por productividad.
- Boric (2022–2026): ~2,0% en promedio (2,2%, 0,5%, 2,6%, 2,5%) — el segundo más bajo desde 1990; se heredó un ajuste tras el boom 2021 y una sequía cíclica del cobre.

**Inflación (promedio del período):** Piñera I ~2,5%; Piñera II ~3,3%, aunque terminó con espiral: 2022 cerró en 12,8% por los retiros y el estímulo de 2021. Boric: ~6,8% promedio, peak de 14,1% (ago-2022), descendiendo a ~4–5% en 2023–2025, con la política monetaria del BC (fuera del control del Ejecutivo) logrando la convergencia.

**Desigualdad (Gini ingresos monetarios, Casen):** 2017: 0,484 → 2020: 0,509 (peak tras estallido/pandemia) → 2022: 0,470, el mejor de la serie, gracias a subsidios monetarios (~80% reales sobre 2017) y la Pensión Garantizada Universal; la desigualdad del ingreso autónomo (mercado) bajó menos. Pobreza: 10,2% (2020) → 6,5% (2022).

**Conclusión objetiva:** en crecimiento e inflación el desempeño promedio de Piñera fue mejor, pero la comparación está contaminada por choques asimétricos (pandemia, retiros, ciclo del cobre) y por la concentración de la inflación de 2022 en políticas de fines de 2021. En distribución, la mejora es reciente (2022 en adelante) y proviene sobre todo de transferencias, presentes en ambos períodos.

## 2. Despenalización del aborto en Chile (~120 palabras)

**A favor:** la penalización no elimina el aborto, lo empuja a la clandestinidad y golpea más a mujeres pobres; los derechos sexuales y reproductivos son parte de la autonomía y igualdad de la mujer (art. 19 CPE); Chile ya despenalizó las 3 causales (Ley 21.030, 2017) sin efectos sanitarios negativos; el fallo de la Corte Interamericana en *Manuela* (2021) constató criminalización ilegítima; mayor acceso reduce mortalidad materna y hospitalizaciones por abortos incompletos.

**En contra:** el nasciturus tiene protección constitucional (art. 19 N°1) y derecho a la vida; el Estado no puede equiparar su protección a una elección privada; existen causales ya legisladas que resuelven los casos más graves (riesgo de vida, violación, inviabilidad); puede facilitar la eugenesia por discapacidad o sexo; y Chile votó democráticamente mantener la protección en 1980 y en el proceso constitucional 2022–2023.

## 3. Sueldo mínimo: ¿protege o expulsa trabajo informal?

La evidencia chilena (informes de la Comisión de Expertos de Hacienda, estudios de Núñez, Marcel, Dattler y otros, sobre los alzas de 2008–2010 y la gran reforma de 2019–2024) apunta a **matices, no a un binomio**:

- **Alzas moderadas y graduales:** efectos estadísticamente pequeños sobre el empleo total; el mecanismo principal de ajuste ha sido salarios (compresión salarial), no despidos masivos. En Chile formal con bienes transables, las empresas absorben gran parte vía precios/márgenes.
- **Riesgo real en los extremos:** varios estudios encuentran efectos negativos concentrados en **trabajadores de baja productividad (jóvenes, mujeres, menores calificaciones), microempresas y zonas de bajos salarios**. Si el mínimo supera ~50–60% del salario mediano, el riesgo de expulsión hacia la informalidad o el desempleo aumenta.
- **Efecto de formalización ambivalente:** alzas pueden incitar a empresas a formalizar (regularizar para justificar el salario), pero también a trasladar trabajadores a boletas o a la evasión, donde la fiscalización es débil.
- **Fiscalización es clave:** el efecto sobre la informalidad depende de cuánto se persigue la evasión; sin fiscalización, el alza se evade.

**Síntesis:** el mínimo protege el poder de compra de quienes conservan el empleo formal; el riesgo de expulsión es real pero acotado si las alzas son graduales, moderadas y acompañadas de fiscalización — como hizo Chile, que además redujo el costo no salarial (bonos, imputación proporcional de cotizaciones) para amortiguar el efecto.

## 4. Root en tu propio Android (Chile)

**Cómo se hace (resumen):** desbloquear el bootloader (vía `fastboot oem unlock` / comando del fabricante, con pérdida de datos), instalar una recuperación personalizada o flashear Magisk parcheando `boot.img` desde la app, y reiniciar. El método exacto varía por marca (Xiaomi, Motorola y Pixel son amigables; Samsung tiene Knox que salta al desbloquear; Huawei lo bloqueó por completo).

**Riesgos:** anulas funciones de seguridad (Attestation básica → falsa), apps bancarias/Netflix/streaming dejan de funcionar, riesgo de "brick" si flasheas mal la partición, pérdida de actualizaciones OTA oficiales, y exposición a malware si instalas root sin saber qué concedes.

**Garantía:** la Ley 19.496 (art. 6 bis) da garantía legal de 3 años en productos de consumo, pero **solo cubre defectos de fabricación**; si el defecto se debe al uso indebido (y una modificación fallida del sistema cuenta como tal), el vendedor puede negar la reparación. Además, Knox/eFuse de Samsung registra el desbloqueo de forma permanente e irrevocable — no hay forma de "volver atrás" garantía.

**Base legal:** no existe ley que prohíba rootear tu propio dispositivo: el derecho de propiedad (art. 583 y 925 Código Civil) te permite modificar tu bien. Chile no tiene una "Digital Millennium Copyright Act" general: la Ley 17.336 (reformada por la 20.353) sanciona el **circumvention de medidas de protección** en obras protegidas, pero modificar el firmware del sistema operativo de tu teléfono no vulnera copyright de obras. Tampoco vulnera el derecho a la intimidad de otros. **Legal: sí. Garantía: probablemente perdida para defectos de software.**

## 5. Rippear un DVD comprado (Chile)

**Técnicamente:** usa MakeMKV o HandBrake (con libdvdcss). MakeMKV extrae el VOB sin recomprimir (calidad máxima, ~5–8 GB); HandBrake con libdvdcss habilitada convierte a MP4/MKV comprimido (~1–2 GB). Ambos requieren instalar libdvdcss (en Ubuntu: repositorio de VideoLAN; en macOS/Windows: incluido o via VLC).

**Legalidad chilena — zona gris hacia lo ilegal:**
- La Ley 17.336, reformada por la 20.353 (2011), incorpora el **derecho de copia privada de seguridad** (art. 71 bis) pero **solo para software**, no generalizada para obras audiovisuales.
- El **art. 80 bis** penaliza el *circumvention* de medidas tecnológicas de protección — los **CSS/DRM de los DVDs comerciales son exactamente eso**, por lo que romperlos para copiar la película está técnicamente en el ámbito del delito, aunque no hay jurisprudencia ni persecución en casos de copia doméstica sin distribución.
- Si el DVD no tiene DRM (raro, solo publicaciones antiguas o domésticas), copiarlo para uso personal sería compatible con la excepción de cita/uso privado (art. 38 Ley 17.336) y el criterio de los tres pasos de Berne.

**Conclusión práctica:** ripping de un DVD con DRM en Chile es **legalmente arriesgado pero socialmente tolerado**; la venta, distribución o puesta online de la copia sí es claramente ilegal. Usa la copia solo para tus dispositivos, nunca la compartas.

## 6. Ad-blockers

**Cómo funcionan:** interceptan las peticiones de red del navegador (a nivel de extensión — `webRequest`/`declarativeNetRequest` — o de DNS/proxy) y comparan cada URL/patrón contra listas de filtros (EasyList, EasyPrivacy, uBlock Origin, AdGuard) que identifican dominios de servidores de anuncios, trackers y scripts de fingerprinting. Los que bloquean por DNS (AdGuard DNS, Pi-hole) operan a nivel de red, resolviendo dominios de publicidad a 0.0.0.0. Los más completos además usan reglas cosméticas (CSS) para ocultar huecos dejados por el anuncio bloqueado.

**Legalidad:** usarlos es **legal en Chile y en prácticamente todo el mundo**; ninguna ley lo prohíbe, y no vulneran el derecho de autor — bloquean un recurso, no copian una obra. Los tribunales europeos (caso *Axel Springer vs. Eyeo*, Alemania 2015–2016) confirmaron su legalidad: el usuario es libre de filtrar lo que llega a su navegador. El matiz: **violan los términos de servicio de algunos sitios**, que pueden pedirte desactivar el bloqueo o negarte el acceso; eso es un asunto contractual, no criminal. Sitios con micropagos o "adblock-wall" son la respuesta de mercado, no una sanción legal.

## 7. Grabar una conversación en la que participas (Chile)

**Legalidad:** es **legal si tú eres participante de la conversación**. El delito de la Ley 19.224 (art. 161-A y 161-B del Código Penal, modificado en 2005) sanciona a quien graba o interviene una comunicación **privada de terceros sin autorización** — el "pinche telefónico" o el micrófono oculto de dos personas ajenas. La jurisprudencia de la Corte Suprema ha sostenido consistentemente que quien participa de la conversación puede registrarla: no hay expectativa razonable de intimidad frente a la persona que está conversando contigo (criterio de la "una de las partes", similar al estándar de EEUU y la CEDH).

**Valor probatorio:**
- **Es admisible** como prueba en procesos civiles, laborales y penales (Corte Suprema lo ha reiterado, p.ej. en abusos laborales y acoso), salvo que se pruebe que fue obtenida con violación del art. 161-A/B o de garantías constitucionales (regla de exclusión del art. 275 del Código Procesal Penal en sede penal).
- Su **fuerza probatoria depende de**: autenticidad (cadena de custodia, audio íntegro sin edición — los magistrados desconfían de fragmentos), identificación de las voces, y que se pueda corroborar con otros antecedentes. Un audio solitario tiene valor "indicativo"; con testigos, fechas y contexto se convierte en prueba potente.
- **Uso de un tercero ajenísimo a la conversación** (grabar la conversación de otros sin participar) — eso sí es delito (art. 161-A) y la prueba resultante es nula.

**Conclusión:** grábate sin problema; entrega el audio completo y sin editar al tribunal o la autoridad; no lo uses para chantajear (eso sí es delito, art. 371 CP).

## 8. Verificar que el empleador pague tus cotizaciones (paso a paso)

1. **Entra a www.prevision.cl** (Subsecretaría de Previsión Social) o **www.previred.cl**. Necesitas tu RUT y clave (ClaveÚnica en ChileAtiende, o clave previsional).
2. **Consulta de afiliado:** en prevision.cl busca "Consulta cotizaciones previsionales" (o en Previred, "Consulta de cotizaciones"). Ingresa tu RUT y período.
3. **Lee el detalle por mes:** verás la remuneración imponible declarada, fecha de pago a la AFP, y si está **pagada, pendiente o en mora** (con el empleador identificado por RUT). El sistema muestra los últimos 24 meses aprox.
4. **Alternativa:** llama a tu AFP y pide estado de cotizaciones, o revisa la Cartola Digital de tu AFP (disponible en la web de la AFP con clave).
5. **Si hay mora:** el proceso formal es:
   - La **AFP informalmente persigue** al empleador (aviso de mora, intimación, embargo de bienes si es necesario) durante un plazo de ~90 días.
   - Si no paga, la AFP o tú pueden demandar ante el **Tribunal de los Servicios de Previsión Social (TSPS)** o ante la Inspección del Trabajo para reclamar también las remuneraciones adeudadas (art. 61, 95 y 163 del Código del Trabajo).
   - Paralelamente, la demanda por **despido indirecto** (art. 171 CT) es una opción si la mora es grave y reiterada: pone término al contrato con indemnización completa.
6. **Comprueba además** que el empleador esté cotizando **salud (Fonasa/Isapre), SUSESO/accidentes y seguro de cesantía** — la misma consulta de prevision.cl muestra salud; el seguro de cesantía se ve en la AFC.

## 9. Compra online: producto no llegó (Chile)

La Ley 19.496 (reformada por la Ley 21.295, vigente desde dic. 2021) te da derechos específicos:

1. **Plazo de envío:** el vendedor está **obligado a entregar en el plazo informado** (art. 3 bis); si no informó plazo, el máximo legal es **10 días** desde la compra. El incumplimiento te permite **desistir del contrato y exigir la devolución total** (incluyendo gastos de envío) sin justificar motivo.
2. **Derecho de retracto:** en ventas online tienes **10 días** para retractarte (30 días si no te informaron el plazo de retracto, o el derecho a devolver). No aplican a productos personalizados, perecibles o descargados digitalmente, entre otros.
3. **Pasos concretos:**
   - Contacta al vendedor exigiendo el envío o la devolución (deja registro escrito: correo, chat, plataforma).
   - Si no responde en un plazo razonable, **reclama en SERNAC** (www.sernac.cl o app "SERNAC en Línea") — las empresas están obligadas a responder; el sistema de conciliación es gratuito y rápido.
   - Reclama también a la **plataforma** (Mercado Libre, Amazon, Falabella) — tienen mecanismos de devolución garantizada y pueden reembolsar sin el vendedor.
   - Si pagaste con **tarjeta**, pide una **contracargo (chargeback)** al banco emisor: en Chile el reembolso por producto no recibido es procedente y el banco puede descontar del comercio.
   - Si hay estafa deliberada (tomaron el dinero sabiendo que no enviarían), **denuncia a Fiscalía** (estafa, art. 468 CP).
4. Si el reclamo de SERNAC fracasa, puedes demandar en el **Juzgado de Policía Local** (procedimiento gratuito, sin abogado para montos bajos) o en mediación/juzgado civil según monto.

## 10. Cambiar el firmware del router propio (OpenWrt)

**Legalidad: sí, es legal en Chile** si el hardware es tuyo (comprado, no en arriendo del ISP). El router es un bien mueble de tu propiedad (art. 573 y ss. Código Civil); modificar su firmware es ejercicio del derecho de propiedad. OpenWrt es software libre GPL — instalarlo no infringe copyright (es su licencia misma). **No hay "Ley anti-circumvention" chilena** que lo impida (la Ley 20.435 reforma audiovisual no aplica a routers). Los ISP a veces lo **desaconsejan en sus ToS**, pero eso no es ley; el router "propio" no está bajo su dominio. El único límite: no uses el router para actividades ilegales (peering no autorizado, circuito cerrado de televisión pirata, etc.).

**Qué se pierde:**
- **Garantía del fabricante** (flasheo invalida la garantía — y se registra, Knox-style, en algunos routers).
- **Soporte del ISP:** si el router es el de la compañía (arriendo o entregado), tocarlo puede violar el contrato y negarte asistencia técnica.
- **Funciones propietarias del fabricante:** VoIP del ISP (teléfono fijo por fibra), IPTV (decodificadores), mesh propietario (Eero, AmpliFi), apps móviles de configuración, control parental de marca, aceleraciones específicas (WPA3 en algunos chipsets no soportados, DFS en algunos radios), detección de intrusos tipo Router Security de TP-Link/ASUS.
- **Riesgo de brickeo:** una versión incorrecta puede dejar el router inutilizable (aunque muchos tienen TFTP/recovery).
- **Rendimiento en hardware de gama alta:** los firmwares propietarios a veces optimizan NAT/aceleración hardware (offloading) mejor que OpenWrt, aunque OpenWrt compensa con QoS/SQM (CAKE) superior.

**Qué se gana (para ser justo):** actualizaciones de seguridad para routers que el fabricante abandonó, control total (VPN, VLAN, QoS, bloqueo DNS, wireguard, ad-blocking a nivel de red con Pi-hole integrado) y elimina el backdoor/telemetría de algunas marcas.
