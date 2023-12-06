---
sidebar_position: 0
slug: /
---

`این مستند به طور خودکار ترجمه شده و ممکن است حاوی اشتباهات باشد. در صورت پیشنهاد تغییرات، دریغ نکنید از باز کردن یک Pull Request.`

# لاماایندکس.TS چیست؟

لاماایندکس.TS یک چارچوب داده برای برنامه های LLM است که امکان دریافت، ساختاردهی و دسترسی به داده های خصوصی یا مربوط به دامنه را فراهم می کند. در حالی که یک بسته پایتون نیز در دسترس است (برای مشاهده [اینجا](https://docs.llamaindex.ai/en/stable/) را ببینید)، لاماایندکس.TS ویژگی های اصلی را در یک بسته ساده ارائه می دهد که برای استفاده با TypeScript بهینه شده است.

## 🚀 چرا لاماایندکس.TS؟

در اصل، LLM ها یک رابط زبان طبیعی بین انسان ها و داده های استنباطی ارائه می دهند. مدل هایی که در دسترس هستند، پیش از این بر روی مقادیر زیادی از داده های عمومی که از ویکیپدیا و لیست های پستی تا کتاب های درسی و کد منبع استفاده می کنند، آموزش دیده اند.

برنامه هایی که بر روی LLM ها ساخته می شوند، اغلب نیاز به تقویت این مدل ها با داده های خصوصی یا مربوط به دامنه دارند. متأسفانه، این داده ها ممکن است در برنامه ها و فروشگاه های داده مختلف پخش شده باشند. آنها پشت API ها، در پایگاه داده های SQL یا در فایل های PDF و اسلاید دیک ها قرار دارند.

در اینجاست که **لاماایندکس.TS** وارد عمل می شود.

## 🦙 چگونه لاماایندکس.TS می‌تواند کمک کند؟

لاماایندکس.TS ابزارهای زیر را فراهم می‌کند:

- **بارگیری داده**: امکان دریافت مستقیم داده‌های موجود در فرمت‌های `.txt`، `.pdf`، `.csv`، `.md` و `.docx`
- **شاخص‌های داده**: ساختاردهی داده‌های خود را در نمایش‌های میانی که برای استفاده آسان و با عملکرد بالا برای LLM ها مناسب است، انجام دهید.
- **موتورها**: دسترسی به داده‌های خود را از طریق زبان طبیعی فراهم می‌کنند. به عنوان مثال:
  - موتورهای پرس و جو، رابط‌های بازیابی قدرتمندی برای خروجی افزایش دانش هستند.
  - موتورهای چت، رابط‌های مکالمه‌ای برای تعاملات چند پیامی و "پیام به پیام" با داده‌های شما هستند.

"

## 👨‍👩‍👧‍👦 لاماایندکس برای چه کسانی است؟

لاماایندکس.TS مجموعه‌ای از ابزارهای اصلی را فراهم می‌کند که برای هر کسی که در حال ساخت برنامه‌های LLM با جاوااسکریپت و TypeScript است، ضروری است.

API سطح بالای ما به کاربران مبتدی امکان استفاده از لاماایندکس.TS برای دریافت و پرس و جوی داده‌های خود را می‌دهد.

برای برنامه‌های پیچیده‌تر، APIهای سطح پایین ما به کاربران پیشرفته امکان سفارشی‌سازی و گسترش هر ماژول - اتصال‌دهنده‌های داده، اندیس‌ها، بازیابان‌ها و موتورهای پرس و جو - را برای تناسب با نیازهای خود می‌دهد.

## شروع کار

`npm install llamaindex`

مستندات ما شامل [دستورالعمل نصب](./installation.md) و [آموزش شروع کار](./starter.md) برای ساخت اولین برنامه شما است.

با راه اندازی و اجرا شدن، [مفاهیم سطح بالا](./concepts.md) یک نمای کلی از معماری ماژولار لاماایندکس را ارائه می دهد. برای مثال های عملی بیشتر، به [آموزش های پایان به پایان](./end_to_end.md) مراجعه کنید.

"

## 🗺️ اکوسیستم

برای دانلود یا همکاری، لاماایندکس را در مکان های زیر پیدا کنید:

- Github: https://github.com/run-llama/LlamaIndexTS
- NPM: https://www.npmjs.com/package/llamaindex

"

## جامعه

نیاز به کمک دارید؟ پیشنهادی برای ویژگی دارید؟ به جامعه لاماایندکس بپیوندید:

- توییتر: https://twitter.com/llama_index
- دیسکورد: https://discord.gg/dGcwcsnxhU