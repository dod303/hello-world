
//predefined callback
a("Hello world", b);

//custom callback
a("Hello world", function(s) {
	console.log(s + ", how are you?");
});


function a(s, callback) {
	callback(s);
}

function b(s) {
	console.log(s + "!!!");
}
