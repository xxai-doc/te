<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

వెబ్‌సైట్ కోడ్‌లో కొంత భాగం ఓపెన్ సోర్స్, అనువాదాన్ని ఆప్టిమైజ్ చేయడంలో సహాయపడటానికి స్వాగతం.

## ఫ్రంట్-ఎండ్ కోడ్

* [ఫ్రంట్-ఎండ్ కోడ్](https://github.com/xxai-art/web)
* [మొత్తం సైట్ కోసం భాషా ప్యాక్‌లు](https://github.com/xxai-art/web/tree/main/i18n)
* [లాగిన్ మాడ్యూల్స్ కోసం భాషా ప్యాక్‌లు](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [వెబ్‌సైట్ బహుభాషా డాక్యుమెంటేషన్](https://github.com/xxai-doc)

ఫ్రంట్-ఎండ్ ప్రోగ్రామింగ్ లాంగ్వేజ్ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , ఇది కాఫీస్క్రిప్ట్ సింటాక్స్ ఆధారంగా కొన్ని లక్షణాలను జోడిస్తుంది, చూడండి [./coffee_plus.md](./coffee_plus.md) .

## వెబ్‌సైట్‌లు మరియు పత్రాల అంతర్జాతీయీకరణ

కింది 3 ప్రాజెక్ట్‌లపై నిర్మించండి

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  ప్రత్యయం `.mdt` , మీరు బాహ్య ఫైల్‌లను సూచించడానికి `<+ ./coffee_plus/import.js>` మాదిరిగానే వాక్యనిర్మాణాన్ని ఉపయోగించవచ్చు మరియు `.md` ప్రత్యయంతో మార్క్‌డౌన్‌ను రూపొందించవచ్చు.

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  మార్క్‌డౌన్ అనువాదం కోడ్‌లు మరియు లింక్‌లను అనువదించదు మరియు అనువదించబడిన వాక్యాలను కాష్ చేస్తుంది. అనువాదం సవరించబడినప్పటికీ అసలు వచనం సవరించబడనట్లయితే, దానిని మళ్లీ అమలు చేయడం వలన అనువాదం యొక్క సవరణను ఓవర్‌రైట్ చేయదు.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` రూపొందించిన వెబ్‌సైట్‌లను అనువదించడానికి భాషా ఫైల్‌లు.
