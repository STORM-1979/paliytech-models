# PaliyTech Models

Offline translation models used by **PaliyTechTranslate** (downloaded by the
program on demand). Each `.argosmodel` file is an Argos Translate package
containing a CTranslate2 (int8) conversion of an OPUS-MT model.

| File | Direction | Original model | License |
|------|-----------|----------------|---------|
| `opus_en_uk-opus-1.argosmodel` | English → Ukrainian | [Helsinki-NLP/opus-mt-tc-big-en-zle](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-zle) | CC-BY 4.0 |
| `opus_uk_en-opus-1.argosmodel` | Ukrainian → English | [Helsinki-NLP/opus-mt-tc-big-zle-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-zle-en) | CC-BY 4.0 |
| `opus_ru_uk-opus-1.argosmodel` | Russian → Ukrainian | [Helsinki-NLP/opus-mt-ru-uk](https://huggingface.co/Helsinki-NLP/opus-mt-ru-uk) | Apache-2.0 |
| `opus_uk_ru-opus-1.argosmodel` | Ukrainian → Russian | [Helsinki-NLP/opus-mt-uk-ru](https://huggingface.co/Helsinki-NLP/opus-mt-uk-ru) | Apache-2.0 |
| `opus_en_tr-opus-2.argosmodel` | English → Turkish | [Helsinki-NLP/opus-mt-tc-big-en-tr](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-tr) | CC-BY 4.0 |
| `opus_tr_en-opus-2.argosmodel` | Turkish → English | [Helsinki-NLP/opus-mt-tc-big-tr-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-tr-en) | CC-BY 4.0 |
| `opus_en_ca-opus-2.argosmodel` | English → Catalan | [Helsinki-NLP/opus-mt-tc-bible-big-deu_eng_fra_por_spa-itc](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-deu_eng_fra_por_spa-itc) | Apache-2.0 |
| `opus_pl_en-opus-2.argosmodel` | Polish → English | [Helsinki-NLP/opus-mt-tc-big-zlw-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-zlw-en) | CC-BY 4.0 |
| `opus_en_ko-opus-2.argosmodel` | English → Korean | [Helsinki-NLP/opus-mt-tc-big-en-ko](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-ko) | CC-BY 4.0 |
| `opus_ko_en-opus-2.argosmodel` | Korean → English | [Helsinki-NLP/opus-mt-tc-big-ko-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-ko-en) | CC-BY 4.0 |
| `opus_en_ar-opus-2.argosmodel` | English → Arabic | [Helsinki-NLP/opus-mt-tc-big-en-ar](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-ar) | CC-BY 4.0 |
| `opus_id_en-opus-2.argosmodel` | Indonesian → English | [Helsinki-NLP/opus-mt-tc-bible-big-poz-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-poz-en) | Apache-2.0 |
| `opus_ms_en-opus-2.argosmodel` | Malay → English | [Helsinki-NLP/opus-mt-tc-bible-big-poz-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-poz-en) | Apache-2.0 |
| `opus_ar_en-opus-2.argosmodel` | Arabic → English | [Helsinki-NLP/opus-mt-tc-bible-big-sem-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-sem-en) | Apache-2.0 |
| `opus_he_en-opus-2.argosmodel` | Hebrew → English | [Helsinki-NLP/opus-mt-tc-big-he-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-he-en) | CC-BY 4.0 |
| `opus_en_he-opus-2.argosmodel` | English → Hebrew | [Helsinki-NLP/opus-mt-tc-bible-big-deu_eng_fra_por_spa-sem](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-deu_eng_fra_por_spa-sem) | Apache-2.0 |
| `opus_en_hi-opus-2.argosmodel` | English → Hindi | [Helsinki-NLP/opus-mt-tc-bible-big-deu_eng_fra_por_spa-inc](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-deu_eng_fra_por_spa-inc) | Apache-2.0 |
| `opus_hi_en-opus-2.argosmodel` | Hindi → English | [Helsinki-NLP/opus-mt-tc-bible-big-inc-en](https://huggingface.co/Helsinki-NLP/opus-mt-tc-bible-big-inc-en) | Apache-2.0 |
| `opus_ru_pl-opus-3.argosmodel` | Russian → Polish | [Helsinki-NLP/opus-mt-tc-big-zle-zlw](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-zle-zlw) | CC-BY 4.0 |
| `opus_it_es-opus-3.argosmodel` | Italian → Spanish | [Helsinki-NLP/opus-mt-tc-big-itc-itc](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-itc-itc) | CC-BY 4.0 |
| `opus_de_es-opus-3.argosmodel` | German → Spanish | [Helsinki-NLP/opus-mt-tc-big-de-es](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-de-es) | CC-BY 4.0 |
| `opus_fr_it-opus-3.argosmodel` | French → Italian (light package: shares the it→es model) | [Helsinki-NLP/opus-mt-tc-big-itc-itc](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-itc-itc) | CC-BY 4.0 |
| `opus_it_pt-opus-3.argosmodel` | Italian → Portuguese (light package: shares the it→es model) | [Helsinki-NLP/opus-mt-tc-big-itc-itc](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-itc-itc) | CC-BY 4.0 |

Releases: `opus-uk-1` (Ukrainian), `opus-2` (tc-big / tc-bible-big replacements for weak Argos
directions), `opus-3` (direct models without English pivot). Each release has `manifest.json` with SHA-256 of every file.

## Attribution

Models by the Language Technology Research Group, University of Helsinki:

- Tiedemann, J. & Thottingal, S. (2020). *OPUS-MT — Building open translation
  services for the World.* EAMT 2020.
- Tiedemann, J. (2020). *The Tatoeba Translation Challenge — Realistic Data Sets
  for Low Resource and Multilingual MT.* WMT 2020.

**Changes:** weights converted to CTranslate2 format with int8 quantization and
packaged in the Argos Translate format; sentence segmentation uses Stanza models
(Apache-2.0) taken from Argos Translate packages. Multilingual models get a target-language token
(e.g. `>>por<<`) stored in the package metadata; fr→it and it→pt reuse the it→es model files.

CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/ ·
Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
