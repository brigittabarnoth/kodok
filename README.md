var user = prompt("Akarsz játszani? ").toUpperCase();
switch(user) {
case 'IGEN':
console.log("Jó");
var gamer = prompt(" Egyedül vagy a sivatagban, a zsebedben egy alma de a zsebed be van varrva. Mit teszel? ");

switch(gamer) {
case 'semmit' :
var valt = prompt("Előtted egy oroszlán, még mindig lógatod a\ lábad, vagy teszel valamit? ");
if (valt === "igen") {
var valasz =prompt("Mi legyen?");
if (valasz === "várok") {
var valt2 = prompt("Türelmes várakozásod eredménye egy rózsa. Tudod hogyan tovább? ");
switch(valt2) {

case 'kiszúrom a zsebem' :
console.log("Te kis hamis....");
var valt3 =prompt("Ezek után már gondolom tudod hogyan lovagolsz ki a sivatagból?");
if (valt3 === "igen") {
console.log("GRatulálok megfejtetted!");
}
else
{
console.log("Ne búsulj, a google a barátod :) ");
}
break; 
case 'nem tudom' :
console.log("NE add fel! SEgítek: a rózsa tüskés, a zsebed be van varrva...próbáld meg kiszúrni a zsebed ");
var valt2 = prompt("Türelmes várakozásod eredménye egy rózsa. Tudod hogyan tovább? ");

break;
}
}
} break;
case 'várok' :
console.log("Te ismered ezt, mi??? ");
var valt2 = prompt("Türelmes várakozásod eredménye egy rózsa. Tudod hogyan tovább? ");
switch(valt2) {
case 'kiszúrom a zsebem' :
console.log("Te kis hamis....");
var valt3 =prompt("Ezek után már gondolom tudod hogyan lovagolsz ki a sivatagból?");
if (valt3 === "igen") {
console.log("GRatulálok megfejtetted!");
}
else
{
console.log("Ne búsulj, a google a barátod :) ");
}
break; 
case 'nem tudom' :
console.log("NE add fel! SEgítek: a rózsa tüskés, a zsebed be van varrva...próbáld meg kiszúrni a zsebed ");
var valt2 = prompt("Türelmes várakozásod eredménye egy rózsa. Tudod hogyan tovább? ");

break;
}
break;
default :
console.log("juhú, megoldottad a feladatot, túlélted!");
}
break;
case 'NEM' :
console.log("Sajnálom, majd legközelebb!");
break;
default :
console.log("Így nem tudom eldönteni, aludj rá egyet!");
}
