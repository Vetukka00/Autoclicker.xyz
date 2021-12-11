# Autoclicker.xyz
var event = new KeyboardEvent('keydown', {
	key: 'space',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);

var event = new MouseEvent('keydown', {
	key: 'MouseRightClick',
	 ctrlkey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);

var event = new MouseEvent('keydown', {
	key: 'MouseRightClick',
	 ctrlkey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);
