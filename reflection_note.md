# Reflection Note: Comparing My DTD and TEI_all

Working with my own DTD for Assignment 1 and then encoding the same letters with TEI_all for Assignment 2 made me realise how different a simple custom structure is from a full encoding standard. This reflection explains what stayed similar, what changed, and what TEI_all allowed me to understand about editorial needs.

## Similarities with My DTD

Some structural ideas from my DTD aligned with TEI_all.  
I had already identified the basic components of a letter: a header-like zone with author, recipient, and date; a body divided into paragraphs; and an opener and closer.  
I also knew I would need elements for names, places, and dates, since correspondence relies heavily on identifying participants and context. These similarities made the transition to TEI smoother.

## What TEI_all Allowed That My DTD Could Not

Using TEI_all made me see how limited my DTD really was. Three aspects stood out clearly:

1. **Manuscript description.**  
   TEI provides `<msDesc>`, `<physDesc>`, `<handDesc>`, `<additions>`, and `<layoutDesc>`.  
   My DTD had no way to describe handwriting, marginalia, physical layout, or page features.

2. **Editorial and diplomatic encoding.**  
   TEI includes `<choice>`, `<abbr>`, `<expan>`, `<sic>`, `<corr>`, `<hi>`, `<supplied>`, and `<pc>`.  
   My DTD could not express abbreviations, corrections, underlining, pseudonyms, or supplied punctuation.

3. **Correspondence metadata.**  
   `<correspDesc>` and `<correspAction>` offer a precise, standard model for sender, addressee, place, and date.  
   My DTD only had a simple `<header>` without real structure.

## What TEI_all Still Could Not Express

One limitation is the lack of a fully specialised element for **printed vs handwritten letterheads**.  
I used `<note type="letterhead">`, which works, but a customised schema could model these paratextual features more explicitly.

## What I Learned

Designing my DTD taught me to identify the essential components of a text.  
Using TEI_all showed me the richness and flexibility required for real scholarly encoding.  
Overall, the comparison helped me see TEI not just as a technical format, but as a set of editorial decisions shaped by purpose and interpretation.
