var Horas = runtimeScene.getVariables().get("Horas")


var d = new Date();
var hours = d.getHours();
var min = d.getMinutes();
var sec = d.getSeconds();


Horas.setString(hours+":"+min+":"+sec);
