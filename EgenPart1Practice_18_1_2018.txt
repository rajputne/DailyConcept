//THe type of null is object
console.log("------Null Testing--------")
var f=null;
console.log(typeof f);

//The type of undefned is string undefined
console.log("------Undefined Testing--------")
var k=undefined;
console.log(typeof k);

//Create a new Object
console.log("------String Testing--------")
var fName=new String('Praveen');
console.log(fName);

//Create a String Literal
var fName2='Salitra';
console.log(fName2);

//Check by typeof
console.log(typeof fName2);
console.log(typeof fName);

var car='Tesla',
		year=2018,
    make='Model s'
// Backticks example     
var str=`Driving ${car}`

console.log(str);

//Boolean testing
console.log("------Boolean Testing--------")
var isAvailable=new Boolean();
var isAvail=true;

console.log(isAvailable);
console.log(isAvail);

console.log(typeof isAvailable);
console.log(typeof isAvail);

console.log("------Boolean Testing for NaN empty '' null false--------")

var good=null;

if(!good){
console.log('good')
}
console.log("------Number --------")

var num=new Number('1234.677');
console.log(num)
console.log(num.valueOf())

//It parses the number NaN will be the output
var num=new Number('1234677');

console.log(typeof num)
var num1=1;
console.log(typeof num1);
//Show weather the number is present or not
console.log(isNaN(num1));

//Testing If and Else
console.log("------If testing-----")
var test=0
//test=100 means true 
//test=0 means false

if(test){
console.log(test);
}else{
console.log('asdfg');
}

console.log('********Instances**********')
var instance={};
// Dot notation
instance.title='Neeraj';
instance.age=13;



//Box notation
instance['gender']='Male'
console.log(instance);

//Object Literal Notation
//Object inside an object
var instance2={
address:{
city:'Chicago',
}
}

console.log(instance2);
console.log(instance2['address'].city)

console.log(Object.keys(instance));

var jsonObject={
"address":{
"city":"Chicago",
}
}

console.log(jsonObject)