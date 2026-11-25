# AI Educational Chatbot

مساعد ذكي تعليمي مبني باستخدام **Flask** و **Gemini API** مع دعم البحث في الملفات المرفوعة عبر **FAISS** و **Sentence Transformers**.

## المميزات الأساسية
* محادثات تعليمية تفاعلية مدعومة بـ Gemini API.
* قراءة ومعالجة ملفات PDF (`PyMuPDF`) والبحث الدلالي فيها.
* واجهة ويب بسيطة باستخدام HTML و CSS و JavaScript.

## هيكل المشروع
```text
ai_edu_chatbot/
├── static/
│   ├── style.css
│   └── script.js
├── templates/
│   └── index.html
├── uploads/
├── app.py
├── requirements.txt
└── .env (يُضاف محلياً ولا يُرفع على GitHub)
