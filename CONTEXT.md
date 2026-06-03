# Context: Bio PAU 2026 — Carlota

**Data creació:** 3 de juny de 2026  
**Arxiu principal:** `/Users/eloip/Desktop/bio-pau-2026/index.html`  
**Examen PAU:** 11 de juny de 2026 (08:00 dies restants des del 3 de juny)  
**Idioma web:** Català (PAU Cataluña usa DNA/RNA, no ADN/ARN)

## Descripció del projecte
Web d'estudi interactiva personalitzada per a la Carlota per preparar la PAU de Biologia de Catalunya 2026.

## Estat actual (3 juny 2026)
- Web completa amb 10 temes, 6 pantalles per tema
- En Castellà → **PENDENT traduir al Català** 
- Terminologia ADN/ARN → **PENDENT canviar a DNA/RNA** (format PAU)
- Test tipus PAU en les pantalles 5 → **PENDENT afegir preguntes reals 2024**
- Bug: text massa fosc en opcions del tipus test → **PENDENT arreglar**
- Simulacre PAU (20 preguntes aleatòries) funciona
- Mode Pànic funciona
- Comtador dies per a l'examen funciona
- Progrés guardat en localStorage

## Temes coberts (10)
1. DNA i RNA
2. Síntesi de proteïnes
3. Sistema Immunitari
4. La Cèl·lula
5. Mitosi i Meiosi
6. Enzims
7. Virus i Bacteris
8. Fotosíntesi
9. Biomolècules
10. Mutacions i Eng. Genètica

## ATENCIÓ: Temes PAU 2024 NO coberts a la web
- **Respiració cel·lular** (Sèrie 5, Exercici 5 — fermentació làctica vs respiració aeròbica)
- **Evolució** (Sèrie 5, Exercici 1 — selecció natural, especiació, deriva genètica)

## Arxius PAU disponibles (Descarregues)
- `/Users/eloip/Downloads/pau_biol24jl.pdf` — Examen PAU 2024 (Sèries 1 i 5)
- `/Users/eloip/Downloads/pau_biol24jp correccion.pdf` — Correcció PAU 2024
- `/Users/eloip/Downloads/Examen Biología de Cataluña (Ordinaria de 2025)*.pdf` — Examen 2025 (necessita poppler per llegir)

## Preguntes PAU 2024 rellevants per tema

### DNA i RNA (Sèrie 1, Exercici 1)
- Dues diferències components químics DNA/RNA (desoxiribosa vs ribosa, timina vs uracil)
- Identificar tipus RNA en expressió gènica → RNA missatger
- Completar taula codi genètic: RNA AUU-CGU-GAG-ACU-UCA → Ile-Arg-Glu-Thr-Ser
- Transcripció (nucli) + traducció (ribosomes)

### Sistema Immunitari (Sèrie 1, Exercicis 2 i 3 + Sèrie 5 Exercici 2)
- Estructura virus dengue (A=embolcall lípids+proteïnes, B=material genètic RNA, C=nucleocàpsida proteïnes)
- Per què infecció per 1 serotip dengue no dona immunitat als altres → anticossos específics per antígens embolcall
- PCR diagnòstica — retrotranscriptasa (enzim RNA→DNA), resultat positiu (el material genètic s'amplifica)
- Resposta immunitària: macròfags→limfòcits Th→limfòcits B (anticossos)+T citotòxics+cèl·lules memòria
- Sistema del complement: proteïnes en cascada que formen porus a membranes i lisene cèl·lules
- Errades sobre histamina: 1) histamina NO és anticòs, és molècula senyal; 2) eosinòfils NO la secreten, la secreten mastòcits i basòfils
- Seroteràpia: proteïnes (immunoglobulines), immunització PASSIVA i ARTIFICIAL

### Virus i Bacteris (Sèrie 1, Exercicis 2 i 4)
- Estructura virus: embolcall (lípids+proteïnes), material genètic (RNA o DNA), càpsida (proteïnes)
- PCR: primers específics al material genètic del virus → amplifica milions de còpies
- Classificació bacteriana: bacil=forma allargada, heteròtrof=font C matèria orgànica, gramnegatiu=paret peptidoglicà+membrana externa
- Transferència horitzontal: conjugació (contacte directe, pili), transducció (bacteriòfag), transformació (captura DNA del medi)

### Fotosíntesi (Sèrie 1, Exercici 5 + Sèrie 5, Exercici 4)
- Via A (inhibida per Paraquat) = fotofosforilació/fase lluminosa → en tilacoides del cloroplast
- Biomolècules necessàries per cicle de Calvin: NADPH + ATP
- Fotosistema II: fotòlisi de l'aigua → allibera O₂
- Fotosistema I: no allibera O₂ → no es pot mesurar per oxigen
- Anabolisme organismes fotosintètics: Cicle de Calvin SÍ, Fotofosforilació SÍ; Glucòlisi NO, Krebs NO, Fosforilació oxidativa NO

### Biomolècules (Sèrie 5, Exercici 3)
- Identificació: A=àcid nucleic/DNA, B=glúcid/polisacàrid, C=lípid/triacilglicèrid, D=polipèptid/proteïna
- Histamina: molècula senyal (no anticòs!), secretada per mastòcits i basòfils, provoca inflamació

### Mutacions i Genètica (Sèrie 1, Exercicis 3 i 6 Sèrie 5)
- Teràpia gènica: virus = vector (transporta i introdueix el gen funcional)
- Enzims de restricció: tallen DNA en seqüències concretes
- Ligases: uneixen fragments de DNA (DNA recombinant)
- Herència autosòmica recessiva: cal hereda 2 còpies de l'al·lel defectuós
- Herència autosòmica vs lligada al sexe: si el gen és en un autosoma (cr.1) → autosòmica

## Indicacions de l'usuari (Eloi, 3 juny 2026)
1. ✅ Traduir tot al Català (idioma PAU)
2. ✅ Canviar ADN/ARN → DNA/RNA (terminologia PAU)
3. ✅ Arreglar text fosc en opcions tipus test
4. ✅ Afegir preguntes reals de la selectivitat (2024 + variacions inventades)
5. ✅ Per cada pregunta PAU: si no sap la resposta → mostrar tots els conceptes relacionats + guia pas a pas + exercicis similars
6. ✅ Aprendre per capes: conceptes → exemples → test → PAU real
7. ✅ Guardar context fora de unobis

## Notes tècniques
- `localStorage` key: `bio-pau-progress2`
- Examen el 11 de juny 2026 (codificat a `new Date('2026-06-11T09:00:00')`)
- CSS dark theme: bg=#0f0f13, accent=#6c63ff, green=#00c896, yellow=#ffd166, red=#ff4757
- El PDF del 2025 necessita `brew install poppler` per llegir
