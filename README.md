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

## Attribution

Models by the Language Technology Research Group, University of Helsinki:

- Tiedemann, J. & Thottingal, S. (2020). *OPUS-MT — Building open translation
  services for the World.* EAMT 2020.
- Tiedemann, J. (2020). *The Tatoeba Translation Challenge — Realistic Data Sets
  for Low Resource and Multilingual MT.* WMT 2020.

**Changes:** weights converted to CTranslate2 format with int8 quantization and
packaged in the Argos Translate format; sentence segmentation uses Stanza models
(Apache-2.0) taken from Argos Translate packages.

CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/ ·
Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
