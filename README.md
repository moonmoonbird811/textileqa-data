# TextileQA – anonymised data samples

Randomly drawn examples (seed 42) from the datasets used in the TextileQA study. Enterprise names are replaced by `【企业X】` (the city/district prefix is kept so that questions stay interpretable; the same letter within one record denotes the same enterprise). Unified social credit codes, telephone numbers, detailed addresses, websites and patent application numbers are not included.

| File | Dataset (size in the full study) |
|---|---|
| `firms_sample.json` | Enterprise database (24,825 enterprises) |
| `patents_sample.json` | Patent records (19,485) |
| `chain_and_customs_sample.json` | Industrial-chain stage labels and customs textile product classification mapping |
| `regular_single_entity.json` | Regular benchmark, single-entity queries (1,384 questions) |
| `regular_multi_condition.json` | Regular benchmark, multi-condition logical combinations (924) |
| `disamb_fuzzy_reference.json` | Disambiguation benchmark, fuzzy references |
| `disamb_joint_cues.json` | Disambiguation benchmark, joint cues |
| `disamb_character_deletion.json` | Disambiguation benchmark, character deletion |
| `disamb_exact_match_conflict.json` | Disambiguation benchmark, exact-match conflicts |

Each file has the form `{"dataset", "description", "language", "anonymised", "records": [...]}`. Questions are in Chinese.

The full enterprise database was compiled from commercial business-information platforms and public sources, and is not redistributed here.
