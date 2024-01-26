# --2
<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ
РОССИЙСКОЙ ФЕДЕРАЦИИ
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br>
<p align = "center">Институт естественных наук и техносферной безопасности</p>
<p align = "center">Кафедра информатики</p>
<p align = "center">Гурков Владислав Викторович</p>
<br>
<p align = "center">Лабораторная работа №2</p>
<p align = "center">01.03.02 Прикладная математика и информатика</p>
<br>
<p align = "right" >Научный руководитель</p>
<p align = "right" >Соболев Евгений Игоревич</p>
<p align = "center" >Южно-Сахалинск</p>
<p align = "center" >2023 г.</p>
<p align = "center" ><b>ВВЕДЕНИЕ</b></p>
<p>JavaScript — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили. Является реализацией спецификации ECMAScript (стандарт ECMA-262).</p>
<p>JavaScript обычно используется как встраиваемый язык для программного доступа к объектам приложений. Наиболее широкое применение находит в браузерах как язык сценариев для придания интерактивности веб-страницам.
Основные архитектурные черты: динамическая типизация, слабая типизация, автоматическое управление памятью, прототипное программирование, функции как объекты первого класса.</p>
<p>На JavaScript оказали влияние многие языки, при разработке была цель сделать язык похожим на Java. Языком JavaScript не владеет какая-либо компания или организация, что отличает его от ряда языков программирования, используемых в веб-разработке.</p>
<p align = "center" >РЕШЕНИЕ ЗАДАЧ</p>
 
 ```js 
 function zz1(){ 
let name = "ilya";
alert('hello ${1}');
//alert('hello 
//${"name"}'); - перенос строк невозможен
alert('hello ${name}');
}

function zz2(){
	let a=prompt('Введите ваше имя');
	document.write('Здраствуйте, '+(a));
}

function zz3(){
	let a =1, b=1;
	let c=++a;
	let d=b++;
	alert("a="+a +", " +" b=" + b+ "c= "+c+"d= "+d)
}

function zz4(){
	let a =2;
	let x =1+(a*=2);
	alert("a= "+a + "; x = "+x );
}

function zz5(){
alert("" + 1 + 0);
alert("" - 1 + 0);
alert(true + false);
alert(6 / "3");
alert("2" * "3");
alert(4 + 5 + "px");
alert("$" + 4 + 5);
alert("4" - 2);
alert("4px" - 2);
alert(7 / 0);
alert("  -9  " + 5);
alert("  -9  " - 5);
alert(null + 1);
alert(undefined + 1);
alert(" \t \n" - 2);


}

function zz6(){
let a = +prompt("Первое число?", 1);
let b = +prompt("Второе число?", 2);
alert(a + b); 
}

function zz7(){
	
	
	alert(Math.PI.toFixed(2));
}

function zz8(){
	let a = +prompt("Введите число?");
	if (typeof a == 'number')
	alert("Вы ввели число:"+a);
else alert("Это не число :(");
}

function zz9(){
	let a = +prompt("Введите число?");
	if (typeof a == 'number')
	alert("Вы ввели число:"+a);
else alert("Это не число :(");
}

function zz10(){
	let a = +prompt("Введите число?");
	let q = 4+a;
	alert("Ответ:"+q);
}
function zz11(){
	let a = +prompt("Введите число?");
	let d=a*2;
	alert("диаметр="+d);
	
}

function zz12(){
	let R=6350;
	let=+prompt("Введите H");
	let G=L=Math.sqrt(H* (H+2*R)) ;
	alert("Vivod:" +G);
}

function zz13(){
	let a=+prompt("Введите ребро");
	let s=6*Math.pow(a,2);
	alert("Vivod:" +s);
}

function zz14(){
	let a=+prompt("Введите радиус окружности");
	let s= 2*Math.PI*a;
	let p= Math.PI*Math.pow(a,2);
	alert("Vivod:" + "длина="+s+", "+ "площадь="+p);
}

function zz15(){
	var a=1,
    b=2;

	alert("Vivod original:" +a+", "+b);


b = [a, a = b][0];

alert("Vivod izm:" +a+", "+b);
}

function zz16(){
	var a=1,
    b=2;
	//a)
	let s = (a+b)/2;
	//b)
	let g = Math.sqrt(a*b);
	alert("Vivod:" + "ср.арефм.="+s+", "+ "ср.геометр="+p);
}


function zz17(){
let a = +prompt("масса");
let b = +prompt("объем");
alert("плотность = "+ a/b); 
}

function zz18(){
	let a = +prompt("Кол-во жителей");
let b = +prompt("Площадь");
alert("плотность = "+ a/b); 
	

}

function zz19(){
	let a = +prompt("катет 1");
let b = +prompt("катет 2");
alert("гипотенуза = "+ Math.sqrt(Math.pow(a,2)+Math.pow(b,2))); 
}


function zz20(){
	let a = +prompt("R");
let b = +prompt("r");
alert("S кольца = "+ Math.PI*Math.pow(R,2)-Math.pow(r,2)); 
}


function zz21(){
	let a = +prompt("катет 1");
let b = +prompt("катет 2");
alert("гипотенуза = "+ Math.sqrt(Math.pow(a,2)+Math.pow(b,2)+(a+b))); 
}

function zz22(){
let a = +prompt("основание 1");
let b = +prompt("основание 2");
var t = +prompt("высота");
let w = (b-a)/2;
var q = Math.pow(t,2)+Math.pow(w,2);
let P=a+b+q*2;
alert("периметр = "+ P);
}






```

<p>Подводя итог всему сказанному, могу сделать вывод, что, поработав на javascript, я вспомнил многое и применил это на практике. Все задачи были выполнены.</p>
