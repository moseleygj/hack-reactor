var myArray = ['Romeo Sincere', 'ieatpcs'];
var myData = {}
myData.fullName = "Romeo Sincere";
myData.skypeName = myArray[1];
myData.github = "moseleygj";
alert("My Full name is: "+myData.fullName);
alert("My GitHub name is: "+myData.github);
alert("My skype name is: "+myData.skypeName);

console.dir(myData);

//test cutName
cutName(myData.fullName);

function cutName(x){
var str = x.split(' ');
  alert(str);
}
