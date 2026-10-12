[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# Awesome Arabic AI

[العربية](README.ar.md) | English

A curated index of Arabic artificial intelligence tools, MCP servers, and workflows.

## Contents

- [Foundation Models & Audio](#foundation-models--audio)
- [Developer Tooling & Arabic NLP](#developer-tooling--arabic-nlp)
- [Model Context Protocol (MCP) Servers](#model-context-protocol-mcp-servers)
- [Automations & Workflows](#automations--workflows)
- [Datasets & Benchmarks](#datasets--benchmarks)

## Foundation Models & Audio

- [AceGPT](https://huggingface.co/FreedomIntelligence/AceGPT-13B) - Arabic language model built on the Llama architecture adapted for Arabic text.
- [ALLaM](https://huggingface.co/al-allam) - Arabic generative language model developed by the Saudi Data and Artificial Intelligence Authority (SDAIA).
- [AraBERT](https://github.com/aub-mind/arabert) - Pretrained BERT model for Arabic language understanding and text classification tasks.
- [AraELECTRA](https://huggingface.co/aubmindlab/araelectra-base-generator) - Arabic representation model trained on Electra architecture for text processing.
- [Falcon](https://falconllm.tii.ae) - Open weights language model family developed by the Technology Innovation Institute in Abu Dhabi with Arabic support.
- [Fanar](https://fanar.qcri.org) - Arabic conversational language model project developed by the Qatar Computing Research Institute (QCRI).
- [Jais](https://huggingface.co/core42/jais-13b-chat) - Bilingual Arabic and English foundational model developed by Core42, MBZUAI, and Cerebras.
- [MMS Arabic](https://huggingface.co/facebook/mms-1b-all) - Meta speech model checkpoint supporting automatic speech recognition for Arabic audio.
- [Silma](https://huggingface.co/silma-ai) - Open weights instruction-tuned models optimized for Arabic conversation and text generation.
- [Whisper Arabic](https://huggingface.co/tarteel-ai/whisper-base-ar-quran) - Fine-tuned automatic speech recognition model adapted for Arabic dialect and Quranic transcription.

## Developer Tooling & Arabic NLP

- [arabic-reshaper](https://github.com/mpcabd/python-arabic-reshaper) - Python package for reshaping connected Arabic characters for environments lacking native bidirectional text support.
- [CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools) - Open source suite of tools for Arabic natural language processing including tokenization and morphological modeling.
- [Farasa](https://github.com/qcri/farasa) - Fast Arabic text processing toolkit developed by QCRI supporting word segmentation and morphological tagging.
- [Mishkal](https://github.com/linuxscout/mishkal) - Python library and engine for automatic Arabic text diacritization.
- [PyArabic](https://github.com/linuxscout/pyarabic) - Python library providing basic functions for Arabic text manipulation and normalization.
- [python-bidi](https://github.com/MeirKriheli/python-bidi) - Pure Python implementation of the Unicode Bidirectional Algorithm for bidirectional layout display.
- [Qalsadi](https://github.com/linuxscout/qalsadi) - Python library providing morphological analysis and lexical lookup for Arabic words.
- [Tashaphyne](https://github.com/linuxscout/tashaphyne) - Arabic light stemmer and segmenter for search and text processing applications.

## Model Context Protocol (MCP) Servers

- [Aladhan MCP](https://github.com/thefirstmcp/aladhan-mcp) - MCP server providing prayer times and Hijri calendar conversions via the Aladhan API.
- [Arabic Scholar MCP](https://github.com/EngDawood/arabic-scholar-mcp-server) - MCP server for searching Arabic academic research and dissertations across regional repositories.
- [DataSaudi MCP](https://github.com/mohsinmshabbir/datasaudi-mcp) - Model Context Protocol server for querying official Saudi economic indicators and open data statistics in Arabic.
- [IslamQA MCP](https://github.com/ovehbe/islamqa-mcp) - MCP server and data pipeline for querying bilingual fatwa archives with citation tracking.
- [Quran MCP](https://github.com/quran/quran-mcp) - Official Model Context Protocol server by Quran.com providing structured access to Quranic text and verified translations.
- [Tafsir MCP](https://github.com/tafsircenter/tafsir-mcp) - Scholarly MCP server providing verified Quranic text, classical tafsirs, and root-level linguistic analysis.

## Automations & Workflows

- [ChatbotTT](https://github.com/RideneFiras/ChatbotTT) - Multilingual customer service workflow engine connecting n8n and Whisper to support Arabic and regional dialects.
- [filament-n8n-chat](https://github.com/alkoumi/filament-n8n-chat) - Chat interface connecting n8n workflows with Filament admin panels with Arabic language support.
- [n8n-nodes-salla](https://github.com/aolamer/n8n-nodes-salla) - Community node for n8n to automate orders and product management on the Salla e-commerce platform.
- [n8n-nodes-waha](https://github.com/devlikeapro/n8n-nodes-waha) - Community node package connecting n8n with WhatsApp HTTP API for automated customer messaging flows.
- [n8n-nodes-zid](https://github.com/aolamer/n8n-nodes-zid) - Community node for n8n to integrate Zid store operations and customer data into automated workflows.

## Datasets & Benchmarks

- [ALUE](https://github.com/Alue-Benchmark/alue_baselines) - Evaluation benchmark suite measuring Arabic natural language understanding across varied classification tasks.
- [Arabic MMLU](https://huggingface.co/datasets/MBZUAI/Arabic_MMLU) - Massive multitask language understanding benchmark testing Arabic models on academic and cultural subjects.
- [Arabic Speech Corpus](https://huggingface.co/datasets/arbml/arabic_speech_corpus) - Open speech dataset containing phonetically balanced Modern Standard Arabic speech recordings.
- [Arabic Web240M](https://huggingface.co/datasets/aubmindlab/arabic-web240m) - Large-scale filtered Arabic web text corpus designed for pretraining foundation models.
- [ArSarcasm](https://github.com/Ibrahim-AbuFarha/ArSarcasm) - Annotated dataset of Arabic social media posts for sarcasm and sentiment classification.
- [Common Voice Arabic](https://huggingface.co/datasets/mozilla-foundation/common_voice_17_0) - Crowdsourced speech recognition dataset collected by Mozilla for Arabic voice model training.
- [HARD](https://github.com/elnagar/HARD-Arabic-Dataset) - Hotel Arabic Reviews Dataset containing over 100,000 customer reviews labeled for sentiment classification.
- [Khaleej-2004](https://huggingface.co/datasets/arbml/khaleej) - Benchmark text classification dataset containing Arabic news articles categorized by topic.
- [LABR](https://github.com/mohammed-khalifa/LABR) - Large Arabic Book Reviews dataset containing over 63,000 reader reviews for sentiment analysis.
- [MADAR](https://huggingface.co/datasets/camel-lab/madar_parallel_corpus) - Parallel dialect corpus covering speech patterns from 25 Arab cities for dialect translation and identification.
- [MGB-2](https://huggingface.co/datasets/arbml/mgb2_transcription) - Broadcast speech recognition benchmark containing over 1,200 hours of transcribed Arabic television audio.
- [OSCAR Arabic](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301) - High-volume deduplicated web corpus extracted from Common Crawl for Arabic language pretraining.
- [QALB](https://github.com/CAMeL-Lab/qalb) - Annotated text corpus developed for automated spelling correction and grammatical error correction in Arabic.
- [QASID](https://huggingface.co/datasets/arbml/qasid) - Reading comprehension and question answering dataset constructed from Modern Standard Arabic news articles.
- [Shami](https://huggingface.co/datasets/aubmindlab/shami) - Dialectal text corpus focused on Levantine Arabic varieties for regional dialect processing.
- [Tashkeela](https://huggingface.co/datasets/arbml/tashkeela) - Vocalized Arabic text corpus containing classical texts used to train automatic diacritization systems.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for submission rules.

## License

This list is released under [LICENSE](LICENSE) (CC0 1.0 Universal).
