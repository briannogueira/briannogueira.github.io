# Computational Analysis of the Greek New Testament

Researcher: Brian Nicolas Nogueira — Faculdade Batista do Rio de Janeiro Seminário do Sul
ORCID: 0009-0004-0705-0710
Preprint DOI: 10.5281/zenodo.23695706

## Summary

The lexical and morphological structure of the Greek New Testament is
intensively studied, yet the underlying analyses are rarely reproducible.
This project builds an open, agent-assisted pipeline that ingests
public-domain Greek New Testament texts, normalises and tokenises them,
reuses open morphological annotations, and computes reproducible lexical
statistics across books and genres.

## Methods

1. Corpus — assemble public-domain editions (SBLGNT; Robinson–Pierpont)
   with stable verse coordinates.
2. Normalização — Unicode NFC normalisation and Koine-tuned tokenisation.
3. Anotação morfológica — reuse MorphGNT tags; flag low-confidence tokens.
4. Estatística lexical — lemma frequency, hapax legomena, type–token
   ratio, genre distribution, collocations.
5. Pipeline agêntico — implemented in Google Antigravity, versioned and
   containerised for exact re-runs.

## Deliverables

- Open-source pipeline (documented, tested)
- Citable dataset of lexical statistics (DOI)
- Preprint with method, results and limitations

## Contact

- E-mail: brian.33842@seminariodosul.com.br
- ORCID: 0009-0004-0705-0710
- GitHub: https://github.com/briannogueira
