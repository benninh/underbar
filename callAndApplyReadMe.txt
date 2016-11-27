var obj = {num:2};


var addToThis = function(a){
	
	return this.num + a;
}

var val = 3;

addToThis.call(obj, val); // functionName.call(objToFunc, functionNameArguments)






var obj = {num:2};


var addToThis = function(a, b, c){
	
	return this.num + a + b +c;
}

addToThis.apply(obj, val); // functionName.apply(objToFunc, [functionNameArguments])


