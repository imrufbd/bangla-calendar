বঙ্গাব্দ  [Bongabdo](https://github.com/imruf/bongabdo.git)
------


###### বাংলা পঞ্জিকা
	- ইংরেজি তারিখ বাংলায় এবং বাংলা তারিখ ইংরেজিতে রুপান্তরের স্ক্রীপ্ট।
	
	বাংলা একাডেমির ২০১৯ সালের সংশোধন অনুসারে:
		- বৈশাখ-আশ্বিন হবে ৩১ দিনের।
		- ফাল্গুন মাস বাদে কার্তিক-চৈত্র হবে ৩০ দিনের।
		- ফাল্গুন মাস হবে ২৯ দিনের (ইংরেজি লিপ ইয়ারে ফাল্গুন মাস হবে ৩০ দিনের)।
	
#### Bangla Calendar
    - A shell script to convert Gregorian calendar into Bongabdo And Vice-Versa

###### ব্যবহারবিধি:
	- git clone https://github.com/imruf/bongabdo.git
	- cd into directory and give permission or put bongabdo in your path.

###### সাহায্য:
```
bongabdo -h
```

###### আজকের দিনের বাংলা তারিখ:
```
bongabdo
```
###### কোন একটি নির্দিষ্ট দিনে বাংলা তারিখ: (যেমন: ২১ ফেব্রুয়ারি ১৯৫২ )
```
bongabdo -d 21 -m 2 -y 1952
```

###### কোন একটি নির্দিষ্ট দিনের বাংলা তারিখ ইংরেজি তারিখে রুপান্তর (-c 1): (যেমন ৮ ফাল্গুন ১৩৫৮)
```
bongabdo -c 1 -t 8 -z 11 -s 1358
```
###### তারিখ প্রদর্শনের রুপ ( -f ):
```
bongabdo -d 14 -m 2 -f 3
```
	- স্বাভাবিক প্রদর্শন: ঋতু বার তারিখ মাস সন
    	- 1 : বার তারিখ মাস
    	- 2 : বার তারিখ মাস সন
    	- 3 : ঋতু তারিখ মাস
    	- 4 : ঋতু তারিখ মাস সন
		- 5 : মাস তারিখ

###### ভাষা প্রদর্শনের রুপ ( -e ):
```
bongabdo -d 16 -m 12 -y 1971 -f 4 -e
```

###### রুপান্তরের রুপ ( -c ):
```
bongabdo -c 1 -d 16 -m 12 -y 1971 -f 4 -e
```

		- স্বাভাবিক প্রদর্শন: শীত ১ পৌষ ১৩৭৮
		- বাংরেজি ( -e): Sheet 1 Poush 1378
		- রুপান্তর ( -c 0): Sheet 1 Poush 1378
