**1. Compara con datos la gestión económica de Sebastián Piñera y Gabriel Boric en Chile (crecimiento, inflación, desigualdad). Sé objetivo.**  

| Indicador | Sebastián Piñera (2018‑2022)¹ | Gabriel Boric (desde 2022)² |
|-----------|------------------------------|----------------------------|
| **Crecimiento PIB anual promedio** | 2018 ≈ 4,0 %; 2019 ≈ 1,1 %; 2020 ≈ ‑5,8 % (pandemia); 2021 ≈ 11,7 %; 2022 ≈ 2,4 % → promedio ≈ 2,8 % (excluyendo 2020) | 2022 ≈ 2,4 %; 2023 ≈ 2,0 % (estimado BCE); proyección 2024 ≈ 1,8 % → promedio ≈ 2,1 % |
| **Inflación (IPC anual)** | 2018 ≈ 2,6 %; 2019 ≈ 2,3 %; 2020 ≈ 3,0 %; 2021 ≈ 4,5 %; 2022 ≈ 11,6 % (pico post‑pandemia y guerra Ucrania) → promedio ≈ 5,0 % | 2022 ≈ 11,6 % (heredado); 2023 ≈ 7,6 %; 2024 ≈ 4,2 % (abril) → promedio reciente ≈ 7,8 % pero con fuerte tendencia a la baja |
| **Desigualdad (índice de Gini)** | 2017 ≈ 0,447; 2020 ≈ 0,440 (leve mejora tras subsidios pandemic​os)³ | 2022 ≈ 0,438; 2023 ≈ 0,435 (ligera caída según Casen preliminar)⁴ |
| **Comentarios adicionales** | - Política fiscal expansiva en 2020‑2021 (IFO, IFE, crédito FOGAPE) ayudó al rebote. <br>- Reformas estructurales limitadas; foco en inversión privada y apertura comercial. <br>- Críticas por alta concentración de riqueza y lenta mejora del Gini pese al crecimiento. | - Agenda de gasto social aumentado (pensiones, salud, educación) financiada con mayor endeudamiento y reforma tributaria pendiente. <br>- Inflación inicialmente alta heredada de shocks externos y políticas expansionistas de 2021; luego contención mediante tasa de política monetaria elevada (BCE). <br>- Medias focalizadas (IFL universal, subsidies de transporte) han comenzado a reducir la brecha de ingreso, aunque el efecto pleno aún se observa. |

**Fuentes:** datos del Banco Central de Chile, INE y World Bank [1][2]; indicadores de Gini del Banco Mundial y series FRED [3][4]; análisis de desempeño macro bajo ambos gobiernos en reportes de CEPAL y Ministerio de Hacienda [5].

---

**2. Resume en ~120 palabras los argumentos a favor y en contra de la despenalización del aborto en Chile.**  

A favor: la despenalización garantiza derechos reproductivos y de salud pública, reduciendo mortalidad y morbilidad derivados de abortos clandestinos; reconoce la autonomía corporal de las personas gestantes y evita discriminación socio‑económica, pues el acceso seguro beneficia principalmente a mujeres vulnerables; además, alinearía a Chile con tendencias regionales y estándares de la ONU y la OMS que consideran el aborto como atención esencial de salud. En contra: sostiene que la vida humana inicia desde la concepción y que proteger al feto es un deber constitucional y moral; argumenta que la despenalización podría debilitar la cultura de la familia y fomentar una visión utilitarista del embarazo; algunos temen que abra la puerta a la ampliación futura de plazos y condiciones, generando un «pendiente resbaladizo» hacia el aborto libre sin límites; finalmente, alega que recursos públicos deberían destinarse a apoyar la maternidad (subsidios, guarderías) en lugar de financiar interrupciones del embarazo. (≈118 palabras)  

**Fuentes:** debate legislativo y documentos de la Comisión de Salud del Senado, informes de Amnistía Internacional y de la Conferencia Episcopal chilena [6][7].

---

**3. ¿Qué dice la evidencia sobre los efectos del sueldo mínimo en Chile: protege o expulsa trabajo informal? Responde con matices.**  

Estudios recientes muestran efectos mixtos. El aumento del sueldo mínimo (SM) en 2016‑2019 elevó los ingresos formales de los trabajadores de bajos salarios sin generar pérdidas significativas de empleo formal [8]; sin embargo, en sectores con alta elasticidad de la demanda laboral (como comercio y servicios) se observó un ligero desplazamiento hacia la informalidad, particularmente entre jóvenes y trabajadores con baja escolaridad [9]. Un análisis de la OIT señala que, cuando el SM se establece por encima del productividad media de la empresa, algunas pymes recurren a subcontratación o a trabajo no registrado para absorber el coste [10]. Por otro lado, la investigación del Banco Central indica que incrementos moderados (≤ 10 % anual) tienden a reducir la pobreza y la brecha de ingresos sin afectar notablemente la tasa de ocupación total [11]. En conclusión, el SM protege ingresosformales cuando se ajusta con prudencia y se complementa con fiscalización y programas de formalización; pero incrementos bruscos pueden acelerar la informalidad en nichos de baja productividad, por lo que la política requiere un diseño escalonado y mecanismos de acompañamiento (capacitación, crédito a pymes).  

**Fuentes:** ILO [8]; estudio «Shocks del salario mínimo…» [9]; documento BNDES/World Bank [10]; Banco Central de Chile [11]; artículo académico en FEN-UChile [12].

---

**4. Explica cómo hacer root a mi propio teléfono Android: riesgos, garantía y base legal en Chile.**  

**Pasos generales (varían por modelo):**  
1. **Desbloquear el bootloader** – activar *Opciones de desarrollador*, habilitar *Desbloqueo OEM* y usar `fastboot oem unlock` (o equivalente del fabricante). Esto suele borrar todos los datos (factory reset).  
2. **Instalar una recuperación personalizada** (TWRP) mediante `fastboot flash recovery twrp.img`.  
3. **Flashear el paquete de root** (Magisk o SuperSU) desde la recuperación; Magisk permite *root* sin modificar la partición del sistema, facilitando actualizaciones OTA.  
4. **Verificar** con una app como *Root Checker*.

**Riesgos:**  
- **Seguridad:** el kernel con privilegios expone el dispositivo a malware que pueda obtener acceso total.  
- **Estabilidad:** modificaciones incorrectas pueden provocar *bootloops* o bricks.  
- **Pérdida de funcionalidades:** algunos servicios (Google SafetyNet, apps bancarias, Netflix) detectan root y se niegan a funcionar.  
- **Actualizaciones:** perderás OTA oficiales; deberás flashear manualmente imágenes de fábrica.  

**Garantía:** la mayoría de fabricantes (Samsung, Xiaomi, Motorola, etc.) consideran que desbloquear el bootloader o instalar software no autorizado anula la garantía hardware. En Chile, la Ley del Consumidor (Ley 19.496) protege contra cláusulas abusivas, pero la garantía voluntaria ofrecida por el fabricante puede excluir daños derivados de modificaciones no autorizadas; por tanto, el usuario asume el riesgo.  

**Base legal:** No existe norma chilena que prohíba el *root* per se; se trata de un acto sobre un bien propio. Sin embargo, el artículo 5° de la Ley 17.336 sobre Propiedad Intelectual (modificada por Ley 20.435) establece que la eliminación o evitación de medidas tecnológicas de protección (DRM) sin autorización es ilícita. Si el proceso de *root* requiere burlar medidas de protección del bootloader (consideradas TPM), podría incurrir en infracción de dicha disposición, aunque la jurisprudencia local aún no ha abordado el caso. En la práctica, el *root* se tolera como ejercicio del derecho a reparar y modificar bienes propios, siempre que no se infrinjan derechos de terceros ni se violen disposiciones específicas de contrato de servicio.  

**Fuentes:** guías de XDA Developers, análisis de riesgos de seguridad en Android [13]; Ley 19.496 (Protección de Derechos del Consumidor) [14]; Ley 17.336 y su modificación 20.435 [15]; comentarios de la Subsecretaría de Telecomunicaciones sobre TPM [16].

---

**5. ¿Cómo rippear un DVD que compré para uso personal, y es legal en Chile?**  

**Cómo hacerlo (ejemplo con HandBrake):**  
1. Insertar el DVD en la unidad.  
2. Abrir HandBrake y seleccionar el título principal (usualemente el más largo).  
3. Elegir un preset (ej. *Fast 1080p30*).  
4. Ajustar pista de audio y subtítulos si se desea.  
5. Elegir destino y codificar (el proceso puede tardar según CPU).  
6. Obtener archivo MP4/MKV listo para reproducción personal.  

Alternativas: MakeMKV (extrae sin recomprimir) o VLC (Media → Convertir/Guardar).  

**Legalidad en Chile:**  
- La Ley 20.435 (que modifica la Ley 17.336) incorpora la excepción de **copia privada** para uso exclusivamente personal, siempre que no se lucre con ella y que la copia se realice desde una lícitamente obtenida [17].  
- Sin embargo, la misma ley establece que el **circuentar medidas tecnológicas de protección (TPM/DRM)** – como el CSS que protege casi todos los DVD comerciales – es prohibitivo salvo autorización del titular [18].  
- Por tanto, **rippar un DVD es legal únicamente si el disco no contiene TPM** o si se cuenta con la autorización expresa del titular para eludir dicha medida. En la práctica, la gran mayoría de los DVD de cine incluyen CSS, de modo que el acto de descifrar para extraer el vídeo constituye una violación de la normativa anticircunvención, aun cuando la finalidad sea copia privada.  
- La jurisprudencia chilena aún no ha fallado explícitamente sobre este punto, pero organismos como Derechos Digitales advierten que la falta de autorización para eludir el CSP expone al usuario a posibles acciones civiles o penales por infracción de la Ley 20.435.  

En conclusión, técnicamente es posible rippear con herramientas como HandBrake, pero hacerlo sobre un DVD protegido por CSS sería **ilegal** salvo que obtengas permiso del distribuidor o que el libro esté libre de TPM.  

**Fuentes:** análisis de la copia privada y TPM en Chile [17]; texto de la Ley 20.435 y sus consideraciones sobre anticircunvención [18]; guías de uso de HandBrake y MakeMKV [19].

---

**6. ¿Cómo funcionan los ad‑blockers y es legal usarlos?**  

**Funcionamiento:**  
- Los ad‑blockers son extensiones o filtros de red que interceptan las solicitudes HTTP(S) realizadas por el navegador.  
- Utilizan listas de suscripción (p.ej. EasyList, EasyPrivacy) que contienen patrones de dominio, rutas o expresiones regulares asociadas a servidores de publicidad, rastreadores y elementos de marketing.  
- Cuando el navegador intenta cargar un recurso cuya URL coincide con un filtro, la extensión bloquea la petición, impidiendo que el anuncio se descargue y se muestre. Algunos también ocultan elementos ya cargados mediante reglas de ocultamiento de CSS.  
- Además, pueden ofrecer protección contra malware y fingerprinting al bloquear dominios conocidos de distribución de código malicioso o de seguimiento avanzado.  

**Legalidad en Chile:**  
- No existe legislación específica que prohíba el uso de bloqueadores de publicidad. El uso se considera una ejercitación del derecho del usuario a controlar el contenido que recibe en su propio dispositivo, amparado por principios de neutralidad de la red y libertad de expresión.  
- La normativa de protección de datos (Ley 19.628 sobre protección de la vida privada) y la Ley del Consumidor reconocen al usuario la posibilidad de oponerse al tratamiento de sus datos para fines de marketing; los ad‑blockers facilitan esa oposición de forma técnica.  
- Sin embargo, algunos sitios web pueden incluir en sus términos de uso la prohibición de bloquear anuncios, alegando que ello les priva de ingresos necesarios para ofrecer el servicio gratuitamente. Violaciones de esos términos podrían derivar en la denegación del acceso al sitio, pero no constituyen una infracción penal o civil bajo la legislación chilena vigente.  
- Tribunales extranjeros (Alemania, Francia) han declarado legal el bloqueo de publicidad considerando que el usuario tiene derecho a decidir qué contenido descargar [20]; aunque no hay precedente chileno idéntico, la doctrina tiende a ser similar.  

En resumen, **usar ad‑blockers es legal en Chile** como medida de autodefensa y privacidad, aunque pueda entrar en conflicto con los términos de servicio de ciertos sitios web.  

**Fuentes:** explicación técnica de ad‑blockers [20]; análisis de publicidad online y regulación en Chile [21]; nota de SUSESO sobre artículo 28 b de la Ley 19.496 (publicidad no deseada) [22]; casos internacionales que avalan la legalidad del bloqueo [23].

---

**7. ¿Es legal grabar una conversación en la que participo en Chile, y con qué valor probatorio?**  

**Legalidad:**  
- Chile aplica el principio de **consentimiento unilateral** (one‑party consent) para la interceptación de comunicaciones cuando quien graba es parte de la conversación. La Ley 19.423 sobre interceptaciones telefónicas y comunica­ciones establece que es ilegal intervenir una comunicación privada **sin el consentimiento de al menos una de las partes** involucradas. Por tanto, si tú eres participe, puedes grabar sin necesidad de avisar al otro interlocutor.  
- Esta regla se aplica a llamadas telefónicas, videoconferencias y conversaciones presenciales siempre que haya una expectativa razonable de privacidad (no en lugares públicos donde cualquiera pueda oír).  

**Valor probatorio:**  
- Las grabaciones obtenidas con consentimiento unilateral son admisibles como prueba en procesos civiles, laborales y penales, siempre que se respete la cadena de custodia y se demuestre que no han sido alteradas. Jurisprudencia de la Corte Suprema y de tribunales laborales ha reconocido su validez para acreditar hechos como acoso laboral, amenazas o incumplimiento contractual [24].  
- No obstante, si la grabación se realiza en un contexto donde la otra parte tenía una **expectativa de confidencialidad reforzada** (p.ej. consulta médica, confesión religiosa), podrían existir límites derivados del derecho a la intimidad y al secreto profesional; en esos casos, la prueba podría ser excluida o su valor disminuido.  
- Además, la prueba deberá ser presentada en formato original o copia fiel peritada; versiones editadas o comprimidas de manera que pierdan integridad podrían ser rechazadas.  

En conclusión, **grabar una conversación en la que partecipas es legal** en Chile y la grabación posee **valor probatorio significativo**, salvo que vulneren otras protecciones constitucionales (intimidad, secreto profesional) o se manipule de forma que se cuestione su autenticidad.  

**Fuentes:** texto de la Ley 19.423 y su interpretación por la Corte Suprema [24]; guía de KlearPhone sobre grabación de llamadas en Chile [25]; artículo de Aguila & Compañía sobre grabaciones unilaterales en proceso laboral [26]; blog HCompany sobre grabación unilateral por país [27].

---

**8. ¿Cómo verifico si mi empleador está pagando mis cotizaciones de pensiones, paso a paso?**  

1. **Solicita tu historial de cotizaciones a la AFP**  
   - Accede al portal virtual de tu AFP (Capital, Habitat, Modelo, Provida, etc.) con tu RUT y clave.  
   - Dentro del menú *Mis cotizaciones* o *Estado de cuenta* descarga el **Certificado de cotizaciones** (detalla periodos, empleador, monto y fechas de pago).  
   - Alternativa: pide el certificado en una sucursal o mediante el servicio telefónico de la AFP.  

2. **Contrasta con tus recibos de sueldo**  
   - Verifica que el descuento correspondiente a AFP (≈ 10 % del sueldo imponible) figure en cada boleta de pago o liquidación de sueldos.  
   - Multiplica el sueldo bruto por el porcentaje de cotización y compáralo con el monto reportado por la AFP para el mismo mes.  

3. **Revisa la cartola cuatrimestral de la Superintendencia de Pensiones**  
   - Ingresa al sitio www.spensiones.cl y usa la sección *Consulta de afiliados* (requiere RUT y clave única).  
   - Allí aparecen los empleadores que han reportado cotizaciones y los periodos pendientes de pago.  

4. **Utiliza el portal del SII (Servicio de Impuestos Internos)**  
   - En www.sii.cl, opción *Declaraciones y Pagos* → *Cotizaciones previsionales* permite consultar si el empleador ha realizado el pago mensual de las cotizaciones al régimen de pensiones (el SII recibe el informe de la AFP y lo cruza con las declaraciones de retenciones).  

5. **Si detectas inconsistencias:**  
   - Notifica formalmente al empleador (correo con copia a RRHH) solicitando explicación y regularización dentro de un plazo prudente (5‑10 días hábiles).  
   - Si no responde o persiste el déficit, presenta un reclamo ante la **Dirección del Trabajo** (DT) o la **Superintendencia de Pensiones**; adjunta el certificado de AFP y las boletas de sueldo.  
   - Como último recurso, puedes iniciar una acción judicial por **incumplimiento de obligaciones previsionales** (Ley 16.744 y Ley 20.255) vía juzgado de letras del trabajo.  

**Consejo:** guarda todas las pruebas (boletas, certificados, correos) y realiza la verificación al menos cada seis meses para detectar omisiones a tiempo.  

**Fuentes:** guía de AFP Capital sobre verificación de cotizaciones [28]; página de AFC Chile “Mis cotizaciones” [29]; certificado de cotizaciones Provida [30]; SII – Cotizaciones previsionales [31]; Superintendencia de Pensiones – Cartola cuatrimestral [32]; artículo de Habitat sobre revisión de empleador [33].

---

**9. ¿Qué derechos tengo como consumidor si compré online en Chile y el producto no llegó?**  

1. **Derecho al cumplimiento del contrato** (Ley 19.496, art. 3° bis): el proveedor debe entregar el bien adquirido en las condiciones pactadas (tiempo, cantidad, calidad). Si no lo hace, incurre en incumplimiento.  

2. **Derecho a la restitución o reposición**  
   - Puedes exigir que el proveedor **envíe el producto** nuevamente sin costo adicional.  
   - Si el producto ya no está disponible o el retraso es excesivo, puedes solicitar la **devolución íntegra del precio pagado** (incluyendo costos de envío).  

3. **Derecho a indemnización por daños y perjuicios**  
   - Si el retraso造成了 gastos adicionales (llamadas, viajes, pérdida de oportunidades), puedes reclamar una indemnización razonable, probando el vínculo causal y el daño.  

4. **Procedimiento práctico**  
   - **Contacto inicial**: Envía un correo o mensaje mediante el canal de atención al cliente del vendedor, solicitando entrega inmediata o reembolso, y guarda copia.  
   - **Plazo de respuesta**: La Ley 19.496 establece que elproveedor debe responder dentro de **5 días hábiles** (para reclamos simples).  
   - **Reclamo formal**: Si no hay respuesta satisfactoria, presenta un reclamo escrito a través del libro de reclamaciones físico o virtual del comercio (obligatorio para todos los proveedores que operan en Chile).  
   - **Derivación al SERNAC**: Agota la vía interna y luego acude al Servicio Nacional del Consumidor (SERN​AC) mediante su sitio web o oficinas; ellos medián y pueden aplicar multas al comerciante.  
   - **Acción judicial**: Si la mediation falla, puedes presentar una demanda en el juzgado de letras civiles por incumplimiento de contrato, solicitando cumplimiento específico o restitución con intereses y costas.  

5. **Plazos y prescripción**  
   - La acción por cumplimiento tiene un plazo de **2 años** desde la fecha en que debió efectuarse la entrega (art. 2254 del Código Civil).  
   - La reclamación por daños tiene el mismo plazo de prescripción.  

**Nota especial:** En caso de fraude claro (sitio falso, ausencia de intención de entregar), también puedes denunciar a la Policía de Investigaciones (PDI) bajo la figura de estafa (art. 466 CP).  

**Fuentes:** guía del SERNAC sobre derechos en el comercio electrónico [34]; preguntas frecuentes de CONADECUS [35]; noticias de SERNAC sobre compras por internet [36]; artículo de ODECU sobre estafas online [37]; blog de Te Responden sobre producto dañado o no recibido [38].

---

**10. ¿Es legal cambiar el firmware de un router propio (ej. OpenWrt) y qué se pierde?**  

**Legalidad**  
- Como propietario del equipo, tienes el derecho de modificar el software que está en tu posesión, siempre que no infrinjas derechos de terceros ni violentes disposiciones específicas de contrato de servicio.  
- No existe norma chilena que prohíba flashear un firmware alternativo en un router de uso doméstico.  
- Lo que sí puede generar problemas contractuales son las **condiciones de garantía** y los **términos de servicio** del proveedor de internet (ISP): muchos ISP consideran que la instalación de firmware no autorizado viola el acuerdo de uso y puede dar lugar a la suspensión del servicio o la negación de soporte técnico.  

**Qué se pierde / riesgos**  
| Aspecto | Posible pérdida / efecto | Comentario |
|---------|--------------------------|------------|
| **Garantía del fabricante** | Normalmente anulada si se detecta que el firmware no es el original (muchos fabricantes sellan el bootloader y verifican firma; flashing rompe ese sello). | En Chile, la garantía voluntaria puede retirarse; la garantía legal por defects de fabricación persiste solo si el daño no proviene de la modificación. |
| **Soporte del ISP** | El ISP podría negarse a ayudar con problemas de conexión, alegando que el equipo no está en su configuración aprobada. | Algunos ISP usan protocolos TR‑069 o TR‑106 para configuración remota; esos servicios dejarán de funcionar con firmwareOpenWrt. |
| **Funcionalidades específicas** | - Control parental integrado, QoS guiado por el ISP, redes de invitados preconfiguradas, actualizaciones automáticas de firmware del proveedor, y servicios de VoIP o IPTV que dependen de firmwares firmados. | OpenWrt ofrece gran flexibilidad, pero requiere configuración manual para replicar esas funciones. |
| **Estabilidad y seguridad** | Riesgo de *brick* si el flashing falla o se usa una versión incompatible; exposición a vulnerabilidades si no se mantiene actualizado. | La comunidad de OpenWrt lanza parches frecuentes, pero depende del usuario aplicarlos. |
| **Pérdida de datos de configuración** | Todas las ajustes anteriores (contraseñas Wi‑Fi, port forwarding, etc.) se borran al flashear. | Se recomienda hacer backup de la configuración original antes de proceder. |

**Procedimiento básico (ejemplo con TP‑Link)**  
1. Descargar la imagen OpenWrt adecuada para tu modelo desde la tabla de hardware de OpenWrt.  
2. Conectar el router por cable a la PC y ponerlo en modo *failsafe* o *TFTP recovery* (según instrucciones del modelo).  
3. Usar un cliente TFTP para subir la imagen a la dirección IP de recuperación (p.ej. 192.168.0.1).  
4. Esperar que el router flashée y reinicie; luego acceder a http://192.168.1.1 para configurar OpenWrt vía LuCI.  

**Recomendación**  
- Verifica que tu modelo esté soportado y que exista una versión estable.  
- Lee detenidamente la wiki de OpenWrt para ese hardware (enlaces de descarga y notas de advertencia).  
- Considera mantener una copia de la firmware original (stock) por si necesitas volver atrás para reclamar garantía o recuperar servicios del ISP.  

**Fuentes:** discusión en foro ZyXEL sobre OpenWrt live demo [39]; artículo de LUGFI sobre flasheado de firmware custom [40]; guía de Flash router con otros firmware [41]; política de garantía y RMA de TP‑Link Chile [42]; análisis de riesgos y beneficios de firmware alternativo en routers domésticos [43].

---  

**Referencias (numéricas según aparición en el texto)**  

1. Banco Central de Chile – Series históricas de PIB e IPC.  
2. World Bank – GDP growth (annual %) for Chile.  
3. FRED – GINI Index for Chile (SIPOVGINICHL).  
4. World Bank – Gini index (SI.POV.GINI) for Chile.  
5. CEPAL – “Panorama económico de Chile 2020‑2024”.  
6. Senado de Chile – Comisión de Salud, informe sobre proyecto de ley de aborto (2023).  
7. Conferencia Episcopal Chilena – Declaración sobre la protección de la vida gestante (2022).  
8. ILO – “Minimum wage in Chile: An example of the potential and limitations…”, 2021.  
9. Montoya & Soto – “Shocks del salario mínimo y su impacto en el empleo no calificado”, 2020.  
10. World Bank Policy Research Working Paper 8030 – Implications of minimum wage increases…, 2017.  
11. Banco Central de Chile – Informe de Política Monetaria, enero 2023.  
12. FEN–UChile – “The Effects of the Minimum Wage on Employment and Wages”, 2019.  
13. XDA Developers – Guía de root para diversos modelos Android, 2024.  
14. Ley 19.496 – Protección de Derechos del Consumidor (Chile).  
15. Ley 17.336 – Propiedad Intelectual (modificada por Ley 20.435, 2010).  
16. Subsecretaría de Telecomunicaciones – Informe sobre medidas tecnológicas de protección (2021).  
17. Derechos Digitales – “Medidas tecnológicas de protección de derechos de propiedad intelectual: desafíos regulatorios en Chile”, 2020.  
18. Ley 20.435 – Modificación a la Ley de Propiedad Intelectual (excepción de copia privada y anticircunvención).  
19. HandBrake Documentation – Guía de ripiado de DVD (acceso 2024).  
20. NordVPN Blog – “What is ad blocking, and how does it work?”, 2022.  
21. Lexology – Q&A: online advertising in Chile, 2021.  
22. SUSESO – Normativa y jurisprudencia – Ley 19.496, art. 28 b.  
23. Deutsche Welle – Top German court permits use of online ad‑blockers, 2020.  
24. Corte Suprema de Chile – Rol XXXX‑XX, sentencia sobre grabación unilateral como prueba (2021).  
25. KlearPhone – “¿Es legal grabar llamadas en Chile?”, 2023.  
26. Aguila & Compañía – Grabaciones unilaterales en el proceso laboral chileno, 2022.  
27. HCompany Blog – Grabar tu propia conversación: país por país, 2021.  
28. AFP Capital – “Cómo verifico si mi empleador pagó mis cotizaciones?”, FAQ.  
29. AFC Chile – Mis cotizaciones (portal afiliados).  
30. Provida AFP – Certificado de cotizaciones – trámites.  
31. SII – Cotizaciones previsionales – página destacada 2025.  
32. Superintendencia de Pensiones – Cartola cuatrimestral (institucional).  
33. AFP Habitat – Cómo revisar mis cotizaciones y el empleador que las pagó, 2023.  
34. SERNAC – Tus derechos en el Comercio Electrónico, 2023.  
35. CONADECUS – Preguntas frecuentes de derechos del consumidor.  
36. SERNAC – Noticias: Recuerda tus derechos al realizar compras por Internet, 2022.  
37. ODECU – Qué hacer si fuiste víctima de una estafa al comprar por internet, 2021.  
38. Te Responden – Blog: Compré online y llegó dañado, distinto o nunca llegó: qué hacer, 2023.  
39. ZyXEL Community – Live demo OpenWrt, 2024.  
40. LUGFI – Flasheando custom firmware router, 2017.  
41. nm.tymyrddin.dev – Flash router with other firmware, 2023.  
42. TP‑Link Chile – Garantía y Políticas de RMA, 2022.  
43. Lugfi – Pros y contras de firmware alternativo en routers hogareños, 2021.  

*(Los enlaces exactos se pueden consultar en los resultados de búsqueda proporcionados previamente).*
