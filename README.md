# DocDetail-ETDTemplateTable-

ETD = TEMPLATE = TABLE  AIK HI CHEAZ HAI OR ETD BNANA KA LIA ZARORI HAI KA FIELD.DEFINATION WALI FILE HO MARA PASS 
OR TEMPLATE  = ETD  = TABLE KO HAMESHA ROUTINE MA HI USE KAR SAKTA HA or jo prefix ma filed.defination ma donga wo phir 
mara insert file kia sari field ma add hoka ae gi har field ka sath. Or java ma browser sa ETD bna hona chaeya design studio 
ma etd ki class file generate ni hoiti. 


![image](https://user-images.githubusercontent.com/40827670/223357206-583d931c-7070-4bbe-8003-cccbed3b62b2.png)

ETD ma 2 files ki types hoti hai max character or minimum character
Etd wala ki insert files khud generate hoti hai or jab hogi to uska sath har field ma wahi prefix add hoga jo huma field.defination ma hum na bataya tha 

![image](https://user-images.githubusercontent.com/40827670/223357322-c75cfea3-a75a-4876-933d-d909c3baf90c.png)

TEMPLATE KI DO ROUTINES BANTI HAI YA HOYI HA ? 

![image](https://user-images.githubusercontent.com/40827670/223357453-f0f85693-33bd-4984-8025-9bc7845fba0c.png)
Isko hum table khae ga jo iska bad etd bna ga

---------------------------------------------------------------EB.API , SS , File.Control , ETD , PGM.File-----------------------------
EB.API US CODE KI HOTI HAI JISKO HUM KISI NA KISI VERSION OR ENQUIRY MA ADD KARENGA Koi bhi Template  ho or routine ho uska 
4 components  hoti hai Pgm, file control , ss insert file or jab hum ETD bnata hai to uska bad hum Eb.dev helper sa uski ss ,
file control , pgm , insert wahi sa generate kardata hai. Or jab hum kud sa ETD bna rahe honga to huma EB ni likhan hota wo khud sa add
kardata ha uska sath or bnata waqat product ko EB select karenga always . OR etd bnata waqat ID ko hum key field ma bhi ID hi dala ga taka ya 
primary key ba ne or normal field ki tarha isko na la.![image](https://user-images.githubusercontent.com/40827670/223360496-00809aca-763c-40b2-82e9-f92de2b00064.png)
or ETD ki file type hum file.control ![image](https://user-images.githubusercontent.com/40827670/223360565-73afa891-7a67-498e-8381-a9b38f3928f9.png)
  or ETD ma prefix wahi ae ga jo field.defination ma hai or ![image](https://user-images.githubusercontent.com/40827670/223360724-fa5e96a0-aaff-41a3-8037-a3b7543d6290.png)
pgm file ko agar pgm.file ma H matlab history hai to yaha pa none donga OR jab final ma hum ETD ko commit karenga to uski pgm file control ss or insert  khud ban jae ga or insert server ka path pa jaka gir jati hai to un sab jaga pa hum eb.uska name sa search karenga magar etd ma search ka lia eb hata denga or ETD sa bana ka bad pgm ma uski type D ho jati hai . and jo ETD sa hum table banata hai uski insert file ma uski ki field hoti ha jab sab kuch hogaya ![image](https://user-images.githubusercontent.com/40827670/223360801-0a2d3409-12b5-4e25-bd78-64c55036fc51.png)

to hum ETD dobara sa view karenga to usma prefix ma EB khud add hojata hai etd ka andar to ma kia karonga usko DBT sa jaka JET sa modify karonga or EB hata donga . or hum kabhi direct ETD ma change ni karenga jet ka throw karanga DBT ka throw uska tariak ya hai
JET F.EB.TABLE.DEFINATION PKMB.H.ASAN.PARAM.ALI.TEST tariak JET “TABLE KA NAME” “RECORD NAME”  or 29 row pa prefix hota hai ETD ma classic pa to waha sa EB hata ga then small s sa save hoga or smal x sa exit or uska bad mujha insert file a sa bhi EB hatan para ga sirf for exmaple PKMB.ASAN karna hai phalaa banata waqat EB.PKMB.ASAN hoga lakin uska hum dbt sa jaakaa phala etd ma change kara ga PKMB.ASAN or phir hum insert file ma change kara ga EB.PKMB.ASSAN ki jaga PKMB.ASAN har field ka aga sa agar etd bna lia hai lakin picha insert file ni hogi to code ni chala ga


PGM file matlab program file . us ma uski product btata hai lke EB hai or type bta ta hai ka history hai ya live ha  
live record ma kabhi bhi data modify ni hota write hota hai or history record ki 3 files banti hai 
1) history  
2) live  
3) unauthorized
Standard.selection is ma hamara table ka schema hota hai matlab sari field arahe hoti ahi jo hamara table wali class ma define hoti hai or standard selection auto generate hoti hai chaehe code sa ho ya etd sa
File.control:  is ma iski classification ajati hai ka ya int type ka hai ya finantial fn type ka hai ya customer type ka 
Hai agar code sa bnae to uski file.control bnani parti hai.

![image](https://user-images.githubusercontent.com/40827670/223370598-8a665918-5fac-4807-8663-f1927b6cb896.png)


YA JO FIELD KA AGA DROP DOWN KI VALUES ATI HAI KISI BHI APPLICATION SA WO HUM IS TARHA KARTA HAI APPL VET MA HUM APPLICATION KA NAME KA KHA SA ATRAHE HAI OR APPL ENCRICH FLD MA FIELD NAME KA KN SI FIELD AE GI


EB API SABKI HOTI HAI SIRF TEMPILATE SA BNAA HOWA ROUTINE KI NI HOTI AGAR KISI KI ETD NI HOGI TO SAMJHO WO TEMPLATE SA NI BNA HOWA
