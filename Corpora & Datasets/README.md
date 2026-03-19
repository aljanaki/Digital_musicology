# Corpora & Datasets

This folder collects references to the symbolic music datasets used in this project, along with a comparative overview table.

---

## Datasets Used

### Romantic Piano Corpus (DCMLab)
**Repository:** https://github.com/DCMLab/romantic_piano_corpus

A curated corpus of tonal piano music from the long 19th century, annotated with DCML harmony labels (Roman numerals, cadences, phrases, key). Covers 9 composers: Beethoven, Chopin, Debussy, Dvořák, Grieg, Liszt, Medtner, Schumann, and Tchaikovsky.

- **Format:** MusicXML scores + TSV annotation files
- **Size:** ~200 pieces across 9 sub-corpora
- **Annotations:** Roman numerals, cadences, phrase boundaries, key signatures
- **License:** CC BY-NC-SA 4.0

---

### ChoCo – The Chord Corpus (Smashub)
**Repository:** https://github.com/smashub/choco

A large-scale meta-corpus integrating 20,000+ timed chord annotations from 18 source datasets, spanning jazz, pop, rock, folk, and classical music. Annotations are standardised to the Harte notation and released as JAMS files and an RDF knowledge graph.

- **Format:** JAMS (JSON-based) + RDF/TTL
- **Size:** 20,086 pieces, ~1.57M chord observations, 18 source datasets
- **Annotations:** Chord labels (Harte + Roman numerals for some subsets), keys, structural segments
- **License:** CC BY 4.0 (with CC BY-NC-SA 4.0 exceptions for 3 subsets)
- **Paper:** de Berardinis et al., *Scientific Data*, 2023

---

## Dataset Comparison Table

See [`symbolic_midi_datasets.md`](./symbolic_midi_datasets.md) for a full comparative overview of symbolic and MIDI datasets evaluated for this project, including format, size, annotation type, and suitability for contrastive analysis.
