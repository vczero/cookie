cookie
-----------------
cookie is HTTP cookie. This library can better help you use cookie, for example, you can use the getter and setter methods

####Methods
	getCookies():get all cookie
	set(name, value[, opts]):set cookie; name is key，value is value of key; opts 
			is a obj that contains max-age、path、domain、secure attributes
	get(name)：get a cookie value by name
	remove(name)： delete a cookie by name
	clear(): clear all cookie
	noConflict(name)：handling conflict and creating new name for this library
####Quick start
You can see the cookie.html flie, it contains some examples      
(1) Add script in your html    

	<script type="text/javascript" src="cookie.js" ></script>

(2) Use methods: cookie is a global var.   

    cookie.set('name', 'vczero');
	cookie.getCookies();
	cookie.get('name');
	cookie.remove('name');
	cookie.clear();
	cookie.noConflict(true /*a new name of cookie*/);