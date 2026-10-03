# পড়াশুনা — তৃতীয় শ্রেণীর শিক্ষা সহায়িকা

একটি সম্পূর্ণ বাংলা শিক্ষামূলক ওয়েব অ্যাপ। তৃতীয় শ্রেণীর বই, সমাধান, AI সার্চ, বুকমার্ক ও অডিও সুবিধা।

## লাইভ ডিপ্লয় (Vercel)

### উপায় ১: এক ক্লিকে ডিপ্লয়
নিচের বাটনে ক্লিক করলে Vercel-এ সরাসরি ডিপ্লয় হয়ে যাবে:

[![Vercel দিয়ে ডিপ্লয় করুন](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/porashuna)

### উপায় ২: Vercel CLI দিয়ে
```bash
npm i -g vercel
cd porashuna
vercel
```

### উপায় ৩: GitHub + Vercel অটো-ডিপ্লয়
1. GitHub-এ নতুন রিপোজিটরি তৈরি করুন (যেমন `porashuna`)
2. এই ফোল্ডারের সব ফাইল পুশ করুন:
   ```bash
   git init
   git add .
   git commit -m "পড়াশুনা প্রথম সংস্করণ"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/porashuna.git
   git push -u origin main
   ```
3. vercel.com-এ গিয়ে "Import Project" → আপনার GitHub রিপো জোড়া লাগান → Deploy চাপুন
4. কয়েক সেকেন্ডে লাইভ হয়ে যাবে!
