# dagblad-insta-images

Publieke hosting van automatisch gegenereerde Instagram-post-afbeeldingen voor
**Dagblad010** (Rotterdam) en **Dagblad070** (Den Haag).

Deze repo bestaat zodat de **Meta Graph API** (Instagram Content Publishing) de
beelden via een publieke URL kan ophalen. De afbeeldingen in `posts/` worden
dagelijks gegenereerd uit de nieuwste artikelen en daarna gepubliceerd.

- Formaat: 1050×1350 JPEG (Instagram-portret)
- Bestanden in `posts/`, met datum + kanaal in de naam
- Publieke raw-URL: `https://raw.githubusercontent.com/SCMdistro/dagblad-insta-images/main/posts/<bestand>.jpg`

Bevat uitsluitend de post-beelden — geen redactionele bronbestanden of gevoelige data.
