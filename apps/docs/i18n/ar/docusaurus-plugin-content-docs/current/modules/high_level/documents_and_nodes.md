---
sidebar_position: 0
---

`تمت ترجمة هذه الوثيقة تلقائيًا وقد تحتوي على أخطاء. لا تتردد في فتح طلب سحب لاقتراح تغييرات.`

# المستندات والعقد

`المستندات` و `العقد` هما العناصر الأساسية لأي فهرس. بينما يكون واجهة برمجة التطبيق (API) لهذه الكائنات مشابهة، يُمثل كائن `المستند` ملفات كاملة، بينما تكون `العقد` قطعًا أصغر من ذلك المستند الأصلي، والتي تكون مناسبة لـ LLM و Q&A.

```typescript
import { Document } from "llamaindex";

document = new Document({ text: "نص", metadata: { key: "val" } });
```

## مرجع الواجهة البرمجية

- [المستند (Document)](../../api/classes/Document.md)
- [نص العقد (TextNode)](../../api/classes/TextNode.md)

"