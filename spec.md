spec_version=2026-08-26.1
spec_sha256=cc1fa9bf2674ab25
generated_at=2026-08-26T16:16:28.281Z

# Spec de búsqueda de vacantes — Pablo (generado, NO editar a mano)

REGLA CERO (fail-closed): si no puedes leer este archivo completo o falta
spec_version, ABORTA y devuelve únicamente: SPEC | UNKNOWN | SPEC_FETCH_ERROR
Nunca uses un spec anterior, memoria ni contexto de proyecto como sustituto.

## Perfil de búsqueda
Nivel: Senior / Lead / Staff / Principal. Solo remoto (base: Barcelona, España).

ROL CENTRAL — PRIORIDAD 1 (la mayoría de tus búsquedas deben usar ESTOS títulos):
Project Manager, Program Manager, Scrum Master, Delivery Manager, Delivery Lead, Agile Coach, Agile Delivery.
Mi función es Project/Program/Delivery Manager (desde 2022 con ese título;
20+ años de carrera profesional en total, no de PM).
No descartes vacantes que pidan 2-5 años de gestión de proyectos: entran en rango.

TAMBIÉN ENCAJO — prioridad 2 (complemento, nunca la mayoría del resultado):
Technical Product Manager, Growth Product Manager, Product Owner, Technical PM, Platform Product Manager, AI Product Manager, Senior Product Manager, Group Product Manager.

REGLA DE DISTRIBUCIÓN (dura): al menos la MITAD de las vacantes de cada entrega
deben ser del ROL CENTRAL (Project/Program/Delivery/Scrum). Si tu búsqueda solo
encuentra Product Manager, busca más con los títulos centrales antes de entregar.

## Elegibilidad geográfica (regla dura)
- SÍ: remoto desde España; remoto Europa/EMEA/UK/Irlanda; remoto worldwide.
- NO: roles que exijan residencia o autorización en EEUU ni Canadá.
  "Remote UK" sin mención explícita de EU/España significa remoto DENTRO de UK: descártalo.
- NO: roles locales de India, APAC, LATAM (salvo remoto abierto a Europa).

## Sectores
- PRIORIDAD: Media & Entertainment, Gaming, Music / Events tech, Publishing / Digital content, Adtech / Martech platforms, Creative SaaS / Design tools, Arts & Culture / Streaming.
- Aceptable con menor prioridad: SaaS/tech general, fintech, seguros.
- Mi función es fija (PM/delivery): NO roles de marketing ni creativos.

## Exclusiones duras
- Niveles: Junior, Associate, Internship, Graduate, Apprentice, Trainee, Werkstudent, Stagiaire, Jr..
- Dominios: Construction, Clinical, Environmental, Roofing, Cabling, Gas Power, Solid Waste, Commissioning, PFAS, Geologist.
- Stacks como especialización del rol: .NET, Java , iOS, Android, PHP, Ruby, Embedded, Firmware, Blockchain, Web3, Crypto, Mainframe, COBOL, Product Marketing Manager, PMM.
- Empresas vetadas: Neotalent, Neotalent Conclusion, Conclusion, Turner & Townsend, Turner and Townsend.
- Contratos temporales/fixed-term: solo si son excepcionales.

## Compensación
Descarta vacantes que publiquen salario claramente por debajo de 70K EUR.

## Calidad de resultados (crítico)
- Vacantes publicadas en los últimos 3 días.
- URL ORIGINAL del empleador o su ATS (greenhouse, ashby, lever, workable,
  workday, careers propia). Nada de páginas de búsqueda de agregadores.
- Solo URLs abiertas y verificadas en esta ejecución. PROHIBIDO inventarlas.
- No dedupliques contra días anteriores: el sistema receptor deduplica.
- ENTREGA SIEMPRE lo que encuentres. La regla de distribución ordena tu esfuerzo
  de búsqueda, NO justifica retener resultados: si tras buscar con los títulos
  centrales sigues teniendo solo prioridad 2, entrégalos igualmente con status OK.
  SIN_NOVEDADES es SOLO para cuando no sobrevive ninguna vacante válida.

## Contrato de salida (estricto — sin prosa, sin markdown, sin citas)
Primera línea:  SPEC | 2026-08-26.1 | OK
Segunda línea SIEMPRE (auditoría, incluso con SIN_NOVEDADES):
  STATS | candidatas=<N> | descartadas_geo=<N> | descartadas_titulo=<N> | descartadas_fecha=<N> | descartadas_otro=<N>
  (candidatas = vacantes que miraste antes de filtrar; si no puedes contarlas, pon ?)
Después, una vacante por línea:  titulo | empresa | url | ubicacion | fecha_publicacion
Si no hay resultados válidos:  SPEC | 2026-08-26.1 | SIN_NOVEDADES  (seguido igualmente de la línea STATS)
