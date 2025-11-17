# Wilde Correspondence Encoding Project — ReadMe (Assignment 2)

**Student:** Clara Martin  
**Course:** Modelling Humanities Data with TEI-XML  
**Instructor:** Dr. Katarzyna Anna Kapitan  

---

## Project Overview

For Assignment 2, I encoded three manuscript letters written by **Oscar Wilde** using the **TEI_all** schema.  
The letters come from different moments of Wilde’s life and from three different libraries, which gave me a good understanding of how cataloguing practices and digitisation vary between institutions.

The corpus includes:

- **Letter to John Lane (1894)** – A publishing letter about proofs, printing numbers, book pricing, and American copyright.  
  *I did not transcribe this letter myself: I used the transcription provided by the Morgan Library & Museum.*

- **Letter to Major J. O. Nelson (1897)** – Written just after Wilde left Reading Gaol. He thanks the governor for his kindness and reflects on prison life and reform.  
  *I used the transcription provided by the New York Public Library.*

- **Letter to Henrietta Stannard (1897)** – A personal and discreet letter written in Berneval-sur-Mer under the pseudonym Sebastian Melmoth. Wilde talks about gratitude, solitude and secrecy.  
  *I transcribed this letter myself directly from the manuscript images (TCD MS 11437/1/1/5).*

Together, these three letters show Wilde moving from professional literary concerns (Lane) to deep personal reflection after imprisonment (Nelson and Stannard).

---

## Encoding Approach

The goal of Assignment 2 was to create **fully valid TEI XML files** using the **TEI_all.rng** schema.  
I focused on:

- producing a **complete teiHeader** with ms descriptions, provenance, and correspondence details  
- encoding **letter structure**: letterhead, opener, paragraphs, closer, signature  
- representing **lineation** with `<lb/>`  
- marking **abbreviations** and expansions with `<choice>`  
- encoding **pseudonyms, place names, foreign words, and emphasis**  
- capturing **marginal notes** and **archival pencil marks** in `<additions>`  
- keeping a **diplomatic transcription** (no normalisation)

For the Stannard letter, I also had to interpret unreadable passages, mark uncertainties, and keep physical information such as indentation and underlining.

---

## AI Use Statement

I used ChatGPT to help me:

- clarify TEI encoding rules,  
- check the structure of my TEI files,  
- and fix validation errors with TEI_all.

However, **all encoding decisions, metadata research, and all transcription work (especially the entire Stannard letter)** were done by me. The final XML files represent my own understanding and editorial judgment.  
