# Bengali-News-Summarization : BengaliGPT and T5
Bengali News Summarization - BengaliGPT and T5


```
pip install --quiet transformers
pip install --quiet pytorch-lightning
pip install --quiet tokenizers
pip install --quiet sentencepiece
pip install --quiet git+https://github.com/csebuetnlp/normalizer
```


==========================================================
Actual Text : ভারতের অন্য অঞ্চলেও কোক, পেপসি নিষিদ্ধ করার দাবি জানাচ্ছেন কর্মীরা। স্থানীয় পণ্যের ব্যবহার নিশ্চিত করার জন্যই এই উদ্যোগ গ্রহণ করেছে ব্যবসায়ীরা। রাজ্যের শীর্ষ দুটি ব্যবসায়ী এসোসিয়েশন এই দুটি পানীয় নিষিদ্ধ করার প্রস্তাব করেছিল। তারই প্রেক্ষাপটে আজ বুধবার থেকে তামিলনাডু রাজ্যে নিষিদ্ধ হলো কোকা-কোলা ও পেপসি। প্রতিষ্ঠানগুলো বলছে, কোমল পানীয়ের প্রতিষ্ঠানগুলো নদী থেকে প্রচুর পানি ব্যবহার করে, সেকারণে কৃষকদের জমি সেচের সময়ও ব্যাপক ভোগান্তিতে পড়তে হয়। বিশেষ করে খরার সময় সেচে পানি সমস্যা প্রকট হয়ে দাঁড়ায়। রাজ্যের দশ লাখেরও বেশি দোকানদার এ নিষেধাজ্ঞা মেনে চলবে বলে ধারণা করা হচ্ছে। গত মাসে তামিলনাডুতে 'জাল্লিকাটু' নামে ঐতিহ্যবাহী ষাঁড়ের লড়াই নিষিদ্ধের বিরুদ্ধে ব্যাপক বিক্ষোভের ঘটনা দেখে রাজ্যে পেপসি, কোকা-কোলা নিষিদ্ধের প্রস্তাব করে শীর্ষ দুটি ব্যবসায়ী সংগঠন ফেডারেশন অব তামিলনাডু ট্রেডার্স এসোসিয়েশন (এফটিএনটিএ) এবং তামিলনাডু ট্রেডার্স এসোসিয়েশন। বিক্ষোভের সময় অনেকে বলছিলেন 'জাল্লিকাটু' নিষিদ্ধ করা মানে স্থানীয় ঐতিহ্য ও সংস্কৃতিকে অবমাননা করা। "আমরা কয়েক মাস আগে কোমল পানীয়ের বিরুদ্ধে আমাদের প্রচারণা শুরু করি, কিন্তু যখন আমরা 'জাল্লিকাটু' নিষিদ্ধের প্রতিবাদে বিক্ষোভ শুরু করি, কোমল পানীয়ের বিরুদ্ধে আমাদের প্রচারণাও ভিন্ন রূপ পায়"- বিবিসি তামিল সার্ভিসকে দেয়া এক সাক্ষাৎকারে বলছিলেন এফটিএনটিএ'র প্রেসিডেন্ট থা ভেলায়ান। "পেপসি এবং কোকা-কোলার মতো পানীয় কিন্তু আপনার স্বাস্থ্যের জন্য ভালো নয়। কারণ এর মধ্যে বিভিন্ন ধরনের কেমিকেল থাকে এবং অতিরিক্ত চিনি থাকে এসব পানীয়তে। আমরা ভারতীয় কোমল পানীয়ের প্রচার চালাচ্ছি এবং ফলের জুসের বিক্রি যেন আরও বাড়ে সেই চেষ্টাও আমরা চালাবো"-বলছিলেন ব্যবসায়ী থা ভেলায়ান। স্থানীয় ব্যবসা এবং কৃষকদের উন্নতির কথা ভেবে সুপারমার্কেট, রেস্টুরেন্ট ও হোটেলগুলো যেন এই নিষেধাজ্ঞা মেনে চলে সেই আহ্বানও জানিয়েছে এসোসিয়েশনগুলো। এই নিষেধাজ্ঞার বিষয়ে পেপসি ও কোকা-কোলা প্রতিষ্ঠানের পক্ষ থেকে এখনও কোনো মন্তব্য পাওয়া যায়নি। আরো পড়ুন: লিফট-গাড়ি নিয়ে ইন্দোনেশিয়া যাচ্ছেন সৌদি বাদশাহ ইয়াহিয়ার জন্য রান্না বন্ধ করে দিয়েছিলেন বাবুর্চিরা 'ভূত তাড়ানো'র নামে আগুনে পোড়ানো হলো এক নারীকে ফ্রান্সের নির্বাচনে ওবামাকে প্রার্থী হতে আহ্বান
----------------------------------------------------------
Actual : ভারতের দক্ষিণাঞ্চলীয় রাজ্য তামিলনাডুর ব্যবসায়ীরা সেখানে কোকা-কোলা ও পেপসি বিক্রি নিষিদ্ধ ঘোষণা করেছে।
----------------------------------------------------------
Predicted : ভারতের দক্ষিণাঞ্চলীয় রাজ্য তামিলনাড়ুতে কোকা-কোকা-কোলার ওপর নিষেধাজ্ঞা জারি করেছে দেশটির সরকার।
==========================================================
