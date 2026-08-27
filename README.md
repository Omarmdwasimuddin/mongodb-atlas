# MongoDB Atlas Setup গাইড

এই ডকুমেন্টে ধাপে ধাপে দেখানো হয়েছে কীভাবে MongoDB Atlas-এ একটি ফ্রি ক্লাস্টার তৈরি করে সেটার Connection String (.env ফাইল) প্রজেক্টে যুক্ত করতে হয়।

---

## ধাপ ১: MongoDB Atlas খোঁজা

Browser খুলে সার্চ করুন **"mongodb atlas"**।

তারপর সার্চ রেজাল্ট থেকে **Atlas Database** অপশনে ক্লিক করুন।

![Search MongoDB Atlas](https://github.com/user-attachments/assets/aee39572-d022-4bba-b78e-9637e123b125)

---

## ধাপ ২: Sign Up / Login পেজে যাওয়া

পরবর্তী পেজে যে বাটন বা অপশন দেখাবে সেখানে ক্লিক করুন।

![Click here](https://github.com/user-attachments/assets/01390a2a-a709-4c6e-8db3-21616392a563)

---

## ধাপ ৩: পরবর্তী ধাপে যাওয়া

আবার পরের অপশনে ক্লিক করুন।

![Click here](https://github.com/user-attachments/assets/1dc0cc19-11ee-4dcc-ade2-c7cd1c7ba18b)

---

## ধাপ ৪: ফর্ম Submit করা

প্রয়োজনীয় তথ্য দেওয়ার পর **Submit** বাটনে ক্লিক করুন।

![Click Submit](https://github.com/user-attachments/assets/eef2fe64-a118-414c-ba62-2b4aaac66348)

---

## ধাপ ৫: Optional তথ্য পূরণ

এই পেজে চাইলে value দিতে পারেন, না হলে **Skip** করে দিতে পারেন। এটি বাধ্যতামূলক নয়।

![Optional form](https://github.com/user-attachments/assets/5176b004-7d5d-46ac-9e71-9cb187ff3044)

---

## ধাপ ৬: Free Deployment তৈরি করা

এখানে **Free** প্ল্যান সিলেক্ট করে **Create Deployment** বাটনে ক্লিক করুন। ফ্রি প্ল্যানেই ছোট প্রজেক্ট বা লার্নিং পারপাসের জন্য যথেষ্ট।

![Select Free plan](https://github.com/user-attachments/assets/f29c3982-7351-45cd-9e2f-ff5a5573912d)

---

## ধাপ ৭: .env ফাইল ডাউনলোড করা

Deployment তৈরি হয়ে গেলে যে ফাইলটি ডাউনলোড হবে, সেটি VS Code-এ ওপেন করুন। এরপর সেই ফাইলে দেওয়া Connection URL কপি করে নিজের প্রজেক্টের `.env` ফাইলে পেস্ট করুন।

![Download .env file](https://github.com/user-attachments/assets/afb3a501-2676-4edf-a6c7-5935f6e4c434)

---

## ধাপ ৮: Drivers সিলেক্ট করা

Connect অপশন থেকে **Drivers** সিলেক্ট করুন — এটি দেখাবে কোন প্রোগ্রামিং ল্যাঙ্গুয়েজ/ফ্রেমওয়ার্ক দিয়ে Database-এ কানেক্ট করতে হবে, এবং সেই অনুযায়ী কানেকশন কোড/স্ট্রিং দেখাবে।

![Select Drivers](https://github.com/user-attachments/assets/30bf0673-30f9-4329-a765-01269c32b27d)

---

## ধাপ ৯: Setup শেষ করা

সবশেষে **Done** বাটনে ক্লিক করলেই MongoDB Atlas সেটআপ সম্পূর্ণ হয়ে যাবে।

![Click Done](https://github.com/user-attachments/assets/9e8b2b7e-3fce-4a21-9fc6-44bc95ca6773)

---

## সারসংক্ষেপ

| ধাপ | কাজ |
|---|---|
| ১ | Atlas Database সার্চ ও সিলেক্ট |
| ২–৩ | Sign up / প্রাথমিক সেটআপ |
| ৪ | ফর্ম Submit |
| ৫ | Optional তথ্য (Skip করা যায়) |
| ৬ | Free Deployment তৈরি |
| ৭ | .env ফাইল ডাউনলোড ও প্রজেক্টে যুক্ত করা |
| ৮ | Drivers সিলেক্ট করে কানেকশন স্ট্রিং নেওয়া |
| ৯ | Setup সম্পন্ন করা |
