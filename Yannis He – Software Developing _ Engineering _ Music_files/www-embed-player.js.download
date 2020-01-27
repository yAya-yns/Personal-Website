(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
function q(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ba(a){for(var b,c=[];!(b=a.next()).done;)c.push(b.value);return c}
var ca="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},da;
if("function"==typeof Object.setPrototypeOf)da=Object.setPrototypeOf;else{var ea;a:{var fa={a:!0},ha={};try{ha.__proto__=fa;ea=ha.a;break a}catch(a){}ea=!1}da=ea?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ia=da;
function r(a,b){a.prototype=ca(b.prototype);a.prototype.constructor=a;if(ia)ia(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.L=b.prototype}
var ja="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){a!=Array.prototype&&a!=Object.prototype&&(a[b]=c.value)},ka="undefined"!=typeof window&&window===this?this:"undefined"!=typeof global&&null!=global?global:this;
function la(a,b){if(b){for(var c=ka,d=a.split("."),e=0;e<d.length-1;e++){var f=d[e];f in c||(c[f]={});c=c[f]}d=d[d.length-1];e=c[d];f=b(e);f!=e&&null!=f&&ja(c,d,{configurable:!0,writable:!0,value:f})}}
function na(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
la("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=na(this,b,"endsWith");b+="";void 0===c&&(c=d.length);for(var e=Math.max(0,Math.min(c|0,d.length)),f=b.length;0<f&&0<e;)if(d[--e]!=b[--f])return!1;return 0>=f}});
la("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=na(this,b,"startsWith");b+="";for(var e=d.length,f=b.length,g=Math.max(0,Math.min(c|0,d.length)),h=0;h<f&&g<e;)if(d[g++]!=b[h++])return!1;return h>=f}});
function oa(){oa=function(){};
ka.Symbol||(ka.Symbol=pa)}
function qa(a,b){this.f=a;ja(this,"description",{configurable:!0,writable:!0,value:b})}
qa.prototype.toString=function(){return this.f};
var pa=function(){function a(c){if(this instanceof a)throw new TypeError("Symbol is not a constructor");return new qa("jscomp_symbol_"+(c||"")+"_"+b++,c)}
var b=0;return a}();
function ra(){oa();var a=ka.Symbol.iterator;a||(a=ka.Symbol.iterator=ka.Symbol("Symbol.iterator"));"function"!=typeof Array.prototype[a]&&ja(Array.prototype,a,{configurable:!0,writable:!0,value:function(){return sa(aa(this))}});
ra=function(){}}
function sa(a){ra();a={next:a};a[ka.Symbol.iterator]=function(){return this};
return a}
function t(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ta="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)t(d,e)&&(a[e]=d[e])}return a};
la("Object.assign",function(a){return a||ta});
la("WeakMap",function(a){function b(k){this.f=(h+=Math.random()+1).toString();if(k){k=q(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!t(k,g)){var l=new c;ja(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n["delete"](k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!t(k,g))throw Error("WeakMap key fail: "+k);k[g][this.f]=l;return this};
b.prototype.get=function(k){return d(k)&&t(k,g)?k[g][this.f]:void 0};
b.prototype.has=function(k){return d(k)&&t(k,g)&&t(k[g],this.f)};
b.prototype["delete"]=function(k){return d(k)&&t(k,g)&&t(k[g],this.f)?delete k[g][this.f]:!1};
return b});
la("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.f;return sa(function(){if(l){for(;l.head!=h.f;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.g[l];if(n&&t(h.g,l))for(var p=0;p<n.length;p++){var x=n[p];if(k!==k&&x.key!==x.key||k===x.key)return{id:l,list:n,index:p,u:x}}return{id:l,list:n,index:-1,u:void 0}}
function e(h){this.g={};this.f=b();this.size=0;if(h){h=q(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(q([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
ra();var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.g[l.id]=[]);l.u?l.u.value=k:(l.u={next:this.f,previous:this.f.previous,head:this.f,key:h,value:k},l.list.push(l.u),this.f.previous.next=l.u,this.f.previous=l.u,this.size++);return this};
e.prototype["delete"]=function(h){h=d(this,h);return h.u&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.g[h.id],h.u.previous.next=h.u.next,h.u.next.previous=h.u.previous,h.u.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.g={};this.f=this.f.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).u};
e.prototype.get=function(h){return(h=d(this,h).u)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
la("Set",function(a){function b(c){this.f=new Map;if(c){c=q(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.f.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(q([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
ra();b.prototype.add=function(c){c=0===c?0:c;this.f.set(c,c);this.size=this.f.size;return this};
b.prototype["delete"]=function(c){c=this.f["delete"](c);this.size=this.f.size;return c};
b.prototype.clear=function(){this.f.clear();this.size=0};
b.prototype.has=function(c){return this.f.has(c)};
b.prototype.entries=function(){return this.f.entries()};
b.prototype.values=function(){return this.f.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.f.forEach(function(f){return c.call(d,f,f,e)})};
return b});
var ua=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ca(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}();
la("Reflect.construct",function(){return ua});
la("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==na(this,b,"includes").indexOf(b,c||0)}});
var v=this||self;function w(a,b,c){a=a.split(".");c=c||v;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
var va=/^[\w+/_-]+[=]{0,2}$/,wa=null;function y(a,b){for(var c=a.split("."),d=b||v,e=0;e<c.length;e++)if(d=d[c[e]],null==d)return null;return d}
function xa(){}
function ya(a){a.ha=void 0;a.getInstance=function(){return a.ha?a.ha:a.ha=new a}}
function za(a){var b=typeof a;if("object"==b)if(a){if(a instanceof Array)return"array";if(a instanceof Object)return b;var c=Object.prototype.toString.call(a);if("[object Window]"==c)return"object";if("[object Array]"==c||"number"==typeof a.length&&"undefined"!=typeof a.splice&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable("splice"))return"array";if("[object Function]"==c||"undefined"!=typeof a.call&&"undefined"!=typeof a.propertyIsEnumerable&&!a.propertyIsEnumerable("call"))return"function"}else return"null";
else if("function"==b&&"undefined"==typeof a.call)return"object";return b}
function z(a){return"array"==za(a)}
function Aa(a){var b=za(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Ba(a){return"function"==za(a)}
function Ca(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
var Da="closure_uid_"+(1E9*Math.random()>>>0),Ea=0;function Fa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ga(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function A(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?A=Fa:A=Ga;return A.apply(null,arguments)}
function Ha(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
var B=Date.now||function(){return+new Date};
function Ja(a,b){w(a,b,void 0)}
function C(a,b){function c(){}
c.prototype=b.prototype;a.L=b.prototype;a.prototype=new c;a.prototype.constructor=a}
;function D(a){if(Error.captureStackTrace)Error.captureStackTrace(this,D);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))}
C(D,Error);D.prototype.name="CustomError";var Ka=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},F=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},La=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Ma=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Na=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
F(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Oa(a,b){a:{var c=a.length;for(var d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){c=e;break a}c=-1}return 0>c?null:"string"===typeof a?a.charAt(c):a[c]}
function Pa(a,b){var c=Ka(a,b);0<=c&&Array.prototype.splice.call(a,c,1)}
function Qa(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function Ra(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Aa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Sa(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;function Ta(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function Ua(a,b){var c=Aa(b),d=c?b:arguments;for(c=c?0:1;c<d.length;c++){if(null==a)return;a=a[d[c]]}return a}
function Va(a){var b=Wa,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function Xa(a){for(var b in a)return!1;return!0}
function Ya(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function Za(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function $a(a){var b={},c;for(c in a)b[c]=a[c];return b}
function ab(a){var b=za(a);if("object"==b||"array"==b){if(Ba(a.clone))return a.clone();b="array"==b?[]:{};for(var c in a)b[c]=ab(a[c]);return b}return a}
var bb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function cb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<bb.length;f++)c=bb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function db(a,b){this.f=a===eb&&b||"";this.g=fb}
db.prototype.J=!0;db.prototype.I=function(){return this.f};
function gb(){var a=hb;return a instanceof db&&a.constructor===db&&a.g===fb?a.f:"type_error:Const"}
var fb={},eb={},hb=new db(eb,"");function ib(a,b){this.f=a===jb&&b||"";this.g=kb}
ib.prototype.J=!0;ib.prototype.I=function(){return this.f.toString()};
ib.prototype.ga=!0;ib.prototype.da=function(){return 1};
function lb(a){if(a instanceof ib&&a.constructor===ib&&a.g===kb)return a.f;za(a);return"type_error:TrustedResourceUrl"}
var kb={},jb={};var mb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function nb(a,b){if(b)a=a.replace(ob,"&amp;").replace(pb,"&lt;").replace(qb,"&gt;").replace(rb,"&quot;").replace(sb,"&#39;").replace(tb,"&#0;");else{if(!ub.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace(ob,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(pb,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(qb,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(rb,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(sb,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(tb,"&#0;"))}return a}
var ob=/&/g,pb=/</g,qb=/>/g,rb=/"/g,sb=/'/g,tb=/\x00/g,ub=/[\x00&<>"']/;function G(a,b){this.f=a===vb&&b||"";this.g=wb}
G.prototype.J=!0;G.prototype.I=function(){return this.f.toString()};
G.prototype.ga=!0;G.prototype.da=function(){return 1};
function xb(a){if(a instanceof G&&a.constructor===G&&a.g===wb)return a.f;za(a);return"type_error:SafeUrl"}
var yb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;function zb(a){if(a instanceof G)return a;a="object"==typeof a&&a.J?a.I():String(a);yb.test(a)||(a="about:invalid#zClosurez");return new G(vb,a)}
var wb={},vb={};var Ab;a:{var Bb=v.navigator;if(Bb){var Cb=Bb.userAgent;if(Cb){Ab=Cb;break a}}Ab=""};function Db(){this.f="";this.h=Eb;this.g=null}
Db.prototype.ga=!0;Db.prototype.da=function(){return this.g};
Db.prototype.J=!0;Db.prototype.I=function(){return this.f.toString()};
function Gb(a){if(a instanceof Db&&a.constructor===Db&&a.h===Eb)return a.f;za(a);return"type_error:SafeHtml"}
var Eb={};function Hb(a,b){var c=new Db;c.f=a;c.g=b;return c}
Hb("<!DOCTYPE html>",0);var Ib=Hb("",0);Hb("<br>",0);function Jb(a,b){var c=b instanceof G?b:zb(b);a.href=xb(c)}
function Kb(a,b){a.src=lb(b);if(null===wa)b:{var c=v.document;if((c=c.querySelector&&c.querySelector("script[nonce]"))&&(c=c.nonce||c.getAttribute("nonce"))&&va.test(c)){wa=c;break b}wa=""}c=wa;c&&a.setAttribute("nonce",c)}
;function Lb(a){return a=nb(a,void 0)}
function Mb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Nb=-1!=Ab.indexOf("Trident")||-1!=Ab.indexOf("MSIE"),Ob;var Pb;if(v.document&&Nb){var Qb=v.document;Pb=Qb?Qb.documentMode:void 0}else Pb=void 0;Ob=Pb;var Rb={},Sb=null;var H=window;function Tb(a){var b=y("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(f){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||v.$googDebugFname||b}catch(f){e="Not available",c=!0}return!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name?a:(b=a.message,null==b&&(a.constructor&&
a.constructor instanceof Function?(a.constructor.name?b=a.constructor.name:(b=a.constructor,Ub[b]?b=Ub[b]:(b=String(b),Ub[b]||(c=/function\s+([^\(]+)/m.exec(b),Ub[b]=c?c[1]:"[Anonymous]"),b=Ub[b])),b='Unknown Error of type "'+b+'"'):b="Unknown Error of unknown type"),{message:b,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:a.stack||"Not available"})}
var Ub={};function Vb(a){this.f=a||{cookie:""}}
m=Vb.prototype;m.isEnabled=function(){return navigator.cookieEnabled};
m.set=function(a,b,c,d,e,f){if("object"===typeof c){var g=c.g;f=c.secure;e=c.domain;d=c.path;c=c.f}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===c&&(c=-1);e=e?";domain="+e:"";d=d?";path="+d:"";f=f?";secure":"";c=0>c?"":0==c?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(B()+1E3*c)).toUTCString();this.f.cookie=a+"="+b+e+d+c+f+(null!=g?";samesite="+g:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.f.cookie||"").split(";"),e=0,f;e<d.length;e++){f=mb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",0,b,c);return d};
m.isEmpty=function(){return!this.f.cookie};
m.clear=function(){for(var a=(this.f.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=mb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Wb=new Vb("undefined"==typeof document?null:document);var Xb=!Nb||9<=Number(Ob);function Yb(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=Yb.prototype;m.clone=function(){return new Yb(this.x,this.y)};
m.equals=function(a){return a instanceof Yb&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};function Zb(a,b){this.width=a;this.height=b}
m=Zb.prototype;m.clone=function(){return new Zb(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function $b(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function ac(a,b){Ta(b,function(c,d){c&&"object"==typeof c&&c.J&&(c=c.I());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:bc.hasOwnProperty(d)?a.setAttribute(bc[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var bc={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};
function cc(a,b,c){var d=arguments,e=document,f=String(d[0]),g=d[1];if(!Xb&&g&&(g.name||g.type)){f=["<",f];g.name&&f.push(' name="',Lb(g.name),'"');if(g.type){f.push(' type="',Lb(g.type),'"');var h={};cb(h,g);delete h.type;g=h}f.push(">");f=f.join("")}f=dc(e,f);g&&("string"===typeof g?f.className=g:z(g)?f.className=g.join(" "):ac(f,g));2<d.length&&ec(e,f,d);return f}
function ec(a,b,c){function d(g){g&&b.appendChild("string"===typeof g?a.createTextNode(g):g)}
for(var e=2;e<c.length;e++){var f=c[e];!Aa(f)||Ca(f)&&0<f.nodeType?d(f):F(fc(f)?Qa(f):f,d)}}
function dc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function fc(a){if(a&&"number"==typeof a.length){if(Ca(a))return"function"==typeof a.item||"string"==typeof a.item;if(Ba(a))return"function"==typeof a.item}return!1}
function gc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function hc(a){ic();return new ib(jb,a)}
var ic=xa;var jc=/^(?:([^:/?#.]+):)?(?:\/\/(?:([^/?#]*)@)?([^/#?]*?)(?::([0-9]+))?(?=[/#?]|$))?([^?#]+)?(?:\?([^#]*))?(?:#([\s\S]*))?$/;function I(a){return a?decodeURI(a):a}
function J(a,b){return b.match(jc)[a]||null}
function kc(a,b,c){if(z(b))for(var d=0;d<b.length;d++)kc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function lc(a){var b=[],c;for(c in a)kc(c,a[c],b);return b.join("&")}
function mc(a,b){var c=lc(b);if(c){var d=a.indexOf("#");0>d&&(d=a.length);var e=a.indexOf("?");if(0>e||e>d){e=d;var f=""}else f=a.substring(e+1,d);d=[a.substr(0,e),f,a.substr(d)];e=d[1];d[1]=c?e?e+"&"+c:c:e;c=d[0]+(d[1]?"?"+d[1]:"")+d[2]}else c=a;return c}
var nc=/#|$/;function oc(a,b){var c=a.search(nc);a:{var d=0;for(var e=b.length;0<=(d=a.indexOf(b,d))&&d<c;){var f=a.charCodeAt(d-1);if(38==f||63==f)if(f=a.charCodeAt(d+e),!f||61==f||38==f||35==f)break a;d+=e+1}d=-1}if(0>d)return null;e=a.indexOf("&",d);if(0>e||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.substr(d,e-d).replace(/\+/g," "))}
;function pc(a){var b=qc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function rc(){var a=[];pc(function(b){a.push(b)});
return a}
var qc={Ya:"allow-forms",Za:"allow-modals",ab:"allow-orientation-lock",bb:"allow-pointer-lock",cb:"allow-popups",eb:"allow-popups-to-escape-sandbox",fb:"allow-presentation",gb:"allow-same-origin",hb:"allow-scripts",ib:"allow-top-navigation",jb:"allow-top-navigation-by-user-activation"},sc=Sa(function(){return rc()});
function tc(){var a=dc(document,"IFRAME"),b={};F(sc(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;function uc(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var vc=(new Date).getTime();function wc(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));a=a.substring(0,a.indexOf("://"));if("http"!==a&&"https"!==a&&"chrome-extension"!==a&&"file"!==a&&"android-app"!==a&&"chrome-search"!==a&&"app"!==a)throw Error("Invalid URI scheme in origin: "+a);c="";var d=b.indexOf(":");if(-1!=d){var e=
b.substring(d+1);b=b.substring(0,d);if("http"===a&&"80"!==e||"https"===a&&"443"!==e)c=":"+e}return a+"://"+b+c}
;function xc(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var x=g,u=0;64>u;u+=4)x[u/4]=p[u]<<24|p[u+1]<<16|p[u+2]<<8|p[u+3];for(u=16;80>u;u++)p=x[u-3]^x[u-8]^x[u-14]^x[u-16],x[u]=(p<<1|p>>>31)&4294967295;p=e[0];var E=e[1],U=e[2],ma=e[3],Ac=e[4];for(u=0;80>u;u++){if(40>u)if(20>u){var Ia=ma^E&(U^ma);var Fb=1518500249}else Ia=E^U^ma,Fb=1859775393;else 60>u?(Ia=E&U|ma&(E|U),Fb=2400959708):(Ia=E^U^ma,Fb=3395469782);Ia=((p<<5|p>>>27)&4294967295)+Ia+Ac+Fb+x[u]&4294967295;Ac=ma;ma=U;U=(E<<30|E>>>2)&4294967295;E=p;p=Ia}e[0]=e[0]+p&4294967295;e[1]=
e[1]+E&4294967295;e[2]=e[2]+U&4294967295;e[3]=e[3]+ma&4294967295;e[4]=e[4]+Ac&4294967295}
function c(p,x){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var u=[],E=0,U=p.length;E<U;++E)u.push(p.charCodeAt(E));p=u}x||(x=p.length);u=0;if(0==l)for(;u+64<x;)b(p.slice(u,u+64)),u+=64,n+=64;for(;u<x;)if(f[l++]=p[u++],n++,64==l)for(l=0,b(f);u+64<x;)b(p.slice(u,u+64)),u+=64,n+=64}
function d(){var p=[],x=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var u=63;56<=u;u--)f[u]=x&255,x>>>=8;b(f);for(u=x=0;5>u;u++)for(var E=24;0<=E;E-=8)p[x++]=e[u]>>E&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,va:function(){for(var p=d(),x="",u=0;u<p.length;u++)x+="0123456789ABCDEF".charAt(Math.floor(p[u]/16))+"0123456789ABCDEF".charAt(p[u]%16);return x}}}
;function yc(a,b,c){var d=[],e=[];if(1==(z(c)?2:1))return e=[b,a],F(d,function(h){e.push(h)}),zc(e.join(" "));
var f=[],g=[];F(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];F(d,function(h){e.push(h)});
a=zc(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function zc(a){var b=xc();b.update(a);return b.va().toLowerCase()}
;function Bc(a){var b=wc(String(v.location.href)),c;(c=v.__SAPISID||v.__APISID||v.__OVERRIDE_SID)?c=!0:(c=new Vb(document),c=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID"),c=!!c);if(c&&(c=(b=0==b.indexOf("https:")||0==b.indexOf("chrome-extension:"))?v.__SAPISID:v.__APISID,c||(c=new Vb(document),c=c.get(b?"SAPISID":"APISID")||c.get("__Secure-3PAPISID")),c)){b=b?"SAPISIDHASH":"APISIDHASH";var d=String(v.location.href);return d&&c&&b?[b,yc(wc(d),c,a||null)].join(" "):null}return null}
;function Cc(a,b){this.h=a;this.i=b;this.g=0;this.f=null}
Cc.prototype.get=function(){if(0<this.g){this.g--;var a=this.f;this.f=a.next;a.next=null}else a=this.h();return a};
function Dc(a,b){a.i(b);100>a.g&&(a.g++,b.next=a.f,a.f=b)}
;function Ec(a){v.setTimeout(function(){throw a;},0)}
var Fc;
function Gc(){var a=v.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&-1==Ab.indexOf("Presto")&&(a=function(){var e=dc(document,"IFRAME");e.style.display="none";e.src=lb(new ib(jb,gb())).toString();document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.write(Gb(Ib));e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=A(function(k){if(("*"==h||
k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&-1==Ab.indexOf("Trident")&&-1==Ab.indexOf("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.ka;c.ka=null;e()}};
return function(e){d.next={ka:e};d=d.next;b.port2.postMessage(0)}}return"undefined"!==typeof document&&"onreadystatechange"in dc(document,"SCRIPT")?function(e){var f=dc(document,"SCRIPT");
f.onreadystatechange=function(){f.onreadystatechange=null;f.parentNode.removeChild(f);f=null;e();e=null};
document.documentElement.appendChild(f)}:function(e){v.setTimeout(e,0)}}
;function Hc(){this.g=this.f=null}
var Jc=new Cc(function(){return new Ic},function(a){a.reset()});
Hc.prototype.add=function(a,b){var c=Jc.get();c.set(a,b);this.g?this.g.next=c:this.f=c;this.g=c};
Hc.prototype.remove=function(){var a=null;this.f&&(a=this.f,this.f=this.f.next,this.f||(this.g=null),a.next=null);return a};
function Ic(){this.next=this.scope=this.f=null}
Ic.prototype.set=function(a,b){this.f=a;this.scope=b;this.next=null};
Ic.prototype.reset=function(){this.next=this.scope=this.f=null};function Kc(a,b){Lc||Mc();Nc||(Lc(),Nc=!0);Oc.add(a,b)}
var Lc;function Mc(){if(v.Promise&&v.Promise.resolve){var a=v.Promise.resolve(void 0);Lc=function(){a.then(Pc)}}else Lc=function(){var b=Pc;
!Ba(v.setImmediate)||v.Window&&v.Window.prototype&&-1==Ab.indexOf("Edge")&&v.Window.prototype.setImmediate==v.setImmediate?(Fc||(Fc=Gc()),Fc(b)):v.setImmediate(b)}}
var Nc=!1,Oc=new Hc;function Pc(){for(var a;a=Oc.remove();){try{a.f.call(a.scope)}catch(b){Ec(b)}Dc(Jc,a)}Nc=!1}
;function Qc(){this.g=-1}
;function Rc(){this.g=64;this.f=[];this.l=[];this.A=[];this.i=[];this.i[0]=128;for(var a=1;a<this.g;++a)this.i[a]=0;this.j=this.h=0;this.reset()}
C(Rc,Qc);Rc.prototype.reset=function(){this.f[0]=1732584193;this.f[1]=4023233417;this.f[2]=2562383102;this.f[3]=271733878;this.f[4]=3285377520;this.j=this.h=0};
function Sc(a,b,c){c||(c=0);var d=a.A;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.f[0];c=a.f[1];var g=a.f[2],h=a.f[3],k=a.f[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.f[0]=a.f[0]+b&4294967295;a.f[1]=a.f[1]+c&4294967295;a.f[2]=a.f[2]+g&4294967295;a.f[3]=a.f[3]+h&4294967295;a.f[4]=a.f[4]+k&4294967295}
Rc.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.g,d=0,e=this.l,f=this.h;d<b;){if(0==f)for(;d<=c;)Sc(this,a,d),d+=this.g;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.g){Sc(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.g){Sc(this,e);f=0;break}}this.h=f;this.j+=b}};
Rc.prototype.digest=function(){var a=[],b=8*this.j;56>this.h?this.update(this.i,56-this.h):this.update(this.i,this.g-(this.h-56));for(var c=this.g-1;56<=c;c--)this.l[c]=b&255,b/=256;Sc(this,this.l);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.f[c]>>d&255,++b;return a};function K(){this.g=this.g;this.A=this.A}
K.prototype.g=!1;K.prototype.dispose=function(){this.g||(this.g=!0,this.m())};
function Tc(a,b){a.g?b():(a.A||(a.A=[]),a.A.push(b))}
K.prototype.m=function(){if(this.A)for(;this.A.length;)this.A.shift()()};
function Uc(a){a&&"function"==typeof a.dispose&&a.dispose()}
function Vc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Aa(d)?Vc.apply(null,d):Uc(d)}}
;function Wc(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Xc(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Yc(a,b){if(a.classList)var c=a.classList.contains(b);else c=a.classList?a.classList:Wc(a).match(/\S+/g)||[],c=0<=Ka(c,b);return c}
function Zc(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Yc(a,"inverted-hdpi")&&Xc(a,La(a.classList?a.classList:Wc(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var $c="StopIteration"in v?v.StopIteration:{message:"StopIteration",stack:""};function ad(){}
ad.prototype.next=function(){throw $c;};
ad.prototype.D=function(){return this};
function bd(a){if(a instanceof ad)return a;if("function"==typeof a.D)return a.D(!1);if(Aa(a)){var b=0,c=new ad;c.next=function(){for(;;){if(b>=a.length)throw $c;if(b in a)return a[b++];b++}};
return c}throw Error("Not implemented");}
function cd(a,b){if(Aa(a))try{F(a,b,void 0)}catch(c){if(c!==$c)throw c;}else{a=bd(a);try{for(;;)b.call(void 0,a.next(),void 0,a)}catch(c){if(c!==$c)throw c;}}}
function dd(a){if(Aa(a))return Qa(a);a=bd(a);var b=[];cd(a,function(c){b.push(c)});
return b}
;function ed(a,b){this.h={};this.f=[];this.F=this.g=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof ed)for(c=fd(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function fd(a){gd(a);return a.f.concat()}
m=ed.prototype;m.equals=function(a,b){if(this===a)return!0;if(this.g!=a.g)return!1;var c=b||hd;gd(this);for(var d,e=0;d=this.f[e];e++)if(!c(this.get(d),a.get(d)))return!1;return!0};
function hd(a,b){return a===b}
m.isEmpty=function(){return 0==this.g};
m.clear=function(){this.h={};this.F=this.g=this.f.length=0};
m.remove=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)?(delete this.h[a],this.g--,this.F++,this.f.length>2*this.g&&gd(this),!0):!1};
function gd(a){if(a.g!=a.f.length){for(var b=0,c=0;b<a.f.length;){var d=a.f[b];Object.prototype.hasOwnProperty.call(a.h,d)&&(a.f[c++]=d);b++}a.f.length=c}if(a.g!=a.f.length){var e={};for(c=b=0;b<a.f.length;)d=a.f[b],Object.prototype.hasOwnProperty.call(e,d)||(a.f[c++]=d,e[d]=1),b++;a.f.length=c}}
m.get=function(a,b){return Object.prototype.hasOwnProperty.call(this.h,a)?this.h[a]:b};
m.set=function(a,b){Object.prototype.hasOwnProperty.call(this.h,a)||(this.g++,this.f.push(a),this.F++);this.h[a]=b};
m.forEach=function(a,b){for(var c=fd(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new ed(this)};
m.D=function(a){gd(this);var b=0,c=this.F,d=this,e=new ad;e.next=function(){if(c!=d.F)throw Error("The map has changed since the iterator was created");if(b>=d.f.length)throw $c;var f=d.f[b++];return a?f:d.h[f]};
return e};function id(a){var b=[];jd(new kd,a,b);return b.join("")}
function kd(){}
function jd(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(z(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),jd(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),ld(d,c),c.push(":"),jd(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":ld(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var md={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},nd=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function ld(a,b){b.push('"',a.replace(nd,function(c){var d=md[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),md[c]=d);return d}),'"')}
;function od(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function L(a){this.f=0;this.A=void 0;this.i=this.g=this.h=null;this.j=this.l=!1;if(a!=xa)try{var b=this;a.call(void 0,function(c){pd(b,2,c)},function(c){pd(b,3,c)})}catch(c){pd(this,3,c)}}
function qd(){this.next=this.context=this.onRejected=this.g=this.f=null;this.h=!1}
qd.prototype.reset=function(){this.context=this.onRejected=this.g=this.f=null;this.h=!1};
var rd=new Cc(function(){return new qd},function(a){a.reset()});
function sd(a,b,c){var d=rd.get();d.g=a;d.onRejected=b;d.context=c;return d}
function td(a){return new L(function(b,c){c(a)})}
L.prototype.then=function(a,b,c){return ud(this,Ba(a)?a:null,Ba(b)?b:null,c)};
L.prototype.$goog_Thenable=!0;function vd(a,b){return ud(a,null,b,void 0)}
L.prototype.cancel=function(a){if(0==this.f){var b=new wd(a);Kc(function(){xd(this,b)},this)}};
function xd(a,b){if(0==a.f)if(a.h){var c=a.h;if(c.g){for(var d=0,e=null,f=null,g=c.g;g&&(g.h||(d++,g.f==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.f&&1==d?xd(c,b):(f?(d=f,d.next==c.i&&(c.i=d),d.next=d.next.next):yd(c),zd(c,e,3,b)))}a.h=null}else pd(a,3,b)}
function Ad(a,b){a.g||2!=a.f&&3!=a.f||Bd(a);a.i?a.i.next=b:a.g=b;a.i=b}
function ud(a,b,c,d){var e=sd(null,null,null);e.f=new L(function(f,g){e.g=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof wd?g(h):f(k)}catch(l){g(l)}}:g});
e.f.h=a;Ad(a,e);return e.f}
L.prototype.w=function(a){this.f=0;pd(this,2,a)};
L.prototype.B=function(a){this.f=0;pd(this,3,a)};
function pd(a,b,c){if(0==a.f){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.f=1;a:{var d=c,e=a.w,f=a.B;if(d instanceof L){Ad(d,sd(e||xa,f||null,a));var g=!0}else if(od(d))d.then(e,f,a),g=!0;else{if(Ca(d))try{var h=d.then;if(Ba(h)){Cd(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.A=c,a.f=b,a.h=null,Bd(a),3!=b||c instanceof wd||Dd(a,c))}}
function Cd(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Bd(a){a.l||(a.l=!0,Kc(a.o,a))}
function yd(a){var b=null;a.g&&(b=a.g,a.g=b.next,b.next=null);a.g||(a.i=null);return b}
L.prototype.o=function(){for(var a;a=yd(this);)zd(this,a,this.f,this.A);this.l=!1};
function zd(a,b,c,d){if(3==c&&b.onRejected&&!b.h)for(;a&&a.j;a=a.h)a.j=!1;if(b.f)b.f.h=null,Ed(b,c,d);else try{b.h?b.g.call(b.context):Ed(b,c,d)}catch(e){Fd.call(null,e)}Dc(rd,b)}
function Ed(a,b,c){2==b?a.g.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Dd(a,b){a.j=!0;Kc(function(){a.j&&Fd.call(null,b)})}
var Fd=Ec;function wd(a){D.call(this,a)}
C(wd,D);wd.prototype.name="cancel";function M(a){K.call(this);this.l=1;this.i=[];this.j=0;this.f=[];this.h={};this.o=!!a}
C(M,K);m=M.prototype;m.subscribe=function(a,b,c){var d=this.h[a];d||(d=this.h[a]=[]);var e=this.l;this.f[e]=a;this.f[e+1]=b;this.f[e+2]=c;this.l=e+3;d.push(e);return e};
function Gd(a,b,c,d){if(b=a.h[b]){var e=a.f;(b=Oa(b,function(f){return e[f+1]==c&&e[f+2]==d}))&&a.N(b)}}
m.N=function(a){var b=this.f[a];if(b){var c=this.h[b];0!=this.j?(this.i.push(a),this.f[a+1]=xa):(c&&Pa(c,a),delete this.f[a],delete this.f[a+1],delete this.f[a+2])}return!!b};
m.M=function(a,b){var c=this.h[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.o)for(e=0;e<c.length;e++){var g=c[e];Hd(this.f[g+1],this.f[g+2],d)}else{this.j++;try{for(e=0,f=c.length;e<f;e++)g=c[e],this.f[g+1].apply(this.f[g+2],d)}finally{if(this.j--,0<this.i.length&&0==this.j)for(;c=this.i.pop();)this.N(c)}}return 0!=e}return!1};
function Hd(a,b,c){Kc(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.h[a];b&&(F(b,this.N,this),delete this.h[a])}else this.f.length=0,this.h={}};
m.m=function(){M.L.m.call(this);this.clear();this.i.length=0};function Id(a){this.f=a}
Id.prototype.set=function(a,b){void 0===b?this.f.remove(a):this.f.set(a,id(b))};
Id.prototype.get=function(a){try{var b=this.f.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Id.prototype.remove=function(a){this.f.remove(a)};function Jd(a){this.f=a}
C(Jd,Id);function Kd(a){this.data=a}
function Ld(a){return void 0===a||a instanceof Kd?a:new Kd(a)}
Jd.prototype.set=function(a,b){Jd.L.set.call(this,a,Ld(b))};
Jd.prototype.g=function(a){a=Jd.L.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Jd.prototype.get=function(a){if(a=this.g(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Md(a){this.f=a}
C(Md,Jd);Md.prototype.set=function(a,b,c){if(b=Ld(b)){if(c){if(c<B()){Md.prototype.remove.call(this,a);return}b.expiration=c}b.creation=B()}Md.L.set.call(this,a,b)};
Md.prototype.g=function(a){var b=Md.L.g.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<B()||c&&c>B())Md.prototype.remove.call(this,a);else return b}};function Nd(){}
;function Od(){}
C(Od,Nd);Od.prototype.clear=function(){var a=dd(this.D(!0)),b=this;F(a,function(c){b.remove(c)})};function Pd(a){this.f=a}
C(Pd,Od);m=Pd.prototype;m.isAvailable=function(){if(!this.f)return!1;try{return this.f.setItem("__sak","1"),this.f.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.f.setItem(a,b)}catch(c){if(0==this.f.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.f.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.f.removeItem(a)};
m.D=function(a){var b=0,c=this.f,d=new ad;d.next=function(){if(b>=c.length)throw $c;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){this.f.clear()};
m.key=function(a){return this.f.key(a)};function Qd(){var a=null;try{a=window.localStorage||null}catch(b){}this.f=a}
C(Qd,Pd);function Rd(a,b){this.g=a;this.f=null;if(Nb&&!(9<=Number(Ob))){Sd||(Sd=new ed);this.f=Sd.get(a);this.f||(b?this.f=document.getElementById(b):(this.f=document.createElement("userdata"),this.f.addBehavior("#default#userData"),document.body.appendChild(this.f)),Sd.set(a,this.f));try{this.f.load(this.g)}catch(c){this.f=null}}}
C(Rd,Od);var Td={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Sd=null;function Ud(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Td[b]})}
m=Rd.prototype;m.isAvailable=function(){return!!this.f};
m.set=function(a,b){this.f.setAttribute(Ud(a),b);Vd(this)};
m.get=function(a){a=this.f.getAttribute(Ud(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.f.removeAttribute(Ud(a));Vd(this)};
m.D=function(a){var b=0,c=this.f.XMLDocument.documentElement.attributes,d=new ad;d.next=function(){if(b>=c.length)throw $c;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
m.clear=function(){for(var a=this.f.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Vd(this)};
function Vd(a){try{a.f.save(a.g)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Wd(a,b){this.g=a;this.f=b+"::"}
C(Wd,Od);Wd.prototype.set=function(a,b){this.g.set(this.f+a,b)};
Wd.prototype.get=function(a){return this.g.get(this.f+a)};
Wd.prototype.remove=function(a){this.g.remove(this.f+a)};
Wd.prototype.D=function(a){var b=this.g.D(!0),c=this,d=new ad;d.next=function(){for(var e=b.next();e.substr(0,c.f.length)!=c.f;)e=b.next();return a?e.substr(c.f.length):c.g.get(e)};
return d};function Xd(){this.g=[];this.f=-1}
Xd.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.g[a]!=b&&(this.g[a]=b,this.f=-1)};
Xd.prototype.get=function(a){return!!this.g[a]};
function Yd(a){-1==a.f&&(a.f=Na(a.g,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.f}
;function Zd(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var $d=window.yt&&window.yt.config_||window.ytcfg&&window.ytcfg.data_||{};w("yt.config_",$d,void 0);function N(a){Zd($d,arguments)}
function O(a,b){return a in $d?$d[a]:b}
function ae(){return O("PLAYER_CONFIG",{})}
;function be(){var a=ce;y("yt.ads.biscotti.getId_")||w("yt.ads.biscotti.getId_",a,void 0)}
function de(a){w("yt.ads.biscotti.lastId_",a,void 0)}
;var ee=[];function fe(a){ee.forEach(function(b){return b(a)})}
function ge(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){P(b),fe(b)}}:a}
function P(a,b,c,d,e){var f=y("yt.logging.errors.log");f?f(a,b,c,d,e):(f=O("ERRORS",[]),f.push([a,b,c,d,e]),N("ERRORS",f))}
function he(a){P(a,"WARNING",void 0,void 0,void 0)}
;function ie(a){var b=[];Ta(a,function(c,d){var e=encodeURIComponent(String(d)),f;z(c)?f=c:f=[c];F(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function je(a){"?"==a.charAt(0)&&(a=a.substr(1));a=a.split("&");for(var b={},c=0,d=a.length;c<d;c++){var e=a[c].split("=");if(1==e.length&&e[0]||2==e.length)try{var f=decodeURIComponent((e[0]||"").replace(/\+/g," ")),g=decodeURIComponent((e[1]||"").replace(/\+/g," "));f in b?z(b[f])?Ra(b[f],g):b[f]=[b[f],g]:b[f]=g}catch(k){if("q"!=e[0]){var h=Error("Error decoding URL component");h.params={key:e[0],value:e[1]};P(h)}}}return b}
function ke(a,b){return le(a,b||{},!0)}
function le(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=je(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return mc(a,e)+d}
;function me(a){var b=ne;a=void 0===a?y("yt.ads.biscotti.lastId_")||"":a;b=Object.assign(oe(b),pe(b));b.ca_type="image";a&&(b.bid=a);return b}
function oe(a){var b={};b.dt=vc;b.flash="0";a:{try{var c=a.f.top.location.href}catch(f){a=2;break a}a=c?c===a.g.location.href?0:1:2}b=(b.frm=a,b);b.u_tz=-(new Date).getTimezoneOffset();var d=void 0===d?H:d;try{var e=d.history.length}catch(f){e=0}b.u_his=e;b.u_java=!!H.navigator&&"unknown"!==typeof H.navigator.javaEnabled&&!!H.navigator.javaEnabled&&H.navigator.javaEnabled();H.screen&&(b.u_h=H.screen.height,b.u_w=H.screen.width,b.u_ah=H.screen.availHeight,b.u_aw=H.screen.availWidth,b.u_cd=H.screen.colorDepth);
H.navigator&&H.navigator.plugins&&(b.u_nplug=H.navigator.plugins.length);H.navigator&&H.navigator.mimeTypes&&(b.u_nmime=H.navigator.mimeTypes.length);return b}
function pe(a){var b=a.f;try{var c=b.screenX;var d=b.screenY}catch(p){}try{var e=b.outerWidth;var f=b.outerHeight}catch(p){}try{var g=b.innerWidth;var h=b.innerHeight}catch(p){}b=[b.screenLeft,b.screenTop,c,d,b.screen?b.screen.availWidth:void 0,b.screen?b.screen.availTop:void 0,e,f,g,h];c=a.f.top;try{var k=(c||window).document,l="CSS1Compat"==k.compatMode?k.documentElement:k.body;var n=(new Zb(l.clientWidth,l.clientHeight)).round()}catch(p){n=new Zb(-12245933,-12245933)}k=n;n={};l=new Xd;v.SVGElement&&
v.document.createElementNS&&l.set(0);c=tc();c["allow-top-navigation-by-user-activation"]&&l.set(1);c["allow-popups-to-escape-sandbox"]&&l.set(2);v.crypto&&v.crypto.subtle&&l.set(3);v.TextDecoder&&v.TextEncoder&&l.set(4);l=Yd(l);n.bc=l;n.bih=k.height;n.biw=k.width;n.brdim=b.join();a=a.g;return n.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[a.visibilityState||a.webkitVisibilityState||a.mozVisibilityState||""]||0,n.wgl=!!H.WebGLRenderingContext,n}
var ne=new function(){var a=window.document;this.f=window;this.g=a};
w("yt.ads_.signals_.getAdSignalsString",function(a){return ie(me(a))},void 0);B();function Q(a){a=qe(a);return"string"===typeof a&&"false"===a?!1:!!a}
function re(a,b){var c=qe(a);return void 0===c&&void 0!==b?b:Number(c||0)}
function qe(a){var b=O("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:O("EXPERIMENT_FLAGS",{})[a]}
;var se=void 0!==XMLHttpRequest?function(){return new XMLHttpRequest}:void 0!==ActiveXObject?function(){return new ActiveXObject("Microsoft.XMLHTTP")}:null;
function te(){if(!se)return null;var a=se();return"open"in a?a:null}
function ue(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function R(a,b){Ba(a)&&(a=ge(a));return window.setTimeout(a,b)}
function S(a){window.clearTimeout(a)}
;var ve={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},we="app debugcss debugjs expflag force_ad_params force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" "),
xe=!1;
function ye(a,b){b=void 0===b?{}:b;if(!c)var c=window.location.href;var d=J(1,a),e=I(J(3,a));d&&e?(d=c,c=a.match(jc),d=d.match(jc),c=c[3]==d[3]&&c[1]==d[1]&&c[4]==d[4]):c=e?I(J(3,c))==e&&(Number(J(4,c))||null)==(Number(J(4,a))||null):!0;d=Q("web_ajax_ignore_global_headers_if_set");for(var f in ve)e=O(ve[f]),!e||!c&&!ze(a,f)||d&&void 0!==b[f]||(b[f]=e);if(c||ze(a,"X-YouTube-Utc-Offset"))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());(c||ze(a,"X-YouTube-Time-Zone"))&&(f="undefined"!=typeof Intl?
(new Intl.DateTimeFormat).resolvedOptions().timeZone:null)&&(b["X-YouTube-Time-Zone"]=f);if(c||ze(a,"X-YouTube-Ad-Signals"))b["X-YouTube-Ad-Signals"]=ie(me(void 0));return b}
function Ae(a){var b=window.location.search,c=I(J(3,a)),d=I(J(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=je(b),f={};F(we,function(g){e[g]&&(f[g]=e[g])});
return le(a,f||{},!1)}
function ze(a,b){var c=O("CORS_HEADER_WHITELIST")||{},d=I(J(3,a));return d?(c=c[d])?0<=Ka(c,b):!1:!0}
function Be(a,b){if(window.fetch&&"XML"!=b.format){var c={method:b.method||"GET",credentials:"same-origin"};b.headers&&(c.headers=b.headers);a=Ce(a,b);var d=De(a,b);d&&(c.body=d);b.withCredentials&&(c.credentials="include");var e=!1,f;fetch(a,c).then(function(g){if(!e){e=!0;f&&S(f);var h=g.ok,k=function(l){l=l||{};var n=b.context||v;h?b.onSuccess&&b.onSuccess.call(n,l,g):b.onError&&b.onError.call(n,l,g);b.ia&&b.ia.call(n,l,g)};
"JSON"==(b.format||"JSON")&&(h||400<=g.status&&500>g.status)?g.json().then(k,function(){k(null)}):k(null)}});
b.na&&0<b.timeout&&(f=R(function(){e||(e=!0,S(f),b.na.call(b.context||v))},b.timeout))}else Ee(a,b)}
function Ee(a,b){var c=b.format||"JSON";a=Ce(a,b);var d=De(a,b),e=!1,f,g=Fe(a,function(h){if(!e){e=!0;f&&S(f);var k=ue(h),l=null,n=400<=h.status&&500>h.status,p=500<=h.status&&600>h.status;if(k||n||p)l=Ge(c,h,b.nb);if(k)a:if(h&&204==h.status)k=!0;else{switch(c){case "XML":k=0==parseInt(l&&l.return_code,10);break a;case "RAW":k=!0;break a}k=!!l}l=l||{};n=b.context||v;k?b.onSuccess&&b.onSuccess.call(n,h,l):b.onError&&b.onError.call(n,h,l);b.ia&&b.ia.call(n,h,l)}},b.method,d,b.headers,b.responseType,
b.withCredentials);
b.O&&0<b.timeout&&(f=R(function(){e||(e=!0,g.abort(),S(f),b.O.call(b.context||v,g))},b.timeout));
return g}
function Ce(a,b){b.qb&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=O("XSRF_FIELD_NAME",void 0),d=b.Xa;d&&(d[c]&&delete d[c],a=ke(a,d));return a}
function De(a,b){var c=O("XSRF_FIELD_NAME",void 0),d=O("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.C,g=O("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.pb||I(J(3,a))&&!b.withCredentials&&I(J(3,a))!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.C&&b.C[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=je(e),cb(e,f),e=b.oa&&"JSON"==b.oa?JSON.stringify(e):lc(e));f=e||f&&!Xa(f);!xe&&f&&"POST"!=b.method&&(xe=!0,P(Error("AJAX request with postData should use POST")));
return e}
function Ge(a,b,c){var d=null;switch(a){case "JSON":a=b.responseText;b=b.getResponseHeader("Content-Type")||"";a&&0<=b.indexOf("json")&&(d=JSON.parse(a));break;case "XML":if(b=(b=b.responseXML)?He(b):null)d={},F(b.getElementsByTagName("*"),function(e){d[e.tagName]=Ie(e)})}c&&Je(d);
return d}
function Je(a){if(Ca(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=Hb(a[b],null);a[c]=d}else Je(a[b])}}
function He(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Ie(a){var b="";F(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Fe(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&ge(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=te();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;Q("debug_forward_web_query_parameters")&&(a=Ae(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=ye(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Ke={},Le=0;
function Me(a,b,c,d,e){e=void 0===e?"":e;a&&(c&&(c=Ab,c=!(c&&0<=c.toLowerCase().indexOf("cobalt"))),c?a&&(a instanceof G||(a="object"==typeof a&&a.J?a.I():String(a),yb.test(a)||(a="about:invalid#zClosurez"),a=new G(vb,a)),b=xb(a),"about:invalid#zClosurez"===b?a="":(b instanceof Db?a=b:(d="object"==typeof b,a=null,d&&b.ga&&(a=b.da()),b=nb(d&&b.J?b.I():String(b)),a=Hb(b,a)),a=Gb(a).toString(),a=encodeURIComponent(String(id(a)))),/^[\s\xa0]*$/.test(a)||(a=cc("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+
'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))):e?Fe(a,b,"POST",e,d):O("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d?Fe(a,b,"GET","",d):Ne(a,b)||Oe(a,b))}
function Ne(a,b){var c=$d.EXPERIMENT_FLAGS;if(!c||!c.web_use_beacon_api_for_ad_click_server_pings)return!1;c=I(J(5,a));return c&&-1!=c.indexOf("/aclk")&&"1"===oc(a,"ae")&&"1"===oc(a,"act")?Pe(a)?(b&&b(),!0):!1:!1}
function Pe(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Oe(a,b){var c=new Image,d=""+Le++;Ke[d]=c;c.onload=c.onerror=function(){b&&Ke[d]&&b();delete Ke[d]};
c.src=a}
;function Qe(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(c instanceof Array?c:ba(q(c)))}
r(Qe,Error);var Re=new Set,Se=0;function Te(a,b,c,d,e,f){b=void 0===b?"ERROR":b;f=void 0===f?{}:f;f.name=c||O("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||O("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};d=void 0===b?"ERROR":b;d=void 0===d?"ERROR":d;f=window&&window.yterr||!1;if(a&&f&&!(5<=Se)){Q("console_log_js_exceptions")&&(f=[],f.push("Name: "+a.name),f.push("Message: "+a.message),a.hasOwnProperty("params")&&f.push("Error Params: "+JSON.stringify(a.params)),f.push("File name: "+a.fileName),f.push("Stacktrace: "+a.stack),
window.console.log(f.join("\n"),a));f=a.f;b=a.columnNumber;if(a.hasOwnProperty("params"))if(e=a.params,"object"===typeof a.params){var g=0;for(l in e)if(e[l]){var h="params."+l,k=String(JSON.stringify(e[l])).substr(0,500);c[h]=k;g+=h.length+k.length;if(500<g)break}}else c.params=String(JSON.stringify(e)).substr(0,500);a=Tb(a);(f=f||a.stack)||(f="Not available");var l=a.lineNumber.toString();isNaN(l)||!b||isNaN(b)||(l=l+":"+b);window.yterr&&Ba(window.yterr)&&window.yterr(a);if(!(Re.has(a.message)||
0<=f.indexOf("/YouTubeCenter.js")||0<=f.indexOf("/mytube.js"))){l={Xa:{a:"logerror",t:"jserror",type:a.name,msg:a.message.substr(0,250),line:l,level:d,"client.name":c.name},C:{url:O("PAGE_NAME",window.location.href),file:a.fileName},method:"POST"};c.version&&(l["client.version"]=c.version);if(l.C){f&&(l.C.stack=f);d=q(Object.keys(c));for(f=d.next();!f.done;f=d.next())f=f.value,l.C["client."+f]=c[f];if(c=O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(d=q(Object.keys(c)),f=d.next();!f.done;f=
d.next())f=f.value,l.C[f]=c[f]}Ee(O("ECATCHER_REPORT_HOST","")+"/error_204",l);Re.add(a.message);Se++}}}
;var Ue=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};w("yt.msgs_",Ue,void 0);function Ve(a){Zd(Ue,arguments)}
;function We(a){a&&(a.dataset?a.dataset[Xe("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Ye(a,b){return a?a.dataset?a.dataset[Xe(b)]:a.getAttribute("data-"+b):null}
var Ze={};function Xe(a){return Ze[a]||(Ze[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var $e=y("ytPubsubPubsubInstance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.N;M.prototype.publish=M.prototype.M;M.prototype.clear=M.prototype.clear;w("ytPubsubPubsubInstance",$e,void 0);var af=y("ytPubsubPubsubSubscribedKeys")||{};w("ytPubsubPubsubSubscribedKeys",af,void 0);var bf=y("ytPubsubPubsubTopicToKeys")||{};w("ytPubsubPubsubTopicToKeys",bf,void 0);var cf=y("ytPubsubPubsubIsSynchronous")||{};w("ytPubsubPubsubIsSynchronous",cf,void 0);
function df(a,b){var c=ef();if(c){var d=c.subscribe(a,function(){var e=arguments;var f=function(){af[d]&&b.apply(window,e)};
try{cf[a]?f():R(f,0)}catch(g){P(g)}},void 0);
af[d]=!0;bf[a]||(bf[a]=[]);bf[a].push(d);return d}return 0}
function ff(a){var b=ef();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),F(a,function(c){b.unsubscribeByKey(c);delete af[c]}))}
function gf(a,b){var c=ef();c&&c.publish.apply(c,arguments)}
function hf(a){var b=ef();if(b)if(b.clear(a),a)jf(a);else for(var c in bf)jf(c)}
function ef(){return y("ytPubsubPubsubInstance")}
function jf(a){bf[a]&&(a=bf[a],F(a,function(b){af[b]&&delete af[b]}),a.length=0)}
;var kf=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,lf=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function mf(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(kf,""),c=c.replace(lf,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else nf(a,b,c)}
function nf(a,b,c){c=void 0===c?null:c;var d=of(a),e=document.getElementById(d),f=e&&Ye(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=df(d,b),b=""+(b[Da]||(b[Da]=++Ea)),pf[b]=f),g||(e=qf(a,d,function(){Ye(e,"loaded")||(We(e),gf(d),R(Ha(hf,d),0))},c)))}
function qf(a,b,c,d){d=void 0===d?null:d;var e=dc(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Kb(e,hc(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function rf(a){a=of(a);var b=document.getElementById(a);b&&(hf(a),b.parentNode.removeChild(b))}
function sf(a,b){if(a&&b){var c=""+(b[Da]||(b[Da]=++Ea));(c=pf[c])&&ff(c)}}
function of(a){var b=document.createElement("a");Jb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Mb(a)}
var pf={};function tf(){}
function uf(a,b){return vf(a,1,b)}
;function wf(){}
r(wf,tf);function vf(a,b,c){isNaN(c)&&(c=void 0);var d=y("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):R(a,c||0)}
wf.prototype.start=function(){var a=y("yt.scheduler.instance.start");a&&a()};
wf.prototype.pause=function(){var a=y("yt.scheduler.instance.pause");a&&a()};
ya(wf);wf.getInstance();var xf=[],yf=!1;function zf(){if("1"!=Ua(ae(),"args","privembed")){var a=function(){yf=!0;"google_ad_status"in window?N("DCLKSTAT",1):N("DCLKSTAT",2)};
mf("//static.doubleclick.net/instream/ad_status.js",a);xf.push(uf(function(){yf||"google_ad_status"in window||(sf("//static.doubleclick.net/instream/ad_status.js",a),yf=!0,N("DCLKSTAT",3))},5E3))}}
function Af(){return parseInt(O("DCLKSTAT",0),10)}
;function Bf(){this.g=!1;this.f=null}
Bf.prototype.initialize=function(a,b,c,d,e){var f=this;b?(this.g=!0,mf(b,function(){f.g=!1;if(window.botguard)Cf(f,c,d);else{rf(b);var g=Error("Unable to load Botguard");g.params="from "+b;he(g)}},e)):a&&(eval(a),window.botguard?Cf(this,c,d):he(Error("Unable to load Botguard from JS")))};
function Cf(a,b,c){try{a.f=new window.botguard.bg(b)}catch(d){he(d)}c&&c(b)}
Bf.prototype.dispose=function(){this.f=null};var Df=window,T=Df.ytcsi&&Df.ytcsi.now?Df.ytcsi.now:Df.performance&&Df.performance.timing&&Df.performance.now?function(){return Df.performance.timing.navigationStart+Df.performance.now()}:function(){return(new Date).getTime()};var Ef=new Bf,Ff=!1,Gf=0,Hf="";function If(a){Q("botguard_periodic_refresh")?Gf=T():Q("botguard_always_refresh")&&(Hf=a)}
function Jf(a){if(a){if(Ef.g)return!1;if(Q("botguard_periodic_refresh"))return 72E5<T()-Gf;if(Q("botguard_always_refresh"))return Hf!=a}else return!1;return!Ff}
function Kf(){return!!Ef.f}
function Lf(a){a=void 0===a?{}:a;a=void 0===a?{}:a;return Ef.f?Ef.f.invoke(void 0,void 0,a):null}
;var Mf=0;w("ytDomDomGetNextId",y("ytDomDomGetNextId")||function(){return++Mf},void 0);var Nf={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Of(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Nf||(this[b]=a[b]);var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==
this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.f=a.pageX;this.g=a.pageY}}catch(e){}}
function Pf(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.f=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.g=a.clientY+b}}
Of.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Of.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Of.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var Wa=y("ytEventsEventsListeners")||{};w("ytEventsEventsListeners",Wa,void 0);var Qf=y("ytEventsEventsCounter")||{count:0};w("ytEventsEventsCounter",Qf,void 0);
function Rf(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return Va(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ca(e[4])&&Ca(d)&&Za(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Sf=Sa(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function V(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Rf(a,b,c,d);if(e)return e;e=++Qf.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Of(h);if(!gc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Of(h);
h.currentTarget=a;return c.call(a,h)};
g=ge(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Sf()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);Wa[e]=[a,b,c,g,d];return e}
function Tf(a){a&&("string"==typeof a&&(a=[a]),F(a,function(b){if(b in Wa){var c=Wa[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Sf()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete Wa[b]}}))}
;var Uf=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Vf(a){this.w=a;this.f=null;this.j=0;this.o=null;this.l=0;this.h=[];for(a=0;4>a;a++)this.h.push(0);this.i=0;this.G=V(window,"mousemove",A(this.H,this));a=A(this.B,this);Ba(a)&&(a=ge(a));this.K=window.setInterval(a,25)}
C(Vf,K);Vf.prototype.H=function(a){void 0===a.f&&Pf(a);var b=a.f;void 0===a.g&&Pf(a);this.f=new Yb(b,a.g)};
Vf.prototype.B=function(){if(this.f){var a=Uf();if(0!=this.j){var b=this.o,c=this.f,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.j);this.h[this.i]=.5<Math.abs((d-this.l)/this.l)?1:0;for(c=b=0;4>c;c++)b+=this.h[c]||0;3<=b&&this.w();this.l=d}this.j=a;this.o=this.f;this.i=(this.i+1)%4}};
Vf.prototype.m=function(){window.clearInterval(this.K);Tf(this.G)};var Wf={};
function Xf(a){var b=void 0===a?{}:a;a=void 0===b.Aa?!0:b.Aa;b=void 0===b.Ma?!1:b.Ma;if(null==y("_lact",window)){var c=parseInt(O("LACT"),10);c=isFinite(c)?B()-Math.max(c,0):-1;w("_lact",c,window);w("_fact",c,window);-1==c&&Yf();V(document,"keydown",Yf);V(document,"keyup",Yf);V(document,"mousedown",Yf);V(document,"mouseup",Yf);a&&(b?V(window,"touchmove",function(){Zf("touchmove",200)},{passive:!0}):(V(window,"resize",function(){Zf("resize",200)}),V(window,"scroll",function(){Zf("scroll",200)})));
new Vf(function(){Zf("mouse",100)});
V(document,"touchstart",Yf,{passive:!0});V(document,"touchend",Yf,{passive:!0})}}
function Zf(a,b){Wf[a]||(Wf[a]=!0,uf(function(){Yf();Wf[a]=!1},b))}
function Yf(){null==y("_lact",window)&&Xf();var a=B();w("_lact",a,window);-1==y("_fact",window)&&w("_fact",a,window);(a=y("ytglobal.ytUtilActivityCallback_"))&&a()}
function $f(){var a=y("_lact",window);return null==a?-1:Math.max(B()-a,0)}
;var ag=Math.pow(2,16)-1,bg=null,cg=0,dg={log_event:"events",log_interaction:"interactions"},eg=Object.create(null);eg.log_event="GENERIC_EVENT_LOGGING";eg.log_interaction="INTERACTION_LOGGING";var fg=new Set(["log_event"]),gg={},hg=0,ig=0,jg=0,W=y("ytLoggingTransportLogPayloadsQueue_")||{};w("ytLoggingTransportLogPayloadsQueue_",W,void 0);var kg=y("ytLoggingTransportTokensToCttTargetIds_")||{};w("ytLoggingTransportTokensToCttTargetIds_",kg,void 0);var lg=y("ytLoggingTransportDispatchedStats_")||{};
w("ytLoggingTransportDispatchedStats_",lg,void 0);w("ytytLoggingTransportCapturedTime_",y("ytLoggingTransportCapturedTime_")||{},void 0);function mg(){S(hg);S(ig);ig=0;if(!Xa(W)){for(var a in W){var b=gg[a];b&&b.isReady()&&(ng(a,b),delete W[a])}Xa(W)||og()}}
function og(){Q("web_gel_timeout_cap")&&!ig&&(ig=R(mg,6E4));S(hg);hg=R(mg,O("LOGGING_BATCH_TIMEOUT",re("web_gel_debounce_ms",1E4)))}
function pg(a,b){b=void 0===b?"":b;W[a]=W[a]||{};W[a][b]=W[a][b]||[];return W[a][b]}
function ng(a,b){var c=dg[a],d=lg[a]||{};lg[a]=d;var e=Math.round(T());for(p in W[a]){var f=ab,g=b.f||qg();g={client:{hl:g.Ea,gl:g.Da,clientName:g.Ca,clientVersion:g.innertubeContextClientVersion,configInfo:g.Ba}};var h=window.devicePixelRatio;h&&1!=h&&(g.client.screenDensityFloat=String(h));h=O("EXPERIMENTS_TOKEN","");""!==h&&(g.client.experimentsToken=h);var k=h=void 0,l=[],n=O("EXPERIMENTS_FORCED_FLAGS",{});for(k in n)l.push({key:k,value:String(n[k])});k=O("EXPERIMENT_FLAGS",{});for(h in k)h.startsWith("force_")&&
void 0===n[h]&&l.push({key:h,value:String(k[h])});h=l;0<h.length&&(g.request={internalExperimentFlags:h});O("DELEGATED_SESSION_ID")&&!Q("pageid_as_header_web")&&(g.user={onBehalfOfUser:O("DELEGATED_SESSION_ID")});f=f({context:g});f[c]=pg(a,p);d.dispatchedEventCount=d.dispatchedEventCount||0;d.dispatchedEventCount+=f[c].length;if(g=kg[p])a:{l=p;if(g.videoId)h="VIDEO";else if(g.playlistId)h="PLAYLIST";else break a;f.credentialTransferTokenTargetId=g;f.context=f.context||{};f.context.user=f.context.user||
{};f.context.user.credentialTransferTokens=[{token:l,scope:h}]}delete kg[p];f.requestTimeMs=e;Q("unsplit_gel_payloads_in_logs")&&(f.unsplitGelPayloadsInLogs=!0);if(g=O("EVENT_ID",void 0))h=(O("BATCH_CLIENT_COUNTER",void 0)||0)+1,h>ag&&(h=1),N("BATCH_CLIENT_COUNTER",h),g={serializedEventId:g,clientCounter:h},f.serializedClientEventId=g,bg&&cg&&Q("log_gel_rtt_web")&&(f.previousBatchInfo={serializedClientEventId:bg,roundtripMs:cg}),bg=g,cg=0;rg(b,a,f,{retry:fg.has(a),onSuccess:A(sg,this,T())})}if(d.previousDispatchMs){c=
e-d.previousDispatchMs;var p=d.diffCount||0;d.averageTimeBetweenDispatchesMs=p?(d.averageTimeBetweenDispatchesMs*p+c)/(p+1):c;d.diffCount=p+1}d.previousDispatchMs=e}
function sg(a){cg=Math.round(T()-a)}
;var tg=y("ytLoggingGelSequenceIdObj_")||{};w("ytLoggingGelSequenceIdObj_",tg,void 0);
function ug(a,b,c,d){d=void 0===d?{}:d;var e={};e.eventTimeMs=Math.round(d.timestamp||T());e[a]=b;e.context={lastActivityMs:String(d.timestamp?-1:$f())};Q("log_sequence_info_on_gel_web")&&d.P&&(a=e.context,b=d.P,tg[b]=b in tg?tg[b]+1:0,a.sequence={index:tg[b],groupKey:b},d.ob&&delete tg[d.P]);(d=d.ca)?(a={},d.videoId?a.videoId=d.videoId:d.playlistId&&(a.playlistId=d.playlistId),kg[d.token]=a,d=pg("log_event",d.token)):d=pg("log_event");d.push(e);c&&(gg.log_event=new c);c=re("web_logging_max_batch")||
100;e=T();d.length>=c?mg():10<=e-jg&&(og(),jg=e)}
;function vg(a){this.f=a}
function wg(a){var b={};void 0!==a.f.trackingParams?b.trackingParams=a.f.trackingParams:(b.veType=a.f.veType,null!=a.f.veCounter&&(b.veCounter=a.f.veCounter),null!=a.f.elementIndex&&(b.elementIndex=a.f.elementIndex));void 0!==a.f.dataElement&&(b.dataElement=wg(a.f.dataElement));void 0!==a.f.youtubeData&&(b.youtubeData=a.f.youtubeData);return b}
vg.prototype.toString=function(){return JSON.stringify(wg(this))};
var xg=1;function yg(a,b){this.version=a;this.args=b}
;function zg(a,b){this.topic=a;this.f=b}
zg.prototype.toString=function(){return this.topic};var Ag=y("ytPubsub2Pubsub2Instance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.N;M.prototype.publish=M.prototype.M;M.prototype.clear=M.prototype.clear;w("ytPubsub2Pubsub2Instance",Ag,void 0);var Bg=y("ytPubsub2Pubsub2SubscribedKeys")||{};w("ytPubsub2Pubsub2SubscribedKeys",Bg,void 0);var Cg=y("ytPubsub2Pubsub2TopicToKeys")||{};w("ytPubsub2Pubsub2TopicToKeys",Cg,void 0);var Dg=y("ytPubsub2Pubsub2IsAsync")||{};w("ytPubsub2Pubsub2IsAsync",Dg,void 0);
w("ytPubsub2Pubsub2SkipSubKey",null,void 0);function Eg(a,b){var c=Fg();c&&c.publish.call(c,a.toString(),a,b)}
function Gg(a){var b=Hg,c=Fg();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=y("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Bg[d])try{if(f&&b instanceof zg&&b!=e)try{var h=b.f,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.F){var l=new h;h.F=l.version}var n=h.F}catch(p){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
Qa(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){P(p)}},Dg[b.toString()]?y("yt.scheduler.instance")?uf(g):R(g,0):g())});
Bg[d]=!0;Cg[b.toString()]||(Cg[b.toString()]=[]);Cg[b.toString()].push(d);return d}
function Ig(){var a=Jg,b=Gg(function(c){a.apply(void 0,arguments);Kg(b)});
return b}
function Kg(a){var b=Fg();b&&("number"===typeof a&&(a=[a]),F(a,function(c){b.unsubscribeByKey(c);delete Bg[c]}))}
function Fg(){return y("ytPubsub2Pubsub2Instance")}
;function Lg(a){yg.call(this,1,arguments);this.csn=a}
r(Lg,yg);var Hg=new zg("screen-created",Lg),Mg=[],Ng=0;function Og(a,b,c){var d=Pg;b={csn:a,parentVe:wg(b),childVes:Ma(c,function(f){return wg(f)})};
c=q(c);for(var e=c.next();!e.done;e=c.next())e=wg(e.value),(Xa(e)||!e.trackingParams&&!e.veType)&&Te(Error("Child VE logged with no data"),"WARNING");c={ca:void 0,P:a};"UNDEFINED_CSN"==a?Qg("visualElementAttached",b,c):ug("visualElementAttached",b,d,c)}
function Qg(a,b,c){Mg.push({La:a,payload:b,options:c});Ng||(Ng=Ig())}
function Jg(a){if(Mg){for(var b=q(Mg),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,ug(c.La,c.payload,null,c.options));Mg.length=0}Ng=0}
;function Rg(){return"INNERTUBE_API_KEY"in $d&&"INNERTUBE_API_VERSION"in $d}
function qg(){return{innertubeApiKey:O("INNERTUBE_API_KEY",void 0),innertubeApiVersion:O("INNERTUBE_API_VERSION",void 0),Ba:O("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ca:O("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:O("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Ea:O("INNERTUBE_CONTEXT_HL",void 0),Da:O("INNERTUBE_CONTEXT_GL",void 0),Fa:O("INNERTUBE_HOST_OVERRIDE",void 0)||"",Ga:!!O("INNERTUBE_USE_THIRD_PARTY_AUTH",!1)}}
function Sg(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||O("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.lb||O("AUTHORIZATION"))||(a?b="Bearer "+y("gapi.auth.getToken")().kb:b=Bc([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=O("SESSION_INDEX",0),Q("pageid_as_header_web")&&(d["X-Goog-PageId"]=O("DELEGATED_SESSION_ID")));return d}
function Tg(a){a=Object.assign({},a);delete a.Authorization;var b=Bc();if(b){var c=new Rc;c.update(O("INNERTUBE_API_KEY",void 0));c.update(b);b=c.digest();c=3;Aa(b);void 0===c&&(c=0);if(!Sb){Sb={};for(var d="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),e=["+/=","+/","-_=","-_.","-_"],f=0;5>f;f++){var g=d.concat(e[f].split(""));Rb[f]=g;for(var h=0;h<g.length;h++){var k=g[h];void 0===Sb[k]&&(Sb[k]=h)}}}c=Rb[c];d=[];for(e=0;e<b.length;e+=3){var l=b[e],n=(f=e+1<b.length)?
b[e+1]:0;k=(g=e+2<b.length)?b[e+2]:0;h=l>>2;l=(l&3)<<4|n>>4;n=(n&15)<<2|k>>6;k&=63;g||(k=64,f||(n=64));d.push(c[h],c[l],c[n]||"",c[k]||"")}a.hash=d.join("")}return a}
;function Ug(a,b,c,d){Wb.set(""+a,b,c,"/",void 0===d?"youtube.com":d,!1)}
;function Vg(){var a=new Qd;(a=a.isAvailable()?new Wd(a,"yt.innertube"):null)||(a=new Rd("yt.innertube"),a=a.isAvailable()?a:null);this.f=a?new Md(a):null;this.g=document.domain||window.location.hostname}
Vg.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.f)try{this.f.set(a,b,B()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(id(b))}catch(f){return}else e=escape(b);Ug(a,e,c,this.g)};
Vg.prototype.get=function(a,b){var c=void 0,d=!this.f;if(!d)try{c=this.f.get(a)}catch(e){d=!0}if(d&&(c=Wb.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Vg.prototype.remove=function(a){this.f&&this.f.remove(a);var b=this.g;Wb.remove(""+a,"/",void 0===b?"youtube.com":b)};var Wg=new Vg;function Xg(a,b,c,d){if(d)return null;d=Wg.get("nextId",!0)||1;var e=Wg.get("requests",!0)||{};e[d]={method:a,request:b,authState:Tg(c),requestTime:Math.round(T())};Wg.set("nextId",d+1,86400,!0);Wg.set("requests",e,86400,!0);return d}
function Yg(a){var b=Wg.get("requests",!0)||{};delete b[a];Wg.set("requests",b,86400,!0)}
function Zg(a){var b=Wg.get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=Tg(Sg(!1));Za(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),rg(a,d.method,e,{}));delete b[c]}}Wg.set("requests",b,86400,!0)}}
;function Pg(a){var b=this;this.f=null;a?this.f=a:Q("delay_gel_until_config_ready")?Rg()&&(this.f=qg()):this.f=qg();vf(function(){Zg(b)},0,5E3)}
Pg.prototype.isReady=function(){!this.f&&Rg()&&(this.f=qg());return!!this.f};
function rg(a,b,c,d){!O("VISITOR_DATA")&&.01>Math.random()&&P(Error("Missing VISITOR_DATA when sending innertube request."),"WARNING");var e={headers:{"Content-Type":"application/json"},method:"POST",C:c,oa:"JSON",O:function(){d.O()},
na:d.O,onSuccess:function(x,u){if(d.onSuccess)d.onSuccess(u)},
ma:function(x){if(d.onSuccess)d.onSuccess(x)},
onError:function(x,u){if(d.onError)d.onError(u)},
rb:function(x){if(d.onError)d.onError(x)},
timeout:d.timeout,withCredentials:!0},f="",g=a.f.Fa;g&&(f=g);g=a.f.Ga||!1;var h=Sg(g,f,d);Object.assign(e.headers,h);e.headers.Authorization&&!f&&(e.headers["x-origin"]=window.location.origin);var k=ke(""+f+("/youtubei/"+a.f.innertubeApiVersion+"/"+b),{alt:"json",key:a.f.innertubeApiKey}),l;if(d.retry&&Q("retry_web_logging_batches")&&"www.youtube-nocookie.com"!=f&&(l=Xg(b,c,h,g))){var n=e.onSuccess,p=e.ma;e.onSuccess=function(x,u){Yg(l);n(x,u)};
c.ma=function(x,u){Yg(l);p(x,u)}}try{Q("use_fetch_for_op_xhr")?Be(k,e):(e.method="POST",e.C||(e.C={}),Ee(k,e))}catch(x){if("InvalidAccessError"==x)l&&(Yg(l),l=0),P(Error("An extension is blocking network request."),"WARNING");
else throw x;}l&&vf(function(){Zg(a)},0,5E3)}
;var $g=B().toString();
function ah(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=B();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if($g)for(a=1,b=0;b<$g.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^$g.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var bh=y("ytLoggingTimeDocumentNonce_")||ah();w("ytLoggingTimeDocumentNonce_",bh,void 0);function ch(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function dh(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function eh(a){return O(dh(void 0===a?0:a),void 0)}
w("yt_logging_screen.getRootVeType",eh,void 0);function fh(){var a=eh(0),b;a?b=new vg({veType:a,youtubeData:void 0}):b=null;return b}
function gh(a){a=void 0===a?0:a;var b=O(ch(a));b||0!=a||(Q("kevlar_client_side_screens")||Q("c3_client_side_screens")?b="UNDEFINED_CSN":b=O("EVENT_ID"));return b?b:null}
w("yt_logging_screen.getCurrentCsn",gh,void 0);function hh(a,b,c){c=void 0===c?0:c;if(a!==O(ch(c))||b!==O(dh(c)))N(ch(c),a),N(dh(c),b),0==c&&(b=function(){setTimeout(function(){a&&ug("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:bh,clientScreenNonce:a},Pg)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b())}
w("yt_logging_screen.setCurrentScreen",hh,void 0);function ih(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=O("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=O("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=I(J(3,window.location.href));g&&f.push(g);g=I(J(3,d));if(0<=Ka(f,g)||!g&&0==d.lastIndexOf("/",0))if(Q("autoescape_tempdata_url")&&(f=document.createElement("a"),Jb(f,d),d=f.href),d){g=d.match(jc);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||
b.ved)&&(b=Object.assign({csn:gh()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&(e=b,b="ST-"+Mb(d).toString(36),e=e?lc(e):"",Ug(b,e,k||5))}else k=b,e="ST-"+Mb(d).toString(36),k=k?lc(k):"",Ug(e,k,5)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var n=void 0===n?"":n;var p=void 0===p?window:p;c=p.location;a=mc(a,l)+n;a=a instanceof G?a:zb(a);c.href=xb(a)}return!0}
;function jh(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||$a(b);this.assets=a.assets||{};this.attrs=a.attrs||$a(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
jh.prototype.clone=function(){var a=new jh,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==za(c)?a[b]=$a(c):a[b]=c}return a};function kh(){K.call(this);this.f=[]}
r(kh,K);kh.prototype.m=function(){for(;this.f.length;){var a=this.f.pop();a.target.removeEventListener(a.name,a.mb)}K.prototype.m.call(this)};var lh=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function mh(a){a=a||"";if(window.spf){var b=a.match(lh);spf.style.load(a,b?b[1]:"",void 0)}else nh(a)}
function nh(a){var b=oh(a),c=document.getElementById(b),d=c&&Ye(c,"loaded");d||c&&!d||(c=ph(a,b,function(){Ye(c,"loaded")||(We(c),gf(b),R(Ha(hf,b),0))}))}
function ph(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=hc(a);d.rel="stylesheet";d.href=lb(a).toString();(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function oh(a){var b=dc(document,"A");Jb(b,new G(vb,a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Mb(a)}
;function qh(a,b,c,d){K.call(this);var e=this;this.l=this.X=a;this.U=b;this.w=!1;this.api={};this.V=this.G=null;this.H=new M;Tc(this,Ha(Uc,this.H));this.i={};this.R=this.W=this.h=this.ba=this.f=null;this.K=!1;this.j=this.B=null;this.Y={};this.sa=["onReady"];this.aa=null;this.ja=NaN;this.S={};this.o=d;rh(this);this.Z("WATCH_LATER_VIDEO_ADDED",this.Ia.bind(this));this.Z("WATCH_LATER_VIDEO_REMOVED",this.Ja.bind(this));this.Z("onAdAnnounce",this.ua.bind(this));this.ta=new kh(this);Tc(this,Ha(Uc,this.ta));
this.T=0;c?this.T=R(function(){e.loadNewVideoConfig(c)},0):d&&(sh(this),th(this))}
r(qh,K);m=qh.prototype;m.getId=function(){return this.U};
m.loadNewVideoConfig=function(a){if(!this.g){this.T&&(S(this.T),this.T=0);a instanceof jh||(a=new jh(a));this.ba=a;this.f=a.clone();sh(this);this.W||(this.W=uh(this,this.f.args.jsapicallback||"onYouTubePlayerReady"));this.f.args.jsapicallback=null;if(a=this.f.attrs.width)this.l.style.width=uc(Number(a)||a);if(a=this.f.attrs.height)this.l.style.height=uc(Number(a)||a);th(this);this.w&&vh(this)}};
function sh(a){var b;a.o?b=a.o.rootElementId:b=a.f.attrs.id;a.h=b||a.h;"video-player"==a.h&&(a.h=a.U,a.f.attrs.id=a.U);a.l.id==a.h&&(a.h+="-player",a.f.attrs.id=a.h)}
m.xa=function(){return this.ba};
function vh(a){a.f&&!a.f.loaded&&(a.f.loaded=!0,"0"!=a.f.args.autoplay?a.api.loadVideoByPlayerVars(a.f.args):a.api.cueVideoByPlayerVars(a.f.args))}
function wh(a){var b=!0,c=xh(a);c&&a.f&&(a=yh(a),b=Ye(c,"version")==a);return b&&!!y("yt.player.Application.create")}
function th(a){if(!a.g&&!a.K){var b=wh(a);if(b&&"html5"==(xh(a)?"html5":null))a.R="html5",a.w||zh(a);else if(Ah(a),a.R="html5",b&&a.j)a.X.appendChild(a.j),zh(a);else{a.f&&(a.f.loaded=!0);var c=!1;a.B=function(){c=!0;var d=y("yt.player.Application.create"),e=a.f?a.f.clone():void 0;d(a.X,e,a.o);zh(a)};
a.K=!0;b?a.B():(mf(yh(a),a.B),mh(a.o?a.o.cssUrl:a.f.assets.css),Bh(a)&&!c&&w("yt.player.Application.create",null,void 0))}}}
function xh(a){var b=$b(a.h);!b&&a.l&&a.l.querySelector&&(b=a.l.querySelector("#"+a.h));return b}
function zh(a){if(!a.g){var b=xh(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);c?(a.K=!1,b.isNotServable&&a.f&&b.isNotServable(a.f.args.video_id)||Ch(a)):a.ja=R(function(){zh(a)},50)}}
function Ch(a){rh(a);a.w=!0;var b=xh(a);b.addEventListener&&(a.G=Dh(a,b,"addEventListener"));b.removeEventListener&&(a.V=Dh(a,b,"removeEventListener"));var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=0;d<c.length;d++){var e=c[d];a.api[e]||(a.api[e]=Dh(a,b,e))}for(var f in a.i)a.G(f,a.i[f]);vh(a);a.W&&a.W(a.api);a.H.M("onReady",a.api)}
function Dh(a,b,c){var d=b[c];return function(){try{return a.aa=null,d.apply(b,arguments)}catch(e){"sendAbandonmentPing"!=c&&(e.params=c,a.aa=e,he(e))}}}
function rh(a){a.w=!1;if(a.V)for(var b in a.i)a.V(b,a.i[b]);for(var c in a.S)S(parseInt(c,10));a.S={};a.G=null;a.V=null;for(var d in a.api)a.api[d]=null;a.api.addEventListener=a.Z.bind(a);a.api.removeEventListener=a.Oa.bind(a);a.api.destroy=a.dispose.bind(a);a.api.getLastError=a.ya.bind(a);a.api.getPlayerType=a.za.bind(a);a.api.getCurrentVideoConfig=a.xa.bind(a);a.api.loadNewVideoConfig=a.loadNewVideoConfig.bind(a);a.api.isReady=a.Ha.bind(a)}
m.Ha=function(){return this.w};
m.Z=function(a,b){var c=this,d=uh(this,b);if(d){if(!(0<=Ka(this.sa,a)||this.i[a])){var e=Eh(this,a);this.G&&this.G(a,e)}this.H.subscribe(a,d);"onReady"==a&&this.w&&R(function(){d(c.api)},0)}};
m.Oa=function(a,b){if(!this.g){var c=uh(this,b);c&&Gd(this.H,a,c)}};
function uh(a,b){var c=b;if("string"==typeof b){if(a.Y[b])return a.Y[b];c=function(){var d=y(b);d&&d.apply(v,arguments)};
a.Y[b]=c}return c?c:null}
function Eh(a,b){var c="ytPlayer"+b+a.U;a.i[b]=c;v[c]=function(d){var e=R(function(){if(!a.g){a.H.M(b,d);var f=a.S,g=String(e);g in f&&delete f[g]}},0);
Ya(a.S,String(e))};
return c}
m.ua=function(a){gf("a11y-announce",a)};
m.Ia=function(a){gf("WATCH_LATER_VIDEO_ADDED",a)};
m.Ja=function(a){gf("WATCH_LATER_VIDEO_REMOVED",a)};
m.za=function(){return this.R||(xh(this)?"html5":null)};
m.ya=function(){return this.aa};
function Ah(a){a.cancel();rh(a);a.R=null;a.f&&(a.f.loaded=!1);var b=xh(a);b&&(wh(a)||!Bh(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));for(a=a.X;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.B&&sf(yh(this),this.B);S(this.ja);this.K=!1};
m.m=function(){Ah(this);if(this.j&&this.f&&this.j.destroy)try{this.j.destroy()}catch(b){P(b)}this.Y=null;for(var a in this.i)v[this.i[a]]=null;this.ba=this.f=this.api=null;delete this.X;delete this.l;K.prototype.m.call(this)};
function Bh(a){return a.f&&a.f.args&&a.f.args.fflags?-1!=a.f.args.fflags.indexOf("player_destroy_old_version=true"):!1}
function yh(a){return a.o?a.o.jsUrl:a.f.assets.js}
;var Fh={},Gh="player_uid_"+(1E9*Math.random()>>>0);function Hh(a){delete Fh[a.getId()]}
;var Ih=window,X=Ih.performance||Ih.mozPerformance||Ih.msPerformance||Ih.webkitPerformance||{};function Jh(a,b){yg.call(this,1,arguments)}
r(Jh,yg);function Kh(a,b){yg.call(this,1,arguments)}
r(Kh,yg);var Lh=new zg("aft-recorded",Jh),Mh=new zg("timing-sent",Kh);var Nh=!1;function Oh(a,b){if(Q("debug_csi_data")){var c=y("yt.timing.csiData");c||(c=[],w("yt.timing.csiData",c,void 0));c.push({page:location.href,time:new Date,args:a})}c="";for(var d in a)a.hasOwnProperty(d)&&(c+="&"+d+"="+a[d]);d="/csi_204?"+c.substring(1);if(window.navigator&&window.navigator.sendBeacon&&b){var e=void 0===e?"":e;Pe(d,e)||Me(d,void 0,void 0,void 0,e)}else Me(d);Ja("yt.timing.pingSent_",!0)}
function Ph(){var a=Qh(void 0);if(a.aft)return a.aft;for(var b=O("TIMING_AFT_KEYS",["ol"]),c=b.length,d=0;d<c;d++){var e=a[b[d]];if(e)return e}return NaN}
function Rh(){var a=Qh(void 0),b=a.pbr,c=a.vc;a=a.pbs;return!!(b&&c&&a&&b<c&&c<a&&Sh().yt_pvis)}
function Th(a){var b;(b=y("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Ja("ytcsi."+(a||"")+"data_",b));return b}
function Sh(){var a=Th(void 0);a.info||(a.info={});return a.info}
function Qh(a){a=Th(a);a.tick||(a.tick={});return a.tick}
function Uh(){var a=Th(void 0).nonce;a||(a=ah(),Th(void 0).nonce=a);return a}
function Vh(){var a=Qh(""),b=Ph();b&&!Nh&&(Eg(Lh,new Jh(Math.round(b-a._start),void 0)),Nh=!0)}
;function Wh(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!Xh(a)||c.some(function(e){return!Xh(e)}))throw Error("Only objects may be merged.");
c=q(c);for(d=c.next();!d.done;d=c.next())Yh(a,d.value);return a}
function Yh(a,b){for(var c in b)if(Xh(b[c])){if(c in a&&!Xh(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Yh(a[c],b[c])}else if(Zh(b[c])){if(c in a&&!Zh(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);$h(a[c],b[c])}else a[c]=b[c];return a}
function $h(a,b){for(var c=q(b),d=c.next();!d.done;d=c.next())d=d.value,Xh(d)?a.push(Yh({},d)):Zh(d)?a.push($h([],d)):a.push(d);return a}
function Xh(a){return"object"===typeof a&&!Array.isArray(a)}
function Zh(a){return"object"===typeof a&&Array.isArray(a)}
;function ai(){var a=y("ytcsi.debug");a||(a=[],w("ytcsi.debug",a,void 0),w("ytcsi.reference",{},void 0));return a}
function bi(){var a=y("ytcsi.reference");a||(ai(),a=y("ytcsi.reference"));if(a[""])return a[""];var b={timerName:"",info:{},tick:{}};ai().push(b);return a[""]=b}
;function ci(a,b,c){c=void 0===c?{}:c;var d=Pg;O("ytLoggingEventsDefaultDisabled",!1)&&Pg==Pg&&(d=null);ug(a,b,d,c)}
;var di=y("ytLoggingLatencyUsageStats_")||{};w("ytLoggingLatencyUsageStats_",di,void 0);var ei=0;function fi(a){di[a]=di[a]||{count:0};var b=di[a];b.count++;b.time=T();ei||(ei=vf(gi,0,5E3));if(5<b.count){if(6==b.count&&1>1E5*Math.random()){b=0==a.indexOf("info")?"WARNING":"ERROR";var c=Error("CSI data exceeded logging limit with key");c.params=a;Te(c,b)}return!0}return!1}
function gi(){var a=T(),b;for(b in di)6E4<a-di[b].time&&delete di[b];ei=0}
;var Y={},hi=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an="adNetworks",Y.ad_at="adType",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cpn="clientPlaybackNonce",Y.cseg="creatorInfo.creatorSegment",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="getHomeRequestId",Y.is_continuation="isContinuation",Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav=
"kabukiInfo.isSecondaryNav",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.ncnp="webInfo.nonPreloadedNodeCount",Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",
Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.st="serverTimeMs",Y.aq="tvInfo.appQuality",Y.br_trs="tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",
Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",Y.GetSettings_rid="mwebInfo.getSettingsRequestId",Y.GetTrending_rid="mwebInfo.getTrendingRequestId",Y),ii="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
ji={},ki=(ji.mver="MEASUREMENT_VERSION_",ji.pis="PLAYER_INITIALIZED_STATE_",ji.yt_pt="LATENCY_PLAYER_",ji.pa="LATENCY_ACTION_",ji.yt_vst="VIDEO_STREAM_TYPE_",ji),li="all_vc ap c cver cbrand cmodel cplatform ctheme ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetBrowse_rid GetPlayer_rid GetSearch_rid GetWatchNext_rid cmt d_vpct d_vpnfi d_vpni pc pfa pfeh pftr prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function mi(){return!!O("FORCE_CSI_ON_GEL",!1)||Q("csi_on_gel")||!!Th(void 0).useGel}
function ni(){var a=Th(void 0);if(!("gel"in a))a.gel={gelTicks:{},gelInfos:{}};else if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}return a.gel}
;function oi(){Sh().yt_lt="hot_bg";if(mi()){var a="hot_bg";var b=ni();if(b.gelInfos)b.gelInfos.info_yt_lt=!0;else{var c={};b.gelInfos=(c.info_yt_lt=!0,c)}if("yt_lt"in hi){b=hi.yt_lt;0<=Ka(ii,b)&&(a=!!a);"yt_lt"in ki&&"string"===typeof a&&(a=ki.yt_lt+a.toUpperCase());b=b.split(".");for(var d=c={},e=0;e<b.length-1;e++){var f=b[e];d[f]={};d=d[f]}d[b[b.length-1]]=a;a=Wh({},c)}else 0<=Ka(li,"yt_lt")||(a=new Qe("Unknown label logged with GEL CSI"),a.params={label:"yt_lt"},he(a)),a=void 0;a&&mi()&&(b=bi(),
Wh(b.info,a),b=ni(),"gelInfos"in b||(b.gelInfos={}),Wh(b.gelInfos,a),b=Uh(),c=Object.keys(a).join(""),fi("info_"+c+"_"+b)||(a.clientActionNonce=b,ci("latencyActionInfo",a)))}else bi().info.yt_lt="hot_bg"}
;var pi={vc:!0};function qi(){if(!mi()){var a=Qh(void 0),b=Sh(),c=a._start;for(f in a)if(0==f.lastIndexOf("_",0)&&z(a[f])){var d=f.slice(1);if(d in pi){var e=Ma(a[f],function(l){return Math.round(l-c)});
b["all_"+d]=e.join()}delete a[f]}e=O("CSI_SERVICE_NAME","youtube");var f={v:2,s:e,action:O("TIMING_ACTION",void 0)};d=b.srt;void 0!==a.srt&&delete b.srt;if(b.h5jse){var g=window.location.protocol+y("ytplayer.config.assets.js");(g=X.getEntriesByName?X.getEntriesByName(g)[0]:null)?b.h5jse=Math.round(b.h5jse-g.responseEnd):delete b.h5jse}a.aft=Ph();Rh()&&"youtube"==e&&(oi(),e=a.vc,g=a.pbs,delete a.aft,b.aft=Math.round(g-e));for(var h in b)"_"!=h.charAt(0)&&(f[h]=b[h]);a.ps=T();h={};e=[];for(var k in a)"_"!=
k.charAt(0)&&(g=Math.round(a[k]-c),h[k]=g,e.push(k+"."+g));f.rt=e.join(",");(a=y("ytdebug.logTiming"))&&a(f,h);Oh(f,!!b.ap);Eg(Mh,new Kh(h.aft+(d||0),void 0))}}
A(X.clearResourceTimings||X.webkitClearResourceTimings||X.mozClearResourceTimings||X.msClearResourceTimings||X.oClearResourceTimings||xa,X);function ri(a){return(0==a.search("cue")||0==a.search("load"))&&"loadModule"!=a}
function si(a,b,c){"string"===typeof a&&(a={mediaContentUrl:a,startSeconds:b,suggestedQuality:c});b=/\/([ve]|embed)\/([^#?]+)/.exec(a.mediaContentUrl);a.videoId=b&&b[2]?b[2]:null;return ti(a)}
function ti(a,b,c){if(Ca(a)){b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}return{videoId:a,startSeconds:b,suggestedQuality:c}}
function ui(a,b,c,d){if(Ca(a)&&!z(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16==a.length?b.list="PL"+a:b.playlist=a;return b}
;function vi(a){a=void 0===a?!1:a;K.call(this);this.f=new M(a);Tc(this,Ha(Uc,this.f))}
C(vi,K);vi.prototype.subscribe=function(a,b,c){return this.g?0:this.f.subscribe(a,b,c)};
vi.prototype.j=function(a,b){this.g||this.f.M.apply(this.f,arguments)};function wi(a,b,c){vi.call(this);this.h=a;this.i=b;this.l=c}
r(wi,vi);function xi(a,b,c){if(!a.g){var d=a.h;d.g||a.i!=d.f||(a={id:a.l,command:b},c&&(a.data=c),d.f.postMessage(id(a),d.i))}}
wi.prototype.m=function(){this.i=this.h=null;vi.prototype.m.call(this)};function yi(a){K.call(this);this.f=a;this.f.subscribe("command",this.qa,this);this.h={};this.j=!1}
r(yi,K);m=yi.prototype;m.start=function(){this.j||this.g||(this.j=!0,xi(this.f,"RECEIVING"))};
m.qa=function(a,b,c){if(this.j&&!this.g){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&(a=d.event,a in this.h||(c=A(this.Qa,this,a),this.h[a]=c,this.addEventListener(a,c)));break;case "removeEventListener":"string"===typeof d.event&&zi(this,d.event);break;default:this.i.isReady()&&this.i.isExternalMethodAvailable(a,c||null)&&(b=Ai(a,b||{}),c=this.i.handleExternalCall(a,b,c||null),(c=Bi(a,c))&&this.j&&!this.g&&xi(this.f,a,c))}}};
m.Qa=function(a,b){this.j&&!this.g&&xi(this.f,a,this.ea(a,b))};
m.ea=function(a,b){if(null!=b)return{value:b}};
function zi(a,b){b in a.h&&(a.removeEventListener(b,a.h[b]),delete a.h[b])}
m.m=function(){var a=this.f;a.g||Gd(a.f,"command",this.qa,this);this.f=null;for(var b in this.h)zi(this,b);K.prototype.m.call(this)};function Ci(a,b){yi.call(this,b);this.i=a;this.start()}
r(Ci,yi);Ci.prototype.addEventListener=function(a,b){this.i.addEventListener(a,b)};
Ci.prototype.removeEventListener=function(a,b){this.i.removeEventListener(a,b)};
function Ai(a,b){switch(a){case "loadVideoById":return b=ti(b),[b];case "cueVideoById":return b=ti(b),[b];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return b=ui(b),[b];case "cuePlaylist":return b=ui(b),[b];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Bi(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Ci.prototype.ea=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return yi.prototype.ea.call(this,a,b)};
Ci.prototype.m=function(){yi.prototype.m.call(this);delete this.i};function Di(a,b,c){K.call(this);var d=this;c=c||O("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.h=b||null;this.w="*";this.i=c;this.sessionId=null;this.channel="widget";this.B=!!a;this.o=function(e){a:if(!("*"!=d.i&&e.origin!=d.i||d.h&&e.source!=d.h||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.B&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.i=d.w=e.origin);d.h=e.source;d.sessionId=f.id;d.f&&(d.f(),d.f=null);break;case "command":d.j&&(!d.l||0<=Ka(d.l,f.func))&&d.j(f.func,f.args,e.origin)}}};
this.l=this.f=this.j=null;window.addEventListener("message",this.o)}
r(Di,K);Di.prototype.sendMessage=function(a,b){var c=b||this.h;if(c){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var d=JSON.stringify(a);c.postMessage(d,this.w)}catch(e){P(e,"WARNING")}}};
Di.prototype.m=function(){window.removeEventListener("message",this.o);K.prototype.m.call(this)};function Ei(){var a=this.g=new Di(!!O("WIDGET_ID_ENFORCE")),b=A(this.Na,this);a.j=b;a.l=null;this.g.channel="widget";if(a=O("WIDGET_ID"))this.g.sessionId=a;this.i=[];this.l=!1;this.j={}}
m=Ei.prototype;m.Na=function(a,b,c){"addEventListener"==a&&b?(a=b[0],this.j[a]||"onReady"==a||(this.addEventListener(a,Fi(this,a)),this.j[a]=!0)):this.la(a,b,c)};
m.la=function(){};
function Fi(a,b){return A(function(c){this.sendMessage(b,c)},a)}
m.addEventListener=function(){};
m.wa=function(){this.l=!0;this.sendMessage("initialDelivery",this.fa());this.sendMessage("onReady");F(this.i,this.ra,this);this.i=[]};
m.fa=function(){return null};
function Gi(a,b){a.sendMessage("infoDelivery",b)}
m.ra=function(a){this.l?this.g.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.ra({event:a,info:void 0==b?null:b})};
m.dispose=function(){this.g=null};function Hi(a){Ei.call(this);this.f=a;this.h=[];this.addEventListener("onReady",A(this.Ka,this));this.addEventListener("onVideoProgress",A(this.Ua,this));this.addEventListener("onVolumeChange",A(this.Va,this));this.addEventListener("onApiChange",A(this.Pa,this));this.addEventListener("onPlaybackQualityChange",A(this.Ra,this));this.addEventListener("onPlaybackRateChange",A(this.Sa,this));this.addEventListener("onStateChange",A(this.Ta,this));this.addEventListener("onWebglSettingsChanged",A(this.Wa,
this))}
r(Hi,Ei);m=Hi.prototype;m.la=function(a,b,c){if(this.f.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&ri(a)){var d=b;if(Ca(d[0])&&!z(d[0]))d=d[0];else{var e={};switch(a){case "loadVideoById":case "cueVideoById":e=ti.apply(window,d);break;case "loadVideoByUrl":case "cueVideoByUrl":e=si.apply(window,d);break;case "loadPlaylist":case "cuePlaylist":e=ui.apply(window,d)}d=e}b.length=1;b[0]=d}this.f.handleExternalCall(a,b,c);ri(a)&&Gi(this,this.fa())}};
m.Ka=function(){var a=A(this.wa,this);this.g.f=a};
m.addEventListener=function(a,b){this.h.push({eventType:a,listener:b});this.f.addEventListener(a,b)};
m.fa=function(){if(!this.f)return null;var a=this.f.getApiInterface();Pa(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0==e.search("get")||0==e.search("is")){var f=0;0==e.search("get")?f=3:0==e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.f[e]();b[f]=g}catch(h){}}}b.videoData=this.f.getVideoData();b.currentTimeLastUpdated_=B()/1E3;return b};
m.Ta=function(a){a={playerState:a,currentTime:this.f.getCurrentTime(),duration:this.f.getDuration(),videoData:this.f.getVideoData(),videoStartBytes:0,videoBytesTotal:this.f.getVideoBytesTotal(),videoLoadedFraction:this.f.getVideoLoadedFraction(),playbackQuality:this.f.getPlaybackQuality(),availableQualityLevels:this.f.getAvailableQualityLevels(),currentTimeLastUpdated_:B()/1E3,playbackRate:this.f.getPlaybackRate(),mediaReferenceTime:this.f.getMediaReferenceTime()};this.f.getVideoUrl&&(a.videoUrl=
this.f.getVideoUrl());this.f.getVideoContentRect&&(a.videoContentRect=this.f.getVideoContentRect());this.f.getProgressState&&(a.progressState=this.f.getProgressState());this.f.getPlaylist&&(a.playlist=this.f.getPlaylist());this.f.getPlaylistIndex&&(a.playlistIndex=this.f.getPlaylistIndex());this.f.getStoryboardFormat&&(a.storyboardFormat=this.f.getStoryboardFormat());Gi(this,a)};
m.Ra=function(a){Gi(this,{playbackQuality:a})};
m.Sa=function(a){Gi(this,{playbackRate:a})};
m.Pa=function(){for(var a=this.f.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.f.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.f.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Va=function(){Gi(this,{muted:this.f.isMuted(),volume:this.f.getVolume()})};
m.Ua=function(a){a={currentTime:a,videoBytesLoaded:this.f.getVideoBytesLoaded(),videoLoadedFraction:this.f.getVideoLoadedFraction(),currentTimeLastUpdated_:B()/1E3,playbackRate:this.f.getPlaybackRate(),mediaReferenceTime:this.f.getMediaReferenceTime()};this.f.getProgressState&&(a.progressState=this.f.getProgressState());Gi(this,a)};
m.Wa=function(){var a={sphericalProperties:this.f.getSphericalProperties()};Gi(this,a)};
m.dispose=function(){Ei.prototype.dispose.call(this);for(var a=0;a<this.h.length;a++){var b=this.h[a];this.f.removeEventListener(b.eventType,b.listener)}this.h=[]};function Ii(a,b,c){K.call(this);this.f=a;this.i=c;this.j=V(window,"message",A(this.l,this));this.h=new wi(this,a,b);Tc(this,Ha(Uc,this.h))}
r(Ii,K);Ii.prototype.l=function(a){var b;if(b=!this.g)if(b=a.origin==this.i)a:{b=this.f;do{b:{var c=a.source;do{if(c==b){c=!0;break b}if(c==c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.h,c.g||c.j("command",b.command,b.data,a.origin))}};
Ii.prototype.m=function(){Tf(this.j);this.f=null;K.prototype.m.call(this)};function Ji(){var a=$a(Ki),b;return vd(new L(function(c,d){a.onSuccess=function(e){ue(e)?c(e):d(new Li("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Li("Unknown request error","net.unknown",e))};
a.O=function(e){d(new Li("Request timed out","net.timeout",e))};
b=Ee("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof wd&&b.abort();
return td(c)})}
function Li(a,b){D.call(this,a+", errorCode="+b);this.errorCode=b;this.name="PromiseAjaxError"}
r(Li,D);function Mi(){this.g=0;this.f=null}
Mi.prototype.then=function(a,b,c){return 1===this.g&&a?(a=a.call(c,this.f),od(a)?a:Ni(a)):2===this.g&&b?(a=b.call(c,this.f),od(a)?a:Oi(a)):this};
Mi.prototype.getValue=function(){return this.f};
Mi.prototype.$goog_Thenable=!0;function Oi(a){var b=new Mi;a=void 0===a?null:a;b.g=2;b.f=void 0===a?null:a;return b}
function Ni(a){var b=new Mi;a=void 0===a?null:a;b.g=1;b.f=void 0===a?null:a;return b}
;function Pi(a){D.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Qi;this.isTimeout=a instanceof Li&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof wd}
r(Pi,D);Pi.prototype.name="BiscottiError";function Qi(){D.call(this,"Biscotti ID is missing from server")}
r(Qi,D);Qi.prototype.name="BiscottiMissingError";var Ki={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Ri=null;function ce(){if("1"===Ua(ae(),"args","privembed"))return td(Error("Biscotti ID is not available in private embed mode"));Ri||(Ri=vd(Ji().then(Si),function(a){return Ti(2,a)}));
return Ri}
function Si(a){a=a.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Qi;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Qi;a=a.id;de(a);Ri=Ni(a);Ui(18E5,2);return a}
function Ti(a,b){var c=new Pi(b);de("");Ri=Oi(c);0<a&&Ui(12E4,a-1);throw c;}
function Ui(a,b){R(function(){vd(Ji().then(Si,function(c){return Ti(b,c)}),xa)},a)}
function Vi(){try{var a=y("yt.ads.biscotti.getId_");return a?a():ce()}catch(b){return td(b)}}
;function Wi(a){if("1"!==Ua(ae(),"args","privembed")){a&&be();try{Vi().then(function(){},function(){}),R(Wi,18E5)}catch(b){P(b)}}}
;var Z=y("ytglobal.prefsUserPrefsPrefs_")||{};w("ytglobal.prefsUserPrefsPrefs_",Z,void 0);function Xi(){this.f=O("ALT_PREF_COOKIE_NAME","PREF");var a=Wb.get(""+this.f,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Z[d]=c.toString())}}}
m=Xi.prototype;m.get=function(a,b){Yi(a);Zi(a);var c=void 0!==Z[a]?Z[a].toString():null;return null!=c?c:b?b:""};
m.set=function(a,b){Yi(a);Zi(a);if(null==b)throw Error("ExpectedNotNull");Z[a]=b.toString()};
m.remove=function(a){Yi(a);Zi(a);delete Z[a]};
m.save=function(){Ug(this.f,this.dump(),63072E3)};
m.clear=function(){for(var a in Z)delete Z[a]};
m.dump=function(){var a=[],b;for(b in Z)a.push(b+"="+encodeURIComponent(String(Z[b])));return a.join("&")};
function Zi(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Yi(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function $i(a){a=void 0!==Z[a]?Z[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
ya(Xi);var aj=null,bj=null,cj=null,dj={};function ej(a){var b=a.id;a=a.ve_type;var c=xg++;a=new vg({veType:a,veCounter:c,elementIndex:void 0,dataElement:void 0,youtubeData:void 0});dj[b]=a;b=gh();c=fh();b&&c&&Og(b,c,[a])}
function fj(a){var b=a.csn;a=a.root_ve_type;if(b&&a&&(hh(b,a),a=fh()))for(var c in dj){var d=dj[c];d&&Og(b,a,[d])}}
function gj(a){dj[a.id]=new vg({trackingParams:a.tracking_params})}
function hj(a){var b=gh(),c=dj[a.id];if(b&&c){a=Pg;c={csn:b,ve:wg(c),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"};var d={ca:void 0,P:b};"UNDEFINED_CSN"==b?Qg("visualElementGestured",c,d):ug("visualElementGestured",c,a,d)}}
function ij(a){a=a.ids;var b=gh();if(b)for(var c=0;c<a.length;c++){var d=dj[a[c]];if(d){var e=Pg;d={csn:b,ve:wg(d),eventType:1};var f={ca:void 0,P:b};"UNDEFINED_CSN"==b?Qg("visualElementShown",d,f):ug("visualElementShown",d,e,f)}}}
;w("yt.setConfig",N,void 0);w("yt.config.set",N,void 0);w("yt.setMsg",Ve,void 0);w("yt.msgs.set",Ve,void 0);w("yt.logging.errors.log",Te,void 0);
w("writeEmbed",function(){var a=O("PLAYER_CONFIG",void 0);Wi(!0);"gvn"==a.args.ps&&(document.body.style.backgroundColor="transparent");var b=document.referrer,c=O("POST_MESSAGE_ORIGIN");window!=window.top&&b&&b!=document.URL&&(a.args.loaderUrl=b);O("LIGHTWEIGHT_AUTOPLAY")&&(a.args.autoplay="1");b="player";b="string"===typeof b?$b(b):b;var d=Gh+"_"+(b[Da]||(b[Da]=++Ea)),e=Fh[d];e&&(void 0===f||f)?a&&a.args&&a.args.fflags&&a.args.fflags.includes("web_player_remove_playerproxy=true")?e.api.loadVideoByPlayerVars(a.args||
null):e.loadNewVideoConfig(a):(e=new qh(b,d,a,void 0),Fh[d]=e,gf("player-added",e.api),Tc(e,Ha(Hh,e)));a=e.api;aj=a;a.addEventListener("onScreenChanged",fj);a.addEventListener("onLogClientVeCreated",ej);a.addEventListener("onLogServerVeCreated",gj);a.addEventListener("onLogVeClicked",hj);a.addEventListener("onLogVesShown",ij);var f=O("POST_MESSAGE_ID","player");O("ENABLE_JS_API")?cj=new Hi(a):O("ENABLE_POST_API")&&"string"===typeof f&&"string"===typeof c&&(bj=new Ii(window.parent,f,c),cj=new Ci(a,
bj.h));c=O("BG_P",void 0);Jf(c)&&(O("BG_I")||O("BG_IU"))&&(Ff=!0,Ef.initialize(O("BG_I",null),O("BG_IU",null),c,If,void 0));zf()},void 0);
w("yt.www.watch.ads.restrictioncookie.spr",function(a){Me(a+"mac_204?action_fcts=1");return!0},void 0);
var jj=ge(function(){var a=Qh(void 0),b;(b=!Q("use_first_tick"))||(b=!("ol"in Qh(void 0)));if(b&&(b="ol",X.mark&&(0==b.lastIndexOf("mark_",0)||(b="mark_"+b),X.mark(b)),b=T(),a.ol&&(a._ol=a._ol||[a.ol],a._ol.push(b)),a.ol=b,a=ni(),a.gelTicks&&(a.gelTicks.tick_ol=!0),T(),mi()?(bi().tick.ol=void 0,a=Uh(),fi("tick_ol_"+a)||ci("latencyActionTicked",{tickName:"ol",clientActionNonce:a},{timestamp:void 0}),Vh(),a=!0):a=!1,!a)){if(!y("yt.timing.pingSent_")&&(b=O("TIMING_ACTION",void 0),a=Qh(void 0),y("ytglobal.timingready_")&&
b&&a._start&&Ph())){Vh();b=!0;var c=O("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in a)){b=!1;break}b&&qi()}bi().tick.ol=void 0}a=Xi.getInstance();c=!!(($i("f"+(Math.floor(119/31)+1))||0)&67108864);b=1<window.devicePixelRatio;document.body&&Yc(document.body,"exp-invert-logo")&&(b&&!Yc(document.body,"inverted-hdpi")?(d=document.body,d.classList?d.classList.add("inverted-hdpi"):Yc(d,"inverted-hdpi")||(e=Wc(d),Xc(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi")))):!b&&Yc(document.body,
"inverted-hdpi")&&Zc());c!=b&&(c="f"+(Math.floor(119/31)+1),d=$i(c)||0,d=b?d|67108864:d&-67108865,0==d?delete Z[c]:(b=d.toString(16),Z[c]=b.toString()),a.save())}),kj=ge(function(){var a=aj;
a&&a.sendAbandonmentPing&&a.sendAbandonmentPing();O("PL_ATT")&&Ef.dispose();a=0;for(var b=xf.length;a<b;a++){var c=xf[a];if(!isNaN(c)){var d=y("yt.scheduler.instance.cancelJob");d?d(c):S(c)}}xf.length=0;rf("//static.doubleclick.net/instream/ad_status.js");yf=!1;N("DCLKSTAT",0);Vc(cj,bj);if(a=aj)a.removeEventListener("onScreenChanged",fj),a.removeEventListener("onLogClientVeCreated",ej),a.removeEventListener("onLogServerVeCreated",gj),a.removeEventListener("onLogVeClicked",hj),a.removeEventListener("onLogVesShown",
ij),a.destroy();dj={}});
window.addEventListener?(window.addEventListener("load",jj),window.addEventListener("unload",kj)):window.attachEvent&&(window.attachEvent("onload",jj),window.attachEvent("onunload",kj));Ja("yt.abuse.player.botguardInitialized",y("yt.abuse.player.botguardInitialized")||Kf);Ja("yt.abuse.player.invokeBotguard",y("yt.abuse.player.invokeBotguard")||Lf);Ja("yt.abuse.dclkstatus.checkDclkStatus",y("yt.abuse.dclkstatus.checkDclkStatus")||Af);
Ja("yt.player.exports.navigate",y("yt.player.exports.navigate")||ih);Ja("yt.util.activity.init",y("yt.util.activity.init")||Xf);Ja("yt.util.activity.getTimeSinceActive",y("yt.util.activity.getTimeSinceActive")||$f);Ja("yt.util.activity.setTimestamp",y("yt.util.activity.setTimestamp")||Yf);}).call(this);
