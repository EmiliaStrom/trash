# Read me H06b

## Data collection H06b German

Data collection of H06b datasets started on 04.04.2025 and ended on 30.04.2026.

## Data annotation H06b German

### General remarks

1. The study was automatically transcribed and translated by an app.
2. The automatic transcription was manually corrected by a German native speaker who was an (under)graduate student of linguistics and research assistant in the project. The same research assistant picked out the relevant utterances for glossing/coding.
3. The automatic translation based on the corrected transcription was corrected by a second German native speaker who was a graduate student of English and research assistant in the project.
4. The glossing was completed by a third German native speaker and research assistant, who was a student of linguistics.
5. Around 10% of the transcribed, translated and glossed data was cross-checked by the project’s lab manager.
6. The transcription, translation and glossing conventions can be found on Github: https://github.com/LeibnizDream/A02-Instructions/tree/main/Data_Handling_Process

### Transcription and audio files

1. Transcriptions include any utterances made by all parties present, including participants, experimenters or any accompanying third parties.
2. The transcriptions follow the general conventions of the LeibnizDream project which build upon the CHAT manual from the CHILDES webpage: https://github.com/LeibnizDream/A02-Instructions/blob/main/Data_Handling_Process/transcription_conventions.md
3. We strictly adhere to the project’s ethics and keep the participants anonymous, codifying any personal identifiable information (PII); audios containing PII or third party utterances were not published.
4. All utterances were extracted and sorted in order [1], [2] and so on.
5. Markings according to the general transcription guidelines were only used in the overall transcription, not in the chosen utterances. Brackets were only used in the general transcription, not in the chosen utterances.
6. Recordings played from the tablet were marked as EXP.
7. Teachers' utterances were marked as PAR.

### Translation

1. The translation is based on the German transcription and focuses on understandability for non-German speakers.
2. Relevant translation decisions
   a. Interjections (all marked @i):
      - 'hä' = 'huh'
      - 'mhm' = 'mhm'
      - 'mhmhmh' = 'mhmhmh'
      - 'hm' = 'hm'
      - 'hmhm' = 'hmhm'
      - 'öhm' = 'uhm'
      - 'öh' = 'uh'
      - 'äh' = 'uh'
   b. For a word-for-word translation of relevant utterances refer to glossing.
3. Markings were only used in the general translation, not in the translation of the chosen utterances.
4. Brackets were only used in the general translation, not in the translation of the chosen utterances.

### Glossing

1. Glossing was only done for participants’ relevant utterances in accordance with the Leipzig glossing rules: https://www.eva.mpg.de/lingua/pdf/Glossing-Rules.pdf

2. Glossing decisions

   a) Maximal glossing (marking as many features as possible)

   For verbs: `verb-person.number.tense.modus`

   **EXAMPLE:**

   ```
   schubst / push-3.SG.PRS.IND
   ```

   b) Morphosegmentation (in object language, X = root, Y = category)

   i. Morpheme borders were marked with `X-Y`  
   ii. Circumfixes were marked `X>Y<CIRC`  
   iii. Vowel alternations in the stem were marked `X\Y`  
   iv. Examples:

   ```
   (i) hase-n / rabbit-PL
   (ii) ge>rutsch<t / PASTP>slide<CIRC
   (iii) zu-ge-worf-en / at-PASTP>throw<CIRC
   (iiii) sang / sing\PST
   ```

   c) Glossing

   i. Case: Due to syncretism in the German case system, if a morphological form was ambiguous regarding case, all possible cases were marked (e.g., NOM/ACC).

   **EXAMPLE:**

   ```
   die katze / ART.DEF.F.SG.NOM/ACC VS. cat.F.SG.NOM/ACC
   ```

   ii. Gender: Gender features in German are inherent to the root. They were marked only at the corresponding noun if the article/determiner bore the matching gender feature.

   **EXAMPLE:**

   ```
   die katze / ART.DEF.F.SG.NOM/ACC cat.F.SG.NOM/ACC VS. *das katze / ART.DEF.N.SG.NOM cat
   ```

3. Abbreviations used

   a. Categories: ART = article; DEM = demonstrative; REL = relative pronoun  
   b. Case: NOM = nominative; ACC = accusative; DAT = dative; GEN = genitive  
   c. Number: SG = singular; PL = plural  
   d. Person: 1 = first person; 2 = second; 3 = third  
   e. Gender: M = masculine; F = feminine; N = neuter  
   f. Tense: PRS = present; PST = past  
   g. Participles: PASTP = past participle  
   h. Others: CIRC = circumfix; DEF = definite; INDF = indefinite; NEG = negation; INTS = intensifier  

4. Comments in the `glossing_comment` column mark any mismatches/deviation from adult-like grammar.
