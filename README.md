# سفره‌خانه شیراز | Shiraz Table

وب‌سایت دوزبانه (فارسی / انگلیسی) برای یک رستوران ایرانی، در قالب یک فایل HTML بدون وابستگی.
A bilingual (Persian / English) website for an Iranian restaurant, built as a single dependency-free HTML file.

## ویژگی‌ها | Features

- تغییر زبان فارسی ⇄ انگلیسی با دکمه، همراه با تغییر خودکار جهت صفحه (RTL / LTR)
- Instant FA ⇄ EN toggle with automatic RTL / LTR switching
- ذخیرهٔ زبان انتخابی کاربر در مرورگر
- Remembers the visitor's language choice
- قیمت‌ها به تومان؛ ارقام فارسی در حالت فارسی و لاتین در حالت انگلیسی
- Prices in Toman, formatted with Persian digits (FA) or Latin digits (EN)
- منوی تب‌بندی‌شده: همه، پیش‌غذا، غذای اصلی، دسر و نوشیدنی
- Filterable menu: All, Starters, Mains, Desserts & Drinks
- حالت تاریک و روشن خودکار
- Automatic light / dark theme
- واکنش‌گرا برای موبایل و دسکتاپ
- Responsive on mobile and desktop

## اجرا | Run

فایل `index.html` را در مرورگر باز کنید. نیازی به نصب یا build نیست.
Open `index.html` in any browser. No install or build step.

## شخصی‌سازی | Customize

- **منو و قیمت / Menu & prices:** در بخش `#menu` هر غذا یک `div.item` است. قیمت (به تومان) در `data-p` نوشته می‌شود، مثلاً `data-p="1700000"`.
  Each dish is a `div.item` in `#menu`. Set the price in Toman via `data-p`, e.g. `data-p="1700000"`.
- **دسته‌بندی / Category:** مقدار `data-c` هر آیتم: `s` (پیش‌غذا)، `m` (غذای اصلی)، `d` (دسر و نوشیدنی).
- **متن‌ها / Text:** هر متن دو `span` دارد: `.fa` برای فارسی و `.en` برای انگلیسی.
- **رنگ‌ها / Colors:** متغیرهای CSS در `:root` بالای فایل.
- **آدرس و تلفن / Address & phone:** بخش `#contact`.

## نسخهٔ آنلاین | Live Demo

این پروژه روی GitHub Pages منتشر شده است:
This project is hosted on GitHub Pages:

`https://amiralidlb93-hash.github.io/shiraz-table/`

## فونت‌ها | Fonts

[Vazirmatn](https://github.com/rastikerdar/vazirmatn) و Playfair Display از Google Fonts.

## مجوز | License

MIT — see [LICENSE](LICENSE)
