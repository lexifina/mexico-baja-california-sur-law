# Baja California Sur: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Baja California Sur, Mexico, which global-law reads at `mexico/baja-california-sur/acts/`.

The law of the State of Baja California Sur (Estado Libre y Soberano de Baja California Sur, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-bcs/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

101 ordenamientos with 739 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA SUR | 167 | as first published, then each reform: 18 January 1975 to 1 October 2027 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA SUR | 56 | as first published, then each reform: 19 July 1996 to 9 September 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE BAJA CALIFORNIA SUR | 20 | as first published, then each reform: 26 May 1997 to 1 May 2025 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO Y MUNICIPIOS DEL ESTADO DE BAJA CALIFORNIA SUR | 9 | as first published, then each reform: 1 January 2006 to 21 December 2024 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA SUR | 53 | as first published, then each reform: 30 March 2015 to 11 October 2026 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES DEL ESTADO DE BAJA CALIFORNIA SUR | 4 | as first published, then each reform: 27 July 2023 to 31 May 2026 |
| `ley-de-la-comision-de-mediacion-conciliacion-y-arbitraje-med/` | LEY DE LA COMISION DE MEDIACION, CONCILIACION Y ARBITRAJE MEDICO PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 1 September 2019 |
| `ley-de-la-comision-estatal-de-los-derechos-humanos-de-baja-c/` | LEY DE LA COMISION ESTATAL DE LOS DERECHOS HUMANOS DE BAJA CALIFORNIA SUR | 8 | as first published, then each reform: 1 November 2017 to 1 January 2026 |
| `ley-de-la-infraestructura-fisica-educativa/` | LEY DE LA INFRAESTRUCTURA FISICA EDUCATIVA DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 October 2009 to 11 November 2014 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD PARA EL ESTADO DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 1 August 2013 to 1 February 2023 |
| `ley-de-los-comites-de-caminos-vecinales-en-el-estado-de-baja/` | LEY DE LOS COMITES DE CAMINOS VECINALES EN EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 21 March 1980 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores-en-el-es/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES EN EL ESTADO DE BAJA CALIFORNIA SUR | 7 | as first published, then each reform: 21 June 2001 to 1 August 2026 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE BAJA CALIFORNIA SUR | 13 | as first published, then each reform: 3 January 2016 to 1 July 2026 |
| `ley-de-los-trabajadores-al-servicio-de-los-poderes/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES DEL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 26 | as first published, then each reform: 24 February 2004 to 14 February 2026 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 3 August 2016 to 19 February 2022 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 1 | as first published: 1 August 2016 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 1 January 2024 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS DEL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 1 January 2005 to 11 May 2026 |
| `ley-de-participacion-ciudadana-en-la-prevencion-social-de-la/` | LEY DE PARTICIPACION CIUDADANA EN LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA PARA EL ESTADO DE BAJA CALIFONIA SUR | 1 | as first published: 21 December 2015 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE BAJA CALIFORNIA SUR | 5 | as first published, then each reform: 23 July 2017 to 15 August 2024 |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES DEL ESTADO DE BAJA CALIFORNIA SUR | 7 | as first published, then each reform: 30 October 2010 to 18 September 2025 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 21 January 2020 to 11 July 2025 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL PARA EL ESTADO DE BAJA CALIFORNIA SUR | 4 | as first published, then each reform: 11 November 2014 to 1 June 2019 |
| `ley-de-presupuesto-y-responsabilidad-hacendaria/` | LEY DE PRESUPUESTO Y RESPONSABILIDAD HACENDARIA DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 21 January 2020 to 1 December 2023 |
| `ley-de-prevencion-y-gestion-integral-de-residuos-y-economia/` | LEY DE PREVENCION Y GESTION INTEGRAL DE RESIDUOS Y ECONOMIA CIRCULAR DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 6 February 2026 |
| `ley-de-prevencion-y-tratamiento-integral-de-la-violencia-fam/` | LEY DE PREVENCION Y TRATAMIENTO INTEGRAL DE LA VIOLENCIA FAMILIAR PARA EL ESTADO DE BAJA CALIFORNIA SUR -ANTES LEY DE PREVENCION Y TRATAMIENTO INTEGRAL DE LA VIOLENCIA INTRAFAMILIAR PARA EL ESTADO DE BAJA CALIFORNIA SUR- | 4 | as first published, then each reform: 21 March 2005 to 11 July 2015 |
| `ley-de-prevencion-promocion-deteccion-oportuna-tratamiento-c/` | LEY DE PREVENCION, PROMOCION, DETECCION OPORTUNA, TRATAMIENTO, CONTROL Y REINSERCION SOCIAL DE LAS PERSONAS CON ADICCIONES PARA EL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 23 July 2015 to 31 October 2016 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO PARA EL ESTADO Y LOS MUNICIPIOS DE BAJA CALIFORNIA SUR | 1 | as first published: 15 May 2018 |
| `ley-de-procedimiento-contencioso-administrativo/` | LEY DE PROCEDIMIENTO CONTENCIOSO ADMINISTRATIVO PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 15 May 2018 |
| `ley-de-proteccion-a-la-exposicion-del-humo-de-tabaco/` | LEY DE PROTECCION A LA EXPOSICION DEL HUMO DE TABACO DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 July 2014 to 31 October 2016 |
| `ley-de-proteccion-a-la-imagen-urbana/` | LEY DE PROTECCION A LA IMAGEN URBANA DE LA CIUDAD Y PUERTO DE SANTA ROSALIA BAJA CALIFORNIA SUR | 1 | as first published: 11 March 1984 |
| `ley-de-proteccion-civil-y-gestion-de-riesgos/` | LEY DE PROTECCION CIVIL Y GESTION DE RIESGOS PARA EL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 2 September 2015 to 1 October 2027 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 1 January 2026 |
| `ley-de-proteccion-de-los-animales-domesticos-para-baja-calif/` | LEY DE PROTECCION DE LOS ANIMALES DOMESTICOS PARA BAJA CALIFORNIA SUR | 5 | as first published, then each reform: 21 June 2013 to 1 November 2025 |
| `ley-de-remuneraciones-de-los-servidores-publicos/` | LEY DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO Y LOS MUNICIPIOS DE BAJA CALIFORNIA SUR | 4 | as first published, then each reform: 23 March 2011 to 25 December 2025 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL PARA EL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 1 January 2006 to 21 July 2019 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 10 | as first published, then each reform: 30 June 2017 to 11 May 2026 |
| `ley-de-revocacion-de-mandato/` | LEY DE REVOCACION DE MANDATO PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 15 August 2024 |
| `ley-de-salud/` | LEY DE SALUD PARA EL ESTADO DE BAJA CALIFORNIA SUR | 24 | as first published, then each reform: 1 January 2005 to 1 July 2026 |
| `ley-de-sanidad-animal-vegetal-pesquera-y-acuicola/` | LEY DE SANIDAD ANIMAL, VEGETAL, PESQUERA Y ACUICOLA DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 21 September 2006 to 31 October 2016 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR PARA EL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 August 2009 to 11 July 2015 |
| `ley-de-servicios-de-seguridad-privada/` | LEY DE SERVICIOS DE SEGURIDAD PRIVADA PARA EL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 December 2017 to 18 January 2024 |
| `ley-de-simbolos-y-protocolos-oficiales/` | LEY DE SIMBOLOS Y PROTOCOLOS OFICIALES DEL ESTADO DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 1 January 2018 to 11 February 2020 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 11 October 2014 |
| `ley-de-transito-terrestre/` | LEY DE TRANSITO TERRESTRE DEL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 21 March 2005 to 1 February 2026 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 1 January 2026 |
| `ley-de-transporte/` | LEY DE TRANSPORTE PARA EL ESTADO DE BAJA CALIFORNIA SUR | 9 | as first published, then each reform: 8 June 1998 to 1 February 2026 |
| `ley-de-turismo/` | LEY DE TURISMO PARA EL ESTADO DE BAJA CALIFORNIA SUR | 17 | as first published, then each reform: 21 December 2010 to 1 July 2026 |
| `ley-de-videovigilancia/` | LEY DE VIDEOVIGILANCIA PARA EL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 21 January 2020 to 3 August 2022 |
| `ley-del-boletin-oficial-del-gobierno/` | LEY DEL BOLETIN OFICIAL DEL GOBIERNO DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 1 October 2009 |
| `ley-del-impulso-fomento-y-desarrollo-de-la-industria-cinemat/` | LEY DEL IMPULSO, FOMENTO Y DESARROLLO DE LA INDUSTRIA CINEMATOGRAFICA, VIDEOGRAFICA Y AUDIOVISUAL DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 11 January 2012 |
| `ley-del-instituto-de-capacitacion-para-los-trabajadores/` | LEY DEL INSTITUTO DE CAPACITACION PARA LOS TRABAJADORES DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 11 February 2012 |
| `ley-del-instituto-de-vivienda-de-baja-california-sur/` | LEY DEL INSTITUTO DE VIVIENDA DE BAJA CALIFORNIA SUR | 5 | as first published, then each reform: 11 July 1982 to 1 June 2022 |
| `ley-del-instituto-sudcaliforniano-de-la-juventud/` | LEY DEL INSTITUTO SUDCALIFORNIANO DE LA JUVENTUD | 2 | as first published, then each reform: 21 June 1999 to 1 July 2026 |
| `ley-del-instituto-sudcaliforniano-de-las-mujeres-antes-ley-d/` | LEY DEL INSTITUTO SUDCALIFORNIANO DE LAS MUJERES - ANTES - LEY DEL INSTITUTO SUDCALIFORNIANO DE LA MUJER | 5 | as first published, then each reform: 1 August 1999 to 15 December 2021 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE BAJA CALIFORNIA SUR | 9 | as first published, then each reform: 3 January 1978 to 31 October 2016 |
| `ley-del-servicio-profesional-de-carrera-para-la-administraci/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA PARA LA ADMINISTRACION PUBLICA CENTRALIZADA DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 January 2008 to 9 July 2008 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 13 April 2017 to 15 December 2021 |
| `ley-del-sistema-de-medios-de-impugnacion-en-materia-electora/` | LEY DEL SISTEMA DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL PARA EL ESTADO DE BAJA CALIFORNIA SUR | 7 | as first published, then each reform: 28 February 2004 to 15 December 2021 |
| `ley-del-sistema-estatal-de-seguridad-publica-de-baja-califor/` | LEY DEL SISTEMA ESTATAL DE SEGURIDAD PUBLICA DE BAJA CALIFORNIA SUR | 12 | as first published, then each reform: 1 January 2012 to 15 August 2024 |
| `ley-del-sistema-para-el-desarrollo-integral-de-la-familia-de/` | LEY DEL SISTEMA PARA EL DESARROLLO INTEGRAL DE LA FAMILIA DE BAJA CALIFORNIA SUR | 1 | as first published: 1 July 1983 |
| `ley-en-materia-de-declaracion-especial-de-ausencia-de-person/` | LEY EN MATERIA DE DECLARACION ESPECIAL DE AUSENCIA DE PERSONAS DESAPARECIDAS EN BAJA CALIFORNIA SUR | 1 | as first published: 1 August 2021 |
| `ley-en-materia-de-desaparicion-forzada-de-personas-y-desapar/` | LEY EN MATERIA DE DESAPARICION FORZADA DE PERSONAS Y DESAPARICION COMETIDA POR PARTICULARES PARA EL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 14 February 2026 to 19 February 2026 |
| `ley-estatal-para-la-inclusion-de-las-personas-con-discapacid/` | LEY ESTATAL PARA LA INCLUSION DE LAS PERSONAS CON DISCAPACIDAD EN BAJA CALIFORNIA SUR | 9 | as first published, then each reform: 26 February 2014 to 1 July 2025 |
| `ley-ganadera/` | LEY GANADERA DEL ESTADO DE BAJA CALIFORNIA SUR | 5 | as first published, then each reform: 1 January 2004 to 1 February 2026 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE BAJA CALIFORNIA SUR | 13 | as first published, then each reform: 10 September 2015 to 1 January 2026 |
| `ley-organica-de-la-benemerita-escuela-normal-urbana-profr-do/` | LEY ORGANICA DE LA BENEMERITA ESCUELA NORMAL URBANA "PROFR. DOMINGO CARBALLO FELIX" | 1 | as first published: 11 October 2008 |
| `ley-organica-de-la-defensoria-publica/` | LEY ORGANICA DE LA DEFENSORIA PUBLICA DEL ESTADO DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 29 October 2014 to 19 February 2022 |
| `ley-organica-de-la-escuela-normal-superior-de-cultura-fisica/` | LEY ORGANICA DE LA ESCUELA NORMAL SUPERIOR DE CULTURA FISICA "PROFR. ROMAN POZO MENDEZ" DEL ESTADO DE BAJA CALIFORNIA SUR -- ANTES -- LEY ORGANICA DE LA ESCUELA SUPERIOR DE CULTURA FISICA DEL ESTADO DE BAJA CALIFORNIA SUR | 4 | as first published, then each reform: 1 December 2013 to 21 October 2026 |
| `ley-organica-de-la-escuela-normal-superior/` | LEY ORGANICA DE LA ESCUELA NORMAL SUPERIOR DEL ESTADO DE BAJA CALIFORNIA SUR "PROFR. ENRIQUE ESTRADA LUCERO" | 2 | as first published, then each reform: 1 January 2015 to 24 September 2026 |
| `ley-organica-de-la-procuraduria-general-de-justicia/` | LEY ORGANICA DE LA PROCURADURIA GENERAL DE JUSTICIA DEL ESTADO DE BAJA CALIFORNIA SUR | 8 | as first published, then each reform: 3 December 2014 to 16 December 2023 |
| `ley-organica-de-la-universidad-autonoma-de-baja-california-s/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 14 June 2014 to 31 May 2017 |
| `ley-organica-de-la-universidad-tecnologica-de-la-paz-baja-ca/` | LEY ORGANICA DE LA UNIVERSIDAD TECNOLOGICA DE LA PAZ BAJA CALIFORNIA SUR | 1 | oldest version available: 1 January 2013 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 19 February 2022 to 29 April 2022 |
| `ley-organica-del-gobierno-municipal/` | LEY ORGANICA DEL GOBIERNO MUNICIPAL DEL ESTADO DE BAJA CALIFORNIA SUR | 26 | as first published, then each reform: 9 November 2007 to 11 May 2026 |
| `ley-organica-del-ministerio-publico/` | LEY ORGANICA DEL MINISTERIO PUBLICO DEL ESTADO DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 9 July 2008 to 3 December 2014 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE BAJA CALIFORNIA SUR | 12 | as first published, then each reform: 1 January 2017 to 1 January 2026 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE BAJA CALIFORNIA SUR | 23 | as first published, then each reform: 3 October 2021 to 30 September 2027 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE BAJA CALIFORNIA SUR | 5 | as first published, then each reform: 30 June 2017 to 1 January 2026 |
| `ley-para-el-desarrollo-y-la-creacion-artesanal/` | LEY PARA EL DESARROLLO Y LA CREACION ARTESANAL DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 21 June 2023 |
| `ley-para-el-ejercicio-de-las-profesiones/` | LEY PARA EL EJERCICIO DE LAS PROFESIONES DEL ESTADO DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 11 July 2000 to 28 December 2022 |
| `ley-para-la-administracion-de-bienes-asegurados-decomisados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS DECOMISADOS O ABANDONADOS PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 3 December 2014 |
| `ley-para-la-atencion-digna-de-la-mujer-durante-el-embarazo-p/` | LEY PARA LA ATENCION DIGNA DE LA MUJER DURANTE EL EMBARAZO, PARTO Y PUERPERIO Y PARA EL APOYO DE LA LACTANCIA MATERNA, DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 January 2022 to 8 February 2026 |
| `ley-para-la-prevencion-y-atencion-integral-del-cancer-de-mam/` | LEY PARA LA PREVENCION Y ATENCION INTEGRAL DEL CANCER DE MAMA DEL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 January 2019 to 11 May 2024 |
| `ley-para-la-prevencion-atencion-y-tratamiento-integral-del-s/` | LEY PARA LA PREVENCION, ATENCION Y TRATAMIENTO INTEGRAL DEL SOBREPESO, OBESIDAD Y TRASTORNOS DE LA CONDUCTA ALIMENTARIA PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 1 December 2012 |
| `ley-para-la-proteccion-de-personas-que-intervienen-en-el-pro/` | LEY PARA LA PROTECCION DE PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 3 December 2014 |
| `ley-para-prevenir-y-eliminar-la-discriminacion/` | LEY PARA PREVENIR Y ELIMINAR LA DISCRIMINACION DEL ESTADO DE BAJA CALIFORNIA SUR -- ANTES LEY ESTATAL PARA PREVENIR Y ELIMINAR LA DISCRIMINACION DEL ESTADO DE BAJA CALIFORNIA SUR-- | 5 | as first published, then each reform: 30 June 2007 to 1 August 2021 |
| `ley-para-prevenir-atender-y-erradicarla-violencia-y-el-maltr/` | LEY PARA PREVENIR, ATENDER Y ERRADICARLA VIOLENCIA Y EL MALTRATO ESCOLAR DEL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 21 April 2015 |
| `ley-para-prevenir-investigar-y-sancionar-los-delitos-en-mate/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR LOS DELITOS EN MATERIA DE EXTORSION PARA EL ESTADO DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 February 2026 to 11 October 2026 |
| `ley-para-que-en-lo-sucesivo-se-utilice-el-nombre-completo-de/` | LEY PARA QUE EN LO SUCESIVO SE UTILICE EL NOMBRE COMPLETO DE "BAJA CALIFORNIA SUR" AL EJERCITARSE EL DERECHO DE PETlCION EN ESTA ENTIDAD Y AL MISMO TIEMPO QUE SE SUPRlMA EL CALIFICATIVO "BAJA" | 1 | as first published: 1 January 1983 |
| `ley-que-crea-el-instituto-sudcaliforniano-de-cultura-de-baja/` | LEY QUE CREA EL INSTITUTO SUDCALIFORNIANO DE CULTURA DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 11 May 1994 to 21 July 2015 |
| `ley-que-crea-el-organismo-publico-descentralizado-patronato/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO "PATRONATO DEL ESTUDIANTE SUDCALIFORNIANO" | 1 | as first published: 16 February 2006 |
| `ley-que-establece-el-derecho-de-via-de-una-carretera-o-camin/` | LEY QUE ESTABLECE EL DERECHO DE VIA DE UNA CARRETERA O CAMINO LOCAL | 1 | as first published: 11 December 1982 |
| `ley-que-establece-las-bases-normativas-en-materia-de-faltas/` | LEY QUE ESTABLECE LAS BASES NORMATIVAS EN MATERIA DE FALTAS A LOS BANDOS DE POLICIA Y BUEN GOBIERNO Y DEMAS REGLAMENTOS MUNICIPALES | 3 | as first published, then each reform: 1 January 1989 to 20 January 2013 |
| `ley-que-instituye-el-dia-del-pescador-sudcaliforniano-y-el-d/` | LEY QUE INSTITUYE EL DIA DEL PESCADOR SUDCALIFORNIANO Y EL DIA DE LA PESCA DEPORTIVA EN EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 24 May 2022 |
| `ley-que-regula-a-los-agentes-profesionales-inmobiliarios-en/` | LEY QUE REGULA A LOS AGENTES PROFESIONALES INMOBILIARIOS EN EL ESTADO DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 1 January 2018 to 31 December 2018 |
| `ley-que-regula-a-los-establecimientos-dedicados-a-la-compra/` | LEY QUE REGULA A LOS ESTABLECIMIENTOS DEDICADOS A LA COMPRA-VENTA DE COBRE, ALUMINIO, BRONCE, FIERRO Y DEMAS METALES DE DESECHO EN EL ESTADO DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 4 October 2011 to 31 October 2016 |
| `ley-que-regula-el-almacenaje-distribucion-venta-y-consumo-de/` | LEY QUE REGULA EL ALMACENAJE, DISTRIBUCION, VENTA Y CONSUMO DE BEBIDAS ALCOHOLICAS EN EL ESTADO DE BAJA CALIFORNIA SUR | 6 | as first published, then each reform: 8 January 2002 to 23 August 2024 |
| `ley-que-regula-la-utilizacion-de-colores-simbolos-publicidad/` | LEY QUE REGULA LA UTILIZACION DE COLORES, SIMBOLOS, PUBLICIDAD Y PROPAGANDA GUBERNAMENTAL PARA EL ESTADO DE BAJA CALIFORNIA SUR | 1 | as first published: 11 August 2019 |
| `ley-sobre-el-regimen-de-propiedad-en-condominio/` | LEY SOBRE EL REGIMEN DE PROPIEDAD EN CONDOMINIO DEL ESTADO DE BAJA CALIFORNIA SUR | 3 | as first published, then each reform: 1 December 2007 to 31 October 2016 |
| `ley-sobre-el-uso-de-medios-electronicos-y-firma-electronica/` | LEY SOBRE EL USO DE MEDIOS ELECTRONICOS Y FIRMA ELECTRONICA PARA EL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA SUR | 2 | as first published, then each reform: 1 January 2019 to 21 December 2024 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mazatlan, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
