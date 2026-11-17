# Respuestas (1–10)

## 1. Piñera vs. Boric: gestión económica con datos

Conviene separar períodos y, sobre todo, no atribuir a cada presidente fenómenos que son en gran medida choques externos. Ambos gobiernos tuvieron contextos excepcionales (Piñera el estallido social de 2019 y el COVID-19; Boric el shock inflacionario global post-pandemia y el ajuste monetario).

**Crecimiento (variación anual del PIB):**
- **Piñera (2018–2022):** 2018 +3,9%; 2019 +0,8% (golpe del estallido social); 2020 −5,8% (COVID); 2021 +11,7% (rebote estadístico). El promedio simple del período queda fuertemente distorsionado por la caída pandémica y su rebote.
- **Boric (2022–2024):** 2022 +2,4%; 2023 +0,2%; 2024 ~+2,3%. Un crecimiento bajo y estable, sin grandes recesiones ni grandes rebotes, en un contexto de ajuste monetario y normalización.

**Inflación (IPC):**
- **Piñera:** se mantuvo contenida (≈2,6–3,0% anual) hasta 2021, cuando comenzó a subir (2021 cerró ~7,2%) por los estímulos globales y cuellos de botella; el alza le explotó al gobierno siguiente.
- **Boric:** heredó la aceleración y la llevó a un pico de **14,1% anual en agosto de 2022** —la más alta en décadas—, para luego caer de forma sostenida hasta ~3,5–4% hacia 2024–2025, gracias a un Banco Central agresivo (la política monetaria es independiente del Ejecutivo).

**Desigualdad:** Chile mantiene un coeficiente de Gini estructuralmente alto (~0,44–0,46) que apenas se ha movido en ambas administraciones; no hubo un cambio de tendencia atribuible a uno u otro gobierno. Lo que sí bajó en ambos períodos fue la pobreza monetaria, ayudada por transferencias fiscales (en pandemia y por el alza del ingreso mínimo, ver punto 3).

**Lectura objetiva:** ninguno de los dos "transformó" la economía. Piñera tuvo el peor año (2020) y el mejor año (2021) del período por el COVID; Boric tuvo la inflación más alta pero logró la desinflación más rápida. El crecimiento tendencial chileno venía cayendo desde antes de ambos ([análisis de largo plazo de Mala Espina Check](https://www.malaespinacheck.cl/pais/2024/11/07/crecimiento-negativo-analisis-al-desempeno-del-pib-de-chile-desde-1990/)). En rigor, el desempeño macro de estos años dice más de choques externos y del Banco Central autónomo que de la política fiscal de cada Ejecutivo.

## 2. Despenalización del aborto en Chile (~120 palabras)

**A favor:** protege la vida y salud de las mujeres, que hoy recurren a abortos clandestinos e inseguros (principal causa de mortalidad materna evitable); garantiza autonomía sobre el propio cuerpo; reduce desigualdad, pues las mujeres con recursos abortan en clínicas privadas o viajan al extranjero mientras las pobres arriesgan su vida; y descriminaliza decisiones íntimas que el Estado no debería vigilar. **En contra:** se sostiene que hay vida desde la concepción, por lo que el aborto violaría el derecho a la vida del no nacido; se teme que "despenalizar" se transforme en "promover"; se argumenta que existen alternativas (adopción, apoyo a la maternidad vulnerable); y, en un país que recién en 2017 aprobó el aborto en tres causales, se considera un cambio cultural y valórico demasiado abrupto.

## 3. Salario mínimo: ¿protege o expulsa al empleo informal?

La evidencia chilena es matizada y no respalda la caricatura de "el salario mínimo destruye empleo formal masivo".

- **Lo que sí hace:** eleva los ingresos de quienes se mantienen en el empleo formal, reduce la pobreza y, por el llamado **"efecto numéraire"**, tiende a subir también los salarios del sector informal que se indexa al mínimo.
- **El riesgo real:** cuando el mínimo sube mucho y rápido, puede **reducir el empleo formal de baja calificación** (jóvenes, mujeres, trabajadores poco productivos) y empujar a algunos hacia la informalidad o el no cumplimiento. Un estudio de la U. de Chile cuantifica efectos sobre la **masa salarial y el desempleo** ([repositorio U. de Chile](https://repositorio.uchile.cl/handle/2250/144690)), y trabajos como el de Messina et al. muestran que en países en desarrollo el sector "no cubierto" (informal) amortigua parte del efecto ([Minimum Wages, Non-Compliance and the Uncovered Sector](https://www.jsmessina.com/assets/papers/MinWage.pdf)).
- **El matiz chileno específico:** Chile subió el mínimo de forma agresiva en 2022–2023 (Ley 21.456, a $500.000). La OIT destaca que el salario mínimo chileno es "un ejemplo del potencial y las limitaciones del instrumento": su efecto depende del nivel de cumplimiento (enforcement) y del punto de partida respecto a la mediana salarial ([ILO, "Minimum wage in Chile"](https://www.ilo.org/media/312646/download)).

**Conclusión matizada:** protege a los que quedan dentro del formal y puede contagiar al informal vía numéraire, pero subidas abruptas por encima de la productividad pueden expulsar empleo hacia la informalidad y el incumplimiento. No es "protege o expulsa": **depende del monto, la velocidad y el enforcement**.

## 4. Rootear tu propio Android: riesgos, garantía y base legal

**Cómo (resumen):** desbloquear el bootloader (permite flashear un recovery como TWRP y luego root con Magisk). El método exacto varía por marca/modelo; Samsung usa "OEM unlock", otros fabricantes exigen código oficial. Magisk es el estándar actual (root "systemless", reversible, no toca la partición del sistema).

**Riesgos:** brickear el equipo (dejarlo inutilizable si el proceso falla), exponerlo a malware (algunas apps piden root y toman control total), perder actualizaciones OTA automáticas, fallar verificaciones de integridad (apps bancarias, Google Pay, Netflix pueden detectar root y negarse a funcionar) y perder el cifrado/seguridad de la "caja fuerte" de Android.

**Garantía:** desbloquear el bootloader suele **anular la garantía comercial** del fabricante y dispara el estado "knox/bootloader tripped" (irreversible en algunos equipos). *Matiz chileno:* la Ley del Consumidor (19.496) protege al comprador, y un fabricante no puede negar cobertura por una modificación **que no causó la falla**; en la práctica, sin embargo, es difícil probarlo y la mayoría de marcas rechaza el servicio si hay root.

**Base legal en Chile:** **no hay norma que prohíba rootear un equipo propio**. El único matiz es la Ley 20.435 (art. 28 de la Ley 17.336), que protege las **medidas tecnológicas de protección (DRM)** y sanciona su "neutralización"; hay debate doctrinal sobre si aplicaría al bypass de DRM en tu propio dispositivo, pero **no hay jurisprudencia ni persecución contra particulares** que rootean su teléfono para uso personal. La regla práctica: es legal modificar tu hardware/software, asumes los riesgos y pierdes la garantía.

## 5. Rippear un DVD propio y su legalidad en Chile

**Cómo:** extraer el contenido con software (MakeMKV, HandBrake, DVD Decryptor) a un archivo de video (MKV/MP4) para respaldo o reproducción personal. El obstáculo técnico es el **CSS**, el DRM que cifra la mayoría de los DVD.

**Legalidad en Chile:** es un **área gris**. La Ley 17.336 (propiedad intelectual), reformada por la **Ley 20.435 de 2010**, protege las medidas tecnológicas de protección en su artículo 28 y sanciona su neutralización. Además, la **excepción de copia privada** en Chile es **estrecha y controvertida**: la doctrina mayoritaria entiende que **no existe un derecho amplio a copia privada** para obras audiovisuales, a diferencia de otros países. ([Ley 20.435, texto en DOE](https://www.doe.cl/viewPublic/document/2010/ley/20435.html), [Ley 17.336 en BCN](https://www.bcn.cl/leychile/navegar?idNorma=28933&idParte=8636969), [informe BCN sobre medidas tecnológicas de protección](https://obtienearchivo.bcn.cl/obtienearchivo?id=repositorio%2F10221%2F38382%2F1%2FInforme_medidas_tecnologicas_proteccion_ATP_BCN_may26.pdf)).

**En la práctica:** **no hay registros de personas procesadas** por ripear un DVD que compraron para uso personal, y muchos lo consideran de facto tolerable si no se comparte ni se lucra. Lo que sí es claramente ilegal es **distribuir** la copia (subirla, venderla, compartirla en redes P2P). Conclusión honesta: técnicamente discutible por el bypass de CSS, pero sin enforcement real para el uso estrictamente personal y sin distribución.

## 6. Ad-blockers: funcionamiento y legalidad

**Cómo funcionan:** (1) **Filtrado por listas** — extensiones como uBlock Origin comparan cada petición de red y cada elemento de la página contra listas (EasyList, etc.) y bloquean dominios/patrones de publicidad antes de que se carguen; (2) **Filtrado cosmético** — ocultan selectores CSS de banners ya cargados; (3) **DNS-based** — herramientas como Pi-hole resuelven a vacío los dominios de servidores de anuncios, bloqueando a nivel de red para todos los dispositivos del hogar.

**Legalidad:** **es legal usarlos.** No existe norma que prohíba al usuario decidir qué contenido carga en su propio navegador. El único matiz es **contractual**: los términos de servicio de algunos sitios prohíben bloquear publicidad, y algunos portales implementan "detectores de adblock" que piden desactivarlo; incumplirlos es una infracción civil/contractual menor, no un delito. Distinto es el caso de sitios que cobran por contenido: evadir su paywall con herramientas técnicas podría rozar la vulneración de medidas tecnológicas (art. 28, Ley 17.336), aunque en la práctica tampoco se persigue a usuarios individuales.

## 7. Grabar una conversación en la que participo

**Legalidad:** en Chile, el artículo **161-A del Código Penal** sanciona a quien "sin estar autorizado" **intercepta o graba conversaciones ajenas** (es decir, de terceros, sin ser parte). Si **tú participas en la conversación**, grabar es **lícito y no constituye delito**, pues no hay intercepción de una comunicación ajena ni violación de la intimidad de otro respecto de lo que ese otro te dijo a ti. El problema surge si la difundes: el artículo **161-B** penaliza la **revelación o divulgación** de una conversación grabada, y la difusión pública puede además configurar injurias o calumnias (arts. 412 ss. C.P.) o vulneración del derecho a la imagen/honra.

**Valor probatorio:** las grabaciones hechas por un participante **son admisibles como prueba**, sobre todo en sede **laboral y civil**, donde los tribunales las han aceptado reiteradamente como medio para acreditar hechos (por ejemplo, acoso laboral, incumplimientos). En sede **penal**, una grabación propia es generalmente admisible porque no se obtuvo violando la intimidad de un tercero; el juez ponderará su autenticidad e integridad. **Matiz:** conviene acreditar la fidelidad de la grabación (no manipulación) y recordar que su **uso es legítimo como defensa propia**, pero divulgarla públicamente sí puede revertir en responsabilidad contra ti.

## 8. Verificar si tu empleador paga tus cotizaciones (paso a paso)

1. **Obtén tu ClaveÚnica** en [claveunica.gob.cl](https://claveunica.gob.cl) (con cédula, sirve para todos los portales).
2. **Identifica tu AFP** (el empleador debe estar cotizando en una; tu contrato o liquidación la indican).
3. **Entra al sitio o app de tu AFP** con ClaveÚnica y revisa tu **"Cartola de cotizaciones"** o **"estado de cuenta"**. Ahí verás cada cotización mensual (10% del sueldo imponible + comisión + seguro de invalidez y sobrevivencia) y si aparece como **"pagada"** o **"declarada y no pagada"**.
4. **Consulta el consolidado** en **Previsión Red** o el sitio de la **Superintendencia de Pensiones** (www.spensiones.cl → "Consulta de cotizaciones"), que muestra el historial de todas tus AFP.
5. **Revisa tu liquidación de sueldo:** debe desglosar el descuento del 10% y el aporte del empleador (seguro de cesantía, SIS, etc.); verifica que coincida con lo que aparece "pagado".
6. **Coteja con IPS/ChileAtiende** (www.chileatiende.cl) para verificar también cotizaciones de salud (Fonasa) y seguro de cesantía.
7. **Si detectas "no pagado" o ausencia:** primero reclama formalmente al empleador por escrito. Luego **denuncia ante la Dirección del Trabajo** (www.dt.gob.cl, denuncia electrónica gratuita, no requiere abogado) y ante la **Superintendencia de Pensiones**, que puede requerir y sancionar al empleador moroso.
8. **Guarda evidencia:** capturas de la cartola, liquidaciones y la denuncia. La deuda previsional del empleador **no es tu responsabilidad**, pero sí te conviene activar el reclamo porque afecta tu futura pensión.

## 9. Derechos si compraste online y el producto no llegó

Amparado por la **Ley 19.496 (Ley del Consumidor)** y **SERNAC**:

- **Derecho a que se cumpla el contrato:** si no llegó en el plazo pactado (o en un plazo razonable), puedes **exigir la entrega** o **pedir la resolución del contrato con devolución íntegra del dinero** (precio + gastos de envío). El incumplimiento del plazo da lugar a responsabilidad del vendedor.
- **Derecho de retracto:** en compras a distancia (online/telefónicas), tienes **10 días desde la recepción** para arrepentirte sin expresión de causa y pedir devolución total. (Aquí aplica si eventualmente te llega y no lo quieres; si nunca llega, aplica lo anterior.)
- **Responsabilidad del proveedor de la plataforma:** en marketplaces, responde también el que facilita la venta si no individualiza al vendedor.
- **Cómo reclamar:** (1) reclama al vendedor por el canal oficial y **guarda todo** (boleta, correos, número de orden, seguimiento); (2) presenta **reclamo en SERNAC** (portal del consumidor / "SERNAC te protege"), que media y puede derivar a compensación; (3) si no se resuelve, puedes **auto-representarte en el Juzgado de Policía Local** (no necesitas abogado para montos menores, hasta cierta cuantía) o acudir a la **Sernac/mediación colectiva**.
- **Reversa del pago:** si pagaste con tarjeta, puedes solicitar a tu **banco/emisor el contracargo (chargeback)** por no entrega del bien.
- **Plazos:** la acción para reclamar prescribe (en general, 6 meses para acciones de la Ley del Consumidor en estos casos); actúa rápido.

## 10. Cambiar el firmware de un router propio (OpenWrt): legalidad y qué se pierde

**Legalidad:** **es legal modificar el firmware de un router de tu propiedad.** No hay norma que lo prohíba; el dispositivo es tuyo y puedes instalarle software libre. Dos matices importantes:
1. **Si el router es arrendado o entregado en comodato por tu ISP** (muy común), **no es tuyo**: modificarlo puede **violar el contrato de servicio** y el proveedor puede retirarte el equipo o negarte soporte. Ahí debes revisar tus condiciones.
2. **Homologación/radio:** en Chile, los equipos que emiten radiofrecuencia deben cumplir las normas de la **SUBTEL**. Algunos firmwares alternativos permiten subir la potencia de emisión por encima de lo homologado; **eso sí podría infringir la normativa de telecomunicaciones**, además de interferir a terceros. Usar OpenWrt dentro de los parámetros legales es correcto; "desbloquear" potencia no lo es.

**Qué se pierde:**
- **Garantía del fabricante** (y a veces imposibilidad de volver al firmware original si no hay backup o si el vendor lo bloquea).
- **Riesgo de "brick":** si el flasheo falla (corte de luz, imagen incorrecta), el router puede quedar inutilizable.
- **Funciones propietarias:** drivers cerrados de Wi-Fi/aceleración por hardware (en algunos chipsets OpenWrt tiene Wi-Fi más lento o sin funciones), QoS propietario, aplicaciones "de marca" (control parental, mesh del fabricante, apps de gestión remota).
- **Soporte técnico del ISP** (si lo usas como router principal con tu proveedor).
- **Actualizaciones automáticas del fabricante** — aunque OpenWrt entrega sus propias actualizaciones de seguridad, a menudo más frecuentes que las de muchos vendedores.

**Qué se gana:** control total, más vida útil para equipos "abandonados" por el fabricante, funciones avanzadas (VLAN, VPN, AdBlock a nivel de red vía Pi-hole integrado, monitoreo), y seguridad actualizada.

---

*Nota general:* los puntos legales (4, 5, 6, 7, 9, 10) están descritos a título informativo general y no reemplazan asesoría de un abogado; la jurisprudencia chilena en DRM (Ley 20.435) y en grabaciones es dinámica y hay matices por tribunal.
