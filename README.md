# Речевые технологии для русского языка


# Данные для обучения

  * <https://github.com/salute-developers/golos>
  * <https://github.com/snakers4/open_stt>
  * <https://github.com/GeorgeFedoseev/DeepSpeech>
  * <https://github.com/sovaai/sova-dataset>
  * <https://www.openslr.org/96/> - Russian Librispeech
  * <https://commonvoice.mozilla.org/ru/datasets> - MCV

# Синтез речи

  * <https://www.caito.de/2019/01/03/the-m-ailabs-speech-dataset/> - M-AILabs dataset (from Librivox)
  * <https://ruslan-corpus.github.io/>
  * <https://github.com/sovaai/sova-tts>
  * <https://huggingface.co/bene-ges/tts_ru_hifigan_ruslan>
  * <https://github.com/alphacep/vosk-tts>
  * <https://github.com/RHVoice>
  * <https://github.com/snakers4/silero-models#text-to-speech>

# Расстановка ударений, фонетические словари и g2p

  * <https://github.com/reynoldsnlp/udar>
  * <https://github.com/einhornus/russian_accentuation>
  * <https://github.com/wilpert/RusPhonetizer>
  * <https://huggingface.co/bene-ges/ru_g2p_ipa_bert_large>
  * <https://github.com/Desklop/StressRNN>
  * <https://github.com/nsu-ai/russian_g2p>
  * <https://github.com/nsu-ai-team/russian_g2p_neuro>
  * <https://github.com/suralmasha/RuTranscript>
  * <https://github.com/MashaPo/russtress>
  * <https://huggingface.co/IlyaGusev/ru-word-stress-transformer>

# Словари

  * <https://github.com/reynoldsnlp/udar/blob/main/src/udar/resources/src/Tixonov.txt> - Морфемно-орфографический словарь Тихонова
  * <http://aot.ru> - Источник словаря Зализняка в машинном формате 
  * <https://kaikki.org/dictionary/Russian/> - дамп wiktionary в удобном формате

# Ёфикаторы

  * <https://github.com/e2yo/eyo-kernel>
  * <https://github.com/kalashnikovisme/karamzin>
  * <https://github.com/link2xt/yoficator>
  * <https://github.com/Text-extend-tools/python-yoficator>
  * <https://github.com/emacsmirror/yoficator>
  * <https://github.com/unabashed/yoficator>

# Предобработка для синтеза

  * <https://github.com/sovaai/sova-tts-tps>
  * <https://github.com/snakers4/silero-models#text-enhancement>
  * <https://github.com/snakers4/russian_stt_text_normalization>

# Модели для распознавания речи

Сравнение моделей [тут](https://alphacephei.com/nsh/2023/01/22/russian-models.html).

  * Vosk Small <https://alphacephei.com/vosk/models/vosk-model-small-ru-0.22.zip>
  * Vosk Big 0.22 <https://alphacephei.com/vosk/models/vosk-model-ru-0.22.zip>
  * Vosk Big 0.42 <https://alphacephei.com/vosk/models/vosk-model-ru-0.42.zip>
  * Nvidia RNNT Large <https://huggingface.co/nvidia/stt_ru_conformer_transducer_large>
  * Whisper medium <https://github.com/openai/whisper>
  * Whisper Adapted Medium <https://huggingface.co/mitchelldehaven/whisper-medium-ru>
  * Whisper Adapted Large <https://huggingface.co/mitchelldehaven/whisper-large-v2-ru>
  * Wav2VecLM <https://huggingface.co/jonatasgrosman/wav2vec2-xls-r-1b-russian>
  * Wav2VecLM Bond005 <https://huggingface.co/bond005/wav2vec2-large-ru-golos> (version 03.2023)
  * Salute Citrinet <https://github.com/salute-developers/golos>
  * FunASR Russian <https://modelscope.cn/models/damo/speech_UniASR_asr_2pass-ru-16k-common-vocab1664-tensorflow1-offline/summary>

Не тестировались (похуже качеством)

  * <https://github.com/sovse/base_rus_whisper_stt>

# Лингвистика (списки слов, морфология)

  * <http://aot.ru>
  * <https://natasha.github.io>

# Пунткуация и заглавные буквы

  * <https://github.com/kotikkonstantin/ru-autopunctuation>
  * <https://huggingface.co/kontur-ai/sbert_punc_case_ru>
  * <https://github.com/vlomme/Bert-Russian-punctuation>
  * <https://github.com/Lesha17/Punctuation>
  * <https://github.com/gleb-skobinsky/ru_punct>
  * <https://github.com/sviperm/neuro-comma>
  * <https://github.com/snakers4/silero-models>
  * <https://github.com/marlon-br/neuro-comma>
  * <https://github.com/sviperm/neuro-comma>
  * <https://github.com/averkij/multipunct>

# История

  * [А.А. Зализняк Грамматический словарь](https://ru.wikipedia.org/wiki/%D0%93%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D1%8C_%D1%80%D1%83%D1%81%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_%D1%8F%D0%B7%D1%8B%D0%BA%D0%B0_%D0%90._%D0%90._%D0%97%D0%B0%D0%BB%D0%B8%D0%B7%D0%BD%D1%8F%D0%BA%D0%B0)
  * <https://github.com/gramdict/gramdict> - современная версия словаря Зализняка
  * [ОТиПЛ — это кафедра и отделение теоретической и прикладной лингвистики филологического факультета МГУ](http://tipl.philol.msu.ru/)
  * [Лобанов Борис Мефодьевич](https://obm.bsu.by/matematiki/lobanov-boris-mefodevich/)
  * [Русский язык на Voxforge](http://www.voxforge.org/ru)
  * [Festlang Clunits](https://www.opennet.ru/opennews/art.shtml?num=12399)
  * [2005 год начало работы над синтезатором Фестиваль](https://www.linux.org.ru/news/linux-general/775065?cid=776417)
  * [CMUSphinx](https://cmusphinx.github.io/)
