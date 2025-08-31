# 🎬 IMDB Movie Reviews — Sentiment Analysis (TensorFlow/Keras NLP)

این پروژه احساسات (مثبت/منفی) نقدهای فیلم را با استفاده از پردازش زبان طبیعی و شبکه‌های عصبی در **TensorFlow/Keras** پیش‌بینی می‌کند. 
داده‌ها از Kaggle دریافت می‌شوند و نوت‌بوک روی Google Colab/لوکال قابل اجراست.

---

## 📂 ساختار پروژه
- `IMBD_movie_reviews.ipynb`: نوت‌بوک اصلی شامل:
  - دانلود دیتاست از Kaggle
  - پاکسازی متن (حذف تگ‌های HTML و کاراکترهای اضافی)
  - برچسب‌گذاری (Label Encoding)
  - توکنایز کردن متن و تبدیل به توالی
  - ساخت و آموزش مدل عصبی (Embedding + لایه‌های Dense/CNN/RNN برحسب نوت‌بوک شما)
  - ارزیابی مدل

> 📌 توجه: این نوت‌بوک در **Google Colab** نوشته شده؛ اگر مسیرهایی مثل `/content/...` دارید، هنگام اجرا متناسب با محیط خود تنظیم کنید.
> برای دانلود خودکار از Kaggle به `kaggle.json` در مسیر `~/.kaggle/` نیاز دارید (آن را عمومی نکنید).

---

## 🧰 تکنولوژی‌ها
- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas
- scikit-learn
- Matplotlib
- BeautifulSoup4 (برای حذف تگ‌های HTML)

---

## 📥 نصب و اجرا
1. مخزن را کلون کنید:


```bash
git clone https://github.com/evi-data-vision/IMDB-Sentiment-Analysis.git
cd IMDB-Sentiment-Analysis
pip install -r requirements.txt
```

---
