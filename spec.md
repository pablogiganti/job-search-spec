spec_version=2026-09-12.1
spec_sha256=85197563f6280840
generated_at=2026-09-12T07:55:55.932Z

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
NO ME MUDO FUERA DE ESPAÑA. Soy ciudadano de la UE, así que no tengo problema
legal, pero eso no significa que me traslade: son dos cosas distintas. Dentro de
España sí me plantearía mudarme.
- SÍ: remoto desde España; remoto Europa/EMEA sin país atado; remoto worldwide;
  listas explícitas de países que incluyan España; cualquier ubicación DENTRO de
  España (Madrid, Barcelona, Valencia, Zaragoza, presencial o híbrido).
- NO: cualquier rol que exija residir fuera de España, aunque sea remoto y aunque
  sea la UE. Un "remoto" con país pegado NO es remoto, es residencia obligatoria:
  "Remote, Ireland", "AUT-Remote", "DE-Germany-Remote", "Remote (within UK)",
  "Home Office Portugal" y equivalentes son DESCARTE.
- NO: presencial o híbrido en cualquier ciudad no española (Londres, Dublín,
  Berlín, París, Milán, Estocolmo, Ámsterdam, Zúrich, Dubái...).
- NO: roles que exijan residencia o autorización en EEUU ni Canadá.
- NO: roles locales de India, APAC, LATAM (salvo remoto abierto a Europa o a España).

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
Primera línea:  SPEC | 2026-09-12.1 | OK
Segunda línea SIEMPRE (auditoría, incluso con SIN_NOVEDADES):
  STATS | candidatas=<N> | descartadas_geo=<N> | descartadas_titulo=<N> | descartadas_fecha=<N> | descartadas_otro=<N>
  (candidatas = vacantes que miraste antes de filtrar; si no puedes contarlas, pon ?)
Después, una vacante por línea:  titulo | empresa | url | ubicacion | fecha_publicacion
Si no hay resultados válidos:  SPEC | 2026-09-12.1 | SIN_NOVEDADES  (seguido igualmente de la línea STATS)
