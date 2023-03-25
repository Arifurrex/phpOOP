Oop (object oriented programming language)
Object ki ta bojte hobe.object holo bosto ba ak ak ta jinis .jesob jinis er ak akta boisisto ace thake object bole .prothek ta jinis er ek ek ta boisisto ace jemon bus er akta boisisto ace ,car er ekta boisisto ace.jemon
Bus e size boro hoye thake ,bus er chaka boro hoye thake ,bus er onekgolo chaka thake.
R car er size choto hoi .4 ta sit thaka ke,chaka choto thake
So ai bus er boisis ta bollle bojte parbo eta ekta bus
Temon e car er boisito bolle bojte parbo eta ekta car

Object sikte gele tumi class ki ta bojte bole .class holo akta pitar sas ba forma.mane kolo pita mananor jonno forma use kora hoi .ai forma takar karone pita golor designe aki rokom hobe.eki babe class holo forma.
Panir botol ta holo object .ai kolom ta holo object . botol bananor jonno akta forma bas as use kora hoi .ai sas ba formak bole class . ai class er madomme apni bar bar aki doroner ba designer botol ba kolom banate parben.  
Eki format takar karone biscut golor designe aki rokom thake .Class holo format .
akta programme korte gel onekgolo object lagbe .oi object golo create korte class declair kora lagbe.se class a takbe .sei class golor modde tabe oi jinis golo ba object golo ki ki kaj korbe.

Jemon tumi Jodi akta poriban er akta software banaba .sekane hoito bus ,truck etc takbe .ekane bus er boisisto takbe ek rokom r truck er boisisto takbe ek rokom
Bus er boisisto hocce tumi koto toko jarti nicco r
Truck er boisisto hocce tumi koto ton mal nicco
But ai doitar modde kicho common jinis thake jemon bus er o driver lagbe truck er o driver lagbe ,bus er o chaka lagbe ,truck er o chaka lagbe
Ai common jinis golo alada alada class er modde diclare na kore akta class er modde declair koro
Ai uporer ai common jinis golo holo parent class
Inheritance holo baper sompotti ortat parent er jinis golo pawwa

Incapsulation holo oneksomi tumi tomar betore jinis kew k bolte chaw na tokon tha incapsulation kore rakba.jemon tumi tomar facebook er privacy setting incapsulation kore rakba .or tumar bank er privacy setting

Polymorsium er holo common .example holo doro tomar kache 3 ta paki ace .maoina ,tiya,kak .3 ta paki dak dite pare .moina moinar moto,tiya tiyar moto r kak kak er moto dak dite pare .akon tuma kache a paki niye asche kacher modde kore jekane kacha ta kapor diye morono.tumi janona na betore kon phaki ace .tumi jano ai 3 ta paki gan gaite pare .akon Jodi tumi tader gaan gaite bolo r tara Jodi gaan gai .tkon tumi bojte parbe betore kon paki ace .eta holo polymorimom

3 ta jinis tumi sikla
Inheritance –uttoradir sotrre pawwa
Incapsulation-sak diye loti ranna korar sotor ja onno kew janne na
Polymorimom-pakir gan gawwa

Overall ja discuss kora hoiyeche ta holo object keno lage . object keno lagbe koron karon programing korar somoi ak ak ta boisisto onno sare kaj bolo a organize kore raka .class holo object golo a akta format e raka .r sei chak onnosare kaj kora

PHP OOP
So, a class is a template for objects, and an object is an instance of a class.
Class holo botol bananor sas b forma . r object holo class/formar akti sample ba distantoo ba udaharon ba instance

Class,method,object
2005 saler dike opp market a ase.
Php5 er age oop cilo na.
Object ki?everything is object.
object k doibabe bag kora jai
1.Property
2.method

Lets start work----
Xmmap >htdoct>er modde akta folder create kori opp name>ai opp file a index.php file create kori+something .php name a file create kori

How to declair class:

<?php
Class anyname
?>

C#,java te file er name onnosare class er name hote hobe.
R class name capital letter a hobe

Class er modde ki thake?
Class er modde thake function r thar definition

Sum namer je function ace ta call korbo onno page theke .index.php page theke.
Amra jani kono function k call korte sei function er name like first bracket dite hoi—sum()
Index.php file r something.php file er modde kono somporko nai .tahole tader modde somporko create korte hobe.require_once() ba include er maddome

Kibabe ak file sate onno file connection kibabe korbo?
Require_once ‘something.php’
Require_once er sate ak file er sate onno file er connection kora hoi

Index.php file a Jodi Require_once er maddome onno file add korar por file run korle o error dekabe

Ai error ta dekabe.karon holo something.php file a amra class use kotre chi.something.php file a amra class ta ustiye diye try kori.. odbe kaj korbe

Tahole class file theke function a k call korar niyom?
Index.php file a something class er aka object create korte hobe .
Something class er object kibabe creae korbo?
New something()
Eta holo object sign

Something class a er akra object class crae korlam Korlam
then amra Jodi something class er sum functione er access nite chi then . tahole amdere $test variable er maddome theke ai object a access pabo then amara function a call korbo

Constructor
Er maddme object er property template create kora hoi

Declaration of constructor

Type of constructor:

More about constructor

Ekane Jodi aro property add kori jemon age,gender,phone num ba aro proprty add kori tobe ekane

Ei type er property bar bar add kore hobe .
Ekane j example dekalam ekane aki maro object niye kaj korlam
Ekane Jodi 4 ./5 a object niye Jodi kaj kori tobe aki property bar bar use korte hobe. tahole code onek boro hobe .si jonne amra object er property templae create kori.ei templae k cnstructor bole .

Full example:

Default values se

---

Default value ser in consrucor

---

Ami Jodi ekane consrucor creae na koram ahole ekane amake
$p1=new person();
$p1->name=”arifur”;
$p1->age=21;

$p2=new person();
$p1->name=”ramkumar”;
$p1->age=15;

$p3=new person();
$p1->name=”salman khan”;
$p1->age=22;

Ebabe code like hoo consrucor na akle .conrucor holo object propery emplae

Consracor end here

OOP - Part-02 (Class Constants, Inheritance, Access Modifiers, Static properties,methods, Interface)

Constants
Consant kibabe creat e kora hoi?
Constant akbar declared korar por ar change hobe na.
Class constants can be useful if you need to define some constant data within a class.
Class er beore constant delare hoi constant keyword
Class constant ta case sensatve
We can access a constant from outside the class by using the class name followed by the scope resolution operator (::) followed by the constant name, like here:
Class er bbarire kibabe consant declare kore parbo:
Amra clss er bahire o consant ta declare kore parbo /followed by scope resolution operator :: followed by consant name

Or anoher example:

Class er beore kibabe constant declare kore parbo:

Echo something::roll something arpor scope resulation opareor hen const name like declare kore parbo
Anoher way hocce
Class name na like self :: scope resulation operaer like hen cont name like declare kora jai
Inheritance
holo pitar sompotti pawa
ak class er boisisto Jodi onno ar ekta class peyethake thake inheritance bola hoi
An inherited class is defined by using the extends keyword.

Ekane amra ki korlam class banalam.jei class er constructor er parameter set korchi r class a jokon instancian kolam tokon value set kore dilam. R ouou je method ace tate akta massage soho oi name ta show kore dilam.

Eibar ekanei amara r ek ta class create korbo.sadaronoto class diffenent file a class golo likte hoi.sodomato bojar jonno aki file a 2 ta class nibo.mark name rr akta class nibo.mrk class student class er sokol boisisto pabe .r etai holo inheritance.

An inherited class is defined by using the extends keyword.

Joko class mehod 2a class e use kora hoi ake mehod overrive bole
PHP - Access Modifiers

Properties and methods can have access modifiers which control where they can be accessed.
Property r method er sathe access modifier takte pare.
Ekane 3 doroner access modifier ace===
1.public
2.provected
3.private

public - the property or method can be accessed from everywhere. This is default

protected - the property or method can be accessed within the class and by classes derived from that class.jemon—pitar motor cycl ami use korte parbo.

private - the property or method can ONLY be accessed within the class.jemon-pitar wallet ami use korte parbo na.

public a jekono jaiga heke access niwa jai .class er beor heke ba class er bahr heke.

Protected sodo maro class r oi class er sub class er modde acces kora jai

private  sodo maro oi class er modde access kora jai.class er barihe ba sub class heke access paben na

PHP OOP - Static Methods
Static methods can be called directly - without creating an instance of the class first.
Object create kora chara called korrar system holo saic method .

Static methods are declared with the static keyword:

Saic meho der sysem

https://www.youtube.com/watch?v=Gnnge0Jv3dc

polymarphysom

aka class jokon r aka class k inheri kore .r oi class joi mehod over ride kore ake polymerphysom bole

inerface

Project sar:
Database create and database connection:
z Database connection

Result

Database connection k akta variable er modde rakbo jeheo object oriented seheto amra ekane $this-> use korbo

Data insert kibabe korbo
Print_r($\_post) er maddome form er data golo dekte parbo

Database e data insert korar jonno:
Class file a modde akta function likbo jekono name a suppose ami save_user name a akta funcvion likbo

---

Dava fach:

Dele:\

Edi

Massage show korbe

AGAIN EXPLANAON

Namespace and composer
Namespace kibabe creae kore hoi namespace er name jekono name a hoe pare

Keno namespace use kora hoi:
Eki class name Jodi bar bar use hoi okon aka isse creae hoi.okon error dakabe .ei somossa somadan er jonno namespace use kora hoi.
jemon

Part-27
Javascrip object
object ki seta janar age amra janbo object keno proyojon:
suppose amak akjon student er details store korte hobe
<script>
// studen1 details
var name="arifur";
var age=30;
var school="golaponj jamia";
var roll=46;
var lang=["bangali","english","hindi"];
</script>

Ekane amra akta student er data store kore rekechii.but ekane ekta problem kewal koron variable kebol marto ekta datatype niye kar korche .
So amra cacci variable multiple datatype store kore rakte pare.sei ketre amder help korbe object.
So object ka amra ek doroner variable bolte pari .er maddome apnara multiple value at a time store kore rakte paren.
Object kibabe create kore
var student1={
property:value,
}

Object example

Property er value golo kibabe print korbe

console.log(student1.name);

More about Object
Akon dora jak aro koyek ta student er jonno amra object create korbo.
<script>
var student1={
name:"arifur",
age:30,
school:"golaponj jamia",
roll:46,
lang:["bangali","english","hindi"];
}
var student2={
name:"abdulalim",
age:32,
school:"tejgoan jamia",
roll:46,
lang:["bangali","english","spanis"];
}
var student3={
name:"abdurrahman",
age:35,
school:"golaponj jamia",
roll:46,
lang:["bangali","english","portugis"];
}
console.log(student2.name);

    </script>

Constractor kibabe add korte hoi

function Student(name,age,school,lang)
{
this.name=name;
this.school=age;
this.age=school;
this.lang=lang;
}

var student1=new Student("arifur",21,"golapgong",['bangla','english']);

age amra jetkaj korecilam.eta holo akta single object
var student1={
name:"arifur",
age:30,
school:"golaponj jamia",
roll:46,
lang:["bangali","english","hindi"];
}

Ebar amra jta koreci ta holo constractor diye amra akta template create kore chi .ei template diye amra multiple object create korte parbo..
function Student(name,age,school,lang)
{
this.name=name;
this.school=age;
this.age=school;
this.lang=lang;
}
Abong ei template thake amra multiple object create krte parbo.
var student1=new Student("arifur",21,"golapgong",['bangla','english']);
var student2=new Student("abdulalim",31,"golapgong",['bangla','english','arabic']);

Explain kibabe kaj korche
<script>
function Student(name,age,school,lang) {
this.name=name;
this.school=age;
this.age=school;
this.lang=lang;
}
var student1=new Student("arifur",21,"golapgong",['bangla','english']);
var student2=new Student("abdulalim",31,"golapgong",['bangla','english','arabic']);

console.log(student1.lang)
</script>

**\*ebabe akta template ba constrctor kore multiple object create kora jai \*\***so er mane hocce multiple object create korte constractor lagbe

Ebar chaile value golo print korte parben
console.log(student1.name);
console.log(student1.age);
console.log(student1.school);
console.log(student1.lang);

print korte chile amra r akta simple way use korte pari…..kibabe function asss kora jai constractor er maje

adding function inside a constructor
problem ta hocce student1 er object print korar jonno amader ebabe 4 bar dite hocce .abbabe studen2 er jonno 4 bar call kora labe .temoni student3 student4 er jonno prit korte hobe .ei kaj took ar ekto easy korte constructo er modde function use korbo

console.log(student1.name);
console.log(student1.age);
console.log(student1.school);
console.log(student1.lang);

console.log(student2.name);
console.log(student2.age);
console.log(student2.school);
console.log(student2.lang);

……….amra ei kaj ti kub sohoje korte partam akta function create kora nibo print korar jonno .abong sei function k amra bar bar call korbo protek ta alada alada object er jonno.
se jonno amra constractor er modde chole jabo .prothom e ki korbo this. Ei object er jonne akta function create korbo function er akta name dite hobe this.display.lokko rakte hobe constractor e function crate korte hoi aktu different way te . this.display=function keyword use korte hobe () dite hobe then body {} dite hobe .ai hoce constractor er modde function create korar poddoti.ebar body er moodde ja ja print kore hobe bole dite pari .. console.log(student1.name);

ekane student1 na diye this.name.karon ai function ti k student1 student2 any object eta k call korte parbe

<script>
		function Student(name,age,school,lang){
		 	this.name=name;
		 	this.age=age;
		 	this.school=school;
		 	this.lang=lang;
			
			this.display=function(){
		                    console.log(this.name);
		                    console.log(this.age);
		                    console.log(this.school);
		                     console.log(this.lang);
			}
		}
	
		var student1=new Student('abdulalim',32,'golapgonj',['bangla','english','hindi']);
		var student2=new Student('arifur',29,'tejgaon',['bangla','english','urdu']);
			
		student1.display();
		
		
	</script>

Part-28
Math object

Math object er bibinno property abong function royeche egolo niye alochona korbo
Prothome console open kore niben .ekane kaj korbo .prothom e Math keyword likte hobe abong Math. Likkeee .dile bivinno property and function chole asbe.suppose prothom e amra je function use korbo tha hocce square root sqrt so jeheto function seheto first bracket dite hobe() . Math.sqrt() .aboing ei first bracket er betore akta value dite hobe

\***\*Math.sqrt() er maddome borgomol korbe
\*\***Math.abs() er maddome absolute valu ber kora jai
**_Math.sin() er maddome sin er man berr korte parben
_** Math.pow(x,y) x to thre power y er value be rkora jai
**_Math.floor(2.4) nicher diker porno sonka ber kore ans: 2
_**Math.cili(2.4) uporer dike porno sonka ber korte parbe ans:3
**_Math.round(3.4) dosomic sonka k porno sonka kore dibe. 3.5 ba tar upore upto 3.9 hole take round kore dibe vale hobe 4 r 3.4 ba tar niche 3.1 hobe round kore dibe valo hobe 3
_** Math.max() er maddome boro value ta ber kore dibe

Math.sqrt() er maddome borgomol korbe
Math.sqrt(25)
5

Math.abs() er maddome absolute valu ber kora jai
Math.abs(-5)
5
Math.sin() Math cos() er maddome sin er man berr korte parben
Math.sin(2)
0.9092974268256817
Math.cos(2)
-0.4161468365471424
Math.pow(x,y) x to thre power y er value be rkora jai
Math.pow(2,2)
4

Math.floor() nicher diker porno sonka ber kore  
Math.floor(2.8)
2
Math.ceil() uporer dike porno sonka ber korte parbe  
Math.ceil(2.4)
3

Math.round() dosomic sonka k porno sonka kore dibe. 3.5 ba tar upore upto 3.9 hole take round kore dibe vale hobe 4 r
3.4 ba tar niche 3.1 hobe round kore dibe valo hobe 3
Math.round(3.5)
4
Math.round(3.4)
3
Math.max er maddome boro value ta ber kore dibe
Math.max(4,3,7,9,8,-4,6)
9

    <script>
    	var x=parseFloat(prompt("enter first number ="));
    	var y=parseFloat(prompt("enter secound number ="));

    	document.write(Math.max(x,y));
    </script>

Math.random() ramdom number genaret kore. 0 theke 1 er modde . 1 hote parbe na

Math.random()
0.3339013248400089
Math.random()
0.5241458404258357
Math.random()
0.07804691076253922
Math.random()
0.9306612215238512

*\*\*Akon Jodi 0 theke 5 er modde random number generat korbo then….random number ganarat korbe but kokono 6 hobe na ..
Math.random()*6
4.26057752013083
Math.random()*6
5.474893398829821
Math.random()*6
4.809817229819005
Math.random()*6
5.074268079385901
Math.random()*6
5.820559709086365
Math.random()\*6
3.1330096435519583

\*\*\*\*Random number dosomic ase ,ei dosomic k nicher diker forno sonka korte use korbo floor.uperr diker porno sonka korte use hoi celi function

Math.floor(Math.random()*6)
0
Math.floor(Math.random()*6)
2
Math.floor(Math.random()*6)
3
Math.floor(Math.random()*6)
2

\****Random number genarat kore 0 thkeke suppose 5 .so ami cacci 1 theke 5 porjonto random number generate korbe
Math.floor(Math.random()*5+1)
1
Math.floor(Math.random()*5+1)
4
Math.floor(Math.random()*5+1)
4
Math.floor(Math.random()*5+1)
3
Math.floor(Math.random()*5+1)
4
Math.floor(Math.random()\*5+1)
1
\*\***Random number 10 thke 20 kibabe korbo
Math.floor(Math.random()*11+10)
12
Math.floor(Math.random()*11+10)
13
Math.floor(Math.random()*11+10)
20
Math.floor(Math.random()*11+10)
20
Math.floor(Math.random()*11+10)
19
Math.floor(Math.random()*11+10)
20
