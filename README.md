# LaTeX-Vorlagen für Fach- und weiteren Arbeiten

Dieses Repository verwendet ein standardisiertes Schema zur Benennung der Vorlagenordner, damit Varianten leicht auffindbar, verständlich und versionierbar sind.

---

## Ordnerschema

```plaintext
<projekt>_<dokuart>_<merkmal>_<zitierstil>_<compiler>_v<version>
```

---

## Elemente im Detail

| Element        | Beschreibung                                        | Beispiele                                                                             |
| -------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------- |
| `<projekt>`    | Bildungskontext oder Bereich                        | `agogis`, `ipa`, `fh`, `gym`, `matura`                                                |
| `<dokuart>`    | Typ der Arbeit                                      | `facharbeit`, `abschlussarbeit`, `projektbericht`                                     |
| `<merkmal>`    | Unterscheidungsmerkmal (Layout, Struktur, Features) | `coverimg`, `textcover`, `minimal`, `helvetica`, `doppelseitig`, `hermes5`, `compact` |
| `<zitierstil>` | Zitationsstandard                                   | `apa`, `mla`, `chicago`, `ieee`                                                       |
| `<compiler>`   | Verwendete LaTeX-Engine                             | `pdflatex`, `xelatex`, `lualatex`                                                     |
| `v<version>`   | Versionierung (beliebig fein)                       | `v25`, `v25.1`, `v25.1.2`, `v26-beta`                                                 |

---

## Beispiele für konkrete Ordnernamen

| Ordnername                                                   | Bedeutung                                          |
| ------------------------------------------------------------ | -------------------------------------------------- |
| `agogis_facharbeit_coverimg_apa_pdflatex_v25`                | Agogis-Facharbeit mit Bilddeckblatt, APA, pdfLaTeX |
| `agogis_facharbeit_textcover_apa_pdflatex_v25.1`             | Agogis, textbasiertes Deckblatt                    |
| `ipa_abschlussarbeit_hermes5_textcover_apa_pdflatex_v25.2.1` | IPA, HERMES 5 Stil, textzentriertes Deckblatt      |
