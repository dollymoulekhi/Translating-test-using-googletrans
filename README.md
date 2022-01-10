# Translating-text-using-googletrans

## Translating the text from other language to english

```
from googletrans import Translator
translator = Translator(service_urls=['translate.googleapis.com'])
a=translator.translate("प्लास्टिक/ केमिकल", dest='en')
a.text

translations = {}
for value in wrong_jobrole:
    translations[value]=translator.translate(value,dest='en').text
print(translations)
```
