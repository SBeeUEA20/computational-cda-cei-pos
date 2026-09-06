# Critical Entity Identification Dataset

This repository contains the annotated dataset used for Critical Entity Identification (CEI) and rhetorical positioning experiments conducted as part of doctoral research into computational analysis of political discourse.

## Dataset

`maindatasetv5.csv`

The dataset contains manually annotated extracts from political speech data.

### Columns

| Column | Description |
|---|---|
| `text` | Source sentence or context containing the annotated entity |
| `word` | Annotated CEI span |
| `start` | Character start position of the annotated span |
| `end` | Character end position of the annotated span |
| `NER_labels` | CEI entity class (`IDENTITY_MARKER` or `PRONOUN`) |
| `POS_labels` | Rhetorical positioning assigned to the entity (`positive`, `negative`, or `neutral`) |

## Annotation framework

A **Critical Entity (CEI)** is a discourse object that can be rhetorically positioned within political discourse.

The annotation framework includes:

- people and social groups;
- organisations and institutions;
- places;
- political and social concepts;
- abstract discourse objects;
- normative values;
- referential pronouns;
- complete noun phrases where modifiers contribute to the construction of an entity's identity.

Positioning annotations describe how each CEI is rhetorically positioned within its local discourse context.

The annotation scheme treats entity identification and positioning as separate tasks.

## Intended use

The dataset was developed for research into:

- Critical Entity Identification;
- rhetorical positioning;
- political discourse analysis;
- token classification;
- transfer learning and domain adaptation;
- multi-task NLP architectures.

## Format

The dataset is supplied as UTF-8 encoded CSV.

## Licence

The annotations and dataset structure produced by the author are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0).

Underlying source speech material remains subject to any rights associated with its original source.

## Citation

Citation information will be added following publication of the associated research.