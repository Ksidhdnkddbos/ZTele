**اوامر التنصيب علي السيرفر او ال vps** :-
```
apt install git && apt install python3
```
```
git clone https://github.com/l-s-I-I/Zele_vps.git
cd Zele_vps
pip3 install -r requirements.txt
```

```
nano config.py
```
**امر انشاء قاعدة البيانات** حط كلمه السر واكتب الامر 
```
sudo su - postgres bash -c "psql -c \"ALTER USER postgres WITH PASSWORD 'كلمه_سر_قاهد_البيانات';\" && createdb speed -O postgres"
```
**وخليها كذا في ملف config.py :- 
```postgresql://postgres:كلمه_سر_قاهد_البيانات@localhost:5432/speed```
__وبعدها حط معلوماتك__ 

**بعدين شغل باحدي الطرق الاتيه** :-

1:-
```
python3 -m zlzl
```
2:- 
```
bash start.sh
```

**تابع اي تحديثات واصلاحات هتنزل في المستودع دا**
<a href="https://ibb.co/sv7XrcH"><img src="https://i.ibb.co/sv7XrcH/Zilzalll.jpg" alt="Zilzalll" border="0"></a>

**〔 سـورس زدثــون - 𝗭𝗧𝗵𝗼𝗻 〕**

**افضـل سـورسـات يـوزر بـوت العربيـة**

**› عربـي بالكـامل › تحديثـات متواصـله › فـارات تلقـائيـه بسهولـه〔 حصريـاً 〕** 

#**By:** https://t.me/ZThon


