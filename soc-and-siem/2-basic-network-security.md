---
description: Network Security
---

# 2-Basic Network Security

 بعضنا قبل ما ندخل عالم أمن المعلومات اعتقد أن موضوع أمن الشبكة Network Security يقتصر على تركيب ال Firewall و أعمل DMZ لدرجة أن سمعت من بعض الناس بيقولوا مش لازم Domain Controller و دي كانت صادمة ليا و كمان بعض الناس أثناء تركيب مشروع Aruba Wireless بيقولى أية لازمة Controller ما أحنا عندنا Fort iGATE و ناس بتقولي مش لازم Antiviruses أحنا عندنا Sophos ولما قولتهم أزاي قالولى هنزل كراك ولما دخلت قريت شوية في الـ Network Vulnerably Assessment حصرت بعض vulnerabilities إلى بتبقي من خلال inside the network و هيا كالاتي :-  
1. أقفل الفلاشات من الدومين أرجوك "من أهم الحاجات إلى تعملها من خلال Domain Controller ".  
2. شغل الـ AAA عشان مش أي حد يوصل اللاب بتاعة يأخذ Authorized على الشبكة.  
3. رفع أداء كلمات السر الخاصة بال Access Point و بلاش تعمل هيدك على الـ Firewall و تشغلها علية هات Access Controller أفضل و أسرع و أأمن للعلم بيبقى فيه IPS-IDS .  
4. تشغل WSUS عشان أي Update بينزل لل vulnerabilities Zero Day" Domain Controller "  
5. شغل الـ Policy على الـ Domain على سبيل المثال لو حد نزل ملف ميشتغلش غير بعد ما ال Antiviruses يعمل علية سكان.  
6. شغل الـ Rule على ال Firewall مين رايح فين و لية يعنى مش أي حد يوصل لل Sub net mask بتاعت ال Servers Or Firewall .  
7. شغل ال File Server و حدد من ال Domain Controller مين يشوف أية و مين يعمل أية.  
8. و للعلم الـ Domain Controller يريحك في حاجات كتير مش هيخلى في Man In The Middle Attack يعنى مش هيبقى في  
• DNS spoofing  
• HTTPS spoofing  
• IP spoofing  
• ARP spoofing  
• SSL hijacking  
• Wi-Fi hacking  
  
9. عن طريق أل Firewall أقفل أي حاجة تسبب أن يتعمل Scanning على Network بتاعتك.  
يمكن أكون مش ذاكر كل حاجة بس دا الشائع و المنتشر حاليا في ظل أنتشار ال Metasploit و ال Back Door و ال Ransom Ware يعنى بالأخص شوف ال Defense in Depth المضبوطة إلى لازم تشتغل عليها تراجعوا البوست دا  
[https://www.facebook.com/theeagle58/photos/a.872826409394025/3652884854721486/?type=3&theater](https://www.facebook.com/theeagle58/photos/a.872826409394025/3652884854721486/?type=3&theater)  
و طبعا لازم يكون عندنا SIEM عشان نقدر نبقى عاملين Monitor للشبكة بأكملها تقدر تراجعوا البوست دا  
  
[https://www.facebook.com/arab.technology.union/photos/a.109144297293033/121144216093041/?type=3&theater](https://www.facebook.com/arab.technology.union/photos/a.109144297293033/121144216093041/?type=3&theater)

