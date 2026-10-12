[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# الذكاء الاصطناعي العربي الرائع (Awesome Arabic AI)

العربية | [English](README.md)

فهرس منتقى لأدوات الذكاء الاصطناعي العربية وخوادم MCP وسير العمل.

## المحتويات

- [النماذج التأسيسية ومعالجة الصوت](#النماذج-التأسيسية-ومعالجة-الصوت)
- [مكتبات وأدوات المطورين](#مكتبات-وأدوات-المطورين)
- [خوادم وتكاملات MCP](#خوادم-وتكاملات-mcp)
- [الأتمتة وسير العمل](#الأتمتة-وسير-العمل)
- [مجموعات البيانات والتقييم](#مجموعات-البيانات-والتقييم)

## النماذج التأسيسية ومعالجة الصوت

- [AceGPT](https://huggingface.co/FreedomIntelligence/AceGPT-13B) - نموذج لغوي عربي مبني على معمارية Llama ومخصص لمعالجة النصوص العربية.
- [ALLaM](https://huggingface.co/al-allam) - نموذج لغوي توليدي للغة العربية طورته الهيئة السعودية للبيانات والذكاء الاصطناعي (سدايا).
- [AraBERT](https://github.com/aub-mind/arabert) - نموذج تحويلي مدرب مسبقاً لفهم النصوص العربية وتصنيفها اللغوي.
- [AraELECTRA](https://huggingface.co/aubmindlab/araelectra-base-generator) - نموذج تمثيل لغوي يعتمد معمارية Electra لتحليل النصوص العربية.
- [Falcon](https://falconllm.tii.ae) - عائلة نماذج لغوية مفتوحة الأوزان طورها معهد الابتكار التكنولوجي في أبوظبي تدعم العربية.
- [Fanar](https://fanar.qcri.org) - مشروع نموذج محادثة لغوي طوره معهد قطر لبحوث الحوسبة لدعم الثقافة واللغة العربية.
- [Jais](https://huggingface.co/core42/jais-13b-chat) - نموذج تأسيسي ثنائي اللغة يجمع العربية والإنجليزية طورته Core42 بالتعاون مع جامعة محمد بن زايد للذكاء الاصطناعي وسيريبراس.
- [MMS Arabic](https://huggingface.co/facebook/mms-1b-all) - نقطة تفتيش لنماذج شركة ميتا الصوتية تدعم تحويل الصوت العربي إلى نصوص مكتوبة.
- [Silma](https://huggingface.co/silma-ai) - عائلة نماذج مفتوحة الأوزان معدلة لاتباع التعليمات وتوليد المحادثات باللغة العربية.
- [Whisper Arabic](https://huggingface.co/tarteel-ai/whisper-base-ar-quran) - نموذج للتعرف التلقائي على الكلام مخصص لتفريغ النصوص والآيات القرآنية باللغة العربية.

## مكتبات وأدوات المطورين

- [arabic-reshaper](https://github.com/mpcabd/python-arabic-reshaper) - حزمة بايثون لإعادة تشكيل الحروف العربية المتصلة للبيئات التي تفتقر للدعم التلقائي للنصوص الموجهة.
- [CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools) - حزمة أدوات مفتوحة المصدر لمعالجة اللغة العربية تشمل التقطيع الصرفي والنمذجة اللغوية.
- [Farasa](https://github.com/qcri/farasa) - مجموعة أدوات سريعة لمعالجة النصوص العربية طورها معهد قطر لبحوث الحوسبة لدعم تجزئة الكلمات والتحليل الصرفي.
- [Mishkal](https://github.com/linuxscout/mishkal) - مكتبة بايثون متخصصة في التشكيل التلقائي وضبط أواخر الكلمات للنصوص العربية.
- [PyArabic](https://github.com/linuxscout/pyarabic) - مكتبة بايثون توفر وظائف قياسية لمعالجة النصوص العربية، إزالة التشكيل، وتوحيد ترميز الحروف.
- [python-bidi](https://github.com/MeirKriheli/python-bidi) - تنفيذ بلغة بايثون لخوارزمية يونيكود ثنائية الاتجاه لضبط عرض النصوص المكتوبة من اليمين إلى اليسار.
- [Qalsadi](https://github.com/linuxscout/qalsadi) - مكتبة بايثون تقدم تحليلاً صرفياً ومعجمياً للكلمات العربية.
- [Tashaphyne](https://github.com/linuxscout/tashaphyne) - مكتبة بايثون للاشتقاق الخفيف وتجذير الكلمات العربية لتطبيقات البحث ومعالجة النصوص.

## خوادم وتكاملات MCP

- [Aladhan MCP](https://github.com/thefirstmcp/aladhan-mcp) - خادم MCP لحساب مواقيت الصلاة وتحويل التواريخ الهجرية عبر واجهة برمجة تطبيقات Aladhan.
- [Arabic Scholar MCP](https://github.com/EngDawood/arabic-scholar-mcp-server) - خادم MCP للبحث في الأبحاث والرسائل العلمية العربية عبر مستودعات أكاديمية إقليمية.
- [DataSaudi MCP](https://github.com/mohsinmshabbir/datasaudi-mcp) - خادم MCP للاستعلام باللغة العربية عن المؤشرات الاقتصادية وبيانات الإحصاء المفتوحة في المملكة العربية السعودية.
- [IslamQA MCP](https://github.com/ovehbe/islamqa-mcp) - خادم MCP يتيح الاستعلام والبحث الموثق في أرشيف الفتاوى باللغتين العربية والإنجليزية.
- [Quran MCP](https://github.com/quran/quran-mcp) - خادم بروتوكول سياق النماذج الرسمي من Quran.com للوصول إلى النص القرآني والترجمات المعتمدة.
- [Tafsir MCP](https://github.com/tafsircenter/tafsir-mcp) - خادم MCP علمي معتمد من مركز تفسير يوفر نصوص القرآن وتفاسيره الكلاسيكية وتحليلاً لغوياً للجذور.

## الأتمتة وسير العمل

- [ChatbotTT](https://github.com/RideneFiras/ChatbotTT) - محرك سير عمل لخدمة العملاء يربط n8n بنموذج Whisper لدعم المحادثات باللغة العربية واللهجات المحلية.
- [filament-n8n-chat](https://github.com/alkoumi/filament-n8n-chat) - واجهة محادثة لربط سير عمل n8n بلوحات تحكم Filament مع دعم كامل للغة العربية.
- [n8n-nodes-salla](https://github.com/aolamer/n8n-nodes-salla) - حزمة عقد مجتمعية لمنصة n8n لأتمتة إدارة الطلبات والمنتجات على منصة سلة للتجارة الإلكترونية.
- [n8n-nodes-waha](https://github.com/devlikeapro/n8n-nodes-waha) - حزمة عقد لربط n8n بواجهة برمجة تطبيقات واتساب (WAHA) لأتمتة إرسال الرسائل وخدمة العملاء.
- [n8n-nodes-zid](https://github.com/aolamer/n8n-nodes-zid) - حزمة عقد مجتمعية لمنصة n8n لربط عمليات متجر زد وبيانات العملاء ضمن تدفقات عمل مؤتمتة.

## مجموعات البيانات والتقييم

- [ALUE](https://github.com/Alue-Benchmark/alue_baselines) - حزمة تقييم مرجعية لقياس أداء النماذج اللغوية في فهم واستيعاب النصوص العربية عبر مهام تصنيف متعددة.
- [Arabic MMLU](https://huggingface.co/datasets/MBZUAI/Arabic_MMLU) - مقياس اختبار شامل ومتعدد التخصصات لتقييم فهم النماذج للمواد الأكاديمية والثقافية باللغة العربية.
- [Arabic Speech Corpus](https://huggingface.co/datasets/arbml/arabic_speech_corpus) - مجموعة بيانات صوتية مفتوحة تضم تسجيلات منطوقة ومتوازنة صوتياً باللغة العربية الفصحى.
- [Arabic Web240M](https://huggingface.co/datasets/aubmindlab/arabic-web240m) - قاعدة نصوص عربية منقحة وواسعة النطاق مخصصة لتدريب النماذج اللغوية التأسيسية مسبقاً.
- [ArSarcasm](https://github.com/Ibrahim-AbuFarha/ArSarcasm) - مجموعة بيانات موسومة لمنشورات وسائل التواصل الاجتماعي لدراسة السخرية وتحليل المشاعر باللغة العربية.
- [Common Voice Arabic](https://huggingface.co/datasets/mozilla-foundation/common_voice_17_0) - مجموعة بيانات صوتية مفتوحة المصدر طورتها موزيلا لتدريب نماذج التعرف على الكلام العربي.
- [HARD](https://github.com/elnagar/HARD-Arabic-Dataset) - قاعدة بيانات تقييمات الفنادق العربية تضم أكثر من 100 ألف مراجعة مصنفة لتحليل المشاعر.
- [Khaleej-2004](https://huggingface.co/datasets/arbml/khaleej) - مجموعة بيانات قياسية لتصنيف النصوص تضم مقالات إخبارية عربية مصنفة حسب الموضوع.
- [LABR](https://github.com/mohammed-khalifa/LABR) - مجموعة بيانات مراجعات الكتب العربية الكبيرة تضم أكثر من 63 ألف مراجعة لأبحاث تحليل المشاعر.
- [MADAR](https://huggingface.co/datasets/camel-lab/madar_parallel_corpus) - قاعدة بيانات موازية للهجات العربية تغطي 25 مدينة لدعم تصنيف وترجمة اللهجات المحلية.
- [MGB-2](https://huggingface.co/datasets/arbml/mgb2_transcription) - مجموعة بيانات قياسية للبث التلفزيوني تضم أكثر من 1,200 ساعة مسجلة ومفرغة باللغة العربية.
- [OSCAR Arabic](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301) - قاعدة نصوص ضخمة ومفلترة من زحف الويب العام مخصصة للتدريب المسبق لنماذج اللغة العربية.
- [QALB](https://github.com/CAMeL-Lab/qalb) - مدونة نصوص محررة ومصححة أُعدت لتطوير أنظمة التدقيق الإملائي والتصحيح النحوي للنصوص العربية.
- [QASID](https://huggingface.co/datasets/arbml/qasid) - مجموعة بيانات للأسئلة والأجوبة واختبارات القراءة المستخرجة من مقالات إخبارية باللغة العربية الفصحى.
- [Shami](https://huggingface.co/datasets/aubmindlab/shami) - مدونة نصوص لهجية تركز على لهجات بلاد الشام لدراسة ومعالجة النصوص المحلية.
- [Tashkeela](https://huggingface.co/datasets/arbml/tashkeela) - قاعدة نصوص عربية مشكولة بالكامل تُستخدم لتدريب واختبار خوارزميات التشكيل الآلي للنصوص.

## المساهمة

انظر [CONTRIBUTING.md](CONTRIBUTING.md) لقواعد التقديم.

## الرخصة

هذه القائمة منشورة بموجب [LICENSE](LICENSE) (CC0 1.0 Universal).
