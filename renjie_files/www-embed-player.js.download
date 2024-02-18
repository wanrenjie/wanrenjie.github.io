(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function ba(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ca="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=da(this);function q(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ca(c,a,{configurable:!0,writable:!0,value:b})}}
q("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ca(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
q("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ca(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(ba(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ia(a){return a.raw=a}
function r(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:ba(a)}}
function ja(a){if(!(a instanceof Array)){a=r(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ka(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ka(d,e)&&(a[e]=d[e])}return a};
q("Object.assign",function(a){return a||la});
var ma="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},na=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ma(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),pa;
if("function"==typeof Object.setPrototypeOf)pa=Object.setPrototypeOf;else{var ra;a:{var sa={a:!0},ua={};try{ua.__proto__=sa;ra=ua.a;break a}catch(a){}ra=!1}pa=ra?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var va=pa;
function u(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(va)va(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.ta=b.prototype}
function wa(){this.D=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.s=0;this.v=this.j=null}
function xa(a){if(a.D)throw new TypeError("Generator is already running");a.D=!0}
wa.prototype.X=function(a){this.i=a};
function ya(a,b){a.j={nd:b,xd:!0};a.h=a.s||a.m}
wa.prototype.return=function(a){this.j={return:a};this.h=this.m};
function w(a,b,c){a.h=c;return{value:b}}
wa.prototype.A=function(a){this.h=a};
function za(a,b,c){a.s=b;void 0!=c&&(a.m=c)}
function Aa(a,b){a.h=b;a.s=0}
function Ba(a){a.s=0;var b=a.j.nd;a.j=null;return b}
function Ca(a){a.v=[a.j];a.s=0;a.m=0}
function Da(a){var b=a.v.splice(0)[0];(b=a.j=a.j||b)?b.xd?a.h=a.s||a.m:void 0!=b.A&&a.m<b.A?(a.h=b.A,a.j=null):a.h=a.m:a.h=0}
function Ea(a){this.h=new wa;this.i=a}
function Fa(a,b){xa(a.h);var c=a.h.l;if(c)return Ga(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ha(a)}
function Ga(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.D=!1,e;var f=e.value}catch(g){return a.h.l=null,ya(a.h,g),Ha(a)}a.h.l=null;d.call(a.h,f);return Ha(a)}
function Ha(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.D=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ya(a.h,c)}a.h.D=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.xd)throw b.nd;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ia(a){this.next=function(b){xa(a.h);a.h.l?b=Ga(a,a.h.l.next,b,a.h.X):(a.h.X(b),b=Ha(a));return b};
this.throw=function(b){xa(a.h);a.h.l?b=Ga(a,a.h.l["throw"],b,a.h.X):(ya(a.h,b),b=Ha(a));return b};
this.return=function(b){return Fa(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ja(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ja(new Ia(new Ea(a)))}
function Ka(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
q("Reflect",function(a){return a?a:{}});
q("Reflect.construct",function(){return na});
q("Reflect.setPrototypeOf",function(a){return a?a:va?function(b,c){try{return va(b,c),!0}catch(d){return!1}}:null});
q("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.D=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=ea.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.l(m)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(m){return function(n){k||(k=!0,m.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.V),reject:g(this.m)}};
b.prototype.V=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.aa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.R(g):this.s(g)}};
b.prototype.R=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ia(h,g):this.s(g)};
b.prototype.m=function(g){this.X(2,g)};
b.prototype.s=function(g){this.X(1,g)};
b.prototype.X=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Z();this.v()};
b.prototype.Z=function(){var g=this;e(function(){if(g.N()){var h=ea.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.N=function(){if(this.D)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.v=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.aa=function(g){var h=this.l();g.dc(h.resolve,h.reject)};
b.prototype.ia=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(v,t){return"function"==typeof v?function(y){try{m(v(y))}catch(D){n(D)}}:t}
var m,n,p=new b(function(v,t){m=v;n=t});
this.dc(k(g,m),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.dc=function(g,h){function k(){switch(m.h){case 1:g(m.j);break;case 2:h(m.j);break;default:throw Error("Unexpected state: "+m.h);}}
var m=this;null==this.i?f.i(k):this.i.push(k);this.D=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=r(g),n=m.next();!n.done;n=m.next())d(n.value).dc(h,k)})};
b.all=function(g){var h=r(g),k=h.next();return k.done?d([]):new b(function(m,n){function p(y){return function(D){v[y]=D;t--;0==t&&m(v)}}
var v=[],t=0;do v.push(void 0),t++,d(k.value).dc(p(v.length-1),n),k=h.next();while(!k.done)})};
return b});
q("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=r(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ka(k,g)){var m=new c;ca(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return m(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),n=new a([[k,2],[m,3]]);if(2!=n.get(k)||3!=n.get(m))return!1;n.delete(k);n.set(m,4);return!n.has(k)&&4==n.get(m)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ka(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=m;return this};
b.prototype.get=function(k){return d(k)&&ka(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.h)?delete k[g][this.h]:!1};
return b});
q("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.h;return fa(function(){if(m){for(;m.head!=h.h;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var n=h.data_[m];if(n&&ka(h.data_,m))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:m,list:n,index:h,entry:p}}return{id:m,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=r(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(r([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),n=m.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=m.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!m.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},m.list.push(m.entry),this.h.previous.next=m.entry,this.h.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),n;!(n=m.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function La(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
q("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=La(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
q("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
q("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=La(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
q("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
q("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
q("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
q("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
function Ma(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
q("Array.prototype.entries",function(a){return a?a:function(){return Ma(this,function(b,c){return[b,c]})}});
q("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
q("Array.prototype.keys",function(a){return a?a:function(){return Ma(this,function(b){return b})}});
q("Array.prototype.values",function(a){return a?a:function(){return Ma(this,function(b,c){return c})}});
q("Array.prototype.fill",function(a){return a?a:function(b,c,d){var e=this.length||0;0>c&&(c=Math.max(0,e+c));if(null==d||d>e)d=e;d=Number(d);0>d&&(d=Math.max(0,e+d));for(c=Number(c||0);c<d;c++)this[c]=b;return this}});
function Na(a){return a?a:Array.prototype.fill}
q("Int8Array.prototype.fill",Na);q("Uint8Array.prototype.fill",Na);q("Uint8ClampedArray.prototype.fill",Na);q("Int16Array.prototype.fill",Na);q("Uint16Array.prototype.fill",Na);q("Int32Array.prototype.fill",Na);q("Uint32Array.prototype.fill",Na);q("Float32Array.prototype.fill",Na);q("Float64Array.prototype.fill",Na);q("Object.setPrototypeOf",function(a){return a||va});
q("Set",function(a){function b(c){this.h=new Map;if(c){c=r(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(r([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
q("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push([d,b[d]]);return c}});
q("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
q("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
q("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==La(this,b,"includes").indexOf(b,c||0)}});
q("globalThis",function(a){return a||ea});
q("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push(b[d]);return c}});
var Oa=Oa||{},z=this||self;function A(a,b,c){a=a.split(".");c=c||z;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||z;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Pa(a){a.Ec=void 0;a.getInstance=function(){return a.Ec?a.Ec:a.Ec=new a}}
function Qa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ra(a){var b=Qa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Sa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ta(a){return Object.prototype.hasOwnProperty.call(a,Ua)&&a[Ua]||(a[Ua]=++Va)}
var Ua="closure_uid_"+(1E9*Math.random()>>>0),Va=0;function Wa(a,b,c){return a.call.apply(a.bind,arguments)}
function Xa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ya(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ya=Wa:Ya=Xa;return Ya.apply(null,arguments)}
function $a(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function ab(a,b){function c(){}
c.prototype=b.prototype;a.ta=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Et=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function bb(a){return a}
;function cb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,cb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
ab(cb,Error);cb.prototype.name="CustomError";function db(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function eb(){}
function fb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var gb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},hb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},ib=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},jb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},kb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
hb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function lb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function mb(a,b){b=gb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function nb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ra(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ob(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function pb(a){var b=qb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function rb(a){for(var b in a)return!1;return!0}
function sb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function tb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function ub(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function vb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function wb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=wb(a[c]);return b}
var yb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function zb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<yb.length;f++)c=yb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var Ab;function Bb(){if(void 0===Ab){var a=null,b=z.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:bb,createScript:bb,createScriptURL:bb})}catch(c){z.console&&z.console.error(c.message)}Ab=a}else Ab=a}return Ab}
;function Cb(a,b){this.j=a===Db&&b||""}
Cb.prototype.i=!0;Cb.prototype.h=function(){return this.j};
function Eb(a){return new Cb(Db,a)}
var Db={};Eb("");var Fb={};function Gb(a,b){this.j=b===Fb?a:"";this.i=!0}
Gb.prototype.toString=function(){return this.j.toString()};
Gb.prototype.h=function(){return this.j.toString()};function Hb(a,b){this.j=b===Ib?a:""}
Hb.prototype.toString=function(){return this.j+""};
Hb.prototype.i=!0;Hb.prototype.h=function(){return this.j.toString()};
function Jb(a){if(a instanceof Hb&&a.constructor===Hb)return a.j;Qa(a);return"type_error:TrustedResourceUrl"}
var Ib={};function Kb(a){var b=Bb();a=b?b.createScriptURL(a):a;return new Hb(a,Ib)}
;var Lb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Mb(a,b){return a<b?-1:a>b?1:0}
;function Nb(a,b){this.j=b===Ob?a:""}
Nb.prototype.toString=function(){return this.j.toString()};
Nb.prototype.i=!0;Nb.prototype.h=function(){return this.j.toString()};
function Pb(a){if(a instanceof Nb&&a.constructor===Nb)return a.j;Qa(a);return"type_error:SafeUrl"}
var Sb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Ob={},Tb=new Nb("about:invalid#zClosurez",Ob);function Ub(){var a=z.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Ub().indexOf(a)}
;function Vb(){return C("Trident")||C("MSIE")}
function Wb(){return C("Firefox")||C("FxiOS")}
function Xb(){return C("Safari")&&!(Yb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Wb()||C("Silk")||C("Android"))}
function Yb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function Zb(){return C("Android")&&!(Yb()||Wb()||C("Opera")||C("Silk"))}
function $b(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function ac(a){var b=Ub();if("Internet Explorer"===a){if(Vb())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=$b(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Yb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Wb()||"Safari"===a&&Xb()||"Android Browser"===a&&Zb()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function bc(a){a=ac(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var cc={};function dc(a){this.j=cc===cc?a:"";this.i=!0}
dc.prototype.h=function(){return this.j.toString()};
dc.prototype.toString=function(){return this.j.toString()};function ec(a,b){b instanceof Nb||b instanceof Nb||(b="object"==typeof b&&b.i?b.h():String(b),Sb.test(b)||(b="about:invalid#zClosurez"),b=new Nb(b,Ob));a.href=Pb(b)}
function fc(a,b){a.rel="stylesheet";a.href=Jb(b).toString();(b=gc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function hc(){return gc("script[nonce]")}
var ic=/^[\w+/_-]+[=]{0,2}$/;function gc(a,b){b=(b||z).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&ic.test(a)?a:"":""}
;function jc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var kc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function lc(a){return a?decodeURI(a):a}
function oc(a,b){return b.match(kc)[a]||null}
function pc(a){return lc(oc(3,a))}
function qc(a){var b=a.match(kc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function rc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function sc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)sc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function tc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)sc(a[b],a[b+1],c);return c.join("&")}
function uc(a){var b=[],c;for(c in a)sc(c,a[c],b);return b.join("&")}
function vc(a,b){var c=2==arguments.length?tc(arguments[1],0):tc(arguments,1);return rc(a,c)}
function wc(a,b){b=uc(b);return rc(a,b)}
function xc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return rc(a,b+c)}
function yc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var zc=/#|$/,Ac=/[?&]($|#)/;function Bc(a,b){for(var c=a.search(zc),d=0,e,f=[];0<=(e=yc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Ac,"$1")}
;function Cc(a){z.setTimeout(function(){throw a;},0)}
;function Dc(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Ec(){var a=Ub(),b="";C("Windows")?(b=/Windows (?:NT|Phone) ([0-9.]+)/,b=(a=b.exec(a))?a[1]:"0.0"):Dc()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,b=(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,b=(a=b.exec(a))?a[1].replace(/_/g,"."):"10"):-1!=Ub().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b=(a=b.exec(a))&&a[1]):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b=(a=b.exec(a))&&a[1]):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,
b=(a=b.exec(a))&&a[1]);a=0;b=Lb(String(b||"")).split(".");for(var c=Lb("12").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Mb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Mb(0==f[2].length,0==g[2].length)||Mb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}}
;function Fc(a){Fc[" "](a);return a}
Fc[" "]=function(){};var Gc=C("Opera"),Hc=Vb(),Ic=C("Edge"),Jc=C("Gecko")&&!(-1!=Ub().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Kc=-1!=Ub().toLowerCase().indexOf("webkit")&&!C("Edge"),Lc=C("Android");function Mc(){var a=z.document;return a?a.documentMode:void 0}
var Nc;a:{var Oc="",Sc=function(){var a=Ub();if(Jc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Ic)return/Edge\/([\d\.]+)/.exec(a);if(Hc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Kc)return/WebKit\/(\S+)/.exec(a);if(Gc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Sc&&(Oc=Sc?Sc[1]:"");if(Hc){var Tc=Mc();if(null!=Tc&&Tc>parseFloat(Oc)){Nc=String(Tc);break a}}Nc=Oc}var Uc=Nc,Vc;if(z.document&&Hc){var Wc=Mc();Vc=Wc?Wc:parseInt(Uc,10)||void 0}else Vc=void 0;var Xc=Vc;var Yc=Dc()||C("iPod"),Zc=C("iPad");Zb();Yb();var $c=Xb()&&!(Dc()||C("iPad")||C("iPod"));var ad={},bd=null;function cd(a,b){Ra(a);void 0===b&&(b=0);dd();b=ad[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],m=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+m+g+h+k}m=0;k=d;switch(a.length-e){case 2:m=a[e+1],k=b[(m&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|m>>4]+k+d}return c.join("")}
function ed(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;fd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function fd(a,b){function c(k){for(;d<a.length;){var m=a.charAt(d++),n=bd[m];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(m))throw Error("Unknown base64 encoding at char: "+m);}return k}
dd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function dd(){if(!bd){bd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));ad[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===bd[f]&&(bd[f]=e)}}}}
;var gd="undefined"!==typeof Uint8Array;function hd(a){return gd&&null!=a&&a instanceof Uint8Array}
var id={};var jd;function kd(a){if(a!==id)throw Error("illegal external caller");}
function ld(a,b){kd(b);this.za=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
function md(){return jd||(jd=new ld(null,id))}
ld.prototype.Jb=function(){return null==this.za};
ld.prototype.sizeBytes=function(){kd(id);var a=this.za;null==a||hd(a)||("string"===typeof a?a=ed(a):(Qa(a),a=null));return(a=null==a?a:this.za=a)?a.length:0};var nd="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;function od(a,b){if(nd)return a[nd]|=b;if(void 0!==a.Da)return a.Da|=b;Object.defineProperties(a,{Da:{value:b,configurable:!0,writable:!0,enumerable:!1}});return b}
function pd(a,b){var c=qd(a);(c&b)!==b&&(Object.isFrozen(a)&&(a=Array.prototype.slice.call(a)),rd(a,c|b));return a}
function sd(a,b){nd?a[nd]&&(a[nd]&=~b):void 0!==a.Da&&(a.Da&=~b)}
function qd(a){var b;nd?b=a[nd]:b=a.Da;return null==b?0:b}
function rd(a,b){nd?a[nd]=b:void 0!==a.Da?a.Da=b:Object.defineProperties(a,{Da:{value:b,configurable:!0,writable:!0,enumerable:!1}})}
function td(a){od(a,1);return a}
function ud(a){return!!(qd(a)&2)}
function vd(a,b){rd(b,(a|0)&-51)}
function wd(a,b){rd(b,(a|18)&-41)}
;var xd={};function yd(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var zd,Ad,Bd=[];rd(Bd,23);Ad=Object.freeze(Bd);function Cd(a){if(ud(a.M))throw Error("Cannot mutate an immutable Message");}
function Dd(a){var b=a.length;(b=b?a[b-1]:void 0)&&yd(b)?b.g=1:(b={},a.push((b.g=1,b)))}
;function Ed(a){return a.displayName||a.name||"unknown type name"}
function Fd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Ed(b)+" but got "+(a&&Ed(a.constructor)));return a}
;function Gd(a){var b=a.l+a.fb;return a.wa||(a.wa=a.M[b]={})}
function Hd(a,b,c){return-1===b?null:b>=a.l?a.wa?a.wa[b]:void 0:c&&a.wa&&(c=a.wa[b],null!=c)?c:a.M[b+a.fb]}
function F(a,b,c,d){Cd(a);return Id(a,b,c,d)}
function Id(a,b,c,d){a.m&&(a.m=void 0);if(b>=a.l||d)return Gd(a)[b]=c,a;a.M[b+a.fb]=c;(c=a.wa)&&b in c&&delete c[b];return a}
function Jd(a,b){a&&ud(b.M)&&ud(a.M);return a}
function Kd(a,b,c,d,e){var f=Hd(a,b,d);Array.isArray(f)||(f=Ad);var g=qd(f);g&1||td(f);if(e)g&2||od(f,2),c&1||Object.freeze(f);else{e=!(c&2);var h=g&2;c&1||!h?e&&g&16&&!h&&sd(f,16):(f=td(Array.prototype.slice.call(f)),Id(a,b,f,d))}return f}
function Ld(a,b,c,d){Cd(a);(c=Md(a,c))&&c!==b&&null!=d&&Id(a,c,void 0,!1);return Id(a,b,d)}
function Md(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Hd(a,e)&&(0!==c&&Id(a,c,void 0,!1),c=e)}return c}
function Rd(a,b,c,d){var e=d=void 0===d?!1:d,f=Hd(a,c,e);var g=!1;var h=null==f||"object"!==typeof f||(g=Array.isArray(f))||f.Kc!==xd?g?new b(f):void 0:f;h!==f&&null!=h&&(Id(a,c,h,e),od(h.M,qd(a.M)&18));b=Jd(h,a);if(null==b)return b;ud(a.M)||(e=Sd(b),e!==b&&(b=e,Id(a,c,b,d)));return Jd(b,a)}
function Td(a,b,c,d,e,f){a.i||(a.i={});var g=a.i[c],h=Kd(a,c,3,d,f);if(!g){var k=h;g=[];var m=!!(qd(a.M)&16);h=ud(k);var n=k;!f&&h&&(k=Array.prototype.slice.call(k));for(var p=h,v=0;v<k.length;v++){var t=k[v];var y=b,D=!1;D=void 0===D?!1:D;t=Array.isArray(t)?new y(t):D?new y:void 0;if(void 0!==t){y=t.M;var E=D=qd(y);h&&(E|=2);m&&(E|=16);E!=D&&rd(y,E);y=E;p=p||!!(2&y);g.push(t)}}a.i[c]=g;b=k;k=!p;m=qd(b);p=m|33;p=k?p|8:p&-9;m!=p&&(Object.isFrozen(b)&&(b=Array.prototype.slice.call(b)),rd(b,p));k=b;
n!==k&&Id(a,c,k,d);(f||e&&h)&&od(g,2);e&&Object.freeze(g);return g}f||(d=Object.isFrozen(g),e&&!d?Object.freeze(g):!e&&d&&(g=Array.prototype.slice.call(g),a.i[c]=g));return g}
function Ud(a,b,c,d){var e=ud(a.M);b=Td(a,b,c,d,e,e);a=Kd(a,c,3,d,e);if(!(e||qd(a)&8)){for(e=0;e<b.length;e++)c=b[e],d=Sd(c),c!==d&&(b[e]=d,a[e]=d.M);od(a,8)}return b}
function G(a,b,c,d){Cd(a);null!=d?Fd(d,b):d=void 0;return Id(a,c,d)}
function Vd(a,b,c,d,e){Cd(a);null!=e?Fd(e,b):e=void 0;Ld(a,c,d,e)}
function Wd(a,b,c,d,e){Cd(a);var f=null==d?Ad:td([]);if(null!=d){for(var g=!!d.length,h=0;h<d.length;h++){var k=d[h];Fd(k,b);g=g&&!ud(k.M);f[h]=k.M}f=pd(f,(g?8:0)|1);a.i||(a.i={});a.i[c]=d}else a.i&&(a.i[c]=void 0);return Id(a,c,f,e)}
function Xd(a,b,c,d){Cd(a);var e=Td(a,c,b,void 0,!1,!1);c=null!=d?Fd(d,c):new c;a=Kd(a,b,2,void 0,!1);e.push(c);a.push(c.M);ud(c.M)&&sd(a,8)}
function Yd(a,b){return null==a?b:a}
function Zd(a,b){return Yd(Hd(a,b),"")}
;var $d;function ae(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a)if(Array.isArray(a)){if(0!==(qd(a)&128))return a=Array.prototype.slice.call(a),Dd(a),a}else{if(hd(a))return cd(a);if(a instanceof ld){var b=a.za;return null==b?"":"string"===typeof b?b:a.za=cd(b)}}}return a}
;function be(a,b,c,d){if(null!=a){if(Array.isArray(a))a=ce(a,b,c,void 0!==d);else if(yd(a)){var e={},f;for(f in a)e[f]=be(a[f],b,c,d);a=e}else a=b(a,d);return a}}
function ce(a,b,c,d){var e=qd(a);d=d?!!(e&16):void 0;a=Array.prototype.slice.call(a);for(var f=0;f<a.length;f++)a[f]=be(a[f],b,c,d);c(e,a);return a}
function de(a){return a.Kc===xd?a.toJSON():ae(a)}
function ee(a,b){a&128&&Dd(b)}
;function fe(a,b,c){c=void 0===c?wd:c;if(null!=a){if(gd&&a instanceof Uint8Array)return a.length?new ld(new Uint8Array(a),id):md();if(Array.isArray(a)){var d=qd(a);if(d&2)return a;if(b&&!(d&32)&&(d&16||0===d))return rd(a,d|2),a;a=ce(a,fe,d&4?wd:c,!0);b=qd(a);b&4&&b&2&&Object.freeze(a);return a}return a.Kc===xd?ge(a):a}}
function he(a,b,c,d,e,f,g){(a=a.i&&a.i[c])?(d=0<a.length?a[0].constructor:void 0,f=qd(a),f&2||(a=jb(a,ge),wd(f,a),Object.freeze(a)),Wd(b,d,c,a,e)):F(b,c,fe(d,f,g),e)}
function ge(a){if(ud(a.M))return a;a=ie(a,!0);od(a.M,2);return a}
function ie(a,b){var c=a.M,d=[];od(d,16);var e=a.constructor.h;e&&d.push(e);e=a.wa;if(e){d.length=c.length;d.fill(void 0,d.length,c.length);var f={};d[d.length-1]=f}0!==(qd(c)&128)&&Dd(d);b=b||ud(a.M)?wd:vd;var g=a.constructor;qd(d);$d=d;d=new g(d);$d=void 0;a.wd&&(d.wd=a.wd.slice());g=!!(qd(c)&16);for(var h=e?c.length-1:c.length,k=0;k<h;k++)he(a,d,k-a.fb,c[k],!1,g,b);if(e)for(var m in e)c=e[m],h=+m,Number.isNaN(h)?f[h]=c:he(a,d,h,c,!0,g,b);return d}
function Sd(a){if(!ud(a.M))return a;var b=ie(a,!1);b.m=a;return b}
;function H(a,b,c){null==a&&(a=$d);$d=void 0;var d=this.constructor.i||0,e=0<d,f=this.constructor.h,g=!1;if(null==a){a=f?[f]:[];var h=48;var k=!0;e&&(d=0,h|=128);rd(a,h)}else{if(!Array.isArray(a))throw Error();if(f&&f!==a[0])throw Error();var m=h=od(a,0);if(k=0!==(16&m))(g=0!==(32&m))||(m|=32);if(e)if(128&m)d=0;else{if(0<a.length){var n=a[a.length-1];if(yd(n)&&"g"in n){d=0;m|=128;delete n.g;var p=!0,v;for(v in n){p=!1;break}p&&a.pop()}}}else if(128&m)throw Error();h!==m&&rd(a,m)}this.fb=(f?0:-1)-d;
this.i=void 0;this.M=a;a:{f=this.M.length;d=f-1;if(f&&(f=this.M[d],yd(f))){this.wa=f;this.l=d-this.fb;break a}void 0!==b&&-1<b?(this.l=Math.max(b,d+1-this.fb),this.wa=void 0):this.l=Number.MAX_VALUE}if(!e&&this.wa&&"g"in this.wa)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');if(c){b=k&&!g&&!0;e=this.l;var t;for(k=0;k<c.length;k++)g=c[k],g<e?(g+=this.fb,(d=a[g])?je(d,b):a[g]=Ad):(t||(t=Gd(this)),(d=t[g])?je(d,b):t[g]=Ad)}}
H.prototype.toJSON=function(){var a=this.M,b;zd?b=a:b=ce(a,de,ee);return b};
function ke(a){zd=!0;try{return JSON.stringify(a.toJSON(),le)}finally{zd=!1}}
H.prototype.clone=function(){return ie(this,!1)};
function je(a,b){if(Array.isArray(a)){var c=qd(a),d=1;!b||c&2||(d|=16);(c&d)!==d&&rd(a,c|d)}}
H.prototype.Kc=xd;H.prototype.toString=function(){return this.M.toString()};
function le(a,b){return ae(b)}
;function me(a){var b=this.h,c=this.i;return this.isRepeated?Ud(a,b,c,!0):Rd(a,b,c,!0)}
;function ne(a){this.gd=a}
;function oe(a,b,c){this.i=a;this.l=b;this.h=c||[];this.pb=new Map}
l=oe.prototype;l.ae=function(a){var b=Ka.apply(1,arguments),c=this.yc(b);c?c.push(new ne(a)):this.Kd(a,b)};
l.Kd=function(a){this.pb.set(this.pd(Ka.apply(1,arguments)),[new ne(a)])};
l.yc=function(){var a=this.pd(Ka.apply(0,arguments));return this.pb.has(a)?this.pb.get(a):void 0};
l.re=function(){var a=this.yc(Ka.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.pb.clear()};
l.pd=function(){var a=Ka.apply(0,arguments);return a?a.join(","):"key"};function pe(a,b){oe.call(this,a,3,b)}
u(pe,oe);pe.prototype.j=function(a){var b=Ka.apply(1,arguments),c=0,d=this.re(b);d&&(c=d.gd);this.Kd(c+a,b)};function qe(a,b){oe.call(this,a,2,b)}
u(qe,oe);qe.prototype.j=function(a){this.ae(a,Ka.apply(1,arguments))};function re(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function se(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ra(d)?se.apply(null,d):re(d)}}
;function J(){this.X=this.X;this.D=this.D}
J.prototype.X=!1;J.prototype.h=function(){return this.X};
J.prototype.dispose=function(){this.X||(this.X=!0,this.L())};
function te(a,b){ue(a,$a(re,b))}
function ue(a,b){a.X?b():(a.D||(a.D=[]),a.D.push(b))}
J.prototype.L=function(){if(this.D)for(;this.D.length;)this.D.shift()()};function ve(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
ve.prototype.stopPropagation=function(){this.j=!0};
ve.prototype.preventDefault=function(){this.defaultPrevented=!0};function we(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||z.$googDebugFname||b}catch(g){e="Not available",c=!0}b=xe(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,ye[c])c=ye[c];else{c=String(c);if(!ye[c]){var f=/function\s+([^\(]+)/m.exec(c);ye[c]=f?f[1]:"[Anonymous]"}c=ye[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function xe(a,b){b||(b={});b[ze(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[ze(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=xe(a,b));return c}
function ze(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var ye={};var Ae=function(){if(!z.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{z.addEventListener("test",function(){},b),z.removeEventListener("test",function(){},b)}catch(c){}return a}();function Be(a,b){ve.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
ab(Be,ve);var Ce={2:"touch",3:"pen",4:"mouse"};
Be.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Jc){a:{try{Fc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Ce[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Be.ta.preventDefault.call(this)};
Be.prototype.stopPropagation=function(){Be.ta.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Be.prototype.preventDefault=function(){Be.ta.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var De="closure_listenable_"+(1E6*Math.random()|0);var Ee=0;function Fe(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.ic=e;this.key=++Ee;this.Nb=this.cc=!1}
function Ge(a){a.Nb=!0;a.listener=null;a.proxy=null;a.src=null;a.ic=null}
;function He(a){this.src=a;this.listeners={};this.h=0}
He.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Ie(a,b,d,e);-1<g?(b=a[g],c||(b.cc=!1)):(b=new Fe(b,this.src,f,!!d,e),b.cc=c,a.push(b));return b};
He.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Ie(e,b,c,d);return-1<b?(Ge(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Je(a,b){var c=b.type;c in a.listeners&&mb(a.listeners[c],b)&&(Ge(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Ie(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Nb&&f.listener==b&&f.capture==!!c&&f.ic==d)return e}return-1}
;var Ke="closure_lm_"+(1E6*Math.random()|0),Le={},Me=0;function Ne(a,b,c,d,e){if(d&&d.once)Oe(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Ne(a,b[f],c,d,e);else c=Pe(c),a&&a[De]?a.Ma(b,c,Sa(d)?!!d.capture:!!d,e):Qe(a,b,c,!1,d,e)}
function Qe(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Sa(e)?!!e.capture:!!e,h=Re(a);h||(a[Ke]=h=new He(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Se();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ae||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Te(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Me++}}
function Se(){function a(c){return b.call(a.src,a.listener,c)}
var b=Ue;return a}
function Oe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Oe(a,b[f],c,d,e);else c=Pe(c),a&&a[De]?a.l.add(String(b),c,!0,Sa(d)?!!d.capture:!!d,e):Qe(a,b,c,!0,d,e)}
function Ve(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ve(a,b[f],c,d,e);else(d=Sa(d)?!!d.capture:!!d,c=Pe(c),a&&a[De])?a.l.remove(String(b),c,d,e):a&&(a=Re(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Ie(b,c,d,e)),(c=-1<a?b[a]:null)&&We(c))}
function We(a){if("number"!==typeof a&&a&&!a.Nb){var b=a.src;if(b&&b[De])Je(b.l,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Te(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Me--;(c=Re(b))?(Je(c,a),0==c.h&&(c.src=null,b[Ke]=null)):Ge(a)}}}
function Te(a){return a in Le?Le[a]:Le[a]="on"+a}
function Ue(a,b){if(a.Nb)a=!0;else{b=new Be(b,this);var c=a.listener,d=a.ic||a.src;a.cc&&We(a);a=c.call(d,b)}return a}
function Re(a){a=a[Ke];return a instanceof He?a:null}
var Xe="__closure_events_fn_"+(1E9*Math.random()>>>0);function Pe(a){if("function"===typeof a)return a;a[Xe]||(a[Xe]=function(b){return a.handleEvent(b)});
return a[Xe]}
;function Ye(){J.call(this);this.l=new He(this);this.Xd=this;this.Pa=null}
ab(Ye,J);Ye.prototype[De]=!0;Ye.prototype.addEventListener=function(a,b,c,d){Ne(this,a,b,c,d)};
Ye.prototype.removeEventListener=function(a,b,c,d){Ve(this,a,b,c,d)};
function Ze(a,b){var c=a.Pa;if(c){var d=[];for(var e=1;c;c=c.Pa)d.push(c),++e}a=a.Xd;c=b.type||b;"string"===typeof b?b=new ve(b,a):b instanceof ve?b.target=b.target||a:(e=b,b=new ve(c,a),zb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=$e(g,c,!0,b)&&e}b.j||(g=b.h=a,e=$e(g,c,!0,b)&&e,b.j||(e=$e(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=$e(g,c,!1,b)&&e}
Ye.prototype.L=function(){Ye.ta.L.call(this);if(this.l){var a=this.l,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Ge(d[e]);delete a.listeners[c];a.h--}}this.Pa=null};
Ye.prototype.Ma=function(a,b,c,d){return this.l.add(String(a),b,!1,c,d)};
function $e(a,b,c,d){b=a.l.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Nb&&g.capture==c){var h=g.listener,k=g.ic||g.src;g.cc&&Je(a.l,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function af(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
af.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function bf(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function hf(a,b){return a+Math.random()*(b-a)}
;function jf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=jf.prototype;l.clone=function(){return new jf(this.x,this.y)};
l.equals=function(a){return a instanceof jf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function kf(a,b){this.width=a;this.height=b}
l=kf.prototype;l.clone=function(){return new kf(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.Jb=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function lf(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function mf(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function nf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var of;function pf(){var a=z.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=mf("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ya(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Vb()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.fd;c.fd=null;e()}};
return function(e){d.next={fd:e};d=d.next;b.port2.postMessage(0)}}return function(e){z.setTimeout(e,0)}}
;function qf(){this.i=this.h=null}
qf.prototype.add=function(a,b){var c=rf.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
qf.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var rf=new af(function(){return new sf},function(a){return a.reset()});
function sf(){this.next=this.scope=this.h=null}
sf.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
sf.prototype.reset=function(){this.next=this.scope=this.h=null};var tf,uf=!1,vf=new qf;function wf(a,b){tf||xf();uf||(tf(),uf=!0);vf.add(a,b)}
function xf(){if(z.Promise&&z.Promise.resolve){var a=z.Promise.resolve(void 0);tf=function(){a.then(yf)}}else tf=function(){var b=yf;
"function"!==typeof z.setImmediate||z.Window&&z.Window.prototype&&!C("Edge")&&z.Window.prototype.setImmediate==z.setImmediate?(of||(of=pf()),of(b)):z.setImmediate(b)}}
function yf(){for(var a;a=vf.remove();){try{a.h.call(a.scope)}catch(b){Cc(b)}bf(rf,a)}uf=!1}
;function zf(a){this.h=0;this.D=void 0;this.l=this.i=this.j=null;this.m=this.s=!1;if(a!=eb)try{var b=this;a.call(void 0,function(c){Af(b,2,c)},function(c){Af(b,3,c)})}catch(c){Af(this,3,c)}}
function Bf(){this.next=this.context=this.i=this.j=this.h=null;this.l=!1}
Bf.prototype.reset=function(){this.context=this.i=this.j=this.h=null;this.l=!1};
var Cf=new af(function(){return new Bf},function(a){a.reset()});
function Df(a,b,c){var d=Cf.get();d.j=a;d.i=b;d.context=c;return d}
function Ef(a){return new zf(function(b,c){c(a)})}
zf.prototype.then=function(a,b,c){return Ff(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
zf.prototype.$goog_Thenable=!0;l=zf.prototype;l.tc=function(a,b){return Ff(this,null,a,b)};
l.catch=zf.prototype.tc;l.cancel=function(a){if(0==this.h){var b=new Gf(a);wf(function(){Hf(this,b)},this)}};
function Hf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.l||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Hf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):If(c),Jf(c,e,3,b)))}a.j=null}else Af(a,3,b)}
function Kf(a,b){a.i||2!=a.h&&3!=a.h||Lf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Ff(a,b,c,d){var e=Df(null,null,null);e.h=new zf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.i=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Gf?g(h):f(k)}catch(m){g(m)}}:g});
e.h.j=a;Kf(a,e);return e.h}
l.hf=function(a){this.h=0;Af(this,2,a)};
l.jf=function(a){this.h=0;Af(this,3,a)};
function Af(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.hf,f=a.jf;if(d instanceof zf){Kf(d,Df(e||eb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Sa(d))try{var k=d.then;if("function"===typeof k){Mf(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.D=c,a.h=b,a.j=null,Lf(a),3!=b||c instanceof Gf||Nf(a,c))}}
function Mf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Lf(a){a.s||(a.s=!0,wf(a.me,a))}
function If(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
l.me=function(){for(var a;a=If(this);)Jf(this,a,this.h,this.D);this.s=!1};
function Jf(a,b,c,d){if(3==c&&b.i&&!b.l)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,Of(b,c,d);else try{b.l?b.j.call(b.context):Of(b,c,d)}catch(e){Pf.call(null,e)}bf(Cf,b)}
function Of(a,b,c){2==b?a.j.call(a.context,c):a.i&&a.i.call(a.context,c)}
function Nf(a,b){a.m=!0;wf(function(){a.m&&Pf.call(null,b)})}
var Pf=Cc;function Gf(a){cb.call(this,a)}
ab(Gf,cb);Gf.prototype.name="cancel";function Qf(a,b){Ye.call(this);this.j=a||1;this.i=b||z;this.m=Ya(this.ff,this);this.s=Date.now()}
ab(Qf,Ye);l=Qf.prototype;l.enabled=!1;l.ya=null;function Rf(a,b){a.j=b;a.ya&&a.enabled?(a.stop(),a.start()):a.ya&&a.stop()}
l.ff=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.j?this.ya=this.i.setTimeout(this.m,this.j-a):(this.ya&&(this.i.clearTimeout(this.ya),this.ya=null),Ze(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.ya||(this.ya=this.i.setTimeout(this.m,this.j),this.s=Date.now())};
l.stop=function(){this.enabled=!1;this.ya&&(this.i.clearTimeout(this.ya),this.ya=null)};
l.L=function(){Qf.ta.L.call(this);this.stop();delete this.i};
function Sf(a,b,c){if("function"===typeof a)c&&(a=Ya(a,c));else if(a&&"function"==typeof a.handleEvent)a=Ya(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:z.setTimeout(a,b||0)}
;function Tf(a){this.D=a;this.h=new Map;this.s=new Set;this.j=0;this.l=100;this.flushInterval=3E4;this.i=new Qf(this.flushInterval);this.i.Ma("tick",this.vc,!1,this);this.m=!1}
l=Tf.prototype;l.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function Uf(a){a.i.enabled||a.i.start();a.j++;a.j>=a.l&&a.vc()}
l.vc=function(){var a=this.h.values();a=[].concat(ja(a)).filter(function(b){return b.pb.size});
a.length&&this.D.flush(a,this.m);Vf(a);this.j=0;this.i.enabled&&this.i.stop()};
l.bd=function(a){var b=Ka.apply(1,arguments);this.h.has(a)||this.h.set(a,new pe(a,b))};
l.cd=function(a){var b=Ka.apply(1,arguments);this.h.has(a)||this.h.set(a,new qe(a,b))};
function Wf(a,b){return a.s.has(b)?void 0:a.h.get(b)}
l.Vb=function(a){this.Vd.apply(this,[a,1].concat(ja(Ka.apply(1,arguments))))};
l.Vd=function(a,b){var c=Ka.apply(2,arguments),d=Wf(this,a);d&&d instanceof pe&&(d.j(b,c),Uf(this))};
l.uc=function(a,b){var c=Ka.apply(2,arguments),d=Wf(this,a);d&&d instanceof qe&&(d.j(b,c),Uf(this))};
function Vf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Xf(a){this.h=a;this.h.bd("/client_streamz/bg/fiec",{Ib:3,Hb:"rk"},{Ib:2,Hb:"ec"})}
function Yf(a){this.h=a;this.h.cd("/client_streamz/bg/fil",{Ib:3,Hb:"rk"})}
function Zf(a){this.h=a;this.h.bd("/client_streamz/bg/fsc",{Ib:3,Hb:"rk"})}
function $f(a){this.h=a;this.h.cd("/client_streamz/bg/fsl",{Ib:3,Hb:"rk"})}
;var ag={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function bg(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=cg(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=dg(a,h),d+=dg(a,h+4),e+=dg(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return ag.toString(e)}
function cg(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function dg(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;function eg(a){H.call(this,a,-1,fg)}
u(eg,H);function gg(a){H.call(this,a,-1,hg)}
u(gg,H);function ig(a){H.call(this,a)}
u(ig,H);function jg(a){H.call(this,a)}
u(jg,H);var fg=[3,6,4],hg=[1],kg=[1,2,3],lg=[1,2,3];function mg(a){H.call(this,a,-1,ng)}
u(mg,H);var ng=[1];function og(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function pg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=m=0}
function b(p){for(var v=g,t=0;64>t;t+=4)v[t/4]=p[t]<<24|p[t+1]<<16|p[t+2]<<8|p[t+3];for(t=16;80>t;t++)p=v[t-3]^v[t-8]^v[t-14]^v[t-16],v[t]=(p<<1|p>>>31)&4294967295;p=e[0];var y=e[1],D=e[2],E=e[3],O=e[4];for(t=0;80>t;t++){if(40>t)if(20>t){var N=E^y&(D^E);var S=1518500249}else N=y^D^E,S=1859775393;else 60>t?(N=y&D|E&(y|D),S=2400959708):(N=y^D^E,S=3395469782);N=((p<<5|p>>>27)&4294967295)+N+O+S+v[t]&4294967295;O=E;E=D;D=(y<<30|y>>>2)&4294967295;y=p;p=N}e[0]=e[0]+p&4294967295;e[1]=e[1]+y&4294967295;e[2]=
e[2]+D&4294967295;e[3]=e[3]+E&4294967295;e[4]=e[4]+O&4294967295}
function c(p,v){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var t=[],y=0,D=p.length;y<D;++y)t.push(p.charCodeAt(y));p=t}v||(v=p.length);t=0;if(0==m)for(;t+64<v;)b(p.slice(t,t+64)),t+=64,n+=64;for(;t<v;)if(f[m++]=p[t++],n++,64==m)for(m=0,b(f);t+64<v;)b(p.slice(t,t+64)),t+=64,n+=64}
function d(){var p=[],v=8*n;56>m?c(h,56-m):c(h,64-(m-56));for(var t=63;56<=t;t--)f[t]=v&255,v>>>=8;b(f);for(t=v=0;5>t;t++)for(var y=24;0<=y;y-=8)p[v++]=e[t]>>y&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,n;a();return{reset:a,update:c,digest:d,ie:function(){for(var p=d(),v="",t=0;t<p.length;t++)v+="0123456789ABCDEF".charAt(Math.floor(p[t]/16))+"0123456789ABCDEF".charAt(p[t]%16);return v}}}
;function qg(a,b,c){var d=String(z.location.href);return d&&a&&b?[b,rg(og(d),a,c||null)].join(" "):null}
function rg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],hb(d,function(h){e.push(h)}),sg(e.join(" "));
var f=[],g=[];hb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];hb(d,function(h){e.push(h)});
a=sg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function sg(a){var b=pg();b.update(a);return b.ie().toLowerCase()}
;var tg={};function ug(a){this.h=a||{cookie:""}}
l=ug.prototype;l.isEnabled=function(){if(!z.navigator.cookieEnabled)return!1;if(!this.Jb())return!0;this.set("TESTCOOKIESENABLED","1",{lc:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Wt;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.lc}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Lb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{lc:0,path:b,domain:c});return d};
l.Bc=function(){return vg(this).keys};
l.Jb=function(){return!this.h.cookie};
l.clear=function(){for(var a=vg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function vg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Lb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var wg=new ug("undefined"==typeof document?null:document);function xg(a){return!!tg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function yg(a){a=void 0===a?!1:a;var b=z.__SAPISID||z.__APISID||z.__3PSAPISID||z.__OVERRIDE_SID;xg(a)&&(b=b||z.__1PSAPISID);if(b)return!0;var c=new ug(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");xg(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function zg(a,b,c,d){(a=z[a])||(a=(new ug(document)).get(b));return a?qg(a,c,d):null}
function Ag(a,b){b=void 0===b?!1:b;var c=og(String(z.location.href)),d=[];if(yg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?z.__SAPISID:z.__APISID;e||(e=new ug(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?qg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&xg(b)&&((b=zg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=zg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Bg(a){H.call(this,a,-1,Cg)}
u(Bg,H);var Cg=[2];function Dg(a){this.h=this.i=this.j=a}
Dg.prototype.reset=function(){this.h=this.i=this.j};
Dg.prototype.getValue=function(){return this.i};function Eg(a){var b=[];Fg(new Gg,a,b);return b.join("")}
function Gg(){}
function Fg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Fg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Hg(d,c),c.push(":"),Fg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Hg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Ig={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Jg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Hg(a,b){b.push('"',a.replace(Jg,function(c){var d=Ig[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Ig[c]=d);return d}),'"')}
;function Kg(){}
Kg.prototype.h=null;Kg.prototype.getOptions=function(){var a;(a=this.h)||(a={},Lg(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var Mg;function Ng(){}
ab(Ng,Kg);function Og(a){return(a=Lg(a))?new ActiveXObject(a):new XMLHttpRequest}
function Lg(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
Mg=new Ng;function Pg(a){Ye.call(this);this.headers=new Map;this.V=a||null;this.i=!1;this.R=this.G=null;this.m=this.ia="";this.j=this.aa=this.v=this.Z=!1;this.s=0;this.N=null;this.Aa="";this.oa=this.qa=!1}
ab(Pg,Ye);var Qg=/^https?$/i,Rg=["POST","PUT"],Sg=[];function Tg(a,b,c,d,e,f,g){var h=new Pg;Sg.push(h);b&&h.Ma("complete",b);h.l.add("ready",h.ge,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.qa=g);h.send(a,c,d,e)}
l=Pg.prototype;l.ge=function(){this.dispose();mb(Sg,this)};
l.send=function(a,b,c,d){if(this.G)throw Error("[goog.net.XhrIo] Object is active with another request="+this.ia+"; newUri="+a);b=b?b.toUpperCase():"GET";this.ia=a;this.m="";this.Z=!1;this.i=!0;this.G=this.V?Og(this.V):Og(Mg);this.R=this.V?this.V.getOptions():Mg.getOptions();this.G.onreadystatechange=Ya(this.Bd,this);try{this.getStatus(),this.aa=!0,this.G.open(b,String(a),!0),this.aa=!1}catch(g){this.getStatus();Ug(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===
Object.prototype)for(var e in d)c.set(e,d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=r(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=z.FormData&&a instanceof z.FormData;!(0<=gb(Rg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=r(c);for(d=b.next();!d.done;d=b.next())c=r(d.value),d=c.next().value,c=c.next().value,this.G.setRequestHeader(d,c);this.Aa&&(this.G.responseType=this.Aa);"withCredentials"in this.G&&this.G.withCredentials!==this.qa&&(this.G.withCredentials=this.qa);try{Vg(this),0<this.s&&(this.oa=Wg(this.G),this.getStatus(),this.oa?(this.G.timeout=this.s,this.G.ontimeout=Ya(this.Od,
this)):this.N=Sf(this.Od,this.s,this)),this.getStatus(),this.v=!0,this.G.send(a),this.v=!1}catch(g){this.getStatus(),Ug(this,g)}};
function Wg(a){return Hc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.Od=function(){"undefined"!=typeof Oa&&this.G&&(this.m="Timed out after "+this.s+"ms, aborting",this.getStatus(),Ze(this,"timeout"),this.abort(8))};
function Ug(a,b){a.i=!1;a.G&&(a.j=!0,a.G.abort(),a.j=!1);a.m=b;Xg(a);Yg(a)}
function Xg(a){a.Z||(a.Z=!0,Ze(a,"complete"),Ze(a,"error"))}
l.abort=function(){this.G&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.G.abort(),this.j=!1,Ze(this,"complete"),Ze(this,"abort"),Yg(this))};
l.L=function(){this.G&&(this.i&&(this.i=!1,this.j=!0,this.G.abort(),this.j=!1),Yg(this,!0));Pg.ta.L.call(this)};
l.Bd=function(){this.h()||(this.aa||this.v||this.j?Zg(this):this.Je())};
l.Je=function(){Zg(this)};
function Zg(a){if(a.i&&"undefined"!=typeof Oa)if(a.R[1]&&4==$g(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==$g(a))Sf(a.Bd,0,a);else if(Ze(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(ah(a))Ze(a,"complete"),Ze(a,"success");else{try{var b=2<$g(a)?a.G.statusText:""}catch(c){b=""}a.m=b+" ["+a.getStatus()+"]";Xg(a)}}finally{Yg(a)}}}
function Yg(a,b){if(a.G){Vg(a);var c=a.G,d=a.R[0]?function(){}:null;
a.G=null;a.R=null;b||Ze(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Vg(a){a.G&&a.oa&&(a.G.ontimeout=null);a.N&&(z.clearTimeout(a.N),a.N=null)}
l.isActive=function(){return!!this.G};
l.isComplete=function(){return 4==$g(this)};
function ah(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=oc(1,String(a.ia)),!a&&z.self&&z.self.location&&(a=z.self.location.protocol.slice(0,-1)),b=!Qg.test(a?a.toLowerCase():"");c=b}return c}
function $g(a){return a.G?a.G.readyState:0}
l.getStatus=function(){try{return 2<$g(this)?this.G.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.m?this.m:String(this.m)};function bh(a){H.call(this,a)}
u(bh,H);function ch(a){H.call(this,a,-1,dh)}
u(ch,H);var dh=[1];var eh=["platform","platformVersion","architecture","model","uaFullVersion"];new ch;function fh(a){H.call(this,a)}
u(fh,H);function gh(a){H.call(this,a,31,hh)}
u(gh,H);var hh=[3,20,27];function ih(a){H.call(this,a,17,jh)}
u(ih,H);var jh=[3,5];function kh(a){H.call(this,a,6,lh)}
u(kh,H);var lh=[5];function mh(a){H.call(this,a)}
u(mh,H);var nh;nh=new function(a,b,c){this.i=a;this.fieldName=b;this.h=c;this.isRepeated=0;this.j=me}(175237375,{Mt:0},mh);function oh(a,b,c,d,e,f,g,h,k,m,n){Ye.call(this);var p=this;this.Z="";this.j=[];this.Yc="";this.Zc=this.eb=-1;this.Xb=!1;this.R=this.m=null;this.N=0;this.Yd=1;this.timeoutMillis=0;this.Aa=!1;Ye.call(this);this.Yb=b||function(){};
this.v=new ph(a,f);this.Wd=d;this.Wb=n;this.Zd=$a(hf,0,1);this.ia=e||null;this.V=c||null;this.oa=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Cb=f||!1;!this.Cb&&(65<=bc("Chromium")||45<=bc("Firefox")||12<=bc("Safari")||(Dc()||C("iPad")||C("iPod"))&&Ec());a=F(new fh,1,1);qh(this.v,a);this.s=new Dg(1E4);this.i=new Qf(this.s.getValue());te(this,this.i);m=rh(this,m);Ne(this.i,"tick",m,!1,this);this.aa=new Qf(6E5);te(this,this.aa);Ne(this.aa,"tick",m,!1,this);this.oa||this.aa.start();
this.Cb||(Ne(document,"visibilitychange",function(){"hidden"===document.visibilityState&&p.qa()}),Ne(document,"pagehide",this.qa,!1,this))}
u(oh,Ye);function rh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
oh.prototype.L=function(){this.qa();Ye.prototype.L.call(this)};
function sh(a){a.ia||(a.ia=.01>a.Zd()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.ia}
function th(a,b){a.s=new Dg(1>b?1:b);Rf(a.i,a.s.getValue())}
oh.prototype.log=function(a){a=a.clone();var b=this.Yd++;F(a,21,b);this.Z&&F(a,26,this.Z);if(!Hd(a,1)){b=a;var c=Date.now().toString();F(b,1,c)}null==Hd(a,15)&&F(a,15,60*(new Date).getTimezoneOffset());this.m&&(b=this.m.clone(),G(a,Bg,16,b));for(;1E3<=this.j.length;)this.j.shift(),++this.N;this.j.push(a);Ze(this,new uh(a));this.oa||this.i.enabled||this.i.start()};
oh.prototype.flush=function(a,b){var c=this;if(0===this.j.length)a&&a();else if(this.Aa)vh(this);else{var d=Date.now();if(this.Zc>d&&this.eb<d)b&&b("throttled");else{var e=wh(this.v,this.j,this.N);d={};var f=this.Yb();f&&(d.Authorization=f);var g=sh(this);this.V&&(d["X-Goog-AuthUser"]=this.V,g=xc(g,"authuser",this.V));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=xc(g,"pageId",this.pageId));if(f&&this.Yc===f)b&&b("stale-auth-token");else{this.j=[];this.i.enabled&&this.i.stop();this.N=0;var h=ke(e),
k;this.R&&this.R.isSupported(h.length)&&(k=this.R.compress(h));var m={url:g,body:h,de:1,Pc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(t){c.s.reset();Rf(c.i,c.s.getValue());if(t){var y=null;try{var D=JSON.parse(t.replace(")]}'\n",""));y=new kh(D)}catch(E){}y&&(t=Number(Yd(Hd(y,1),"-1")),0<t&&(c.eb=Date.now(),c.Zc=c.eb+t),y=nh.j(y))&&(y=Hd(y,1),y=null==y?-1:y,-1!=y&&(c.Xb||th(c,y)))}a&&a()},p=function(t,y){var D=Ud(e,gh,3),E=c.s;
E.h=Math.min(3E5,2*E.h);E.i=Math.min(3E5,E.h+Math.round(.2*(Math.random()-.5)*E.h));Rf(c.i,c.s.getValue());401===t&&f&&(c.Yc=f);void 0===y&&(y=500<=t&&600>t||401===t||0===t);y&&(c.j=D.concat(c.j),c.oa||c.i.enabled||c.i.start());b&&b("net-send-failed",t)},v=function(){c.Wb?c.Wb.send(m,n,p):c.Wd(m,n,p)};
k?k.then(function(t){m.Pc["Content-Encoding"]="gzip";m.Pc["Content-Type"]="application/binary";m.body=t;m.de=2;v()},function(){v()}):v()}}}};
oh.prototype.qa=function(){this.flush()};
function vh(a){zh(a,function(b,c){b=xc(b,"format","json");b=window.navigator.sendBeacon(b,ke(c));a.Aa&&!b&&(a.Aa=!1);return b})}
function zh(a,b){if(0!==a.j.length){var c=Bc(sh(a),"format");c=vc(c,"auth",a.Yb(),"authuser",a.V||"0");for(var d=0;10>d&&a.j.length;++d){var e=a.j.slice(0,32),f=wh(a.v,e,a.N);if(!b(c,f))break;a.N=0;a.j=a.j.slice(e.length)}a.i.enabled&&a.i.stop()}}
function uh(){ve.call(this,"event-logged",void 0)}
u(uh,ve);function ph(a,b){this.i=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new ih;F(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));qh(this,new fh)}
function qh(a,b){G(a.h,fh,1,b);Hd(b,1)||F(b,1,1);a.i||(b=Ah(a),Hd(b,5)||F(b,5,a.locale));a.uach&&(b=Ah(a),Rd(b,ch,9)||G(b,ch,9,a.uach))}
function Bh(a,b){var c=void 0===c?eh:c;b(window,c).then(function(d){a.uach=d;d=Ah(a);G(d,ch,9,a.uach);return!0}).catch(function(){return!1})}
function Ah(a){a=Rd(a.h,fh,1);var b=Rd(a,bh,11);b||(b=new bh,G(a,bh,11,b));return b}
function wh(a,b,c){c=void 0===c?0:c;a=a.h.clone();var d=Date.now().toString();a=F(a,4,d);b=Wd(a,gh,3,b);c&&F(b,14,c);return b}
;function Ch(a,b,c){Tg(a.url,function(d){d=d.target;if(ah(d)){try{var e=d.G?d.G.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Pc,a.timeoutMillis,a.withCredentials)}
;function Dh(){this.j="https://play.google.com/log?format=json&hasfast=true";this.v=!1;this.m=Ch;this.h=""}
;function Eh(){var a=void 0===a?"":a;var b=void 0===b?"":b;var c=new Dh;c.h="";""!=a&&(c.j=a);b&&(c.i=b);a=new oh(1828,c.R?c.R:Ag,"0",c.m,c.j,c.v,!1,c.aa,void 0,void 0,c.s?c.s:void 0);c.X&&qh(a.v,c.X);if(c.i){b=c.i;var d=Ah(a.v);F(d,7,b)}c.l&&(a.R=c.l);c.h&&(a.Z=c.h);c.D&&((b=c.D)?(a.m||(a.m=new Bg),b=ke(b),F(a.m,4,b)):a.m&&F(a.m,4,void 0,!1));c.V&&(d=c.V,a.m||(a.m=new Bg),b=a.m,d=null==d?Ad:pd(d,1),F(b,2,d));c.N&&(b=c.N,a.Xb=!0,th(a,b));c.Z&&Bh(a.v,c.Z);this.h=a}
Eh.prototype.flush=function(a){var b=a||[];if(b.length){a=new mg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e,g=new eg;var h=F(g,1,f.i);var k=f;g=[];for(var m=0;m<k.h.length;m++)g.push(k.h[m].Hb);if(null==g)g=F(h,3,Ad);else{k=qd(g);if(!(k&4)){if(k&2||Object.isFrozen(g))g=Array.prototype.slice.call(g);for(m=0;m<g.length;m++)g[m]=g[m];rd(g,k|5)}g=F(h,3,g)}h=[];k=[];m=r(f.pb.keys());for(var n=m.next();!n.done;n=m.next())k.push(n.value.split(","));for(m=0;m<k.length;m++){n=k[m];var p=f.l;for(var v=
f.yc(n)||[],t=[],y=0;y<v.length;y++){var D=v[y],E=D&&D.gd;D=new jg;switch(p){case 3:Ld(D,1,lg,Number(E));break;case 2:var O=D;E=Number(E);var N=lg;if(null!=E&&"number"!==typeof E)throw Error("Value of double field must be a number|null|undefined, found "+typeof E+": "+E);Ld(O,2,N,E)}t.push(D)}p=t;for(v=0;v<p.length;v++){t=p[v];y=new gg;t=G(y,jg,2,t);y=n;D=[];O=f;E=[];for(N=0;N<O.h.length;N++)E.push(O.h[N].Ib);O=E;for(E=0;E<O.length;E++){N=O[E];var S=y[E],aa=new ig;switch(N){case 3:Ld(aa,1,kg,String(S));
break;case 2:Ld(aa,2,kg,Number(S));break;case 1:Ld(aa,3,kg,"true"==S)}D.push(aa)}Wd(t,ig,1,D);h.push(t)}}Wd(g,gg,4,h);c.push(g);e.clear()}Wd(a,eg,1,c);b=this.h;a instanceof gh?b.log(a):(c=new gh,a=ke(a),a=F(c,8,a),b.log(a));this.h.flush()}};function Fh(a){this.D=Gh();this.m=new Eh;this.h=new Tf(this.m);this.s=new Yf(this.h);this.j=new Zf(this.h);this.l=new $f(this.h);this.i=new Xf(this.h);this.Va=bg(a)}
function Gh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Hh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Ih(a){var b=this;this.i=!1;var c=a.program;var d=a.te;if(a.Ne){var e;this.Ha=null!=(e=a.Ha)?e:new Fh(d)}var f=new Hh;this.j=f.promise;if(!z[d]){var g;null!=(g=this.Ha)&&g.i.h.Vb("/client_streamz/bg/fiec",g.Va,1)}else if(!z[d].a){var h;null!=(h=this.Ha)&&h.i.h.Vb("/client_streamz/bg/fiec",h.Va,2)}this.l=r((0,z[d].a)(c,function(k,m){Promise.resolve().then(function(){var n;if(null!=(n=b.Ha)){var p=Gh()-n.D;n.s.h.uc("/client_streamz/bg/fil",p,n.Va)}f.resolve({be:k,bf:m})})},!0)).next().value;
this.af=f.promise.then(function(){})}
Ih.prototype.snapshot=function(a){var b=this;if(this.i)throw Error("Already disposed");var c=Gh(),d;null!=(d=this.Ha)&&d.j.h.Vb("/client_streamz/bg/fsc",d.Va);return this.j.then(function(e){var f=e.be;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.Ha)){var m=Gh()-c;k.l.h.uc("/client_streamz/bg/fsl",m,k.Va)}g(h)},[a.jd,
a.cf])})})};
Ih.prototype.Ld=function(a){if(this.i)throw Error("Already disposed");var b=Gh(),c;null!=(c=this.Ha)&&c.j.h.Vb("/client_streamz/bg/fsc",c.Va);a=this.l([a.jd,a.cf]);null!=(c=this.Ha)&&(b=Gh()-b,c.l.h.uc("/client_streamz/bg/fsl",b,c.Va));return a};
Ih.prototype.dispose=function(){var a;null!=(a=this.Ha)&&a.h.vc();this.i=!0;this.j.then(function(b){(b=b.bf)&&b()})};
Ih.prototype.h=function(){return this.i};var Jh=window;Eb("csi.gstatic.com");Eb("googleads.g.doubleclick.net");Eb("partner.googleadservices.com");Eb("pubads.g.doubleclick.net");Eb("securepubads.g.doubleclick.net");Eb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Kh;try{new URL("s://g"),Kh=!0}catch(a){Kh=!1}var Lh=Kh;var Mh={};function Nh(){}
function Oh(a){this.h=a}
u(Oh,Nh);Oh.prototype.toString=function(){return this.h};function Ph(a){var b="true".toString(),c=[new Oh(Qh[0].toLowerCase(),Mh)];if(0===c.length)throw Error("No prefixes are provided");if(c.map(function(d){if(d instanceof Oh)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Rh(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function Sh(a,b){a.src=Jb(b);Rh(a)}
;function Th(a){this.Be=a}
function Uh(a){return new Th(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Vh=[Uh("data"),Uh("http"),Uh("https"),Uh("mailto"),Uh("ftp"),new Th(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Wh(a){var b=Xh;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Yh(){var a=[];Wh(function(b){a.push(b)});
return a}
var Xh={yf:"allow-forms",zf:"allow-modals",Af:"allow-orientation-lock",Bf:"allow-pointer-lock",Cf:"allow-popups",Df:"allow-popups-to-escape-sandbox",Ef:"allow-presentation",Ff:"allow-same-origin",Gf:"allow-scripts",Hf:"allow-top-navigation",If:"allow-top-navigation-by-user-activation"},Zh=fb(function(){return Yh()});
function $h(){var a=ai(),b={};hb(Zh(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function ai(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function bi(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var ci=(new Date).getTime();var di="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ja(di);"undefined"!==typeof TextDecoder&&new TextDecoder;var ei="undefined"!==typeof TextEncoder?new TextEncoder:null,fi=ei?function(a){return ei.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function gi(a){Ye.call(this);var b=this;this.v=this.j=0;this.xa=null!=a?a:{fa:function(e,f){return setTimeout(e,f)},
Ca:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.m=function(){return x(function(e){return w(e,hi(b),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.v||ii(this)}
u(gi,Ye);function ji(){var a=ki;gi.h||(gi.h=new gi(a));return gi.h}
gi.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.xa.Ca(this.v);delete gi.h};
gi.prototype.ma=function(){return this.i};
function ii(a){a.v=a.xa.fa(function(){var b;return x(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.A(3):w(c,hi(a),3):w(c,hi(a),3);ii(a);c.h=0})},3E4)}
function hi(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,za(h,2,3),d&&(a.j=a.xa.fa(function(){d.abort()},b||2E4)),w(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ca(h);a.s=void 0;a.j&&(a.xa.Ca(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?Ze(a,"networkstatus-online"):Ze(a,"networkstatus-offline"));c(g);Da(h);break;case 2:Ba(h),g=!1,h.A(3)}})})}
;function li(){this.data_=[];this.h=-1}
li.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.h=-1)};
li.prototype.get=function(a){return!!this.data_[a]};
function mi(a){-1===a.h&&(a.h=kb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function ni(a,b){this.h=a[z.Symbol.iterator]();this.i=b}
ni.prototype[Symbol.iterator]=function(){return this};
ni.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function oi(a,b){return new ni(a,b)}
;function pi(){this.blockSize=-1}
;function qi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.s=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
ab(qi,pi);qi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function ri(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
qi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)ri(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){ri(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){ri(this,e);f=0;break}}this.i=f;this.l+=b}};
qi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;ri(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function si(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function ti(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function ui(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:si(a).match(/\S+/g)||[],b=0<=gb(a,b));return b}
function vi(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):ui(a,"inverted-hdpi")&&ti(a,Array.prototype.filter.call(a.classList?a.classList:si(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function wi(){}
wi.prototype.next=function(){return xi};
var xi={done:!0,value:void 0};function yi(a){return{value:a,done:!1}}
wi.prototype.Ba=function(){return this};function zi(a){if(a instanceof Ai||a instanceof Bi||a instanceof Ci)return a;if("function"==typeof a.next)return new Ai(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Ai(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ba)return new Ai(function(){return a.Ba()});
throw Error("Not an iterator or iterable.");}
function Ai(a){this.i=a}
Ai.prototype.Ba=function(){return new Bi(this.i())};
Ai.prototype[Symbol.iterator]=function(){return new Ci(this.i())};
Ai.prototype.h=function(){return new Ci(this.i())};
function Bi(a){this.i=a}
u(Bi,wi);Bi.prototype.next=function(){return this.i.next()};
Bi.prototype[Symbol.iterator]=function(){return new Ci(this.i)};
Bi.prototype.h=function(){return new Ci(this.i)};
function Ci(a){Ai.call(this,function(){return a});
this.j=a}
u(Ci,Ai);Ci.prototype.next=function(){return this.j.next()};function Di(a,b){this.i={};this.h=[];this.Xa=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Di)for(c=a.Bc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=Di.prototype;l.Bc=function(){Ei(this);return this.h.concat()};
l.has=function(a){return Fi(this.i,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Gi;Ei(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Gi(a,b){return a===b}
l.Jb=function(){return 0==this.size};
l.clear=function(){this.i={};this.Xa=this.size=this.h.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return Fi(this.i,a)?(delete this.i[a],--this.size,this.Xa++,this.h.length>2*this.size&&Ei(this),!0):!1};
function Ei(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Fi(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Fi(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
l.get=function(a,b){return Fi(this.i,a)?this.i[a]:b};
l.set=function(a,b){Fi(this.i,a)||(this.size+=1,this.h.push(a),this.Xa++);this.i[a]=b};
l.forEach=function(a,b){for(var c=this.Bc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new Di(this)};
l.keys=function(){return zi(this.Ba(!0)).h()};
l.values=function(){return zi(this.Ba(!1)).h()};
l.entries=function(){var a=this;return oi(this.keys(),function(b){return[b,a.get(b)]})};
l.Ba=function(a){Ei(this);var b=0,c=this.Xa,d=this,e=new wi;e.next=function(){if(c!=d.Xa)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return xi;var f=d.h[b++];return yi(a?f:d.i[f])};
return e};
function Fi(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function Hi(a){J.call(this);this.s=1;this.l=[];this.m=0;this.i=[];this.j={};this.v=!!a}
ab(Hi,J);l=Hi.prototype;l.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.s;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.s=e+3;d.push(e);return e};
function Ii(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Bb(b)}}
l.Bb=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=function(){}):(c&&mb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
l.cb=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];Ji(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.Bb(c)}}return 0!=e}return!1};
function Ji(a,b,c){wf(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.Bb,this),delete this.j[a])}else this.i.length=0,this.j={}};
l.L=function(){Hi.ta.L.call(this);this.clear();this.l.length=0};function Ki(a){this.h=a}
Ki.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Eg(b))};
Ki.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Ki.prototype.remove=function(a){this.h.remove(a)};function Li(a){this.h=a}
ab(Li,Ki);function Mi(a){this.data=a}
function Ni(a){return void 0===a||a instanceof Mi?a:new Mi(a)}
Li.prototype.set=function(a,b){Li.ta.set.call(this,a,Ni(b))};
Li.prototype.i=function(a){a=Li.ta.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Li.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Oi(a){this.h=a}
ab(Oi,Li);Oi.prototype.set=function(a,b,c){if(b=Ni(b)){if(c){if(c<Date.now()){Oi.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Oi.ta.set.call(this,a,b)};
Oi.prototype.i=function(a){var b=Oi.ta.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Oi.prototype.remove.call(this,a);else return b}};function Pi(){}
;function Qi(){}
ab(Qi,Pi);Qi.prototype[Symbol.iterator]=function(){return zi(this.Ba(!0)).h()};
Qi.prototype.clear=function(){var a=Array.from(this);a=r(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Ri(a){this.h=a}
ab(Ri,Qi);l=Ri.prototype;l.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.h.removeItem(a)};
l.Ba=function(a){var b=0,c=this.h,d=new wi;d.next=function(){if(b>=c.length)return xi;var e=c.key(b++);if(a)return yi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return yi(e)};
return d};
l.clear=function(){this.h.clear()};
l.key=function(a){return this.h.key(a)};function Si(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
ab(Si,Ri);function Ti(a,b){this.i=a;this.h=null;var c;if(c=Hc)c=!(9<=Number(Xc));if(c){Ui||(Ui=new Di);this.h=Ui.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Ui.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
ab(Ti,Qi);var Vi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Ui=null;function Wi(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Vi[b]})}
l=Ti.prototype;l.isAvailable=function(){return!!this.h};
l.set=function(a,b){this.h.setAttribute(Wi(a),b);Xi(this)};
l.get=function(a){a=this.h.getAttribute(Wi(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.h.removeAttribute(Wi(a));Xi(this)};
l.Ba=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new wi;d.next=function(){if(b>=c.length)return xi;var e=c[b++];if(a)return yi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return yi(e)};
return d};
l.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Xi(this)};
function Xi(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Yi(a,b){this.i=a;this.h=b+"::"}
ab(Yi,Qi);Yi.prototype.set=function(a,b){this.i.set(this.h+a,b)};
Yi.prototype.get=function(a){return this.i.get(this.h+a)};
Yi.prototype.remove=function(a){this.i.remove(this.h+a)};
Yi.prototype.Ba=function(a){var b=this.i[Symbol.iterator](),c=this,d=new wi;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return yi(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var K={},Zi="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;K.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
K.Sc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var $i={ob:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
od:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},aj={ob:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
od:function(a){return[].concat.apply([],a)}};
K.Ze=function(){Zi?(K.bb=Uint8Array,K.Fa=Uint16Array,K.Ud=Int32Array,K.assign(K,$i)):(K.bb=Array,K.Fa=Array,K.Ud=Array,K.assign(K,aj))};
K.Ze();var bj=!0;try{new Uint8Array(1)}catch(a){bj=!1}for(var cj=new K.bb(256),dj=0;256>dj;dj++)cj[dj]=252<=dj?6:248<=dj?5:240<=dj?4:224<=dj?3:192<=dj?2:1;cj[254]=cj[254]=1;
function ej(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new K.bb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var fj={};fj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var gj={},hj,ij=[],jj=0;256>jj;jj++){hj=jj;for(var kj=0;8>kj;kj++)hj=hj&1?3988292384^hj>>>1:hj>>>1;ij[jj]=hj}gj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^ij[(a^b[d])&255];return a^-1};var lj={};lj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function mj(a){for(var b=a.length;0<=--b;)a[b]=0}
var nj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],oj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],pj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],qj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],rj=Array(576);mj(rj);var sj=Array(60);mj(sj);var tj=Array(512);mj(tj);var uj=Array(256);mj(uj);var vj=Array(29);mj(vj);var wj=Array(30);mj(wj);function xj(a,b,c,d,e){this.Md=a;this.oe=b;this.ne=c;this.je=d;this.Fe=e;this.sd=a&&a.length}
var yj,zj,Aj;function Bj(a,b){this.md=a;this.vb=0;this.Wa=b}
function Cj(a,b){a.S[a.pending++]=b&255;a.S[a.pending++]=b>>>8&255}
function Dj(a,b,c){a.ba>16-c?(a.ha|=b<<a.ba&65535,Cj(a,a.ha),a.ha=b>>16-a.ba,a.ba+=c-16):(a.ha|=b<<a.ba&65535,a.ba+=c)}
function Ej(a,b,c){Dj(a,c[2*b],c[2*b+1])}
function Fj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function Gj(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=Fj(d[e]++,e))}
function Hj(a){var b;for(b=0;286>b;b++)a.ja[2*b]=0;for(b=0;30>b;b++)a.gb[2*b]=0;for(b=0;19>b;b++)a.ca[2*b]=0;a.ja[512]=1;a.Na=a.yb=0;a.ra=a.matches=0}
function Ij(a){8<a.ba?Cj(a,a.ha):0<a.ba&&(a.S[a.pending++]=a.ha);a.ha=0;a.ba=0}
function Jj(a,b,c){Ij(a);Cj(a,c);Cj(a,~c);K.ob(a.S,a.window,b,c,a.pending);a.pending+=c}
function Kj(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Lj(a,b,c){for(var d=a.U[c],e=c<<1;e<=a.Ka;){e<a.Ka&&Kj(b,a.U[e+1],a.U[e],a.depth)&&e++;if(Kj(b,d,a.U[e],a.depth))break;a.U[c]=a.U[e];c=e;e<<=1}a.U[c]=d}
function Mj(a,b,c){var d=0;if(0!==a.ra){do{var e=a.S[a.Eb+2*d]<<8|a.S[a.Eb+2*d+1];var f=a.S[a.Hc+d];d++;if(0===e)Ej(a,f,b);else{var g=uj[f];Ej(a,g+256+1,b);var h=nj[g];0!==h&&(f-=vj[g],Dj(a,f,h));e--;g=256>e?tj[e]:tj[256+(e>>>7)];Ej(a,g,c);h=oj[g];0!==h&&(e-=wj[g],Dj(a,e,h))}}while(d<a.ra)}Ej(a,256,b)}
function Nj(a,b){var c=b.md,d=b.Wa.Md,e=b.Wa.sd,f=b.Wa.je,g,h=-1;a.Ka=0;a.sb=573;for(g=0;g<f;g++)0!==c[2*g]?(a.U[++a.Ka]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Ka;){var k=a.U[++a.Ka]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.Na--;e&&(a.yb-=d[2*k+1])}b.vb=h;for(g=a.Ka>>1;1<=g;g--)Lj(a,c,g);k=f;do g=a.U[1],a.U[1]=a.U[a.Ka--],Lj(a,c,1),d=a.U[1],a.U[--a.sb]=g,a.U[--a.sb]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.U[1]=k++,Lj(a,c,1);while(2<=a.Ka);a.U[--a.sb]=
a.U[1];g=b.md;k=b.vb;d=b.Wa.Md;e=b.Wa.sd;f=b.Wa.oe;var m=b.Wa.ne,n=b.Wa.Fe,p,v=0;for(p=0;15>=p;p++)a.Ga[p]=0;g[2*a.U[a.sb]+1]=0;for(b=a.sb+1;573>b;b++){var t=a.U[b];p=g[2*g[2*t+1]+1]+1;p>n&&(p=n,v++);g[2*t+1]=p;if(!(t>k)){a.Ga[p]++;var y=0;t>=m&&(y=f[t-m]);var D=g[2*t];a.Na+=D*(p+y);e&&(a.yb+=D*(d[2*t+1]+y))}}if(0!==v){do{for(p=n-1;0===a.Ga[p];)p--;a.Ga[p]--;a.Ga[p+1]+=2;a.Ga[n]--;v-=2}while(0<v);for(p=n;0!==p;p--)for(t=a.Ga[p];0!==t;)d=a.U[--b],d>k||(g[2*d+1]!==p&&(a.Na+=(p-g[2*d+1])*g[2*d],g[2*
d+1]=p),t--)}Gj(c,h,a.Ga)}
function Oj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];++g<h&&m===f||(g<k?a.ca[2*m]+=g:0!==m?(m!==e&&a.ca[2*m]++,a.ca[32]++):10>=g?a.ca[34]++:a.ca[36]++,g=0,e=m,0===f?(h=138,k=3):m===f?(h=6,k=3):(h=7,k=4))}}
function Pj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];if(!(++g<h&&m===f)){if(g<k){do Ej(a,m,a.ca);while(0!==--g)}else 0!==m?(m!==e&&(Ej(a,m,a.ca),g--),Ej(a,16,a.ca),Dj(a,g-3,2)):10>=g?(Ej(a,17,a.ca),Dj(a,g-3,3)):(Ej(a,18,a.ca),Dj(a,g-11,7));g=0;e=m;0===f?(h=138,k=3):m===f?(h=6,k=3):(h=7,k=4)}}}
function Qj(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.ja[2*c])return 0;if(0!==a.ja[18]||0!==a.ja[20]||0!==a.ja[26])return 1;for(c=32;256>c;c++)if(0!==a.ja[2*c])return 1;return 0}
var Rj=!1;function Sj(a,b,c){a.S[a.Eb+2*a.ra]=b>>>8&255;a.S[a.Eb+2*a.ra+1]=b&255;a.S[a.Hc+a.ra]=c&255;a.ra++;0===b?a.ja[2*c]++:(a.matches++,b--,a.ja[2*(uj[c]+256+1)]++,a.gb[2*(256>b?tj[b]:tj[256+(b>>>7)])]++);return a.ra===a.Kb-1}
;function Tj(a,b){a.msg=lj[b];return b}
function Uj(a){for(var b=a.length;0<=--b;)a[b]=0}
function Vj(a){var b=a.state,c=b.pending;c>a.I&&(c=a.I);0!==c&&(K.ob(a.Lb,b.S,b.Mb,c,a.wb),a.wb+=c,b.Mb+=c,a.Tc+=c,a.I-=c,b.pending-=c,0===b.pending&&(b.Mb=0))}
function Wj(a,b){var c=0<=a.la?a.la:-1,d=a.o-a.la,e=0;if(0<a.level){2===a.F.wc&&(a.F.wc=Qj(a));Nj(a,a.kc);Nj(a,a.fc);Oj(a,a.ja,a.kc.vb);Oj(a,a.gb,a.fc.vb);Nj(a,a.dd);for(e=18;3<=e&&0===a.ca[2*qj[e]+1];e--);a.Na+=3*(e+1)+14;var f=a.Na+3+7>>>3;var g=a.yb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)Dj(a,b?1:0,3),Jj(a,c,d);else if(4===a.strategy||g===f)Dj(a,2+(b?1:0),3),Mj(a,rj,sj);else{Dj(a,4+(b?1:0),3);c=a.kc.vb+1;d=a.fc.vb+1;e+=1;Dj(a,c-257,5);Dj(a,d-1,5);Dj(a,e-4,4);for(f=0;f<e;f++)Dj(a,a.ca[2*
qj[f]+1],3);Pj(a,a.ja,c-1);Pj(a,a.gb,d-1);Mj(a,a.ja,a.gb)}Hj(a);b&&Ij(a);a.la=a.o;Vj(a.F)}
function L(a,b){a.S[a.pending++]=b}
function Xj(a,b){a.S[a.pending++]=b>>>8&255;a.S[a.pending++]=b&255}
function Yj(a,b){var c=a.yd,d=a.o,e=a.na,f=a.Ad,g=a.o>a.ea-262?a.o-(a.ea-262):0,h=a.window,k=a.Ya,m=a.Ea,n=a.o+258,p=h[d+e-1],v=h[d+e];a.na>=a.rd&&(c>>=2);f>a.u&&(f=a.u);do{var t=b;if(h[t+e]===v&&h[t+e-1]===p&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<n;);t=258-(n-d);d=n-258;if(t>e){a.ub=b;e=t;if(t>=f)break;p=h[d+e-1];v=h[d+e]}}}while((b=m[b&k])>g&&0!==--c);return e<=
a.u?e:a.u}
function Zj(a){var b=a.ea,c;do{var d=a.Sd-a.u-a.o;if(a.o>=b+(b-262)){K.ob(a.window,a.window,b,b,0);a.ub-=b;a.o-=b;a.la-=b;var e=c=a.jc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ea[--e],a.Ea[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.F.ga)break;e=a.F;c=a.window;f=a.o+a.u;var g=e.ga;g>d&&(g=d);0===g?c=0:(e.ga-=g,K.ob(c,e.input,e.jb,g,f),1===e.state.wrap?e.C=fj(e.C,c,g,f):2===e.state.wrap&&(e.C=gj(e.C,c,g,f)),e.jb+=g,e.mb+=g,c=g);a.u+=c;if(3<=a.u+a.ka)for(d=a.o-a.ka,a.H=a.window[d],
a.H=(a.H<<a.Ja^a.window[d+1])&a.Ia;a.ka&&!(a.H=(a.H<<a.Ja^a.window[d+3-1])&a.Ia,a.Ea[d&a.Ya]=a.head[a.H],a.head[a.H]=d,d++,a.ka--,3>a.u+a.ka););}while(262>a.u&&0!==a.F.ga)}
function ak(a,b){for(var c;;){if(262>a.u){Zj(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.H=(a.H<<a.Ja^a.window[a.o+3-1])&a.Ia,c=a.Ea[a.o&a.Ya]=a.head[a.H],a.head[a.H]=a.o);0!==c&&a.o-c<=a.ea-262&&(a.J=Yj(a,c));if(3<=a.J)if(c=Sj(a,a.o-a.ub,a.J-3),a.u-=a.J,a.J<=a.Ic&&3<=a.u){a.J--;do a.o++,a.H=(a.H<<a.Ja^a.window[a.o+3-1])&a.Ia,a.Ea[a.o&a.Ya]=a.head[a.H],a.head[a.H]=a.o;while(0!==--a.J);a.o++}else a.o+=a.J,a.J=0,a.H=a.window[a.o],a.H=(a.H<<a.Ja^a.window[a.o+1])&a.Ia;else c=Sj(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(Wj(a,!1),0===a.F.I))return 1}a.ka=2>a.o?a.o:2;return 4===b?(Wj(a,!0),0===a.F.I?3:4):a.ra&&(Wj(a,!1),0===a.F.I)?1:2}
function bk(a,b){for(var c,d;;){if(262>a.u){Zj(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.H=(a.H<<a.Ja^a.window[a.o+3-1])&a.Ia,c=a.Ea[a.o&a.Ya]=a.head[a.H],a.head[a.H]=a.o);a.na=a.J;a.Dd=a.ub;a.J=2;0!==c&&a.na<a.Ic&&a.o-c<=a.ea-262&&(a.J=Yj(a,c),5>=a.J&&(1===a.strategy||3===a.J&&4096<a.o-a.ub)&&(a.J=2));if(3<=a.na&&a.J<=a.na){d=a.o+a.u-3;c=Sj(a,a.o-1-a.Dd,a.na-3);a.u-=a.na-1;a.na-=2;do++a.o<=d&&(a.H=(a.H<<a.Ja^a.window[a.o+3-1])&a.Ia,a.Ea[a.o&a.Ya]=a.head[a.H],a.head[a.H]=a.o);
while(0!==--a.na);a.hb=0;a.J=2;a.o++;if(c&&(Wj(a,!1),0===a.F.I))return 1}else if(a.hb){if((c=Sj(a,0,a.window[a.o-1]))&&Wj(a,!1),a.o++,a.u--,0===a.F.I)return 1}else a.hb=1,a.o++,a.u--}a.hb&&(Sj(a,0,a.window[a.o-1]),a.hb=0);a.ka=2>a.o?a.o:2;return 4===b?(Wj(a,!0),0===a.F.I?3:4):a.ra&&(Wj(a,!1),0===a.F.I)?1:2}
function ck(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){Zj(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.J=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.J=258-(e-d);a.J>a.u&&(a.J=a.u)}3<=a.J?(c=Sj(a,1,a.J-3),a.u-=a.J,a.o+=a.J,a.J=0):(c=Sj(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(Wj(a,!1),0===a.F.I))return 1}a.ka=0;return 4===b?(Wj(a,!0),0===a.F.I?3:4):
a.ra&&(Wj(a,!1),0===a.F.I)?1:2}
function dk(a,b){for(var c;;){if(0===a.u&&(Zj(a),0===a.u)){if(0===b)return 1;break}a.J=0;c=Sj(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(Wj(a,!1),0===a.F.I))return 1}a.ka=0;return 4===b?(Wj(a,!0),0===a.F.I?3:4):a.ra&&(Wj(a,!1),0===a.F.I)?1:2}
function ek(a,b,c,d,e){this.ue=a;this.Ee=b;this.Ie=c;this.De=d;this.qe=e}
var fk;fk=[new ek(0,0,0,0,function(a,b){var c=65535;for(c>a.sa-5&&(c=a.sa-5);;){if(1>=a.u){Zj(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.la+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,Wj(a,!1),0===a.F.I)return 1;if(a.o-a.la>=a.ea-262&&(Wj(a,!1),0===a.F.I))return 1}a.ka=0;if(4===b)return Wj(a,!0),0===a.F.I?3:4;a.o>a.la&&Wj(a,!1);return 1}),
new ek(4,4,8,4,ak),new ek(4,5,16,8,ak),new ek(4,6,32,32,ak),new ek(4,4,16,16,bk),new ek(8,16,32,32,bk),new ek(8,16,128,128,bk),new ek(8,32,128,256,bk),new ek(32,128,258,1024,bk),new ek(32,258,258,4096,bk)];
function gk(){this.F=null;this.status=0;this.S=null;this.wrap=this.pending=this.Mb=this.sa=0;this.B=null;this.va=0;this.method=8;this.tb=-1;this.Ya=this.Vc=this.ea=0;this.window=null;this.Sd=0;this.head=this.Ea=null;this.Ad=this.rd=this.strategy=this.level=this.Ic=this.yd=this.na=this.u=this.ub=this.o=this.hb=this.Dd=this.J=this.la=this.Ja=this.Ia=this.Cc=this.jc=this.H=0;this.ja=new K.Fa(1146);this.gb=new K.Fa(122);this.ca=new K.Fa(78);Uj(this.ja);Uj(this.gb);Uj(this.ca);this.dd=this.fc=this.kc=
null;this.Ga=new K.Fa(16);this.U=new K.Fa(573);Uj(this.U);this.sb=this.Ka=0;this.depth=new K.Fa(573);Uj(this.depth);this.ba=this.ha=this.ka=this.matches=this.yb=this.Na=this.Eb=this.ra=this.Kb=this.Hc=0}
function hk(a,b){if(!a||!a.state||5<b||0>b)return a?Tj(a,-2):-2;var c=a.state;if(!a.Lb||!a.input&&0!==a.ga||666===c.status&&4!==b)return Tj(a,0===a.I?-5:-2);c.F=a;var d=c.tb;c.tb=b;if(42===c.status)if(2===c.wrap)a.C=0,L(c,31),L(c,139),L(c,8),c.B?(L(c,(c.B.text?1:0)+(c.B.Sa?2:0)+(c.B.Ra?4:0)+(c.B.name?8:0)+(c.B.comment?16:0)),L(c,c.B.time&255),L(c,c.B.time>>8&255),L(c,c.B.time>>16&255),L(c,c.B.time>>24&255),L(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),L(c,c.B.os&255),c.B.Ra&&c.B.Ra.length&&(L(c,
c.B.Ra.length&255),L(c,c.B.Ra.length>>8&255)),c.B.Sa&&(a.C=gj(a.C,c.S,c.pending,0)),c.va=0,c.status=69):(L(c,0),L(c,0),L(c,0),L(c,0),L(c,0),L(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),L(c,3),c.status=113);else{var e=8+(c.Vc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;Xj(c,e+(31-e%31));0!==c.o&&(Xj(c,a.C>>>16),Xj(c,a.C&65535));a.C=1}if(69===c.status)if(c.B.Ra){for(e=c.pending;c.va<(c.B.Ra.length&65535)&&(c.pending!==c.sa||(c.B.Sa&&c.pending>
e&&(a.C=gj(a.C,c.S,c.pending-e,e)),Vj(a),e=c.pending,c.pending!==c.sa));)L(c,c.B.Ra[c.va]&255),c.va++;c.B.Sa&&c.pending>e&&(a.C=gj(a.C,c.S,c.pending-e,e));c.va===c.B.Ra.length&&(c.va=0,c.status=73)}else c.status=73;if(73===c.status)if(c.B.name){e=c.pending;do{if(c.pending===c.sa&&(c.B.Sa&&c.pending>e&&(a.C=gj(a.C,c.S,c.pending-e,e)),Vj(a),e=c.pending,c.pending===c.sa)){var f=1;break}f=c.va<c.B.name.length?c.B.name.charCodeAt(c.va++)&255:0;L(c,f)}while(0!==f);c.B.Sa&&c.pending>e&&(a.C=gj(a.C,c.S,c.pending-
e,e));0===f&&(c.va=0,c.status=91)}else c.status=91;if(91===c.status)if(c.B.comment){e=c.pending;do{if(c.pending===c.sa&&(c.B.Sa&&c.pending>e&&(a.C=gj(a.C,c.S,c.pending-e,e)),Vj(a),e=c.pending,c.pending===c.sa)){f=1;break}f=c.va<c.B.comment.length?c.B.comment.charCodeAt(c.va++)&255:0;L(c,f)}while(0!==f);c.B.Sa&&c.pending>e&&(a.C=gj(a.C,c.S,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.B.Sa?(c.pending+2>c.sa&&Vj(a),c.pending+2<=c.sa&&(L(c,a.C&255),L(c,a.C>>8&255),a.C=0,
c.status=113)):c.status=113);if(0!==c.pending){if(Vj(a),0===a.I)return c.tb=-1,0}else if(0===a.ga&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return Tj(a,-5);if(666===c.status&&0!==a.ga)return Tj(a,-5);if(0!==a.ga||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?dk(c,b):3===c.strategy?ck(c,b):fk[c.level].qe(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.I&&(c.tb=-1),0;if(2===d&&(1===b?(Dj(c,2,3),Ej(c,256,rj),16===c.ba?(Cj(c,c.ha),c.ha=0,c.ba=0):8<=c.ba&&(c.S[c.pending++]=c.ha&255,
c.ha>>=8,c.ba-=8)):5!==b&&(Dj(c,0,3),Jj(c,0,0),3===b&&(Uj(c.head),0===c.u&&(c.o=0,c.la=0,c.ka=0))),Vj(a),0===a.I))return c.tb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(L(c,a.C&255),L(c,a.C>>8&255),L(c,a.C>>16&255),L(c,a.C>>24&255),L(c,a.mb&255),L(c,a.mb>>8&255),L(c,a.mb>>16&255),L(c,a.mb>>24&255)):(Xj(c,a.C>>>16),Xj(c,a.C&65535));Vj(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var ik={};ik=function(){this.input=null;this.mb=this.ga=this.jb=0;this.Lb=null;this.Tc=this.I=this.wb=0;this.msg="";this.state=null;this.wc=2;this.C=0};var jk=Object.prototype.toString;
function kk(a){if(!(this instanceof kk))return new kk(a);a=this.options=K.assign({level:-1,method:8,chunkSize:16384,Za:15,Ge:8,strategy:0,K:""},a||{});a.raw&&0<a.Za?a.Za=-a.Za:a.we&&0<a.Za&&16>a.Za&&(a.Za+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.F=new ik;this.F.I=0;var b=this.F;var c=a.level,d=a.method,e=a.Za,f=a.Ge,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=Tj(b,-2);else{8===e&&(e=9);var k=new gk;
b.state=k;k.F=b;k.wrap=h;k.B=null;k.Vc=e;k.ea=1<<k.Vc;k.Ya=k.ea-1;k.Cc=f+7;k.jc=1<<k.Cc;k.Ia=k.jc-1;k.Ja=~~((k.Cc+3-1)/3);k.window=new K.bb(2*k.ea);k.head=new K.Fa(k.jc);k.Ea=new K.Fa(k.ea);k.Kb=1<<f+6;k.sa=4*k.Kb;k.S=new K.bb(k.sa);k.Eb=1*k.Kb;k.Hc=3*k.Kb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.mb=b.Tc=0;b.wc=2;c=b.state;c.pending=0;c.Mb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.C=2===c.wrap?0:1;c.tb=0;if(!Rj){d=Array(16);for(f=g=0;28>f;f++)for(vj[f]=g,e=0;e<1<<nj[f];e++)uj[g++]=
f;uj[g-1]=f;for(f=g=0;16>f;f++)for(wj[f]=g,e=0;e<1<<oj[f];e++)tj[g++]=f;for(g>>=7;30>f;f++)for(wj[f]=g<<7,e=0;e<1<<oj[f]-7;e++)tj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)rj[2*e+1]=8,e++,d[8]++;for(;255>=e;)rj[2*e+1]=9,e++,d[9]++;for(;279>=e;)rj[2*e+1]=7,e++,d[7]++;for(;287>=e;)rj[2*e+1]=8,e++,d[8]++;Gj(rj,287,d);for(e=0;30>e;e++)sj[2*e+1]=5,sj[2*e]=Fj(e,5);yj=new xj(rj,nj,257,286,15);zj=new xj(sj,oj,0,30,15);Aj=new xj([],pj,0,19,7);Rj=!0}c.kc=new Bj(c.ja,yj);c.fc=new Bj(c.gb,zj);c.dd=
new Bj(c.ca,Aj);c.ha=0;c.ba=0;Hj(c);c=0}else c=Tj(b,-2);0===c&&(b=b.state,b.Sd=2*b.ea,Uj(b.head),b.Ic=fk[b.level].Ee,b.rd=fk[b.level].ue,b.Ad=fk[b.level].Ie,b.yd=fk[b.level].De,b.o=0,b.la=0,b.u=0,b.ka=0,b.J=b.na=2,b.hb=0,b.H=0);b=c}}else b=-2;if(0!==b)throw Error(lj[b]);a.header&&(b=this.F)&&b.state&&2===b.state.wrap&&(b.state.B=a.header);if(a.Fb){var m;"string"===typeof a.Fb?m=ej(a.Fb):"[object ArrayBuffer]"===jk.call(a.Fb)?m=new Uint8Array(a.Fb):m=a.Fb;a=this.F;f=m;g=f.length;if(a&&a.state)if(m=
a.state,b=m.wrap,2===b||1===b&&42!==m.status||m.u)b=-2;else{1===b&&(a.C=fj(a.C,f,g,0));m.wrap=0;g>=m.ea&&(0===b&&(Uj(m.head),m.o=0,m.la=0,m.ka=0),c=new K.bb(m.ea),K.ob(c,f,g-m.ea,m.ea,0),f=c,g=m.ea);c=a.ga;d=a.jb;e=a.input;a.ga=g;a.jb=0;a.input=f;for(Zj(m);3<=m.u;){f=m.o;g=m.u-2;do m.H=(m.H<<m.Ja^m.window[f+3-1])&m.Ia,m.Ea[f&m.Ya]=m.head[m.H],m.head[m.H]=f,f++;while(--g);m.o=f;m.u=2;Zj(m)}m.o+=m.u;m.la=m.o;m.ka=m.u;m.u=0;m.J=m.na=2;m.hb=0;a.jb=d;a.input=e;a.ga=c;m.wrap=b;b=0}else b=-2;if(0!==b)throw Error(lj[b]);
this.Bt=!0}}
kk.prototype.push=function(a,b){var c=this.F,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=ej(a):"[object ArrayBuffer]"===jk.call(a)?c.input=new Uint8Array(a):c.input=a;c.jb=0;c.ga=c.input.length;do{0===c.I&&(c.Lb=new K.bb(d),c.wb=0,c.I=d);a=hk(c,e);if(1!==a&&0!==a)return lk(this,a),this.ended=!0,!1;if(0===c.I||0===c.ga&&(4===e||2===e))if("string"===this.options.K){var f=K.Sc(c.Lb,c.wb);b=f;f=f.length;if(65537>f&&(b.subarray&&bj||!b.subarray))b=
String.fromCharCode.apply(null,K.Sc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=K.Sc(c.Lb,c.wb),this.chunks.push(b)}while((0<c.ga||0===c.I)&&1!==a);if(4===e)return(c=this.F)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=Tj(c,-2):(c.state=null,a=113===d?Tj(c,-3):0)):a=-2,lk(this,a),this.ended=!0,0===a;2===e&&(lk(this,0),c.I=0);return!0};
function lk(a,b){0===b&&(a.result="string"===a.options.K?a.chunks.join(""):K.od(a.chunks));a.chunks=[];a.err=b;a.msg=a.F.msg}
;function mk(a){return Kb(null===a?"null":void 0===a?"undefined":a)}
;function nk(a){this.name=a}
;var ok=new nk("rawColdConfigGroup");var pk=new nk("rawHotConfigGroup");function qk(a){H.call(this,a)}
u(qk,H);function rk(a){H.call(this,a)}
u(rk,H);rk.prototype.getKey=function(){return Zd(this,1)};
rk.prototype.getValue=function(){return Zd(this,2===Md(this,sk)?2:-1)};
var sk=[2,3,4,5,6];function tk(a){H.call(this,a)}
u(tk,H);function uk(a){H.call(this,a)}
u(uk,H);function vk(a){H.call(this,a,-1,wk)}
u(vk,H);var wk=[2];function xk(a){H.call(this,a,-1,yk)}
u(xk,H);xk.prototype.getPlayerType=function(){return Hd(this,36)};
xk.prototype.setHomeGroupInfo=function(a){return G(this,vk,81,a)};
xk.prototype.clearLocationPlayabilityToken=function(){return F(this,89,void 0,!1)};
var yk=[9,66,24,32,86,100,101];function zk(a){H.call(this,a,-1,Ak)}
u(zk,H);var Ak=[15,26,28];function Bk(a){H.call(this,a,-1,Ck)}
u(Bk,H);var Ck=[5];function Dk(a){H.call(this,a)}
u(Dk,H);function Ek(a){H.call(this,a,-1,Fk)}
u(Ek,H);Ek.prototype.setSafetyMode=function(a){return F(this,5,a)};
var Fk=[12];function Gk(a){H.call(this,a,-1,Hk)}
u(Gk,H);Gk.prototype.j=function(a){return G(this,xk,1,a)};
var Hk=[12];var Ik=new nk("continuationCommand");var Jk=new nk("webCommandMetadata");var Kk=new nk("signalServiceEndpoint");var Lk={jk:"EMBEDDED_PLAYER_MODE_UNKNOWN",gk:"EMBEDDED_PLAYER_MODE_DEFAULT",ik:"EMBEDDED_PLAYER_MODE_PFP",hk:"EMBEDDED_PLAYER_MODE_PFL"};var Mk=new nk("feedbackEndpoint");var Nk={Xs:"WEB_DISPLAY_MODE_UNKNOWN",Ts:"WEB_DISPLAY_MODE_BROWSER",Vs:"WEB_DISPLAY_MODE_MINIMAL_UI",Ws:"WEB_DISPLAY_MODE_STANDALONE",Us:"WEB_DISPLAY_MODE_FULLSCREEN"};function Ok(a){H.call(this,a,-1,Pk)}
u(Ok,H);function Qk(a){H.call(this,a)}
u(Qk,H);Qk.prototype.getKey=function(){return Zd(this,1)};
Qk.prototype.getValue=function(){return Zd(this,2)};
var Pk=[4,5];function Rk(a){H.call(this,a)}
u(Rk,H);function Sk(a){H.call(this,a)}
u(Sk,H);var ml=[2,3,4];function nl(a){H.call(this,a)}
u(nl,H);nl.prototype.getMessage=function(){return Zd(this,1)};function ol(a){H.call(this,a)}
u(ol,H);function pl(a){H.call(this,a)}
u(pl,H);function ql(a){H.call(this,a,-1,rl)}
u(ql,H);var rl=[10,17];function sl(a){H.call(this,a)}
u(sl,H);function tl(a){H.call(this,a)}
u(tl,H);function ul(a){H.call(this,a)}
u(ul,H);function vl(a){H.call(this,a)}
u(vl,H);function wl(a){H.call(this,a)}
u(wl,H);function xl(a){H.call(this,a,-1,yl)}
u(xl,H);xl.prototype.getVideoData=function(){return Rd(this,wl,15)};
var yl=[4];function zl(a){H.call(this,a)}
u(zl,H);function Al(a,b){return G(a,ul,1,b)}
zl.prototype.h=function(a){return F(this,2,a)};
function Bl(a){H.call(this,a)}
u(Bl,H);function Cl(a,b){G(a,ul,1,b)}
;function Dl(a){H.call(this,a,-1,El)}
u(Dl,H);Dl.prototype.h=function(a){return F(this,1,a)};
function Fl(a,b){return G(a,ul,2,b)}
var El=[3];function Gl(a){H.call(this,a)}
u(Gl,H);Gl.prototype.h=function(a){return F(this,1,a)};function Hl(a){H.call(this,a)}
u(Hl,H);Hl.prototype.h=function(a){return F(this,1,a)};function Il(a){H.call(this,a)}
u(Il,H);Il.prototype.h=function(a){return F(this,1,a)};function Jl(a){H.call(this,a)}
u(Jl,H);Jl.prototype.h=function(a){return F(this,1,a)};function Kl(a){H.call(this,a)}
u(Kl,H);function Ll(a){H.call(this,a)}
u(Ll,H);function Ml(a){H.call(this,a,-1,Nl)}
u(Ml,H);Ml.prototype.getPlayerType=function(){return Yd(Hd(this,7),0)};
Ml.prototype.setVideoId=function(a){return F(this,19,a)};
function Ol(a,b){Xd(a,68,Pl,b)}
function Pl(a){H.call(this,a)}
u(Pl,H);Pl.prototype.getId=function(){return Zd(this,2)};
var Nl=[83,68];function Ql(a){H.call(this,a)}
u(Ql,H);function Rl(a){H.call(this,a)}
u(Rl,H);function Sl(a){H.call(this,a)}
u(Sl,H);function Tl(a){H.call(this,a,459)}
u(Tl,H);
var Ul=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,444,176,222,383,177,178,179,458,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,
351,352,353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117,439,441,448];var Vl={nl:0,Uk:1,al:2,bl:4,kl:8,dl:16,fl:32,ml:64,ll:128,Wk:256,Yk:512,jl:1024,Xk:2048,Zk:4096,Vk:8192,il:16384};function Wl(a){H.call(this,a)}
u(Wl,H);function Xl(a){H.call(this,a)}
u(Xl,H);Xl.prototype.setVideoId=function(a){return Ld(this,1,Yl,a)};
Xl.prototype.getPlaylistId=function(){var a=2===Md(this,Yl)?2:-1;return Hd(this,a)};
var Yl=[1,2];function Zl(a){H.call(this,a,-1,$l)}
u(Zl,H);var $l=[3];var am=new nk("webPlayerShareEntityServiceEndpoint");var bm=new nk("playlistEditEndpoint");var cm=new nk("modifyChannelNotificationPreferenceEndpoint");var dm=new nk("unsubscribeEndpoint");var em=new nk("subscribeEndpoint");function fm(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var gm=z.window,hm,im,jm=(null==gm?void 0:null==(hm=gm.yt)?void 0:hm.config_)||(null==gm?void 0:null==(im=gm.ytcfg)?void 0:im.data_)||{};A("yt.config_",jm);function km(){fm(jm,arguments)}
function M(a,b){return a in jm?jm[a]:b}
function lm(){var a=jm.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;function P(a){a=mm(a);return"string"===typeof a&&"false"===a?!1:!!a}
function nm(a,b){a=mm(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function om(){return M("EXPERIMENTS_TOKEN","")}
function mm(a){var b=M("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:M("EXPERIMENT_FLAGS",{})[a]}
function pm(){for(var a=[],b=M("EXPERIMENTS_FORCED_FLAGS",{}),c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=M("EXPERIMENT_FLAGS",{});var e=r(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;function qm(){var a=rm;B("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a)}
function sm(a){A("yt.ads.biscotti.lastId_",a)}
;var tm=[];function um(a){tm.forEach(function(b){return b(a)})}
function vm(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){wm(b)}}:a}
function wm(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=M("ERRORS",[]),e.push([a,"ERROR",b,c,d]),km("ERRORS",e));um(a)}
function xm(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=M("ERRORS",[]),e.push([a,"WARNING",b,c,d]),km("ERRORS",e))}
;var ym=/^[\w.]*$/,zm={q:!0,search_query:!0};function Am(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Bm(f[0]||""),h=Bm(f[1]||"");g in c?Array.isArray(c[g])?nb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,m=f[0],n=String(Am);k.args=[{key:m,value:f[1],query:a,method:Cm==n?"unchanged":n}];zm.hasOwnProperty(m)||xm(k)}}return c}
var Cm=String(Am);function Dm(a){var b=[];ob(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];hb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Em(a){"?"==a.charAt(0)&&(a=a.substr(1));return Am(a,"&")}
function Fm(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Em(1<a.length?a[1]:a[0])):{}}
function Gm(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Em(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return wc(a,e)+d}
function Hm(a){if(!b)var b=window.location.href;var c=oc(1,a),d=pc(a);c&&d?(a=a.match(kc),b=b.match(kc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?pc(b)==d&&(Number(oc(4,b))||null)==(Number(oc(4,a))||null):!0;return a}
function Bm(a){return a&&a.match(ym)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Im(a){var b=Jm;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=ci;e.flash="0";a:{try{var f=b.h.top.location.href}catch(ha){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Jh:g;try{var h=g.history.length}catch(ha){h=0}e.u_his=h;var k;e.u_h=null==(k=Jh.screen)?void 0:k.height;var m;e.u_w=null==(m=Jh.screen)?void 0:m.width;var n;e.u_ah=null==(n=Jh.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=Jh.screen)?void 0:p.availWidth;var v;e.u_cd=null==(v=Jh.screen)?void 0:v.colorDepth}catch(ha){}h=b.h;try{var t=h.screenX;var y=h.screenY}catch(ha){}try{var D=h.outerWidth;var E=h.outerHeight}catch(ha){}try{var O=h.innerWidth;var N=h.innerHeight}catch(ha){}try{var S=h.screenLeft;var aa=h.screenTop}catch(ha){}try{O=h.innerWidth,N=h.innerHeight}catch(ha){}try{var W=h.screen.availWidth;var xb=h.screen.availTop}catch(ha){}t=[S,aa,t,y,W,xb,D,E,O,N];try{var Za=(b.h.top||window).document,qa="CSS1Compat"==
Za.compatMode?Za.documentElement:Za.body;var I=(new kf(qa.clientWidth,qa.clientHeight)).round()}catch(ha){I=new kf(-12245933,-12245933)}Za=I;I={};var oa=void 0===oa?z:oa;qa=new li;oa.SVGElement&&oa.document.createElementNS&&qa.set(0);y=$h();y["allow-top-navigation-by-user-activation"]&&qa.set(1);y["allow-popups-to-escape-sandbox"]&&qa.set(2);oa.crypto&&oa.crypto.subtle&&qa.set(3);oa.TextDecoder&&oa.TextEncoder&&qa.set(4);oa=mi(qa);I.bc=oa;I.bih=Za.height;I.biw=Za.width;I.brdim=t.join();b=b.i;b=(I.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,I.wgl=!!Jh.WebGLRenderingContext,I);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Jm=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return Dm(Im(a))});Date.now();var Km="XMLHttpRequest"in z?function(){return new XMLHttpRequest}:null;
function Lm(){if(!Km)return null;var a=Km();return"open"in a?a:null}
function Mm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Nm(a,b){"function"===typeof a&&(a=vm(a));return window.setTimeout(a,b)}
;var Om={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},Pm="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ja(di)),Qm=!1;
function Rm(a,b){b=void 0===b?{}:b;var c=Hm(a),d=P("web_ajax_ignore_global_headers_if_set"),e;for(e in Om){var f=M(Om[e]);"X-Goog-Visitor-Id"!==e||f||(f=M("VISITOR_DATA"));!f||!c&&pc(a)||d&&void 0!==b[e]||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!pc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!pc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}document.location.hostname.endsWith("youtubeeducation.com")||
!c&&pc(a)||(b["X-YouTube-Ad-Signals"]=Dm(Im()));return b}
function Sm(a){var b=window.location.search,c=pc(a);P("debug_handle_relative_url_for_query_forward_killswitch")||!c&&Hm(a)&&(c=document.location.hostname);var d=lc(oc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Em(b),f={};hb(Pm,function(g){e[g]&&(f[g]=e[g])});
return Gm(a,f||{},!1)}
function Tm(a,b){var c=b.format||"JSON";a=Um(a,b);var d=Vm(a,b),e=!1,f=Wm(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var m=Mm(k),n=null,p=400<=k.status&&500>k.status,v=500<=k.status&&600>k.status;if(m||p||v)n=Xm(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(n&&n.return_code,10);break a;case "RAW":m=!0;break a}m=!!n}n=n||{};p=b.context||z;m?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,
k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Nm(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||z,f))},d)}return f}
function Um(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=M("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Gm(a,b||{},!0);return a}
function Vm(a,b){var c=M("XSRF_FIELD_NAME"),d=M("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=M("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||pc(a)&&!b.withCredentials&&pc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(P("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Em(e),zb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):uc(e));f=e||f&&!rb(f);!Qm&&f&&"POST"!=b.method&&(Qm=!0,wm(Error("AJAX request with postData should use POST")));return e}
function Xm(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,xm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Ym(a):null)e={},hb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Zm(g)})}d&&$m(e);
return e}
function $m(a){if(Sa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=Bb();d=e?e.createHTML(d):d;a[c]=new dc(d)}else $m(a[b])}}
function Ym(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Zm(a){var b="";hb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function an(a,b){b.method="POST";b.postParams||(b.postParams={});return Tm(a,b)}
function Wm(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&vm(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Lm();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;P("debug_forward_web_query_parameters")&&(a=Sm(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Rm(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var bn=Yc||Zc;function cn(a){var b=Ub();return b?0<=b.toLowerCase().indexOf(a):!1}
;var dn=[{Jc:function(a){return"Cannot read property '"+a.key+"'"},
mc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Jc:function(a){return"Cannot call '"+a.key+"'"},
mc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Jc:function(a){return a.key+" is not defined"},
mc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var fn={Ua:[],Qa:[{callback:en,weight:500}]};function en(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function gn(){this.Qa=[];this.Ua=[]}
var hn;function jn(){if(!hn){var a=hn=new gn;a.Ua.length=0;a.Qa.length=0;fn.Ua&&a.Ua.push.apply(a.Ua,fn.Ua);fn.Qa&&a.Qa.push.apply(a.Qa,fn.Qa)}return hn}
;var kn=new Hi;function ln(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=mn(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=mn(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=mn(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function mn(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function nn(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=on(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=ln(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?on(e+".ve",f,g,h):0;d+=g;d+=on(e,a[e],b,c);if(500<d)break}}else c[b]=pn(a),d+=c[b].length;else c[b]=pn(a),d+=c[b].length;return d}
function on(a,b,c,d){c+="."+a;a=pn(b);d[c]=a;return c.length+a.length}
function pn(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function qn(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function rn(){if(!z.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return z.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":z.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":z.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":z.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function sn(a,b,c,d,e){wg.set(""+a,b,{lc:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function tn(a,b,c){wg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function un(){if(!wg.isEnabled())return!1;if(!wg.Jb())return!0;wg.set("TESTCOOKIESENABLED","1",{lc:60});if("1"!==wg.get("TESTCOOKIESENABLED"))return!1;wg.remove("TESTCOOKIESENABLED");return!0}
;var vn=B("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",vn);function wn(){this.h=M("ALT_PREF_COOKIE_NAME","PREF");this.i=M("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=wg.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(vn[d]=c.toString())}}}
wn.prototype.get=function(a,b){xn(a);yn(a);a=void 0!==vn[a]?vn[a].toString():null;return null!=a?a:b?b:""};
wn.prototype.set=function(a,b){xn(a);yn(a);if(null==b)throw Error("ExpectedNotNull");vn[a]=b.toString()};
function zn(a){return!!((An("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
wn.prototype.remove=function(a){xn(a);yn(a);delete vn[a]};
wn.prototype.clear=function(){for(var a in vn)delete vn[a]};
function yn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function xn(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function An(a){a=void 0!==vn[a]?vn[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Pa(wn);var Bn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Cn={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Dn={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},En={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Fn(){var a=z.navigator;return a?a.connection:void 0}
function Gn(){var a=Fn();if(a){var b=Bn[a.type||"unknown"]||"CONN_UNKNOWN";a=Bn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Hn(){var a=Fn();if(null!=a&&a.effectiveType)return En.hasOwnProperty(a.effectiveType)?En[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function In(){}
function Jn(a,b){return Kn(a,0,b)}
In.prototype.fa=function(a,b){return Kn(a,1,b)};
function Ln(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function Mn(){In.apply(this,arguments)}
u(Mn,In);function Nn(){Mn.h||(Mn.h=new Mn);return Mn.h}
function Kn(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Nm(a,c||0)}
Mn.prototype.Ca=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
Mn.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
Mn.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};
var ki=Nn();function Q(a){var b=Ka.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ja(b))}
u(Q,Error);function On(){try{return Pn(),!0}catch(a){return!1}}
function Pn(a){if(void 0!==M("DATASYNC_ID"))return M("DATASYNC_ID");throw new Q("Datasync ID not set",void 0===a?"unknown":a);}
;function Qn(a){var b=new Si;(b=b.isAvailable()?a?new Yi(b,a):b:null)||(a=new Ti(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Oi(a):null;this.i=document.domain||window.location.hostname}
Qn.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Eg(b))}catch(f){return}else e=escape(b);sn(a,e,c,this.i)};
Qn.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=wg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Qn.prototype.remove=function(a){this.h&&this.h.remove(a);tn(a,"/",this.i)};var Rn=function(){var a;return function(){a||(a=new Qn("ytidb"));return a}}();
function Sn(){var a;return null==(a=Rn())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Tn=[],Un,Vn=!1;function Wn(){var a={};for(Un=new Xn(void 0===a.handleError?Yn:a.handleError,void 0===a.logEvent?Zn:a.logEvent);0<Tn.length;)switch(a=Tn.shift(),a.type){case "ERROR":Un.handleError(a.payload);break;case "EVENT":Un.logEvent(a.eventType,a.payload)}}
function $n(a){Vn||(Un?Un.handleError(a):(Tn.push({type:"ERROR",payload:a}),10<Tn.length&&Tn.shift()))}
function ao(a,b){Vn||(Un?Un.logEvent(a,b):(Tn.push({type:"EVENT",eventType:a,payload:b}),10<Tn.length&&Tn.shift()))}
;function bo(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function co(a){return a.substr(0,a.indexOf(":"))||a}
;var eo={},fo=(eo.AUTH_INVALID="No user identifier specified.",eo.EXPLICIT_ABORT="Transaction was explicitly aborted.",eo.IDB_NOT_SUPPORTED="IndexedDB is not supported.",eo.MISSING_INDEX="Index not created.",eo.MISSING_OBJECT_STORES="Object stores not created.",eo.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",eo.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",eo.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
eo.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",eo.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",eo.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",eo.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",eo),go={},ho=(go.AUTH_INVALID="ERROR",go.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",go.EXPLICIT_ABORT="IGNORED",go.IDB_NOT_SUPPORTED="ERROR",go.MISSING_INDEX=
"WARNING",go.MISSING_OBJECT_STORES="ERROR",go.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",go.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",go.QUOTA_EXCEEDED="WARNING",go.QUOTA_MAYBE_EXCEEDED="WARNING",go.UNKNOWN_ABORT="WARNING",go.INCOMPATIBLE_DB_VERSION="WARNING",go),io={},jo=(io.AUTH_INVALID=!1,io.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,io.EXPLICIT_ABORT=!1,io.IDB_NOT_SUPPORTED=!1,io.MISSING_INDEX=!1,io.MISSING_OBJECT_STORES=!1,io.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,io.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,io.QUOTA_EXCEEDED=!1,io.QUOTA_MAYBE_EXCEEDED=!0,io.UNKNOWN_ABORT=!0,io.INCOMPATIBLE_DB_VERSION=!1,io);function ko(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?fo[a]:c;d=void 0===d?ho[a]:d;e=void 0===e?jo[a]:e;Q.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,ko.prototype)}
u(ko,Q);function lo(a,b){ko.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},fo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,lo.prototype)}
u(lo,ko);function mo(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,mo.prototype)}
u(mo,Error);var no=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function oo(a,b,c,d){b=co(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof ko)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new ko("QUOTA_EXCEEDED",a);if($c&&"UnknownError"===e.name)return new ko("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof mo)return new ko("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&no.some(function(f){return e.message.includes(f)}))return new ko("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new ko("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Cd:e.name})];e.level="WARNING";return e}
function po(a,b,c){var d=Sn();return new ko("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function qo(a){if(!a)throw Error();throw a;}
function ro(a){return a}
function so(a){this.h=a}
function to(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=r(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=r(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
to.all=function(a){return new to(new so(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={nb:0};f.nb<a.length;f={nb:f.nb},++f.nb)to.resolve(a[f.nb]).then(function(g){return function(h){d[g.nb]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
to.resolve=function(a){return new to(new so(function(b,c){a instanceof to?a.then(b,c):b(a)}))};
to.reject=function(a){return new to(new so(function(b,c){c(a)}))};
to.prototype.then=function(a,b){var c=this,d=null!=a?a:ro,e=null!=b?b:qo;return new to(new so(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){uo(c,c,d,f,g)}),c.i.push(function(){vo(c,c,e,f,g)})):"FULFILLED"===c.state.status?uo(c,c,d,f,g):"REJECTED"===c.state.status&&vo(c,c,e,f,g)}))};
to.prototype.catch=function(a){return this.then(void 0,a)};
function uo(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof to?wo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function vo(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof to?wo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function wo(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof to?wo(a,b,f,d,e):d(f)},function(f){e(f)})}
;function xo(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function yo(a){return new Promise(function(b,c){xo(a,b,c)})}
function zo(a){return new to(new so(function(b,c){xo(a,b,c)}))}
;function Ao(a,b){return new to(new so(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Bo=window,R=Bo.ytcsi&&Bo.ytcsi.now?Bo.ytcsi.now:Bo.performance&&Bo.performance.timing&&Bo.performance.now&&Bo.performance.timing.navigationStart?function(){return Bo.performance.timing.navigationStart+Bo.performance.now()}:function(){return(new Date).getTime()};function Co(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(R());this.i=!1}
l=Co.prototype;l.add=function(a,b,c){return Do(this,[a],{mode:"readwrite",da:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return Do(this,[a],{mode:"readwrite",da:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return Do(this,[a],{mode:"readonly",da:!0},function(c){return c.objectStore(a).count(b)})};
function Eo(a,b,c){a=a.h.createObjectStore(b,c);return new Fo(a)}
l.delete=function(a,b){return Do(this,[a],{mode:"readwrite",da:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return Do(this,[a],{mode:"readonly",da:!0},function(c){return c.objectStore(a).get(b)})};
function Go(a,b,c){return Do(a,[b],{mode:"readwrite",da:!0},function(d){d=d.objectStore(b);return zo(d.h.put(c,void 0))})}
l.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Do(a,b,c,d){var e,f,g,h,k,m,n,p,v,t,y,D;return x(function(E){switch(E.h){case 1:var O={mode:"readonly",da:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?O.mode=c:Object.assign(O,c);e=O;a.transactionCount++;f=e.da?3:1;g=0;case 2:if(h){E.A(3);break}g++;k=Math.round(R());za(E,4);m=a.h.transaction(b,e.mode);O=new Ho(m);O=Io(O,d);return w(E,O,6);case 6:return n=E.i,p=Math.round(R()),Jo(a,k,p,g,void 0,b.join(),e),E.return(n);case 4:v=Ba(E);t=Math.round(R());y=oo(v,a.h.name,b.join(),
a.h.version);if((D=y instanceof ko&&!y.h)||g>=f)Jo(a,k,t,g,y,b.join(),e),h=y;E.A(2);break;case 3:return E.return(Promise.reject(h))}})}
function Jo(a,b,c,d,e,f,g){b=c-b;e?(e instanceof ko&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&ao("QUOTA_EXCEEDED",{dbName:co(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof ko&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),ao("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Ko(a,!1,d,f,b,g.tag),$n(e)):Ko(a,!0,d,f,b,g.tag)}
function Ko(a,b,c,d,e,f){ao("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.h.name};
function Fo(a){this.h=a}
l=Fo.prototype;l.add=function(a,b){return zo(this.h.add(a,b))};
l.autoIncrement=function(){return this.h.autoIncrement};
l.clear=function(){return zo(this.h.clear()).then(function(){})};
function Lo(a,b,c){a.h.createIndex(b,c,{unique:!1})}
l.count=function(a){return zo(this.h.count(a))};
function Mo(a,b){return No(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?Mo(this,a):zo(this.h.delete(a))};
l.get=function(a){return zo(this.h.get(a))};
l.index=function(a){try{return new Oo(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new mo(a,this.h.name);throw b;}};
l.getName=function(){return this.h.name};
l.keyPath=function(){return this.h.keyPath};
function No(a,b,c){a=a.h.openCursor(b.query,b.direction);return Po(a).then(function(d){return Ao(d,c)})}
function Ho(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=ko;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Io(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return r(d).next().value})}
Ho.prototype.abort=function(){this.h.abort();this.i=!0;throw new ko("EXPLICIT_ABORT");};
Ho.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new Fo(a),this.j.set(a,b));return b};
function Oo(a){this.h=a}
l=Oo.prototype;l.count=function(a){return zo(this.h.count(a))};
l.delete=function(a){return Qo(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return zo(this.h.get(a))};
l.getKey=function(a){return zo(this.h.getKey(a))};
l.keyPath=function(){return this.h.keyPath};
l.unique=function(){return this.h.unique};
function Qo(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Po(a).then(function(d){return Ao(d,c)})}
function Ro(a,b){this.request=a;this.cursor=b}
function Po(a){return zo(a).then(function(b){return b?new Ro(a,b):null})}
l=Ro.prototype;l.advance=function(a){this.cursor.advance(a);return Po(this.request)};
l.continue=function(a){this.cursor.continue(a);return Po(this.request)};
l.delete=function(){return zo(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return zo(this.cursor.update(a))};function So(a,b,c){return new Promise(function(d,e){function f(){v||(v=new Co(g.result,{closed:p}));return v}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.ce,k=c.blocking,m=c.ef,n=c.upgrade,p=c.closed,v;g.addEventListener("upgradeneeded",function(t){try{if(null===t.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&"none"!==t.dataLoss&&ao("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:co(a)});var y=f(),D=new Ho(g.transaction);
n&&n(y,function(E){return t.oldVersion<E&&t.newVersion>=E},D);
D.done.catch(function(E){e(E)})}catch(E){e(E)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){ao("IDB_UNEXPECTEDLY_CLOSED",{dbName:co(a),dbVersion:t.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function To(a,b,c){c=void 0===c?{}:c;return So(a,b,c)}
function Uo(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.h)return za(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.ce)&&c.addEventListener("blocked",function(){e()}),w(g,yo(c),4);
if(2!=g.h)return Aa(g,0);f=Ba(g);throw oo(f,a,"",-1);})}
;function Vo(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
Vo.prototype.i=function(a,b,c){c=void 0===c?{}:c;return To(a,b,c)};
Vo.prototype.delete=function(a){a=void 0===a?{}:a;return Uo(this.name,a)};
function Wo(a,b){return new ko("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Xo(a,b){if(!b)throw po("openWithToken",co(a.name));return Yo(a)}
function Yo(a){function b(){var f,g,h,k,m,n,p,v,t,y;return x(function(D){switch(D.h){case 1:return g=null!=(f=Error().stack)?f:"",za(D,2),w(D,a.i(a.name,a.options.version,d),4);case 4:h=D.i;for(var E=a.options,O=[],N=r(Object.keys(E.xb)),S=N.next();!S.done;S=N.next()){S=S.value;var aa=E.xb[S],W=void 0===aa.Oe?Number.MAX_VALUE:aa.Oe;!(h.h.version>=aa.Db)||h.h.version>=W||h.h.objectStoreNames.contains(S)||O.push(S)}k=O;if(0===k.length){D.A(5);break}m=Object.keys(a.options.xb);n=h.objectStoreNames();
if(a.m<nm("ytidb_reopen_db_retries",0))return a.m++,h.close(),$n(new ko("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:n})),D.return(b());if(!(a.l<nm("ytidb_remake_db_retries",1))){D.A(6);break}a.l++;return w(D,a.delete(),7);case 7:return $n(new ko("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:n})),D.return(b());case 6:throw new lo(n,m);case 5:return D.return(h);case 2:p=Ba(D);if(p instanceof DOMException?
"VersionError"!==p.name:"DOMError"in self&&p instanceof DOMError?"VersionError"!==p.name:!(p instanceof Object&&"message"in p)||"An attempt was made to open a database using a lower version than the existing version."!==p.message){D.A(8);break}return w(D,a.i(a.name,void 0,Object.assign({},d,{upgrade:void 0})),9);case 9:v=D.i;t=v.h.version;if(void 0!==a.options.version&&t>a.options.version+1)throw v.close(),a.j=!1,Wo(a,t);return D.return(v);case 8:throw c(),p instanceof Error&&!P("ytidb_async_stack_killswitch")&&
(p.stack=p.stack+"\n"+g.substring(g.indexOf("\n")+1)),oo(p,a.name,"",null!=(y=a.options.version)?y:-1);}})}
function c(){a.h===e&&(a.h=void 0)}
if(!a.j)throw Wo(a);if(a.h)return a.h;var d={blocking:function(f){f.close()},
closed:c,ef:c,upgrade:a.options.upgrade};var e=b();a.h=e;return a.h}
;var Zo=new Vo("YtIdbMeta",{xb:{databases:{Db:1}},upgrade:function(a,b){b(1)&&Eo(a,"databases",{keyPath:"actualName"})}});
function $o(a,b){var c;return x(function(d){if(1==d.h)return w(d,Xo(Zo,b),2);c=d.i;return d.return(Do(c,["databases"],{da:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return zo(f.h.put(a,void 0)).then(function(){})})}))})}
function ap(a,b){var c;return x(function(d){if(1==d.h)return a?w(d,Xo(Zo,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function bp(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],w(e,Xo(Zo,b),2)):3!=e.h?(d=e.i,w(e,Do(d,["databases"],{da:!0,mode:"readonly"},function(f){c.length=0;return No(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function cp(a){return bp(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function dp(a,b,c){return bp(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function ep(a){var b,c;return x(function(d){if(1==d.h)return b=Pn("YtIdbMeta hasAnyMeta other"),w(d,bp(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var fp,gp=new function(){}(new function(){});
function hp(){var a,b,c,d;return x(function(e){switch(e.h){case 1:a=Sn();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=bn)f=/WebKit\/([0-9]+)/.exec(Ub()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Ub()),f=!(f&&602<=parseInt(f[1],10)));if(f||Ic)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
za(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(e,$o(d,gp),4);case 4:return w(e,ap("yt-idb-test-do-not-use",gp),5);case 5:return e.return(!0);case 2:return Ba(e),e.return(!1)}})}
function ip(){if(void 0!==fp)return fp;Vn=!0;return fp=hp().then(function(a){Vn=!1;var b;if(null!=(b=Rn())&&b.h){var c;b={hasSucceededOnce:(null==(c=Sn())?void 0:c.hasSucceededOnce)||a};var d;null==(d=Rn())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function jp(){return B("ytglobal.idbToken_")||void 0}
function kp(){var a=jp();return a?Promise.resolve(a):ip().then(function(b){(b=b?gp:void 0)&&A("ytglobal.idbToken_",b);return b})}
;var lp=0;function mp(a,b){lp||(lp=ki.fa(function(){var c,d,e,f,g;return x(function(h){switch(h.h){case 1:return w(h,kp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;za(h,3);return w(h,dp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return w(h,Uo(f.actualName),7);case 7:return w(h,ap(f.actualName,c),6);case 6:Aa(h,4);break;case 3:g=Ba(h),$n(g),d=!1;case 4:ki.Ca(lp),lp=0,d&&mp(a,b),h.h=0}})}))}
function np(){var a;return x(function(b){return 1==b.h?w(b,kp(),2):(a=b.i)?b.return(ep(a)):b.return(!1)})}
new Hh;function op(a){if(!On())throw a=new ko("AUTH_INVALID",{dbName:a}),$n(a),a;var b=Pn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function pp(a,b,c,d){var e,f,g,h,k,m;return x(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",w(n,kp(),2);case 2:g=n.i;if(!g)throw h=po("openDbImpl",a,b),P("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),$n(h),h;bo(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:op(a);za(n,3);return w(n,$o(k,g),5);case 5:return w(n,To(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return m=Ba(n),za(n,7),w(n,ap(k.actualName,g),9);case 9:Aa(n,
8);break;case 7:Ba(n);case 8:throw m;}})}
function qp(a,b,c){c=void 0===c?{}:c;return pp(a,b,!1,c)}
function rp(a,b,c){c=void 0===c?{}:c;return pp(a,b,!0,c)}
function sp(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return w(e,kp(),2);if(3!=e.h){c=e.i;if(!c)return e.return();bo(a);d=op(a);return w(e,Uo(d.actualName,b),3)}return w(e,ap(d.actualName,c),0)})}
function tp(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?w(e,Uo(d.actualName,b),2):w(e,ap(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function up(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return w(d,kp(),2);if(3!=d.h){b=d.i;if(!b)return d.return();bo("LogsDatabaseV2");return w(d,cp(b),3)}c=d.i;return w(d,tp(c,a,b),0)})}
function vp(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return w(d,kp(),2);if(3!=d.h){c=d.i;if(!c)return d.return();bo(a);return w(d,Uo(a,b),3)}return w(d,ap(a,c),0)})}
;function wp(a,b){Vo.call(this,a,b);this.options=b;bo(a)}
u(wp,Vo);function xp(a,b){var c;return function(){c||(c=new wp(a,b));return c}}
wp.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.sc?rp:qp)(a,b,Object.assign({},c))};
wp.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.sc?vp:sp)(this.name,a)};
function yp(a,b){return xp(a,b)}
;var zp={},Ap=yp("ytGcfConfig",{xb:(zp.coldConfigStore={Db:1},zp.hotConfigStore={Db:1},zp),sc:!1,upgrade:function(a,b){b(1)&&(Lo(Eo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),Lo(Eo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Bp(a){return Xo(Ap(),a)}
function Cp(a,b,c){var d,e,f;return x(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:R()},w(g,Bp(c),2);case 2:return e=g.i,w(g,e.clear("hotConfigStore"),3);case 3:return w(g,Go(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Dp(a,b,c,d){var e,f,g;return x(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:R()},w(h,Bp(d),2);case 2:return f=h.i,w(h,f.clear("coldConfigStore"),3);case 3:return w(h,Go(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Ep(a){var b,c;return x(function(d){return 1==d.h?w(d,Bp(a),2):3!=d.h?(b=d.i,c=void 0,w(d,Do(b,["coldConfigStore"],{mode:"readwrite",da:!0},function(e){return Qo(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Fp(a){var b,c;return x(function(d){return 1==d.h?w(d,Bp(a),2):3!=d.h?(b=d.i,c=void 0,w(d,Do(b,["hotConfigStore"],{mode:"readwrite",da:!0},function(e){return Qo(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Gp(){this.h=0}
function Hp(a,b,c){var d,e,f;return x(function(g){if(1==g.h){if(!P("update_log_event_config"))return g.A(0);c&&(a.i=c,A("yt.gcf.config.hotConfigGroup",a.i));a.hotHashData=b;A("yt.gcf.config.hotHashData",a.hotHashData);return(d=jp())?c?g.A(4):w(g,Fp(d),5):g.A(0)}4!=g.h&&(e=g.i,c=null==(f=e)?void 0:f.config);return w(g,Cp(c,b,d),0)})}
function Ip(a,b,c){var d,e,f,g;return x(function(h){if(1==h.h){if(!P("update_log_event_config"))return h.A(0);a.coldHashData=b;A("yt.gcf.config.coldHashData",a.coldHashData);return(d=jp())?c?h.A(4):w(h,Ep(d),5):h.A(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.A(0);g=c.configData;return w(h,Dp(c,b,g,d),0)})}
;function Jp(){return"INNERTUBE_API_KEY"in jm&&"INNERTUBE_API_VERSION"in jm}
function Kp(){return{innertubeApiKey:M("INNERTUBE_API_KEY"),innertubeApiVersion:M("INNERTUBE_API_VERSION"),Dc:M("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),td:M("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),xe:M("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:M("INNERTUBE_CONTEXT_CLIENT_VERSION"),vd:M("INNERTUBE_CONTEXT_HL"),ud:M("INNERTUBE_CONTEXT_GL"),ye:M("INNERTUBE_HOST_OVERRIDE")||"",Ae:!!M("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),ze:!!M("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:M("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Lp(a){var b={client:{hl:a.vd,gl:a.ud,clientName:a.td,clientVersion:a.innertubeContextClientVersion,configInfo:a.Dc}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=z.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=om();""!==c&&(b.client.experimentsToken=c);c=pm();0<c.length&&(b.request={internalExperimentFlags:c});Mp(a,void 0,b);P("enable_third_party_info")&&Np(void 0,b);Op(void 0,b);Pp(a,void 0,b);Qp(void 0,b);P("start_sending_config_hash")&&
Rp(void 0,b);M("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&(b.user={onBehalfOfUser:M("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=r(Object.entries(Em(M("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=r(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,
e);return b}
function Sp(a){var b=new Gk,c=new xk;F(c,1,a.vd);F(c,2,a.ud);F(c,16,a.xe);F(c,17,a.innertubeContextClientVersion);if(a.Dc){var d=a.Dc,e=new tk;d.coldConfigData&&F(e,1,d.coldConfigData);d.appInstallData&&F(e,6,d.appInstallData);d.coldHashData&&F(e,3,d.coldHashData);d.hotHashData&&F(e,5,d.hotHashData);G(c,tk,62,e)}if((d=z.devicePixelRatio)&&1!=d){if(null!=d&&"number"!==typeof d)throw Error("Value of float field must be a number|null|undefined, found "+typeof d+": "+d);F(c,65,d)}d=om();""!==d&&F(c,54,
d);d=pm();if(0<d.length){e=new zk;for(var f=0;f<d.length;f++){var g=new rk;F(g,1,d[f].key);Ld(g,2,sk,d[f].value);Xd(e,15,rk,g)}G(b,zk,5,e)}Mp(a,c);P("enable_third_party_info")&&Np(b);Op(c);Pp(a,c);Qp(c);P("start_sending_config_hash")&&Rp(c);M("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&(a=new Ek,F(a,3,M("DELEGATED_SESSION_ID")));a=r(Object.entries(Em(M("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=r(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?F(c,12,e):"cmodel"===d?F(c,
13,e):"cbr"===d?F(c,87,e):"cbrver"===d?F(c,88,e):"cos"===d?F(c,18,e):"cosver"===d?F(c,19,e):"cplatform"===d&&F(c,42,e);b.j(c);return b}
function Mp(a,b,c){a=a.td;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Rd(b,uk,96)||new uk;var d=rn();d=Object.keys(Nk).indexOf(d);d=-1===d?null:d;null!==d&&F(c,3,d);G(b,uk,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=rn())}
function Np(a,b){var c=B("yt.embedded_player.embed_url");c&&(a?(b=Rd(a,Bk,7)||new Bk,F(b,4,c),G(a,Bk,7,b)):b&&(b.thirdParty={embedUrl:c}))}
function Op(a,b){var c;if(P("web_log_memory_total_kbytes")&&(null==(c=z.navigator)?0:c.deviceMemory)){var d;c=null==(d=z.navigator)?void 0:d.deviceMemory;a?F(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Pp(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Rd(b,tk,62))?d:new tk;F(c,6,a.appInstallData);G(b,tk,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Qp(a,b){var c=Gn();c&&(a?F(a,61,Cn[c]):b&&(b.client.connectionType=c));P("web_log_effective_connection_type")&&(c=Hn())&&(a?F(a,94,Dn[c]):b&&(b.client.effectiveConnectionType=c))}
function Tp(a,b,c){c=void 0===c?{}:c;var d={};M("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":M("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||M("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Dt||M("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().Ct:b=Ag([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=M("SESSION_INDEX",0),P("pageid_as_header_web")&&(d["X-Goog-PageId"]=M("DELEGATED_SESSION_ID")));return d}
function Rp(a,b){Gp.h||(Gp.h=new Gp);var c=Gp.h;var d=R()-c.h;0!==c.h&&d<nm("send_config_hash_timer")?c=void 0:(c.h=R(),c={coldConfigData:B("yt.gcf.config.coldConfigData"),hotHashData:B("yt.gcf.config.hotHashData"),coldHashData:B("yt.gcf.config.coldHashData")});var e=c;if(e&&(c=e.coldConfigData,d=e.coldHashData,e=e.hotHashData,c&&d&&e))if(a){var f;b=null!=(f=Rd(a,tk,62))?f:new tk;F(b,1,c);F(b,3,d);F(b,5,e);G(a,tk,62,b)}else b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.coldConfigData=
c,b.client.configInfo.coldHashData=d,b.client.configInfo.hotHashData=e)}
;function Up(a,b,c,d){try{var e=fi(b);var f=f||{};f.we=!0;var g=new kk(f);g.push(e,!0);if(g.err)throw g.msg||lj[g.err];var h=g.result;c.headers||(c.headers={});c.headers["Content-Encoding"]="gzip";c.postBody=h;c.postParams=void 0;d(a,c)}catch(k){xm(k),d(a,c)}}
;function Vp(a){a=Object.assign({},a);delete a.Authorization;var b=Ag();if(b){var c=new qi;c.update(M("INNERTUBE_API_KEY"));c.update(b);a.hash=cd(c.digest(),3)}return a}
;var Wp;function Xp(){Wp||(Wp=new Qn("yt.innertube"));return Wp}
function Yp(a,b,c,d){if(d)return null;d=Xp().get("nextId",!0)||1;var e=Xp().get("requests",!0)||{};e[d]={method:a,request:b,authState:Vp(c),requestTime:Math.round(R())};Xp().set("nextId",d+1,86400,!0);Xp().set("requests",e,86400,!0);return d}
function Zp(a){var b=Xp().get("requests",!0)||{};delete b[a];Xp().set("requests",b,86400,!0)}
function $p(a){var b=Xp().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(R())-d.requestTime)){var e=d.authState,f=Vp(Tp(!1));ub(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(R())),aq(a,d.method,e,{}));delete b[c]}}Xp().set("requests",b,86400,!0)}}
;function bq(a){this.ac=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.rb=function(){};
this.now=Date.now;this.Gb=!1;var b;this.Nd=null!=(b=a.Nd)?b:100;var c;this.Id=null!=(c=a.Id)?c:1;var d;this.Gd=null!=(d=a.Gd)?d:2592E6;var e;this.Ed=null!=(e=a.Ed)?e:12E4;var f;this.Hd=null!=(f=a.Hd)?f:5E3;var g;this.P=null!=(g=a.P)?g:void 0;this.hc=!!a.hc;var h;this.ec=null!=(h=a.ec)?h:.1;var k;this.nc=null!=(k=a.nc)?k:10;a.handleError&&(this.handleError=a.handleError);a.rb&&(this.rb=a.rb);a.Gb&&(this.Gb=a.Gb);a.ac&&(this.ac=a.ac);this.T=a.T;this.xa=a.xa;this.Y=a.Y;this.W=a.W;this.Oa=a.Oa;this.Mc=
a.Mc;this.Lc=a.Lc;cq(this)&&(!this.T||this.T("networkless_logging"))&&dq(this)}
function dq(a){cq(a)&&!a.Gb&&(a.h=!0,a.hc&&Math.random()<=a.ec&&a.Y.ee(a.P),eq(a),a.W.ma()&&a.Pb(),a.W.Ma(a.Mc,a.Pb.bind(a)),a.W.Ma(a.Lc,a.ed.bind(a)))}
l=bq.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(cq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Y.set(d,this.P).then(function(e){d.id=e;c.W.ma()&&fq(c,d)}).catch(function(e){fq(c,d);
gq(c,e)})}else this.Oa(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(cq(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.T&&this.T("nwl_skip_retry")&&(e.skipRetry=c);if(this.W.ma()||this.T&&this.T("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.h)return w(k,d.Y.set(e,d.P).catch(function(m){gq(d,m)}),2);
f(g,h);k.h=0})}}this.Oa(a,b,e.skipRetry)}else this.Y.set(e,this.P).catch(function(g){d.Oa(a,b,e.skipRetry);
gq(d,g)})}else this.Oa(a,b,this.T&&this.T("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(cq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.Y.qb(d.id,c.P):e=!0;c.W.ib&&c.T&&c.T("vss_network_hint")&&c.W.ib(!0);f(g,h)};
this.Oa(d.url,d.options);this.Y.set(d,this.P).then(function(g){d.id=g;e&&c.Y.qb(d.id,c.P)}).catch(function(g){gq(c,g)})}else this.Oa(a,b)};
l.Pb=function(){var a=this;if(!cq(this))throw po("throttleSend");this.i||(this.i=this.xa.fa(function(){var b;return x(function(c){if(1==c.h)return w(c,a.Y.qd("NEW",a.P),2);if(3!=c.h)return b=c.i,b?w(c,fq(a,b),3):(a.ed(),c.return());a.i&&(a.i=0,a.Pb());c.h=0})},this.Nd))};
l.ed=function(){this.xa.Ca(this.i);this.i=0};
function fq(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!cq(a))throw c=po("immediateSend"),c;if(void 0===b.id){e.A(2);break}return w(e,a.Y.Ce(b.id,a.P),3);case 3:(d=e.i)||a.rb(Error("The request cannot be found in the database."));case 2:if(hq(a,b,a.Gd)){e.A(4);break}a.rb(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.A(5);break}return w(e,a.Y.qb(b.id,a.P),5);case 5:return e.return();case 4:b.skipRetry||(b=iq(a,b));if(!b){e.A(0);break}if(!b.skipRetry||
void 0===b.id){e.A(8);break}return w(e,a.Y.qb(b.id,a.P),8);case 8:a.Oa(b.url,b.options,!!b.skipRetry),e.h=0}})}
function iq(a,b){if(!cq(a))throw po("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,m;return x(function(n){switch(n.h){case 1:g=jq(f);h=kq(f);if(!(a.T&&a.T("nwl_consider_error_code")&&g||a.T&&!a.T("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.nc)){n.A(2);break}if(!a.W.qc){n.A(3);break}return w(n,a.W.qc(),3);case 3:if(a.W.ma()){n.A(2);break}c(e,f);if(!a.T||!a.T("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){n.A(6);break}return w(n,a.Y.Qc(b.id,a.P,!1),6);case 6:return n.return();case 2:if(a.T&&a.T("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.nc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(m=b)?void 0:m.id)){n.A(8);break}return b.sendCount<a.Id?w(n,a.Y.Qc(b.id,a.P,!0,h?!1:void 0),12):w(n,a.Y.qb(b.id,a.P),8);case 12:a.xa.fa(function(){a.W.ma()&&a.Pb()},a.Hd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.A(2):w(h,a.Y.qb(b.id,a.P),2);a.W.ib&&a.T&&a.T("vss_network_hint")&&a.W.ib(!0);d(e,f);h.h=0})};
return b}
function hq(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function eq(a){if(!cq(a))throw po("retryQueuedRequests");a.Y.qd("QUEUED",a.P).then(function(b){b&&!hq(a,b,a.Ed)?a.xa.fa(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.A(2):w(c,a.Y.Qc(b.id,a.P),2);eq(a);c.h=0})}):a.W.ma()&&a.Pb()})}
function gq(a,b){a.Td&&!a.W.ma()?a.Td(b):a.handleError(b)}
function cq(a){return!!a.P||a.ac}
function jq(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function kq(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;function lq(a,b){this.version=a;this.args=b}
;function mq(a,b){this.topic=a;this.h=b}
mq.prototype.toString=function(){return this.topic};var nq=B("ytPubsub2Pubsub2Instance")||new Hi;Hi.prototype.subscribe=Hi.prototype.subscribe;Hi.prototype.unsubscribeByKey=Hi.prototype.Bb;Hi.prototype.publish=Hi.prototype.cb;Hi.prototype.clear=Hi.prototype.clear;A("ytPubsub2Pubsub2Instance",nq);var oq=B("ytPubsub2Pubsub2SubscribedKeys")||{};A("ytPubsub2Pubsub2SubscribedKeys",oq);var pq=B("ytPubsub2Pubsub2TopicToKeys")||{};A("ytPubsub2Pubsub2TopicToKeys",pq);var qq=B("ytPubsub2Pubsub2IsAsync")||{};A("ytPubsub2Pubsub2IsAsync",qq);
A("ytPubsub2Pubsub2SkipSubKey",null);function rq(a,b){var c=sq();c&&c.publish.call(c,a.toString(),a,b)}
function tq(a){var b=uq,c=sq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(oq[d])try{if(f&&b instanceof mq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Xa){var m=new h;h.Xa=m.version}var n=h.Xa}catch(E){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var p=n.construct;
var v=k.args,t=v.length;if(0<t){var y=Array(t);for(k=0;k<t;k++)y[k]=v[k];var D=y}else D=[];f=p.call(n,h,D)}catch(E){throw E.message="yt.pubsub2.Data.deserialize(): "+E.message,E;}}catch(E){throw E.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+E.message,E;}a.call(window,f)}catch(E){wm(E)}},qq[b.toString()]?B("yt.scheduler.instance")?ki.fa(g):Nm(g,0):g())});
oq[d]=!0;pq[b.toString()]||(pq[b.toString()]=[]);pq[b.toString()].push(d);return d}
function vq(){var a=wq,b=tq(function(c){a.apply(void 0,arguments);xq(b)});
return b}
function xq(a){var b=sq();b&&("number"===typeof a&&(a=[a]),hb(a,function(c){b.unsubscribeByKey(c);delete oq[c]}))}
function sq(){return B("ytPubsub2Pubsub2Instance")}
;var yq;
function zq(){if(yq)return yq();var a={};yq=yp("LogsDatabaseV2",{xb:(a.LogsRequestsStore={Db:2},a),sc:!1,upgrade:function(b,c,d){c(2)&&Eo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),Lo(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return yq()}
;function Aq(a){return Xo(zq(),a)}
function Bq(a,b){var c,d,e,f;return x(function(g){if(1==g.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(g,Aq(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:M("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(g,Go(d,"LogsRequestsStore",e),3);f=g.i;c.gf=R();Cq(c);return g.return(f)})}
function Dq(a,b){var c,d,e,f,g,h,k;return x(function(m){if(1==m.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(m,Aq(b),2);if(3!=m.h)return d=m.i,e=M("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,R()],h=IDBKeyRange.bound(f,g),k=void 0,w(m,Do(d,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(n){return Qo(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.getValue()&&(k=p.getValue(),"NEW"===a&&(k.status="QUEUED",
p.update(k)))})}),3);
c.gf=R();Cq(c);return m.return(k)})}
function Eq(a,b){var c;return x(function(d){if(1==d.h)return w(d,Aq(b),2);c=d.i;return d.return(Do(c,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",zo(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Fq(a,b,c,d){c=void 0===c?!0:c;var e;return x(function(f){if(1==f.h)return w(f,Aq(b),2);e=f.i;return f.return(Do(e,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),zo(h.h.put(k,void 0)).then(function(){return k})):to.resolve(void 0)})}))})}
function Gq(a,b){var c;return x(function(d){if(1==d.h)return w(d,Aq(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Hq(a){var b,c;return x(function(d){if(1==d.h)return w(d,Aq(a),2);b=d.i;c=R()-2592E6;return w(d,Do(b,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(e){return No(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Vq(){x(function(a){return w(a,up(),0)})}
function Cq(a){P("nwl_csi_killswitch")||.01>=Math.random()&&rq("nwl_transaction_latency_payload",a)}
;var tr={},ur=yp("ServiceWorkerLogsDatabase",{xb:(tr.SWHealthLog={Db:1},tr),sc:!0,upgrade:function(a,b){b(1)&&Lo(Eo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function vr(a){return Xo(ur(),a)}
function wr(a){var b,c;x(function(d){if(1==d.h)return w(d,vr(a),2);b=d.i;c=R()-2592E6;return w(d,Do(b,["SWHealthLog"],{mode:"readwrite",da:!0},function(e){return No(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function xr(a){var b;return x(function(c){if(1==c.h)return w(c,vr(a),2);b=c.i;return w(c,b.clear("SWHealthLog"),0)})}
;var yr={},zr=0;function Ar(a){var b=new Image,c=""+zr++;yr[c]=b;b.onload=b.onerror=function(){delete yr[c]};
b.src=a}
;function Br(){this.h=new Map;this.i=!1}
function Cr(){if(!Br.h){var a=B("yt.networkRequestMonitor.instance")||new Br;A("yt.networkRequestMonitor.instance",a);Br.h=a}return Br.h}
Br.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Br.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
Br.prototype.removeParams=function(a){return a.split("?")[0]};
Br.prototype.removeParams=Br.prototype.removeParams;Br.prototype.isEndpointCFR=Br.prototype.isEndpointCFR;Br.prototype.requestComplete=Br.prototype.requestComplete;Br.getInstance=Cr;var Dr;function Er(){Dr||(Dr=new Qn("yt.offline"));return Dr}
function Fr(a){if(P("offline_error_handling")){var b=Er().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Er().set("errors",b,2592E3,!0)}}
;function Gr(){Ye.call(this);var a=this;this.j=!1;this.i=ji();this.i.Ma("networkstatus-online",function(){if(a.j&&P("offline_error_handling")){var b=Er().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new Q(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;wm(d)}Er().set("errors",{},2592E3,!0)}}})}
u(Gr,Ye);function Hr(){if(!Gr.h){var a=B("yt.networkStatusManager.instance")||new Gr;A("yt.networkStatusManager.instance",a);Gr.h=a}return Gr.h}
l=Gr.prototype;l.ma=function(){return this.i.ma()};
l.ib=function(a){this.i.i=a};
l.se=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.ke=function(){this.j=!0};
l.Ma=function(a,b){return this.i.Ma(a,b)};
l.qc=function(a){a=hi(this.i,a);a.then(function(b){P("use_cfr_monitor")&&Cr().requestComplete("generate_204",b)});
return a};
Gr.prototype.sendNetworkCheckRequest=Gr.prototype.qc;Gr.prototype.listen=Gr.prototype.Ma;Gr.prototype.enableErrorFlushing=Gr.prototype.ke;Gr.prototype.getWindowStatus=Gr.prototype.se;Gr.prototype.networkStatusHint=Gr.prototype.ib;Gr.prototype.isNetworkAvailable=Gr.prototype.ma;Gr.getInstance=Hr;function Ir(a){a=void 0===a?{}:a;Ye.call(this);var b=this;this.i=this.s=0;this.j=Hr();var c=B("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.pc?(this.pc=a.pc,c("networkstatus-online",function(){Jr(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Jr(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Ze(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Ze(b,"publicytnetworkstatus-offline")})))}
u(Ir,Ye);Ir.prototype.ma=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Ir.prototype.ib=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Ir.prototype.qc=function(a){var b=this,c;return x(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return P("skip_network_check_if_cfr")&&Cr().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ib((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.ma())})):c?d.return(c(a)):d.return(!0)})};
function Jr(a,b){a.pc?a.i?(ki.Ca(a.s),a.s=ki.fa(function(){a.m!==b&&(Ze(a,b),a.m=b,a.i=R())},a.pc-(R()-a.i))):(Ze(a,b),a.m=b,a.i=R()):Ze(a,b)}
;var Kr;function Lr(){var a=bq.call;Kr||(Kr=new Ir({Pt:!0,Jt:!0}));a.call(bq,this,{Y:{ee:Hq,qb:Gq,qd:Dq,Ce:Eq,Qc:Fq,set:Bq},W:Kr,handleError:wm,rb:xm,Oa:Mr,now:R,Td:Fr,xa:Nn(),Mc:"publicytnetworkstatus-online",Lc:"publicytnetworkstatus-offline",hc:!0,ec:.1,nc:nm("potential_esf_error_limit",10),T:P,Gb:!(On()&&Nr())});this.j=new Hh;P("networkless_immediately_drop_all_requests")&&Vq();vp("LogsDatabaseV2")}
u(Lr,bq);function Or(){var a=B("yt.networklessRequestController.instance");a||(a=new Lr,A("yt.networklessRequestController.instance",a),P("networkless_logging")&&kp().then(function(b){a.P=b;dq(a);a.j.resolve();a.hc&&Math.random()<=a.ec&&a.P&&wr(a.P);P("networkless_immediately_drop_sw_health_store")&&Pr(a)}));
return a}
Lr.prototype.writeThenSend=function(a,b){b||(b={});On()||(this.h=!1);bq.prototype.writeThenSend.call(this,a,b)};
Lr.prototype.sendThenWrite=function(a,b,c){b||(b={});On()||(this.h=!1);bq.prototype.sendThenWrite.call(this,a,b,c)};
Lr.prototype.sendAndWrite=function(a,b){b||(b={});On()||(this.h=!1);bq.prototype.sendAndWrite.call(this,a,b)};
Lr.prototype.awaitInitialization=function(){return this.j.promise};
function Pr(a){var b;x(function(c){if(!a.P)throw b=po("clearSWHealthLogsDb"),b;return c.return(xr(a.P).catch(function(d){a.handleError(d)}))})}
function Mr(a,b,c){P("use_cfr_monitor")&&Qr(a,b);if(P("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(R())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;if(a)if(e)Wm(a,void 0,"POST",e);else if(M("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))Wm(a,void 0,"GET","",void 0,void 0,f);else{b:{try{var g=new db({url:a});if(g.j&&g.i||
g.l){var h=lc(oc(5,a)),k;if(!(k=!h||!h.endsWith("/aclk"))){var m=a.search(zc),n=yc(a,0,"ri",m);if(0>n)var p=null;else{var v=a.indexOf("&",n);if(0>v||v>m)v=m;p=decodeURIComponent(a.slice(n+3,-1!==v?v:0).replace(/\+/g," "))}k="1"!==p}var t=!k;break b}}catch(D){}t=!1}if(t){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var y=!0;break b}}catch(D){}y=!1}c=y?!0:!1}else c=!1;c||Ar(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),
Up(a,b.postBody,b,Tm)):Up(a,JSON.stringify(b.postParams),b,an):Tm(a,b)}
function Qr(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Cr().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Cr().requestComplete(a,!0);d(e,f)}}
function Nr(){return"www.youtube-nocookie.com"!==pc(document.location.toString())}
;var Rr=!1,Sr=z.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Rr};A("ytNetworklessLoggingInitializationOptions",Sr);function Tr(){var a;x(function(b){if(1==b.h)return w(b,kp(),2);a=b.i;if(!a||!On()&&!P("nwl_init_require_datasync_id_killswitch")||!Nr())return b.A(0);Rr=!0;Sr.isNwlInitialized=Rr;return w(b,Or().awaitInitialization(),0)})}
;function Ur(a){var b=this;this.config_=null;a?this.config_=a:Jp()&&(this.config_=Kp());Jn(function(){$p(b)},5E3)}
Ur.prototype.isReady=function(){!this.config_&&Jp()&&(this.config_=Kp());return!!this.config_};
function aq(a,b,c,d){function e(y){y=void 0===y?!1:y;var D;if(d.retry&&"www.youtube-nocookie.com"!=h&&(y||P("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(D=Yp(b,c,m,k)),D)){var E=g.onSuccess,O=g.onFetchSuccess;g.onSuccess=function(S,aa){Zp(D);E(S,aa)};
c.onFetchSuccess=function(S,aa){Zp(D);O(S,aa)}}try{if(y&&d.retry&&!d.zd.bypassNetworkless)g.method="POST",d.zd.writeThenSend?Or().writeThenSend(t,g):Or().sendAndWrite(t,g);
else if(d.compress)if(g.postBody){var N=g.postBody;"string"!==typeof N&&(N=JSON.stringify(g.postBody));Up(t,N,g,Tm)}else Up(t,JSON.stringify(g.postParams),g,an);else P("web_all_payloads_via_jspb")?Tm(t,g):an(t,g)}catch(S){if("InvalidAccessError"==S.name)D&&(Zp(D),D=0),xm(Error("An extension is blocking network request."));else throw S;}D&&Jn(function(){$p(a)},5E3)}
!M("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&xm(new Q("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Q("innertube xhrclient not ready",b,c,d);wm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(y,D){if(d.onSuccess)d.onSuccess(D)},
onFetchSuccess:function(y){if(d.onSuccess)d.onSuccess(y)},
onError:function(y,D){if(d.onError)d.onError(D)},
onFetchError:function(y){if(d.onError)d.onError(y)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.ye)&&(h=f);var k=a.config_.Ae||!1,m=Tp(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},v=a.config_.ze&&f;v=v&&f.startsWith("Bearer");v||(p.key=a.config_.innertubeApiKey);var t=Gm(""+h+n,p||{},!0);(B("ytNetworklessLoggingInitializationOptions")?
Sr.isNwlInitialized:Rr)?ip().then(function(y){e(y)}):e(!1)}
;var Vr=0,Wr=Kc?"webkit":Jc?"moz":Hc?"ms":Gc?"o":"";A("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Vr});var Xr={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Yr(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Xr||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Zr(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Yr.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Yr.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Yr.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var qb=z.ytEventsEventsListeners||{};A("ytEventsEventsListeners",qb);var $r=z.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",$r);
function as(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return pb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Sa(e[4])&&Sa(d)&&ub(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var bs=fb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function cs(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=as(a,b,c,d);if(e)return e;e=++$r.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Yr(h);if(!nf(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Yr(h);
h.currentTarget=a;return c.call(a,h)};
g=vm(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),bs()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);qb[e]=[a,b,c,g,d];return e}
function ds(a){a&&("string"==typeof a&&(a=[a]),hb(a,function(b){if(b in qb){var c=qb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?bs()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete qb[b]}}))}
;function es(a){this.N=a;this.i=null;this.m=0;this.v=null;this.s=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.V=cs(window,"mousemove",Ya(this.Z,this));a=Ya(this.R,this);"function"===typeof a&&(a=vm(a));this.aa=window.setInterval(a,25)}
ab(es,J);es.prototype.Z=function(a){void 0===a.h&&Zr(a);var b=a.h;void 0===a.i&&Zr(a);this.i=new jf(b,a.i)};
es.prototype.R=function(){if(this.i){var a=R();if(0!=this.m){var b=this.v,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.N();this.s=d}this.m=a;this.v=this.i;this.l=(this.l+1)%4}};
es.prototype.L=function(){window.clearInterval(this.aa);ds(this.V)};var fs={};
function gs(a){var b=void 0===a?{}:a;a=void 0===b.Le?!1:b.Le;b=void 0===b.le?!0:b.le;if(null==B("_lact",window)){var c=parseInt(M("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&hs();cs(document,"keydown",hs);cs(document,"keyup",hs);cs(document,"mousedown",hs);cs(document,"mouseup",hs);a?cs(window,"touchmove",function(){is("touchmove",200)},{passive:!0}):(cs(window,"resize",function(){is("resize",200)}),b&&cs(window,"scroll",function(){is("scroll",200)}));
new es(function(){is("mouse",100)});
cs(document,"touchstart",hs,{passive:!0});cs(document,"touchend",hs,{passive:!0})}}
function is(a,b){fs[a]||(fs[a]=!0,ki.fa(function(){hs();fs[a]=!1},b))}
function hs(){null==B("_lact",window)&&gs();var a=Date.now();A("_lact",a,window);-1==B("_fact",window)&&A("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function js(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var ks=z.ytPubsubPubsubInstance||new Hi,ls=z.ytPubsubPubsubSubscribedKeys||{},ms=z.ytPubsubPubsubTopicToKeys||{},ns=z.ytPubsubPubsubIsSynchronous||{};function os(a,b){var c=ps();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){ls[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{ns[a]?f():Nm(f,0)}catch(g){wm(g)}},void 0);
ls[d]=!0;ms[a]||(ms[a]=[]);ms[a].push(d);return d}return 0}
function qs(a){var b=ps();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),hb(a,function(c){b.unsubscribeByKey(c);delete ls[c]}))}
function rs(a,b){var c=ps();c&&c.publish.apply(c,arguments)}
function ss(a){var b=ps();if(b)if(b.clear(a),a)ts(a);else for(var c in ms)ts(c)}
function ps(){return z.ytPubsubPubsubInstance}
function ts(a){ms[a]&&(a=ms[a],hb(a,function(b){ls[b]&&delete ls[b]}),a.length=0)}
Hi.prototype.subscribe=Hi.prototype.subscribe;Hi.prototype.unsubscribeByKey=Hi.prototype.Bb;Hi.prototype.publish=Hi.prototype.cb;Hi.prototype.clear=Hi.prototype.clear;A("ytPubsubPubsubInstance",ks);A("ytPubsubPubsubTopicToKeys",ms);A("ytPubsubPubsubIsSynchronous",ns);A("ytPubsubPubsubSubscribedKeys",ls);var us=Symbol("injectionDeps");function vs(a){this.name=a}
vs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function ws(){this.key=xs}
function ys(){this.h=new Map;this.i=new Map}
ys.prototype.resolve=function(a){return a instanceof ws?zs(this,a.key,[],!0):zs(this,a,[])};
function zs(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(d.Qd)var e=d.Qd;else if(d.kf)e=d[us]?As(a,d[us],c):[],e=d.kf.apply(d,ja(e));else if(d.Pd){e=d.Pd;var f=e[us]?As(a,e[us],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ja(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Zt||a.i.set(b,e);return e}
function As(a,b,c){return b?b.map(function(d){return d instanceof ws?zs(a,d.key,c,!0):zs(a,d,c)}):[]}
;var Bs;function Cs(){Bs||(Bs=new ys);return Bs}
;function Ds(){this.store={};this.h={}}
Ds.prototype.storePayload=function(a,b){a=Es(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
Ds.prototype.extractMatchingEntries=function(a){a=Fs(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ja(this.store[a[c]])),delete this.store[a[c]]);return b};
Ds.prototype.getSequenceCount=function(a){a=Fs(this,a);for(var b=0,c=0;c<a.length;c++)b+=this.store[a[c]].length||0;return b};
function Fs(a,b){var c=Es(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&Es(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(Gs(b.auth,g[0])){var h=b.isJspb;Gs(void 0===h?"undefined":h?"true":"false",g[1])&&Gs(b.cttAuthInfo,g[2])&&e.push(d[f])}}return a.h[c]=e}
function Gs(a,b){return void 0===a||"undefined"===a?!0:a===b}
Ds.prototype.getSequenceCount=Ds.prototype.getSequenceCount;Ds.prototype.extractMatchingEntries=Ds.prototype.extractMatchingEntries;Ds.prototype.storePayload=Ds.prototype.storePayload;function Es(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/")}
;function Hs(a,b){if(a)return a[b.name]}
;var Is=nm("initial_gel_batch_timeout",2E3),Js=nm("gel_queue_timeout_max_ms",6E4),Ks=Math.pow(2,16)-1,Ls=void 0;function Ms(){this.j=this.h=this.i=0}
var Ns=new Ms,Os=new Ms,Ps,Qs=!0,Rs=z.ytLoggingTransportGELQueue_||new Map;A("ytLoggingTransportGELQueue_",Rs);var Ss=z.ytLoggingTransportGELProtoQueue_||new Map;A("ytLoggingTransportGELProtoQueue_",Ss);var Ts=z.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",Ts);var Us=z.ytLoggingTransportTokensToJspbCttTargetIds_||{};A("ytLoggingTransportTokensToJspbCttTargetIds_",Us);var Vs={};function Ws(){var a=B("yt.logging.ims");a||(a=new Ds,A("yt.logging.ims",a));return a}
function Xs(a,b){P("web_all_payloads_via_jspb")&&xm(new Q("transport.log called for JSON in JSPB only experiment"));if("log_event"===a.endpoint){Ys(a);var c=Zs(a);if(P("use_new_in_memory_storage")){Vs[c]=!0;var d={cttAuthInfo:c,isJspb:!1};Ws().storePayload(d,a.payload);$s(b,[],c,!1,d)}else d=Rs.get(c)||[],Rs.set(c,d),d.push(a.payload),$s(b,d,c)}}
function at(a,b){if("log_event"===a.endpoint){Ys(void 0,a);var c=Zs(a,!0);if(P("use_new_in_memory_storage")){Vs[c]=!0;var d={cttAuthInfo:c,isJspb:!0};Ws().storePayload(d,a.payload.toJSON());$s(b,[],c,!0,d)}else d=Ss.get(c)||[],Ss.set(c,d),a=a.payload.toJSON(),d.push(a),$s(b,d,c,!0)}}
function $s(a,b,c,d,e){d=void 0===d?!1:d;a&&(Ls=new a);a=nm("tvhtml5_logging_max_batch_ads_fork")||nm("tvhtml5_logging_max_batch")||nm("web_logging_max_batch")||100;var f=R(),g=d?Os.j:Ns.j;b=b.length;e&&(b=Ws().getSequenceCount(e));b>=a?Ps||(Ps=bt(function(){ct({writeThenSend:!0},P("flush_only_full_queue")?c:void 0,d);Ps=void 0},0)):10<=f-g&&(dt(d),d?Os.j=f:Ns.j=f)}
function et(a,b){P("web_all_payloads_via_jspb")&&xm(new Q("transport.logIsolatedGelPayload called in JSPB only experiment"));if("log_event"===a.endpoint){Ys(a);var c=Zs(a),d=new Map;d.set(c,[a.payload]);b&&(Ls=new b);return new zf(function(e,f){Ls&&Ls.isReady()?ft(d,Ls,e,f,{bypassNetworkless:!0},!0):e()})}}
function gt(a,b){if("log_event"===a.endpoint){Ys(void 0,a);var c=Zs(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(Ls=new b);return new zf(function(e){Ls&&Ls.isReady()?ht(d,Ls,e,{bypassNetworkless:!0},!0):e()})}}
function Zs(a,b){var c="";if(a.dangerousLogToVisitorSession)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new Xl;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Ld(d,2,Yl,c.playlistId);Us[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Ts[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function ct(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;!c&&P("web_all_payloads_via_jspb")&&xm(new Q("transport.flushLogs called for JSON in JSPB only experiment"));new zf(function(d,e){c?(jt(Os.i),jt(Os.h),Os.h=0):(jt(Ns.i),jt(Ns.h),Ns.h=0);if(Ls&&Ls.isReady())if(P("use_new_in_memory_storage")){var f=a,g=c,h=Ls;f=void 0===f?{}:f;g=void 0===g?!1:g;var k=new Map,m=new Map;if(void 0!==b)g?(e=Ws().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),k.set(b,e),ht(k,h,d,f)):(k=Ws().extractMatchingEntries({isJspb:g,
cttAuthInfo:b}),m.set(b,k),ft(m,h,d,e,f));else if(g){e=r(Object.keys(Vs));for(g=e.next();!g.done;g=e.next())m=g.value,g=Ws().extractMatchingEntries({isJspb:!0,cttAuthInfo:m}),0<g.length&&k.set(m,g),delete Vs[m];ht(k,h,d,f)}else{k=r(Object.keys(Vs));for(g=k.next();!g.done;g=k.next()){g=g.value;var n=Ws().extractMatchingEntries({isJspb:!1,cttAuthInfo:g});0<n.length&&m.set(g,n);delete Vs[g]}ft(m,h,d,e,f)}}else f=a,k=c,h=Ls,f=void 0===f?{}:f,k=void 0===k?!1:k,void 0!==b?k?(e=new Map,k=Ss.get(b)||[],e.set(b,
k),ht(e,h,d,f),Ss.delete(b)):(k=new Map,m=Rs.get(b)||[],k.set(b,m),ft(k,h,d,e,f),Rs.delete(b)):k?(ht(Ss,h,d,f),Ss.clear()):(ft(Rs,h,d,e,f),Rs.clear());else dt(c),d()})}
function dt(a){a=void 0===a?!1:a;if(P("web_gel_timeout_cap")&&(!a&&!Ns.h||a&&!Os.h)){var b=bt(function(){ct({writeThenSend:!0},void 0,a)},Js);
a?Os.h=b:Ns.h=b}jt(a?Os.i:Ns.i);b=M("LOGGING_BATCH_TIMEOUT",nm("web_gel_debounce_ms",1E4));P("shorten_initial_gel_batch_timeout")&&Qs&&(b=Is);b=bt(function(){ct({writeThenSend:!0},void 0,a)},b);
a?Os.i=b:Ns.i=b}
function ft(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(R()),h=a.size,k={};a=r(a);for(var m=a.next();!m.done;k={Sb:k.Sb,ab:k.ab,zb:k.zb,Ub:k.Ub,Tb:k.Tb},m=a.next()){var n=r(m.value);m=n.next().value;n=n.next().value;k.ab=wb({context:Lp(b.config_||Kp())});if(!Ra(n)&&!P("throw_err_when_logevent_malformed_killswitch")){d();break}k.ab.events=n;(n=Ts[m])&&kt(k.ab,m,n);delete Ts[m];k.zb="visitorOnlyApprovedKey"===m;lt(k.ab,g,k.zb);mt(e);k.Ub=function(p){P("update_log_event_config")&&ki.fa(function(){return x(function(v){return w(v,
nt(p),0)})});
h--;h||c()};
k.Sb=0;k.Tb=function(p){return function(){p.Sb++;if(e.bypassNetworkless&&1===p.Sb)try{aq(b,"log_event",p.ab,ot({writeThenSend:!0},p.zb,p.Ub,p.Tb,f)),Qs=!1}catch(v){wm(v),d()}h--;h||c()}}(k);
try{aq(b,"log_event",k.ab,ot(e,k.zb,k.Ub,k.Tb,f)),Qs=!1}catch(p){wm(p),d()}}}
function ht(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(R()),g=a.size,h=new Map([].concat(ja(a)));h=r(h);for(var k=h.next();!k.done;k=h.next()){var m=r(k.value).next().value,n=a.get(m);k=new Zl;var p=Sp(b.config_||Kp());G(k,Gk,1,p);n=n?pt(n):[];n=r(n);for(p=n.next();!p.done;p=n.next())Xd(k,3,Tl,p.value);(n=Us[m])&&qt(k,m,n);delete Us[m];m="visitorOnlyApprovedKey"===m;rt(k,f,m);mt(d);k=ke(k);m=ot(d,m,function(v){P("update_log_event_config")&&ki.fa(function(){return x(function(t){return w(t,nt(v),
0)})});
g--;g||c()},function(){g--;
g||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=k;aq(b,"log_event","",m);Qs=!1}}
function mt(a){P("always_send_and_write")&&(a.writeThenSend=!1)}
function ot(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,zd:a,dangerousLogToVisitorSession:b,Ft:!!e,headers:{},postBodyFormat:"",postBody:"",compress:P("compress_gel")};st()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R())));return a}
function lt(a,b,c){st()||(a.requestTimeMs=String(b));P("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=M("EVENT_ID"))&&(c=tt(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function rt(a,b,c){st()||F(a,2,b);if(!c&&(b=M("EVENT_ID"))){c=tt();var d=new Wl;F(d,1,b);F(d,2,c);G(a,Wl,5,d)}}
function tt(){var a=M("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*Ks/2));a++;a>Ks&&(a=1);km("BATCH_CLIENT_COUNTER",a);return a}
function kt(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function qt(a,b,c){var d=1===Md(c,Yl)?1:-1;if(Hd(c,d))d=1;else if(c.getPlaylistId())d=2;else return;G(a,Xl,4,c);a=Rd(a,Gk,1)||new Gk;c=Rd(a,Ek,3)||new Ek;var e=new Dk;F(e,2,b);F(e,1,d);Xd(c,12,Dk,e);G(a,Ek,3,c)}
function pt(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Tl(a[c]))}catch(d){wm(new Q("Transport failed to deserialize "+String(a[c])))}return b}
function Ys(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);A("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function st(){return P("use_request_time_ms_header")||P("lr_use_request_time_ms_header")}
function bt(a,b){return P("transport_use_scheduler")?Jn(a,b):Nm(a,b)}
function jt(a){P("transport_use_scheduler")?ki.Ca(a):window.clearTimeout(a)}
function nt(a){var b,c,d,e,f,g,h,k,m,n;return x(function(p){return 1==p.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=Hs(d,pk),g=null==(f=d)?void 0:f.hotHashData,h=Hs(d,ok),m=null==(k=d)?void 0:k.coldHashData,n=Cs().resolve(Gp),g?e?w(p,Hp(n,g,e),2):w(p,Hp(n,g),2):p.A(2)):m?h?w(p,Ip(n,m,h),0):w(p,Ip(n,m),0):p.A(0)})}
;var ut=z.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",ut);
function vt(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||R());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;P("enable_unknown_lact_fix_on_html5")&&gs();a=js();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};P("log_sequence_info_on_gel_web")&&d.sequenceGroup&&(a=e.context,b=d.sequenceGroup,b={index:wt(b),groupKey:b},a.sequence=b,d.endOfSequence&&delete ut[d.sequenceGroup]);(d.sendIsolatedPayload?et:Xs)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,
dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},c)}
function xt(a){ct(void 0,void 0,void 0===a?!1:a)}
function wt(a){ut[a]=a in ut?ut[a]+1:0;return ut[a]}
;var zt=[];function Zn(a,b,c){c=void 0===c?{}:c;var d=Ur;M("ytLoggingEventsDefaultDisabled",!1)&&Ur===Ur&&(d=null);P("web_all_payloads_via_jspb")?zt.push({Nc:a,payload:b,options:c}):vt(a,b,d,c)}
;var At=z.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",At);
function Bt(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||R());F(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=js();d=new Sl;F(d,1,c.timestamp||!isFinite(e)?-1:e);if(P("log_sequence_info_on_gel_web")&&c.sequenceGroup){e=c.sequenceGroup;var f=wt(e),g=new Rl;F(g,2,f);F(g,1,e);G(d,Rl,3,g);c.endOfSequence&&delete At[c.sequenceGroup]}G(a,Sl,33,d);(c.sendIsolatedPayload?gt:at)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,dangerousLogToVisitorSession:c.dangerousLogToVisitorSession},b)}
;function Ct(a,b){b=void 0===b?{}:b;var c=!1;M("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);Bt(a,c?null:Ur,b)}
;function Dt(a,b,c){var d=new Tl;Vd(d,Il,72,Ul,a);c?Bt(d,c,b):Ct(d,b)}
function Et(a,b,c){var d=new Tl;Vd(d,Hl,73,Ul,a);c?Bt(d,c,b):Ct(d,b)}
function Ft(a,b,c){var d=new Tl;Vd(d,Gl,78,Ul,a);c?Bt(d,c,b):Ct(d,b)}
function Gt(a,b,c){var d=new Tl;Vd(d,Jl,208,Ul,a);c?Bt(d,c,b):Ct(d,b)}
function Ht(a,b,c){var d=new Tl;Vd(d,zl,156,Ul,a);c?Bt(d,c,b):Ct(d,b)}
function It(a,b,c){var d=new Tl;Vd(d,Dl,215,Ul,a);c?Bt(d,c,b):Ct(d,b)}
;var Jt=new Set,Kt=0,Lt=0,Mt=0,Nt=[],Ot=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Yn(a){Pt(a)}
function Qt(a){Pt(a,"WARNING")}
function Pt(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||M("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||M("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(P("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=Kt)){var m=Nt,n=we(a),p=n.message||"Unknown Error",v=n.name||"UnknownError",t=n.stack||a.i||"Not available";if(t.startsWith(v+": "+p)){var y=t.split("\n");y.shift();t=y.join("\n")}var D=n.lineNumber||"Not available",E=n.fileName||"Not available",O=t,N=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var S=0;S<a.args.length&&!(N=nn(a.args[S],"params."+S,g,N),500<=N);S++);else if(a.hasOwnProperty("params")&&
a.params){var aa=a.params;if("object"===typeof a.params)for(var W in aa){if(aa[W]){var xb="params."+W,Za=pn(aa[W]);g[xb]=Za;N+=xb.length+Za.length;if(500<N)break}}else g.params=pn(aa)}if(m.length)for(var qa=0;qa<m.length&&!(N=nn(m[qa],"params.context."+qa,g,N),500<=N);qa++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var I={message:p,name:v,lineNumber:D,fileName:E,stack:O,params:g,sampleWeight:1},oa=Number(a.columnNumber);isNaN(oa)||(I.lineNumber=I.lineNumber+
":"+oa);if("IGNORED"===a.level)var ha=0;else a:{for(var cf=jn(),df=r(cf.Ua),Nd=df.next();!Nd.done;Nd=df.next()){var ta=Nd.value;if(I.message&&I.message.match(ta.Qt)){ha=ta.weight;break a}}for(var Iq=r(cf.Qa),Tk=Iq.next();!Tk.done;Tk=Iq.next()){var Jq=Tk.value;if(Jq.callback(I)){ha=Jq.weight;break a}}ha=1}I.sampleWeight=ha;for(var Kq=r(dn),Uk=Kq.next();!Uk.done;Uk=Kq.next()){var Vk=Uk.value;if(Vk.mc[I.name])for(var Lq=r(Vk.mc[I.name]),Wk=Lq.next();!Wk.done;Wk=Lq.next()){var Mq=Wk.value,xh=I.message.match(Mq.regexp);
if(xh){I.params["params.error.original"]=xh[0];for(var Xk=Mq.groups,Nq={},Od=0;Od<Xk.length;Od++)Nq[Xk[Od]]=xh[Od+1],I.params["params.error."+Xk[Od]]=xh[Od+1];I.message=Vk.Jc(Nq);break}}}I.params||(I.params={});var Oq=jn();I.params["params.errorServiceSignature"]="msg="+Oq.Ua.length+"&cb="+Oq.Qa.length;I.params["params.serviceWorker"]="false";z.document&&z.document.querySelectorAll&&(I.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Eb("sample").constructor!==
Cb&&(I.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(I);if(0!==I.sampleWeight&&!Jt.has(I.message)){if("ERROR"===h){kn.cb("handleError",I);if(P("record_app_crashed_web")&&0===Mt&&1===I.sampleWeight)if(Mt++,P("errors_via_jspb")){var Yk=new sl;F(Yk,1,1);if(!P("report_client_error_with_app_crash_ks")){var Pq=new nl;F(Pq,1,I.message);var Qq=new ol;G(Qq,nl,3,Pq);var Rq=new pl;G(Rq,ol,5,Qq);var Sq=new ql;G(Sq,pl,9,Rq);G(Yk,ql,4,Sq)}var Tq=new Tl;Vd(Tq,sl,20,
Ul,Yk);Ct(Tq)}else{var Uq={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};P("report_client_error_with_app_crash_ks")||(Uq.systemHealth={crashData:{clientError:{logMessage:{message:I.message}}}});Zn("appCrashed",Uq)}Lt++}else"WARNING"===h&&kn.cb("handleWarning",I);if(P("kevlar_gel_error_routing"))a:{var ef=h;if(P("errors_via_jspb")){if(Rt())var Wq=void 0;else{var Pd=new Rk;F(Pd,1,I.stack);I.fileName&&F(Pd,4,I.fileName);var Qb=I.lineNumber&&I.lineNumber.split?I.lineNumber.split(":"):[];0!==Qb.length&&(1!==
Qb.length||isNaN(Number(Qb[0]))?2!==Qb.length||isNaN(Number(Qb[0]))||isNaN(Number(Qb[1]))||(F(Pd,2,Number(Qb[0])),F(Pd,3,Number(Qb[1]))):F(Pd,2,Number(Qb[0])));var Pc=new nl;F(Pc,1,I.message);F(Pc,3,I.name);F(Pc,6,I.sampleWeight);"ERROR"===ef?F(Pc,2,2):"WARNING"===ef?F(Pc,2,1):F(Pc,2,0);var Zk=new Sk;F(Zk,1,!0);Vd(Zk,Rk,3,ml,Pd);var mc=new Ok;F(mc,3,window.location.href);for(var Xq=M("FEXP_EXPERIMENTS",[]),$k=0;$k<Xq.length;$k++){var Mx=Xq[$k];Cd(mc);Kd(mc,5,2,!1,!1).push(Mx)}var al=M("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!lm()&&al)for(var Yq=r(Object.keys(al)),Qc=Yq.next();!Qc.done;Qc=Yq.next()){var Zq=Qc.value,bl=new Qk;F(bl,1,Zq);F(bl,2,String(al[Zq]));Xd(mc,4,Qk,bl)}var cl=I.params;if(cl){var $q=r(Object.keys(cl));for(Qc=$q.next();!Qc.done;Qc=$q.next()){var ar=Qc.value,dl=new Qk;F(dl,1,"client."+ar);F(dl,2,String(cl[ar]));Xd(mc,4,Qk,dl)}}var br=M("SERVER_NAME"),cr=M("SERVER_VERSION");if(br&&cr){var el=new Qk;F(el,1,"server.name");F(el,2,br);Xd(mc,4,Qk,el);var fl=new Qk;F(fl,1,"server.version");F(fl,2,cr);Xd(mc,
4,Qk,fl)}var yh=new ol;G(yh,Ok,1,mc);G(yh,Sk,2,Zk);G(yh,nl,3,Pc);Wq=yh}var dr=Wq;if(!dr)break a;var er=new Tl;Vd(er,ol,163,Ul,dr);Ct(er)}else{if(Rt())var fr=void 0;else{var ff={stackTrace:I.stack};I.fileName&&(ff.filename=I.fileName);var Rb=I.lineNumber&&I.lineNumber.split?I.lineNumber.split(":"):[];0!==Rb.length&&(1!==Rb.length||isNaN(Number(Rb[0]))?2!==Rb.length||isNaN(Number(Rb[0]))||isNaN(Number(Rb[1]))||(ff.lineNumber=Number(Rb[0]),ff.columnNumber=Number(Rb[1])):ff.lineNumber=Number(Rb[0]));
var gl={level:"ERROR_LEVEL_UNKNOWN",message:I.message,errorClassName:I.name,sampleWeight:I.sampleWeight};"ERROR"===ef?gl.level="ERROR_LEVEL_ERROR":"WARNING"===ef&&(gl.level="ERROR_LEVEL_WARNNING");var Nx={isObfuscated:!0,browserStackInfo:ff},Qd={pageUrl:window.location.href,kvPairs:[]};M("FEXP_EXPERIMENTS")&&(Qd.experimentIds=M("FEXP_EXPERIMENTS"));var hl=M("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!lm()&&hl)for(var gr=r(Object.keys(hl)),Rc=gr.next();!Rc.done;Rc=gr.next()){var hr=Rc.value;Qd.kvPairs.push({key:hr,
value:String(hl[hr])})}var il=I.params;if(il){var ir=r(Object.keys(il));for(Rc=ir.next();!Rc.done;Rc=ir.next()){var jr=Rc.value;Qd.kvPairs.push({key:"client."+jr,value:String(il[jr])})}}var kr=M("SERVER_NAME"),lr=M("SERVER_VERSION");kr&&lr&&(Qd.kvPairs.push({key:"server.name",value:kr}),Qd.kvPairs.push({key:"server.version",value:lr}));fr={errorMetadata:Qd,stackTrace:Nx,logMessage:gl}}var mr=fr;if(!mr)break a;Zn("clientError",mr)}if("ERROR"===ef||P("errors_flush_gel_always_killswitch"))b:{if(P("web_fp_via_jspb")&&
(xt(!0),!P("web_fp_via_jspb_and_json")))break b;xt()}}if(!P("suppress_error_204_logging")){var gf=I.params||{},nc={urlParams:{a:"logerror",t:"jserror",type:I.name,msg:I.message.substr(0,250),line:I.lineNumber,level:h,"client.name":gf.name},postParams:{url:M("PAGE_NAME",window.location.href),file:I.fileName},method:"POST"};gf.version&&(nc["client.version"]=gf.version);if(nc.postParams){I.stack&&(nc.postParams.stack=I.stack);for(var nr=r(Object.keys(gf)),jl=nr.next();!jl.done;jl=nr.next()){var or=jl.value;
nc.postParams["client."+or]=gf[or]}var kl=M("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(kl)for(var pr=r(Object.keys(kl)),ll=pr.next();!ll.done;ll=pr.next()){var qr=ll.value;nc.postParams[qr]=kl[qr]}var rr=M("SERVER_NAME"),sr=M("SERVER_VERSION");rr&&sr&&(nc.postParams["server.name"]=rr,nc.postParams["server.version"]=sr)}Tm(M("ECATCHER_REPORT_HOST","")+"/error_204",nc)}try{Jt.add(I.message)}catch(tz){}Kt++}}}}
function Rt(){for(var a=r(Ot),b=a.next();!b.done;b=a.next())if(cn(b.value.toLowerCase()))return!0;return!1}
function St(a){var b=Ka.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ja(b))}
;function Tt(){this.register=new Map}
function Ut(a){a=r(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Ut("ABORTED")}
Tt.prototype.clear=function(){Ut(this);this.register.clear()};
var Vt=new Tt;var Wt=Date.now().toString();function Xt(){for(var a=Array(16),b=0;16>b;b++){for(var c=Date.now(),d=0;d<c%23;d++)a[b]=Math.random();a[b]=Math.floor(256*Math.random())}if(Wt)for(b=1,c=0;c<Wt.length;c++)a[b%16]=a[b%16]^a[(b-1)%16]/4^Wt.charCodeAt(c),b++;return a}
function Yt(){if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];return a}catch(d){}return Xt()}
function Zt(){for(var a=Yt(),b=[],c=0;c<a.length;c++)b.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(a[c]&63));return b.join("")}
;var $t=z.ytLoggingDocDocumentNonce_;$t||($t=Zt(),A("ytLoggingDocDocumentNonce_",$t));var au=$t;var bu={Vj:0,ig:1,sg:2,Sn:3,Xj:4,Ks:5,Mo:6,Fq:7,Up:8,sq:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function cu(a){this.O=a}
function du(a){return new cu({trackingParams:a})}
cu.prototype.getAsJson=function(){var a={};void 0!==this.O.trackingParams?a.trackingParams=this.O.trackingParams:(a.veType=this.O.veType,void 0!==this.O.veCounter&&(a.veCounter=this.O.veCounter),void 0!==this.O.elementIndex&&(a.elementIndex=this.O.elementIndex));void 0!==this.O.dataElement&&(a.dataElement=this.O.dataElement.getAsJson());void 0!==this.O.youtubeData&&(a.youtubeData=this.O.youtubeData);return a};
cu.prototype.getAsJspb=function(){var a=new ul;if(void 0!==this.O.trackingParams){var b=this.O.trackingParams;if(null!=b)if("string"===typeof b)b=b?new ld(b,id):md();else if(b.constructor!==ld)if(hd(b))b=b.length?new ld(new Uint8Array(b),id):md();else throw Error();F(a,1,b)}else void 0!==this.O.veType&&F(a,2,this.O.veType),void 0!==this.O.veCounter&&F(a,6,this.O.veCounter),void 0!==this.O.elementIndex&&F(a,3,this.O.elementIndex);void 0!==this.O.dataElement&&(b=this.O.dataElement.getAsJspb(),G(a,ul,
7,b));void 0!==this.O.youtubeData&&G(a,qk,8,this.O.jspbYoutubeData);return a};
cu.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
cu.prototype.isClientVe=function(){return!this.O.trackingParams&&!!this.O.veType};function eu(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function fu(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function gu(a){return M(fu(void 0===a?0:a))}
A("yt_logging_screen.getRootVeType",gu);function hu(a){return(a=gu(void 0===a?0:a))?new cu({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function iu(){var a=M("csn-to-ctt-auth-info");a||(a={},km("csn-to-ctt-auth-info",a));return a}
function ju(a){a=M(eu(void 0===a?0:a));if(!a&&!M("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
A("yt_logging_screen.getCurrentCsn",ju);function ku(a){for(var b=r(Object.values(bu)),c=b.next();!c.done;c=b.next())if(ju(c.value)===a)return!0;return!1}
function lu(a,b,c){var d=iu();(c=ju(c))&&delete d[c];b&&(d[a]=b)}
function mu(a){return iu()[a]}
A("yt_logging_screen.getCttAuthInfo",mu);function nu(a,b,c,d){c=void 0===c?0:c;if(a!==M(eu(c))||b!==M(fu(c)))if(lu(a,d,c),km(eu(c),a),km(fu(c),b),b=function(){setTimeout(function(){if(a)if(P("web_time_via_jspb")){var e=new vl;F(e,1,au);F(e,2,a);var f=new Tl;Vd(f,vl,111,Ul,e);Ct(f)}else Zn("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:au,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
A("yt_logging_screen.setCurrentScreen",nu);var ou=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",ou);function pu(a){fm(ou,arguments)}
;var qu={hg:3611,lf:27686,mf:85013,nf:23462,qf:157557,rf:42016,sf:62407,tf:26926,pf:43781,uf:51236,vf:79148,wf:50160,xf:77504,Jf:153587,Kf:87907,Lf:18630,Mf:54445,Nf:80935,Of:152172,Pf:105675,Qf:150723,Rf:37521,Sf:147285,Tf:47786,Uf:98349,Vf:168271,Wf:168954,Xf:168277,Yf:168273,Zf:168270,ag:123695,cg:6827,dg:29434,eg:171388,fg:7282,gg:124448,kg:32276,jg:76278,lg:147868,mg:147869,ng:93911,og:106531,pg:27259,qg:27262,rg:27263,tg:21759,ug:27107,vg:62936,wg:160866,xg:49568,yg:171243,zg:160789,Ag:171244,
Bg:171241,Cg:171245,Dg:171242,Eg:38408,Fg:80637,Gg:68727,Hg:68728,Ig:80353,Jg:80356,Kg:74610,Lg:45707,Mg:83962,Ng:83970,Og:46713,Pg:166591,Qg:89711,Rg:74612,Sg:155792,Tg:93265,Ug:74611,Vg:131380,Xg:128979,Yg:139311,Zg:128978,Wg:131391,ah:105350,dh:139312,eh:134800,bh:131392,gh:113533,hh:93252,ih:99357,kh:94521,lh:114252,mh:113532,nh:94522,jh:94583,oh:88E3,ph:139580,qh:93253,rh:93254,sh:94387,th:94388,uh:93255,vh:97424,fh:72502,wh:110111,xh:76019,zh:117092,Ah:117093,yh:89431,Bh:110466,Ch:77240,Dh:60508,
Eh:148123,Fh:148124,Gh:137401,Hh:137402,Ih:137046,Jh:73393,Kh:113534,Lh:92098,Mh:131381,Nh:84517,Oh:83759,Ph:162711,Qh:162712,Rh:80357,Sh:86113,Th:72598,Uh:168413,Vh:72733,Wh:107349,Xh:124275,Yh:118203,Zh:133275,ai:160157,bi:152569,ci:156651,di:133274,fi:160159,gi:160158,hi:133272,ii:133273,ji:133276,ki:144507,li:143247,mi:156652,ni:143248,oi:143249,ri:143250,si:143251,ti:156653,vi:144401,xi:117431,wi:133797,yi:153964,zi:128572,Ai:133405,Bi:117429,Ci:117430,Di:117432,Ei:120080,Fi:117259,Gi:156655,
Hi:156654,Ii:121692,Ji:145656,Ki:156656,Li:145655,Mi:145653,Ni:145654,Oi:145657,Pi:132972,Qi:133051,Ri:133658,Si:132971,Ti:97615,Vi:143359,Ui:143356,Xi:143361,Wi:143358,Zi:143360,Yi:143357,aj:142303,bj:143353,cj:143354,dj:144479,ej:143355,fj:31402,hj:133624,ij:146477,jj:133623,kj:133622,gj:133621,lj:84774,nj:160801,mj:95117,oj:150497,pj:98930,qj:98931,rj:98932,sj:153320,tj:153321,uj:43347,vj:129889,wj:149123,xj:45474,yj:100352,zj:84758,Aj:98443,Bj:117985,Cj:74613,Dj:155911,Ej:74614,Fj:64502,Gj:136032,
Hj:74615,Ij:74616,Jj:122224,Kj:74617,Lj:77820,Mj:74618,Nj:93278,Oj:93274,Pj:93275,Qj:93276,Rj:22110,Sj:29433,Tj:133798,Uj:132295,Wj:120541,Yj:82047,Zj:113550,ak:75836,bk:75837,ck:42352,dk:84512,ek:76065,fk:75989,kk:51879,lk:16623,mk:32594,nk:27240,pk:32633,qk:74858,rk:156999,tk:3945,sk:16989,uk:45520,vk:25488,wk:25492,xk:25494,yk:55760,zk:14057,Ak:18451,Bk:57204,Ck:57203,Dk:17897,Ek:57205,Fk:18198,Gk:17898,Hk:17909,Ik:43980,Jk:46220,Kk:11721,Lk:147994,Mk:49954,Nk:96369,Ok:3854,Pk:151633,Qk:56251,
Rk:159108,Sk:25624,Tk:152036,ol:16906,pl:99999,ql:68172,rl:27068,sl:47973,ul:72773,vl:26970,wl:26971,xl:96805,yl:17752,zl:73233,Al:109512,Bl:22256,Cl:14115,Dl:22696,El:89278,Fl:89277,Gl:109513,Hl:43278,Il:43459,Jl:43464,Kl:89279,Ll:43717,Ml:55764,Nl:22255,Ol:147912,Pl:89281,Ql:40963,Rl:43277,Sl:43442,Tl:91824,Ul:120137,Vl:96367,Wl:36850,Xl:72694,Yl:37414,Zl:36851,bm:124863,am:121343,cm:73491,dm:54473,em:166861,fm:43375,gm:46674,hm:143815,im:139095,jm:144402,km:149968,lm:149969,mm:32473,nm:72901,om:72906,
pm:50947,qm:50612,rm:50613,sm:50942,tm:84938,um:84943,vm:84939,wm:84941,xm:84944,ym:84940,zm:84942,Am:35585,Bm:51926,Cm:79983,Dm:63238,Em:18921,Fm:63241,Gm:57893,Hm:41182,Im:135732,Jm:33424,Km:22207,Lm:42993,Mm:36229,Nm:22206,Om:22205,Pm:18993,Qm:19001,Rm:18990,Sm:18991,Tm:18997,Um:18725,Vm:19003,Wm:36874,Xm:44763,Ym:33427,Zm:67793,an:22182,bn:37091,cn:34650,dn:50617,en:47261,fn:22287,gn:25144,hn:97917,jn:62397,kn:150871,ln:150874,mn:125598,nn:137935,pn:36961,qn:108035,rn:27426,sn:27857,tn:27846,
un:27854,vn:69692,wn:61411,xn:39299,yn:38696,zn:62520,An:36382,Bn:108701,Cn:50663,Dn:36387,En:14908,Fn:37533,Gn:105443,Hn:61635,In:62274,Jn:161670,Kn:133818,Ln:65702,Mn:65703,Nn:65701,On:76256,Pn:166382,Qn:37671,Rn:49953,Tn:36216,Un:28237,Vn:39553,Wn:29222,Xn:26107,Yn:38050,Zn:26108,bo:120745,ao:26109,co:26110,eo:66881,fo:28236,ho:14586,jo:160598,ko:57929,lo:74723,mo:44098,no:44099,qo:23528,ro:61699,oo:134104,po:134103,so:59149,to:101951,uo:97346,vo:118051,wo:95102,xo:64882,yo:119505,zo:63595,Ao:63349,
Bo:95101,Co:75240,Do:27039,Eo:68823,Fo:21537,Go:83464,Ho:75707,Io:170215,Jo:83113,Ko:101952,Lo:101953,No:79610,Oo:125755,Po:24402,Qo:24400,Ro:32925,To:57173,So:156421,Uo:122502,Vo:145268,Wo:138480,Xo:64423,Yo:64424,Zo:33986,ap:100828,bp:129089,cp:21409,hp:135155,ip:135156,jp:135157,kp:135158,lp:158225,mp:135159,np:135160,qp:167651,rp:135161,tp:135162,up:135163,sp:158226,vp:158227,wp:135164,xp:135165,yp:135166,ep:11070,fp:11074,gp:17880,zp:14001,Bp:30709,Cp:30707,Dp:30711,Ep:30710,Fp:30708,Ap:26984,
Gp:146143,Hp:63648,Ip:63649,Jp:111059,Kp:5754,Lp:20445,Mp:151308,Np:151152,Qp:130975,Pp:130976,Op:167637,Rp:110386,Sp:113746,Tp:66557,Vp:17310,Wp:28631,Xp:21589,Yp:164817,Zp:168011,aq:154946,bq:68012,cq:162617,fq:60480,gq:138664,hq:141121,iq:164502,jq:31571,kq:141978,lq:150105,mq:150106,nq:150107,oq:150108,pq:76980,qq:41577,rq:45469,tq:38669,uq:13768,wq:13777,xq:141842,yq:62985,zq:4724,Aq:59369,Bq:43927,Cq:43928,Dq:12924,Eq:100355,Hq:56219,Iq:27669,Jq:10337,Gq:47896,Kq:122629,Mq:139723,Lq:139722,
Nq:121258,Oq:107598,Pq:127991,Qq:96639,Rq:107536,Sq:130169,Tq:96661,Uq:145188,Vq:96658,Wq:116646,Xq:159428,Zq:168611,br:168612,Yq:121122,dr:96660,er:127738,fr:127083,gr:155281,hr:162959,ir:163566,jr:147842,kr:104443,lr:96659,mr:147595,pr:106442,qr:162776,rr:134840,sr:63667,tr:63668,ur:63669,vr:130686,wr:147036,xr:78314,yr:147799,zr:148649,Ar:55761,Br:127098,Cr:134841,Dr:96368,Er:67374,Fr:48992,Gr:146176,Hr:49956,Ir:31961,Jr:26388,Kr:23811,Lr:5E4,Mr:126250,Nr:96370,Or:47355,Pr:47356,Qr:37935,Rr:45521,
Sr:21760,Tr:83769,Ur:49977,Vr:49974,Wr:93497,Xr:93498,Yr:34325,Zr:140759,bs:115803,ds:123707,es:100081,gs:35309,hs:68314,ks:25602,ls:100339,ms:170873,ns:143516,qs:59018,rs:18248,ts:50625,us:9729,vs:37168,ws:37169,xs:21667,ys:16749,zs:18635,As:39305,Bs:18046,Cs:53969,Ds:8213,Es:93926,Fs:102852,Gs:110099,Hs:22678,Is:69076,Js:137575,Ls:139224,Ms:100856,Ns:154430,Os:17736,Ps:3832,Qs:147111,Rs:55759,Ss:64031,Ys:93044,Zs:93045,bt:170701,ct:170702,gt:34388,et:167841,ft:170419,ht:17657,jt:17655,kt:39579,
lt:39578,mt:170412,nt:77448,ot:8196,pt:11357,qt:69877,rt:8197,tt:168501,ut:156512,vt:161613,wt:156509,xt:161612,zt:161614,At:82039};function ru(){var a=vb(su),b;return(new zf(function(c,d){a.onSuccess=function(e){Mm(e)?c(new tu(e)):d(new uu("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new uu("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new uu("Request timed out","net.timeout",e))};
b=Tm("//googleads.g.doubleclick.net/pagead/id",a)})).tc(function(c){c instanceof Gf&&b.abort();
return Ef(c)})}
function uu(a,b,c){cb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
u(uu,cb);function tu(a){this.xhr=a}
;function vu(){this.h=0;this.za=null}
vu.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.za))&&"function"===typeof a.then?a:wu(a):2===this.h&&b?(a=b.call(c,this.za))&&"function"===typeof a.then?a:xu(a):this};
vu.prototype.getValue=function(){return this.za};
vu.prototype.$goog_Thenable=!0;function xu(a){var b=new vu;a=void 0===a?null:a;b.h=2;b.za=void 0===a?null:a;return b}
function wu(a){var b=new vu;a=void 0===a?null:a;b.h=1;b.za=void 0===a?null:a;return b}
;function yu(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:Hm(a)?"same-origin":"cors",credentials:Hm(a)?"same-origin":"include"};b={};for(var d=r(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function zu(){return yg()||bn&&cn("applewebkit")&&!cn("version")&&(!cn("safari")||cn("gsa/"))||Lc&&cn("version/")?!0:M("EOM_VISITOR_DATA")?!1:!0}
;function Au(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in Lk)if(Lk[c]==b.embeddedPlayerMode){b=Lk[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function Bu(a){cb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Cu;this.isTimeout=a instanceof uu&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Gf}
u(Bu,cb);Bu.prototype.name="BiscottiError";function Cu(){cb.call(this,"Biscotti ID is missing from server")}
u(Cu,cb);Cu.prototype.name="BiscottiMissingError";var su={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Du=null;function Eu(){if(P("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!zu())return Error("User has not consented - not fetching biscotti id.");var a=M("PLAYER_VARS",{});if("1"==tb(a))return Error("Biscotti ID is not available in private embed mode");if(Au(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function rm(){var a=Eu();if(void 0!==a)return Ef(a);Du||(Du=ru().then(Fu).tc(function(b){return Gu(2,b)}));
return Du}
function Fu(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Cu;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Cu;a=a.id;sm(a);Du=wu(a);Hu(18E5,2);return a}
function Gu(a,b){b=new Bu(b);sm("");Du=xu(b);0<a&&Hu(12E4,a-1);throw b;}
function Hu(a,b){Nm(function(){ru().then(Fu,function(c){return Gu(b,c)}).tc(eb)},a)}
function Iu(){try{var a=B("yt.ads.biscotti.getId_");return a?a():rm()}catch(b){return Ef(b)}}
;function Ju(a){if("1"!=tb(M("PLAYER_VARS",{}))){a&&qm();try{Iu().then(function(){},function(){}),Nm(Ju,18E5)}catch(b){wm(b)}}}
;function Ku(){var a=wn.getInstance(),b=zn(119),c=1<window.devicePixelRatio;if(document.body&&ui(document.body,"exp-invert-logo"))if(c&&!ui(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!ui(d,"inverted-hdpi")){var e=si(d);ti(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&ui(document.body,"inverted-hdpi")&&vi();if(b!=c){b="f"+(Math.floor(119/31)+1);d=An(b)||0;d=c?d|67108864:d&-67108865;0==d?delete vn[b]:(c=d.toString(16),vn[b]=
c.toString());c=!0;P("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in vn)d.push(f+"="+encodeURIComponent(String(vn[f])));sn(b,d.join("&"),63072E3,a.i,c)}}
;function Lu(){this.df=!0}
function Mu(a){var b={},c=Ag([]);c&&(b.Authorization=c,c=a=null==a?void 0:a.sessionIndex,void 0===c&&(c=Number(M("SESSION_INDEX",0)),c=isNaN(c)?0:c),P("voice_search_auth_header_removal")||(b["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in jm||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in jm&&(b["X-Goog-PageId"]=M("DELEGATED_SESSION_ID")));return b}
;var Nu={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var Ou=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Pu(){var a=void 0===a?window.location.href:a;if(P("kevlar_disable_theme_param"))return null;lc(oc(5,a));try{var b=Fm(a).theme;return Ou.get(b)||null}catch(c){}return null}
;function Qu(){this.h={};if(this.i=un()){var a=wg.get("CONSISTENCY",void 0);a&&Ru(this,{encryptedTokenJarContents:a})}}
Qu.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.La.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=r(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Ru(this,a)}};
function Ru(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&sn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Su=window.location.hostname.split(".").slice(-2).join(".");function Tu(){var a=M("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===M("INNERTUBE_CLIENT_NAME")&&(this.h=Uu(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Vu;Tu.getInstance=function(){Vu=B("yt.clientLocationService.instance");Vu||(Vu=new Tu,A("yt.clientLocationService.instance",Vu));return Vu};
l=Tu.prototype;l.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
l.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===M("INNERTUBE_CLIENT_NAME")?(this.h=Uu(this))&&this.h.set("yt-location-playability-token",a,15552E3):sn("YT_CL",JSON.stringify({loctok:a}),15552E3,Su,!0))};
function Uu(a){return void 0===a.h?new Qn("yt-client-location"):a.h}
l.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=Uu(this))&&this.h.remove("yt-location-playability-token"):tn("YT_CL")};
l.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===M("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
l.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Wu(a,b){var c,d=null==(c=Hs(a,Kk))?void 0:c.signal;if(d&&b.Ob&&(c=b.Ob[d]))return c();var e;if((c=null==(e=Hs(a,Ik))?void 0:e.request)&&b.he&&(e=b.he[c]))return e();for(var f in a)if(b.hd[f]&&(a=b.hd[f]))return a()}
;function Xu(a){return function(){return new a}}
;var Yu={},Zu=(Yu.WEB_UNPLUGGED="^unplugged/",Yu.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Yu.WEB_UNPLUGGED_OPS="^unplugged/",Yu.WEB_UNPLUGGED_PUBLIC="^unplugged/",Yu.WEB_CREATOR="^creator/",Yu.WEB_KIDS="^kids/",Yu.WEB_EXPERIMENTS="^experiments/",Yu.WEB_MUSIC="^music/",Yu.WEB_REMIX="^music/",Yu.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Yu.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Yu);
function $u(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Zu[b];if(c){var d=new RegExp(c),e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Zu).forEach(function(g){var h=r(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function av(){}
av.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Nu:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=M("INNERTUBE_CONTEXT");if(g){g=wb(g);P("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=M("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;wn.getInstance();var m="USER_INTERFACE_THEME_LIGHT";zn(165)?m="USER_INTERFACE_THEME_DARK":zn(174)?m="USER_INTERFACE_THEME_LIGHT":!P("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:Pu()||m;h.userInterfaceTheme=k;if(!f){if(k=
Gn())h.connectionType=k;P("web_log_effective_connection_type")&&(k=Hn())&&(g.client.effectiveConnectionType=k)}var n;if(P("web_log_memory_total_kbytes")&&(null==(n=z.navigator)?0:n.deviceMemory)){var p;n=null==(p=z.navigator)?void 0:p.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}p=Fm(z.location.href);!P("web_populate_internal_geo_killswitch")&&p.internalcountrycode&&(h.internalGeo=p.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:z.location.href},P("kevlar_woffle")&&
qn.h&&(p=qn.h,h.mainAppWebInfo.pwaInstallabilityStatus=!p.h&&p.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=rn(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!P("web_lr_app_quality_killswitch")&&(p=M("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:p})),p=M("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||
{},{certificationScope:p}));if(!P("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var v=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(xb){}v=void 0}v&&(h.timeZone=v)}(v=om())?h.experimentsToken=v:delete h.experimentsToken;v=pm();Qu.h||(Qu.h=new Qu);h=Qu.h.h;p=[];n=0;for(var t in h)p[n++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:v,consistencyTokenJars:p});!P("web_prequest_context_killswitch")&&(t=M("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&
(g.request.externalPrequestContext=t);v=wn.getInstance();t=zn(58);v=v.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);v&&(g.user.lockedSafetyMode=!0);P("warm_op_csn_cleanup")?e&&(f=ju())&&(g.clientScreenNonce=f):!f&&(f=ju())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Tu.getInstance().setLocationOnInnerTubeContext(g);try{var y=Im(),D=y.bid;delete y.bid;g.adSignalsInfo={params:[],bid:D};var E=
r(Object.entries(y));for(var O=E.next();!O.done;O=E.next()){var N=r(O.value),S=N.next().value,aa=N.next().value;y=S;D=aa;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:y,value:""+D})}}catch(xb){Pt(xb)}E=g}else Pt(Error("Error: No InnerTubeContext shell provided in ytconfig.")),E={};E={context:E};if(O=this.h(a)){this.i(E,O,b);var W;b="/youtubei/v1/"+$u(this.j());(O=null==(W=Hs(a.commandMetadata,Jk))?void 0:W.apiUrl)&&(b=O);W=b;(b=M("INNERTUBE_HOST_OVERRIDE"))&&(W=String(b)+String(qc(W)));b=
{};b.key=M("INNERTUBE_API_KEY");P("json_condensed_response")&&(b.prettyPrint="false");W=Gm(W,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:W,kb:yu(W),La:E,config:a};a.config.Zb?a.config.Zb.identity=c:a.config.Zb={identity:c};return a}Pt(new Q("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(av.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function bv(){}
u(bv,av);bv.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",kb:yu("/getDatasyncIdsEndpoint","GET"),La:{}}};
bv.prototype.j=function(){return[]};
bv.prototype.h=function(){};
bv.prototype.i=function(){};var cv={},dv=(cv.GET_DATASYNC_IDS=Xu(bv),cv);function ev(a){var b=Ka.apply(1,arguments);if(!fv(a)||b.some(function(d){return!fv(d)}))throw Error("Only objects may be merged.");
b=r(b);for(var c=b.next();!c.done;c=b.next())gv(a,c.value);return a}
function gv(a,b){for(var c in b)if(fv(b[c])){if(c in a&&!fv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});gv(a[c],b[c])}else if(hv(b[c])){if(c in a&&!hv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);iv(a[c],b[c])}else a[c]=b[c];return a}
function iv(a,b){b=r(b);for(var c=b.next();!c.done;c=b.next())c=c.value,fv(c)?a.push(gv({},c)):hv(c)?a.push(iv([],c)):a.push(c);return a}
function fv(a){return"object"===typeof a&&!Array.isArray(a)}
function hv(a){return"object"===typeof a&&Array.isArray(a)}
;function jv(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},A("ytcsi."+(a||"")+"data_",b));return b}
function kv(a){a=jv(a);a.info||(a.info={});return a.info}
function lv(a){a=jv(a);a.metadata||(a.metadata={});return a.metadata}
function mv(a){a=jv(a);a.tick||(a.tick={});return a.tick}
function nv(a){a=jv(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function ov(a){a=nv(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function pv(a){var b=jv(a).nonce;b||(b=Zt(),jv(a).nonce=b);return b}
;function qv(a,b){lq.call(this,1,arguments);this.timer=b}
u(qv,lq);var rv=new mq("aft-recorded",qv);var sv=window;function tv(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function uv(){var a;if(P("csi_use_performance_navigation_timing")||P("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==T?void 0:null==(a=T.getEntriesByType)?void 0:null==(b=a.call(T,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=vv(e.requestStart),e.responseEnd=vv(e.responseEnd),e.redirectStart=vv(e.redirectStart),e.redirectEnd=vv(e.redirectEnd),e.domainLookupEnd=vv(e.domainLookupEnd),e.connectStart=vv(e.connectStart),e.connectEnd=
vv(e.connectEnd),e.responseStart=vv(e.responseStart),e.secureConnectionStart=vv(e.secureConnectionStart),e.domainLookupStart=vv(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=T.timing}else a=T.timing;return a}
function vv(a){return Math.round(wv()+a)}
function wv(){return(P("csi_use_time_origin")||P("csi_use_time_origin_tvhtml5"))&&T.timeOrigin?Math.floor(T.timeOrigin):T.timing.navigationStart}
var T=sv.performance||sv.mozPerformance||sv.msPerformance||sv.webkitPerformance||new tv;var xv=!1,yv={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Ya(T.clearResourceTimings||T.webkitClearResourceTimings||T.mozClearResourceTimings||T.msClearResourceTimings||T.oClearResourceTimings||eb,T);function zv(a){var b=Av("aft",a);if(b)return b;b=M((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Av(b[d],a);if(e)return e}return NaN}
function Av(a,b){if(a=mv(b)[a])return"number"===typeof a?a:a[a.length-1]}
function Bv(a){var b=Av("_start",a),c=zv(a);b&&c&&!xv&&(rq(rv,new qv(Math.round(c-b),a)),xv=!0)}
function Cv(a,b){for(var c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Cv(a[d],b[d]))return!1;return!0}
function Dv(){if(T.getEntriesByType){var a=T.getEntriesByType("paint");if(a=lb(a,function(b){return"first-paint"===b.name}))return vv(a.startTime)}a=T.timing;
return a.He?Math.max(0,a.He):0}
;function Ev(){var a=B("ytcsi.debug");a||(a=[],A("ytcsi.debug",a),A("ytcsi.reference",{}));return a}
function Fv(a){a=a||"";var b=B("ytcsi.reference");b||(Ev(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=Ev(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var U={},Gv=(U.auto_search="LATENCY_ACTION_AUTO_SEARCH",U.ad_to_ad="LATENCY_ACTION_AD_TO_AD",U.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",U["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",U.app_startup="LATENCY_ACTION_APP_STARTUP",U["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",U["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",U["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",U["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",U.browse="LATENCY_ACTION_BROWSE",
U.cast_splash="LATENCY_ACTION_CAST_SPLASH",U.channels="LATENCY_ACTION_CHANNELS",U.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",U["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",U["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",U["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",U["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",U["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",U["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",
U["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",U["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",U["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",U["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",U["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",U["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",U["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",U.chips="LATENCY_ACTION_CHIPS",
U["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",U["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",U["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",U.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",U.embed="LATENCY_ACTION_EMBED",U.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",U.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",U.explore="LATENCY_ACTION_EXPLORE",U.home=
"LATENCY_ACTION_HOME",U.library="LATENCY_ACTION_LIBRARY",U.live="LATENCY_ACTION_LIVE",U.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",U.onboarding="LATENCY_ACTION_ONBOARDING",U.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",U["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",U["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",U["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",U["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",U["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",
U["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",U["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",U["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",U["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",U["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",U.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",U.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",U.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",
U.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",U["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",U["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",U.prebuffer="LATENCY_ACTION_PREBUFFER",U.prefetch="LATENCY_ACTION_PREFETCH",U.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",U.profile_switcher="LATENCY_ACTION_LOGIN",U.reel_watch="LATENCY_ACTION_REEL_WATCH",U.results="LATENCY_ACTION_RESULTS",U["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",U.search_ui="LATENCY_ACTION_SEARCH_UI",
U.search_suggest="LATENCY_ACTION_SUGGEST",U.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",U.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",U.seek="LATENCY_ACTION_PLAYER_SEEK",U.settings="LATENCY_ACTION_SETTINGS",U.store="LATENCY_ACTION_STORE",U.tenx="LATENCY_ACTION_TENX",U.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",U.watch="LATENCY_ACTION_WATCH",U.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",U["watch,watch7"]="LATENCY_ACTION_WATCH",U["watch,watch7_html5"]="LATENCY_ACTION_WATCH",U["watch,watch7ad"]=
"LATENCY_ACTION_WATCH",U["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",U.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",U.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",U["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",U["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",U["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",U["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",U["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",U["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",
U["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",U["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",U["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",U.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",U.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",U.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",U),V={},Hv=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",
V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",
V.is_continuation="isContinuation",V.is_nav="isNavigation",V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",
V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt="playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs=
"tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",
V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),Iv="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Jv={},Kv=(Jv.ccs="CANARY_STATE_",
Jv.mver="MEASUREMENT_VERSION_",Jv.pis="PLAYER_INITIALIZED_STATE_",Jv.yt_pt="LATENCY_PLAYER_",Jv.pa="LATENCY_ACTION_",Jv.ctop="TOP_ENTITY_TYPE_",Jv.yt_vst="VIDEO_STREAM_TYPE_",Jv),Lv="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Mv(a){return Gv[a]||"LATENCY_ACTION_UNKNOWN"}
function Nv(a,b,c){c=nv(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Hv){c=Hv[a];0<=gb(Iv,c)&&(b=!!b);a in Kv&&"string"===typeof b&&(b=Kv[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return ev({},d)}0<=gb(Lv,a)||Qt(new Q("Unknown label logged with GEL CSI",a))}
;var X={LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_GEL_COMPRESSION:215,LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE:204,LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC:203,LATENCY_ACTION_COMMERCE_TRANSACTION:184,
LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,
LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,
LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,
LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,
LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_CONNECT_TO_SESSION:190,
LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,
LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_PRODUCER_EXPORT_PROJECT:193,LATENCY_ACTION_PRODUCER_EDITOR:192,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,
LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,
LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT:219,LATENCY_ACTION_CREATOR_VIDEO_POLICY:217,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT:218,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_CLAIMS:216,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,
LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,
LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CMS_VIDEOS:202,LATENCY_ACTION_CREATOR_CMS_REPORTS:201,LATENCY_ACTION_CREATOR_CMS_RELEASES:226,LATENCY_ACTION_CREATOR_CMS_POLICIES:225,LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC:224,LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING:200,LATENCY_ACTION_CREATOR_CMS_LICENSES:223,
LATENCY_ACTION_CREATOR_CMS_ISSUES:191,LATENCY_ACTION_CREATOR_CMS_DASHBOARD:199,LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY:198,LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS:197,LATENCY_ACTION_CREATOR_CMS_CHANNELS:196,LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS:222,LATENCY_ACTION_CREATOR_CMS_ASSETS:195,LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS:214,LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES:209,LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY:208,LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP:207,LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA:205,
LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES:212,LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES:206,LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS:221,LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS:210,LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION:213,LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS:211,LATENCY_ACTION_CREATOR_CMS_ART_TRACKS:220,LATENCY_ACTION_CREATOR_CMS_ANALYTICS:194,LATENCY_ACTION_CREATOR_CMS_ALLOWLIST:227,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,
LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,
LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,
LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_HOME:1,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_USER_ACTION:189,LATENCY_ACTION_INFRASTRUCTURE:188,LATENCY_ACTION_PAGE_NAVIGATION:187,LATENCY_ACTION_UNKNOWN:0};X[X.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";
X[X.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";X[X.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";X[X.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";X[X.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";X[X.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";X[X.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";
X[X.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";X[X.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";X[X.LATENCY_ACTION_GEL_COMPRESSION]="LATENCY_ACTION_GEL_COMPRESSION";X[X.LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE]="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE";X[X.LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC]="LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC";X[X.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";X[X.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";
X[X.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";X[X.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";X[X.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";X[X.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";X[X.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";X[X.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";
X[X.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";X[X.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";X[X.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";X[X.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";X[X.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";
X[X.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";X[X.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";X[X.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";X[X.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";X[X.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";X[X.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";X[X.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";
X[X.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";X[X.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";X[X.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";X[X.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";X[X.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";X[X.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";X[X.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";
X[X.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";X[X.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";X[X.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";X[X.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";X[X.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";X[X.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";
X[X.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";X[X.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";X[X.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";X[X.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";X[X.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";X[X.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";
X[X.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";X[X.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";X[X.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";X[X.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";X[X.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";X[X.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";
X[X.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";X[X.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";X[X.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";X[X.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";X[X.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";X[X.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";
X[X.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";X[X.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";X[X.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";X[X.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";X[X.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";X[X.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";X[X.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";
X[X.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";X[X.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";X[X.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";X[X.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";X[X.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";X[X.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";X[X.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";
X[X.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";X[X.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";X[X.LATENCY_ACTION_MDX_CONNECT_TO_SESSION]="LATENCY_ACTION_MDX_CONNECT_TO_SESSION";X[X.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";X[X.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";X[X.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";X[X.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";
X[X.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";X[X.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";X[X.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";X[X.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";X[X.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";X[X.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";
X[X.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";X[X.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";X[X.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";X[X.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";X[X.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";X[X.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";X[X.LATENCY_ACTION_PRODUCER_EXPORT_PROJECT]="LATENCY_ACTION_PRODUCER_EXPORT_PROJECT";
X[X.LATENCY_ACTION_PRODUCER_EDITOR]="LATENCY_ACTION_PRODUCER_EDITOR";X[X.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";X[X.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";X[X.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";X[X.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";X[X.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";
X[X.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";X[X.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";X[X.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";X[X.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";X[X.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";X[X.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";X[X.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";X[X.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";
X[X.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";X[X.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";X[X.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";X[X.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";X[X.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";X[X.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";
X[X.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";X[X.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";X[X.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";X[X.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";X[X.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";X[X.LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT";
X[X.LATENCY_ACTION_CREATOR_VIDEO_POLICY]="LATENCY_ACTION_CREATOR_VIDEO_POLICY";X[X.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";X[X.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";X[X.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";X[X.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";X[X.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";
X[X.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";X[X.LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT";X[X.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";X[X.LATENCY_ACTION_CREATOR_VIDEO_CLAIMS]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS";X[X.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";
X[X.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";X[X.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";X[X.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";X[X.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";X[X.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";X[X.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";
X[X.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";X[X.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";
X[X.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";X[X.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";X[X.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";X[X.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";X[X.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";X[X.LATENCY_ACTION_CREATOR_CMS_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_VIDEOS";
X[X.LATENCY_ACTION_CREATOR_CMS_REPORTS]="LATENCY_ACTION_CREATOR_CMS_REPORTS";X[X.LATENCY_ACTION_CREATOR_CMS_RELEASES]="LATENCY_ACTION_CREATOR_CMS_RELEASES";X[X.LATENCY_ACTION_CREATOR_CMS_POLICIES]="LATENCY_ACTION_CREATOR_CMS_POLICIES";X[X.LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC";X[X.LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING";X[X.LATENCY_ACTION_CREATOR_CMS_LICENSES]="LATENCY_ACTION_CREATOR_CMS_LICENSES";
X[X.LATENCY_ACTION_CREATOR_CMS_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ISSUES";X[X.LATENCY_ACTION_CREATOR_CMS_DASHBOARD]="LATENCY_ACTION_CREATOR_CMS_DASHBOARD";X[X.LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY";X[X.LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS";X[X.LATENCY_ACTION_CREATOR_CMS_CHANNELS]="LATENCY_ACTION_CREATOR_CMS_CHANNELS";X[X.LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS";
X[X.LATENCY_ACTION_CREATOR_CMS_ASSETS]="LATENCY_ACTION_CREATOR_CMS_ASSETS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP";
X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS";X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION";
X[X.LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS";X[X.LATENCY_ACTION_CREATOR_CMS_ART_TRACKS]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS";X[X.LATENCY_ACTION_CREATOR_CMS_ANALYTICS]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_CMS_ALLOWLIST]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST";X[X.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";X[X.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";
X[X.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";X[X.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";X[X.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";X[X.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";X[X.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";X[X.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";
X[X.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";X[X.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";X[X.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";X[X.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";X[X.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";X[X.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";X[X.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";X[X.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";
X[X.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";X[X.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";X[X.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";X[X.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";X[X.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";X[X.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";X[X.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";
X[X.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";X[X.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";X[X.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";X[X.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";X[X.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";X[X.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";X[X.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";X[X.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";
X[X.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";X[X.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";X[X.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";X[X.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";X[X.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";X[X.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";X[X.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";X[X.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";
X[X.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";X[X.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";X[X.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";X[X.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";X[X.LATENCY_ACTION_USER_ACTION]="LATENCY_ACTION_USER_ACTION";X[X.LATENCY_ACTION_INFRASTRUCTURE]="LATENCY_ACTION_INFRASTRUCTURE";X[X.LATENCY_ACTION_PAGE_NAVIGATION]="LATENCY_ACTION_PAGE_NAVIGATION";X[X.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";
var Ov={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Ov[Ov.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Ov[Ov.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Ov[Ov.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";var Y={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};
Y[Y.CONN_INVALID]="CONN_INVALID";Y[Y.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";Y[Y.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";Y[Y.CONN_WIFI_METERED]="CONN_WIFI_METERED";Y[Y.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";Y[Y.CONN_DISCO]="CONN_DISCO";Y[Y.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";Y[Y.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";Y[Y.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";Y[Y.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";Y[Y.CONN_WIFI]="CONN_WIFI";Y[Y.CONN_NONE]="CONN_NONE";Y[Y.CONN_UNKNOWN]="CONN_UNKNOWN";
Y[Y.CONN_DEFAULT]="CONN_DEFAULT";
var Z={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Z[Z.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Z[Z.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Z[Z.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Z[Z.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Z[Z.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Z[Z.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Z[Z.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Z[Z.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Z[Z.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Z[Z.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Z[Z.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Z[Z.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Z[Z.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Z[Z.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Z[Z.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Z[Z.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Z[Z.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Z[Z.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Z[Z.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Z[Z.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Z[Z.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Z[Z.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Z[Z.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Z[Z.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Z[Z.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Z[Z.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Z[Z.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var Pv={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};Pv[Pv.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
Pv[Pv.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";Pv[Pv.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";Pv[Pv.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";Pv[Pv.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";Pv[Pv.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";Pv[Pv.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";Pv[Pv.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var Qv={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};Qv[Qv.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";Qv[Qv.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";Qv[Qv.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";Qv[Qv.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var Rv={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
Rv[Rv.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";Rv[Rv.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var Sv={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};Sv[Sv.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";Sv[Sv.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";Sv[Sv.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
Sv[Sv.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";Sv[Sv.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";Sv[Sv.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var Tv={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};Tv[Tv.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";Tv[Tv.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";Tv[Tv.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";Tv[Tv.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var Uv={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};Uv[Uv.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";Uv[Uv.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";Uv[Uv.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var Vv={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};Vv[Vv.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
Vv[Vv.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";Vv[Vv.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var Wv="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo".split(" ");var Xv=z.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",Xv);function Yv(){this.h=0}
function Zv(){Yv.h||(Yv.h=new Yv);return Yv.h}
Yv.prototype.tick=function(a,b,c,d){$v(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},P("web_csi_via_jspb")?(d=new Ql,F(d,1,a),F(d,2,b),a=new Tl,Vd(a,Ql,5,Ul,d),Ct(a,c)):Zn("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
Yv.prototype.info=function(a,b,c){var d=Object.keys(a).join("");$v(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,Zn("latencyActionInfo",a,{cttAuthInfo:c}))};
Yv.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));$v(this,"info_"+d+"_"+b)||(F(a,2,b),b={cttAuthInfo:c},c=new Tl,Vd(c,Ml,7,Ul,a),Ct(c,b))};
Yv.prototype.span=function(a,b,c){var d=Object.keys(a).join("");$v(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,Zn("latencyActionSpan",a,{cttAuthInfo:c}))};
function $v(a,b){Xv[b]=Xv[b]||{count:0};var c=Xv[b];c.count++;c.time=R();a.h||(a.h=Jn(function(){var d=R(),e;for(e in Xv)Xv[e]&&6E4<d-Xv[e].time&&delete Xv[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Q("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Qt(c)),!0):!1}
;function aw(a,b){Fv("").info.actionType=a;b&&km("TIMING_AFT_KEYS",b);km("TIMING_ACTION",a);if(P("web_csi_via_jspb")){a=M("TIMING_INFO",{});var c=new Ml;a=r(Object.entries(a));for(b=a.next();!b.done;b=a.next()){var d=r(b.value);b=d.next().value;d=d.next().value;switch(b){case "GetBrowse_rid":var e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetGuide_rid":e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetHome_rid":e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetPlayer_rid":e=
new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetSearch_rid":e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetSettings_rid":e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetTrending_rid":e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "GetWatchNext_rid":e=new Pl;F(e,1,b);F(e,2,String(d));Ol(c,e);break;case "yt_red":F(c,14,!!d);break;case "yt_ad":F(c,9,!!d)}}bw(c);c=new Ml;c=F(c,25,!0);c=F(c,1,X[Mv(M("TIMING_ACTION"))]);(a=M("PREVIOUS_ACTION"))&&F(c,13,X[Mv(a)]);(a=M("CLIENT_PROTOCOL"))&&
F(c,33,a);(a=M("CLIENT_TRANSPORT"))&&F(c,34,a);(a=ju())&&"UNDEFINED_CSN"!==a&&F(c,4,a);a=cw();1!==a&&-1!==a||F(c,6,!0);a=kv();P("skip_setting_info_in_csi_data_object")&&lv();F(c,3,"cold");dw(a);a=ew();if(0<a.length)for(a=r(a),b=a.next();!b.done;b=a.next())b=b.value,d=new Ll,F(d,1,b),Xd(c,83,Ll,d);bw(c)}else{a=M("TIMING_INFO",{});for(c in a)a.hasOwnProperty(c)&&fw(c,a[c]);c={isNavigation:!0,actionType:Mv(M("TIMING_ACTION"))};if(a=M("PREVIOUS_ACTION"))c.previousAction=Mv(a);if(a=M("CLIENT_PROTOCOL"))c.httpProtocol=
a;if(a=M("CLIENT_TRANSPORT"))c.transportProtocol=a;(a=ju())&&"UNDEFINED_CSN"!==a&&(c.clientScreenNonce=a);a=cw();if(1===a||-1===a)c.isVisible=!0;P("skip_setting_info_in_csi_data_object")&&lv();kv();c.loadType="cold";dw(kv());a=ew();if(0<a.length)for(c.resourceInfo=[],a=r(a),b=a.next();!b.done;b=a.next())c.resourceInfo.push({resourceCache:b.value});gw(c)}c=kv();a=ov();if(!(P("skip_setting_info_in_csi_data_object")&&"cold"!==lv().loadType||"cold"!==c.yt_lt&&"cold"!==a.loadType)){b=mv();d=nv();d=d.gelTicks?
d.gelTicks:d.gelTicks={};for(var f in b)if(!(f in d))if("number"===typeof b[f])hw(f,Av(f));else if(P("log_repeated_ytcsi_ticks")){e=r(b[f]);for(var g=e.next();!g.done;g=e.next())hw(f.slice(1),g.value)}f={};b=!1;d=r(Object.keys(c));for(e=d.next();!e.done;e=d.next())e=e.value,(e=Nv(e,c[e]))&&!Cv(ov(),e)&&(ev(a,e),ev(f,e),b=!0);b&&gw(f)}A("ytglobal.timingready_",!0);f=M("TIMING_ACTION");B("ytglobal.timingready_")&&f&&"_start"in mv()&&zv()&&Bv()}
function fw(a,b,c,d){if(null!==b){var e=kv(c);P("skip_setting_info_in_csi_data_object")?"yt_lt"===a&&(e="string"===typeof b?b:""+b,lv(c).loadType=e):e[a]=b;(a=Nv(a,b,c))&&gw(a,c,d)}}
function gw(a,b,c){if(!P("web_csi_via_jspb")||(void 0===c?0:c))c=Fv(b||""),ev(c.info,a),P("skip_setting_info_in_csi_data_object")&&a.loadType&&(c=a.loadType,lv(b).loadType=c),ev(ov(b),a),c=pv(b),b=jv(b).cttAuthInfo,Zv().info(a,c,b);else{c=new Ml;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":F(c,1,X[a[e]]);break;case "clientActionNonce":F(c,2,a[e]);break;case "clientScreenNonce":F(c,4,a[e]);break;case "loadType":F(c,3,a[e]);break;case "isPrewarmedLaunch":F(c,
92,a[e]);break;case "isFirstInstall":F(c,55,a[e]);break;case "networkType":F(c,5,Ov[a[e]]);break;case "connectionType":F(c,26,Y[a[e]]);break;case "detailedConnectionType":F(c,27,Z[a[e]]);break;case "isVisible":F(c,6,a[e]);break;case "playerType":F(c,7,Pv[a[e]]);break;case "clientPlaybackNonce":F(c,8,a[e]);break;case "adClientPlaybackNonce":F(c,28,a[e]);break;case "previousCpn":F(c,77,a[e]);break;case "targetCpn":F(c,76,a[e]);break;case "isMonetized":F(c,9,a[e]);break;case "isPrerollAllowed":F(c,16,
a[e]);break;case "isPrerollShown":F(c,17,a[e]);break;case "adType":F(c,12,a[e]);break;case "adTypesAllowed":F(c,36,a[e]);break;case "adNetworks":F(c,37,a[e]);break;case "previousAction":F(c,13,X[a[e]]);break;case "isRedSubscriber":F(c,14,a[e]);break;case "serverTimeMs":F(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":F(c,20,a[e]);break;case "targetVideoId":F(c,78,a[e]);break;case "adBreakType":F(c,21,Qv[a[e]]);break;case "isNavigation":F(c,25,a[e]);break;case "viewportHeight":F(c,
29,a[e]);break;case "viewportWidth":F(c,30,a[e]);break;case "screenHeight":F(c,84,a[e]);break;case "screenWidth":F(c,85,a[e]);break;case "browseId":F(c,31,a[e]);break;case "isCacheHit":F(c,32,a[e]);break;case "httpProtocol":F(c,33,a[e]);break;case "transportProtocol":F(c,34,a[e]);break;case "searchQuery":F(c,41,a[e]);break;case "isContinuation":F(c,42,a[e]);break;case "availableProcessors":F(c,43,a[e]);break;case "sdk":F(c,44,a[e]);break;case "isLocalStream":F(c,45,a[e]);break;case "navigationRequestedSameUrl":F(c,
64,a[e]);break;case "shellStartupDurationMs":F(c,70,a[e]);break;case "appInstallDataAgeMs":F(c,73,a[e]);break;case "latencyActionError":F(c,71,Rv[a[e]]);break;case "actionStep":F(c,79,a[e]);break;case "jsHeapSizeLimit":F(c,80,a[e]);break;case "totalJsHeapSize":F(c,81,a[e]);break;case "usedJsHeapSize":F(c,82,a[e]);break;case "sourceVideoDurationMs":F(c,90,a[e]);break;case "videoOutputFrames":F(c,93,a[e]);break;case "isResume":F(c,104,a[e]);break;case "debugTicksExcluded":F(c,105,a[e]);break;case "adPrebufferedTimeSecs":F(c,
39,a[e]);break;case "isLivestream":F(c,47,a[e]);break;case "liveStreamMode":F(c,91,Sv[a[e]]);break;case "adCpn2":F(c,48,a[e]);break;case "adDaiDriftMillis":F(c,49,a[e]);break;case "videoStreamType":F(c,53,Tv[a[e]]);break;case "playbackRequiresTap":F(c,56,a[e]);break;case "performanceNavigationTiming":F(c,67,a[e]);break;case "transactionType":F(c,74,Uv[a[e]]);break;case "playerRotationType":F(c,101,Vv[a[e]]);break;case "allowedPreroll":F(c,10,a[e]);break;case "shownPreroll":F(c,11,a[e]);break;case "getHomeRequestId":F(c,
57,a[e]);break;case "getSearchRequestId":F(c,60,a[e]);break;case "getPlayerRequestId":F(c,61,a[e]);break;case "getWatchNextRequestId":F(c,62,a[e]);break;case "getBrowseRequestId":F(c,63,a[e]);break;case "getLibraryRequestId":F(c,66,a[e]);break;case "isTransformerEnabledForFeature":F(c,106,a[e]);break;default:Wv.includes(f)&&wm(new Q("Codegen laipb translator asked to translate message field",""+f))}}catch(g){wm(Error("Codegen laipb translator failed to set "+f))}}bw(c,b)}}
function bw(a,b){if(P("skip_setting_info_in_csi_data_object")){var c=Zd(a,3);c&&(lv(b).loadType=c)}else c=nv(b),c.jspbInfos||(c.jspbInfos=[]),c.jspbInfos.push(ke(a));Fv(b||"").jspbInfo.push(a);c=pv(b);b=jv(b).cttAuthInfo;Zv().jspbInfo(a,c,b)}
function hw(a,b,c){if(!b&&"_"!==a[0]){var d=a;T.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),T.mark(d))}d=Fv(c||"");d.tick[a]=b||R();if(d.callback&&d.callback[a]){d=r(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=nv(c);d.gelTicks&&(d.gelTicks[a]=!0);e=mv(c);d=b||R();P("log_repeated_ytcsi_ticks")?a in e||(e[a]=d):e[a]=d;e=pv(c);var f=jv(c).cttAuthInfo;"_start"===a?(a=Zv(),$v(a,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},P("web_csi_via_jspb")?(a=new Kl,
F(a,1,e),e=new Tl,Vd(e,Kl,6,Ul,a),Ct(e,b)):Zn("latencyActionBaselined",{clientActionNonce:e},b))):Zv().tick(a,e,b,f);Bv(c);return d}
function iw(){var a=pv();requestAnimationFrame(function(){setTimeout(function(){a===pv()&&hw("ol",void 0,void 0)},0)})}
function cw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Wr+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function dw(a){var b=uv(),c=wv(),d=M("CSI_START_TIMESTAMP_MILLIS",0);0<d&&!P("embeds_web_enable_csi_start_override_killswitch")&&(c=d);c&&(hw("srt",b.responseStart),1!==a.prerender&&hw("_start",c,void 0));a=Dv();0<a&&hw("fpt",a);a=uv();a.isPerformanceNavigationTiming&&gw({performanceNavigationTiming:!0});hw("nreqs",a.requestStart,void 0);hw("nress",a.responseStart,void 0);hw("nrese",a.responseEnd,void 0);0<a.redirectEnd-a.redirectStart&&(hw("nrs",a.redirectStart,void 0),hw("nre",a.redirectEnd,void 0));
0<a.domainLookupEnd-a.domainLookupStart&&(hw("ndnss",a.domainLookupStart,void 0),hw("ndnse",a.domainLookupEnd,void 0));0<a.connectEnd-a.connectStart&&(hw("ntcps",a.connectStart,void 0),hw("ntcpe",a.connectEnd,void 0));a.secureConnectionStart>=wv()&&0<a.connectEnd-a.secureConnectionStart&&(hw("nstcps",a.secureConnectionStart,void 0),hw("ntcpe",a.connectEnd,void 0));T&&"getEntriesByType"in T&&jw()}
function kw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);hc()&&a.setAttribute("nonce",hc());return c?(a=T.getEntriesByName(c))&&a[0]&&(a=a[0],c=wv(),hw("rsf_"+b,c+Math.round(a.fetchStart)),hw("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function ew(){var a=[];if(document.querySelector&&T&&T.getEntriesByName)for(var b in yv)if(yv.hasOwnProperty(b)){var c=yv[b];kw(b,c)&&a.push(c)}return a}
function jw(){var a=window.location.protocol,b=T.getEntriesByType("resource");b=ib(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=kb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(hw("wffs",vv(b.startTime)),hw("wffe",vv(b.responseEnd)))}
var lw=window;lw.ytcsi&&(lw.ytcsi.info=fw,lw.ytcsi.tick=hw);var mw="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),nw=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function ow(a,b,c,d){this.m=a;this.W=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Ob||(a.Ob={});a.Ob=Object.assign({},dv,a.Ob)}
function pw(a,b,c,d){if(void 0!==ow.h){if(d=ow.h,a=[a!==d.m,b!==d.W,c!==d.l,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new Q("InnerTubeTransportService is already initialized",a);
}else ow.h=new ow(a,b,c,d)}
function qw(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Nu:c;var d=Wu(b,a.m);if(!d)return Ef(new Q("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?new zf(function(f){var g,h,k;return x(function(m){if(1==m.h){h="cors"===(null==(g=e.kb)?void 0:g.mode)?"cors":void 0;if(a.l.df){var n=e.config,p;n=null==n?void 0:null==(p=n.Zb)?void 0:p.sessionIndex;p=Mu({sessionIndex:n});k=Object.assign({},rw(h),p);return m.A(2)}return w(m,sw(e.config,
h),3)}2!=m.h&&(k=m.i);f(tw(a,e,k));m.h=0})}):Ef(new Q("Error: Failed to build request for command.",b))}
function uw(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.Xt)?0:d.au)&&a.j){d=r(mw);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function tw(a,b,c){var d,e,f,g,h,k,m,n,p,v,t,y,D,E,O,N,S,aa,W,xb,Za,qa,I,oa,ha,cf,df,Nd;return x(function(ta){switch(ta.h){case 1:ta.A(2);break;case 3:if((d=ta.i)&&!d.isExpired())return ta.return(Promise.resolve(d.h()));case 2:if(null==(e=b)?0:null==(f=e.La)?0:f.context)for(g=r([]),h=g.next();!h.done;h=g.next())k=h.value,k.Tt(b.La.context);if(null==(m=a.i)||!m.Yt(b.input,b.La)){ta.A(4);break}return w(ta,a.i.Ot(b.input,b.La),5);case 5:return n=ta.i,P("kevlar_process_local_innertube_responses_killswitch")||
uw(a,n,b),ta.return(n);case 4:return(t=null==(v=b.config)?void 0:v.Va)&&a.h.has(t)&&P("web_memoize_inflight_requests")?p=a.h.get(t):(y=JSON.stringify(b.La),O=null!=(E=null==(D=b.kb)?void 0:D.headers)?E:{},b.kb=Object.assign({},b.kb,{headers:Object.assign({},O,c)}),N=Object.assign({},b.kb),"POST"===b.kb.method&&(N=Object.assign({},N,{body:y})),(null==(S=b.config)?0:S.Pe)&&hw(b.config.Pe),aa=function(){return a.W.fetch(b.input,N,b.config)},p=aa(),t&&a.h.set(t,p)),w(ta,p,6);
case 6:if((W=ta.i)&&"error"in W&&(null==(xb=W)?0:null==(Za=xb.error)?0:Za.details))for(qa=W.error.details,I=r(qa),oa=I.next();!oa.done;oa=I.next())ha=oa.value,(cf=ha["@type"])&&-1<nw.indexOf(cf)&&(delete ha["@type"],W=ha);t&&a.h.has(t)&&a.h.delete(t);(null==(df=b.config)?0:df.Qe)&&hw(b.config.Qe);if(W||null==(Nd=a.i)||!Nd.Gt(b.input,b.La)){ta.A(7);break}return w(ta,a.i.Nt(b.input,b.La),8);case 8:W=ta.i;case 7:return uw(a,W,b),ta.return(W||void 0)}})}
function sw(a,b){var c,d,e,f;return x(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Zb)?void 0:d.sessionIndex;var h=Mu({sessionIndex:e});if(!(h instanceof zf)){var k=new zf(eb);Af(k,2,h);h=k}return w(g,h,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},rw(b),f)))})}
function rw(a){var b={"Content-Type":"application/json"};M("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=M("EOM_VISITOR_DATA"):M("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=M("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=M("LOGGED_IN",!1);"cors"!==a&&((a=M("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=M("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=M("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=M("DOMAIN_ADMIN_STATE"))&&
(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var vw=new vs("INNERTUBE_TRANSPORT_TOKEN");var ww=["share/get_web_player_share_panel"],xw=["feedback"],yw=["notification/modify_channel_preference"],zw=["browse/edit_playlist"],Aw=["subscription/subscribe"],Bw=["subscription/unsubscribe"];function Cw(){}
u(Cw,av);Cw.prototype.j=function(){return Aw};
Cw.prototype.h=function(a){return Hs(a,em)||void 0};
Cw.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(Cw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Dw(){}
u(Dw,av);Dw.prototype.j=function(){return Bw};
Dw.prototype.h=function(a){return Hs(a,dm)||void 0};
Dw.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(Dw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Ew(){}
u(Ew,av);Ew.prototype.j=function(){return xw};
Ew.prototype.h=function(a){return Hs(a,Mk)||void 0};
Ew.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(Ew.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Fw(){}
u(Fw,av);Fw.prototype.j=function(){return yw};
Fw.prototype.h=function(a){return Hs(a,cm)||void 0};
Fw.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Gw(){}
u(Gw,av);Gw.prototype.j=function(){return zw};
Gw.prototype.h=function(a){return Hs(a,bm)||void 0};
Gw.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Hw(){}
u(Hw,av);Hw.prototype.j=function(){return ww};
Hw.prototype.h=function(a){return Hs(a,am)};
Hw.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var xs=new vs("NETWORK_SLI_TOKEN");function Iw(a){this.h=a}
Iw.prototype.fetch=function(a,b){var c=this,d,e;return x(function(f){c.h&&(d=lc(oc(5,Bc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=new window.Request(a,b);return P("web_fetch_promise_cleanup_killswitch")?f.return(Promise.resolve(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Qt(g)}))):f.return(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Qt(g)}))})};
Iw.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Kt(),b=b.then(function(c){Qt(new Q("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
Iw[us]=[new ws];var Jw=new vs("NETWORK_MANAGER_TOKEN");var Kw;function Lw(a){a=void 0===a||a?Yt():Xt();for(var b=[],c=0;c<a.length;c++)b.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(a[c]&63));return b.join("")}
;function Mw(a){lq.call(this,1,arguments);this.csn=a}
u(Mw,lq);var uq=new mq("screen-created",Mw),Nw=[],Pw=Ow,Qw=0;function Rw(a,b,c,d,e,f,g){function h(){Qt(new Q("newScreen() parent element does not have a VE - rootVe",b))}
var k=Pw(),m=new cu({veType:b,youtubeData:f,jspbYoutubeData:void 0});f={sequenceGroup:k};e&&(f.cttAuthInfo=e);P("il_via_jspb")?(e=Al((new zl).h(k),m.getAsJspb()),c&&c.visualElement?(m=new Bl,c.clientScreenNonce&&F(m,2,c.clientScreenNonce),Cl(m,c.visualElement.getAsJspb()),g&&F(m,4,Vl[g]),G(e,Bl,5,m)):c&&h(),d&&F(e,3,d),Ht(e,f,a)):(e={csn:k,pageVe:m.getAsJson()},c&&c.visualElement?(e.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(e.implicitGesture.gestureType=
g)):c&&h(),d&&(e.cloneCsn=d),a?vt("screenCreated",e,a,f):Zn("screenCreated",e,f));rq(uq,new Mw(k));return k}
function Sw(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:mu(b)||void 0,
sequenceGroup:b};d=r(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(rb(g)||!g.trackingParams&&!g.veType)&&Qt(Error("Child VE logged with no data"));if(P("il_via_jspb")){var h=Fl((new Dl).h(b),c.getAsJspb());jb(e,function(k){k=k.getAsJspb();Xd(h,3,ul,k)});
"UNDEFINED_CSN"===b?Tw("visualElementAttached",f,void 0,h):It(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:jb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"===b?Tw("visualElementAttached",f,c):a?vt("visualElementAttached",c,a,f):Zn("visualElementAttached",c,f)}
function Uw(a,b,c,d,e,f){Vw(a,b,c,e,f)}
function Vw(a,b,c,d,e){var f={cttAuthInfo:mu(b)||void 0,sequenceGroup:b};P("il_via_jspb")?(d=(new Il).h(b),c=c.getAsJspb(),c=G(d,ul,2,c),c=F(c,4,1),e&&G(c,xl,3,e),"UNDEFINED_CSN"===b?Tw("visualElementShown",f,void 0,c):Dt(c,f,a)):(e={csn:b,ve:c.getAsJson(),eventType:1},d&&(e.clientData=d),"UNDEFINED_CSN"===b?Tw("visualElementShown",f,e):a?vt("visualElementShown",e,a,f):Zn("visualElementShown",e,f))}
function Ww(a,b,c){var d=!0,e=(d=void 0===d?!1:d)?16:8,f={cttAuthInfo:mu(b)||void 0,sequenceGroup:b,endOfSequence:d};P("il_via_jspb")?(e=(new Hl).h(b),c=c.getAsJspb(),c=G(e,ul,2,c),F(c,4,d?16:8),"UNDEFINED_CSN"===b?Tw("visualElementHidden",f,void 0,c):Et(c,f,a)):(d={csn:b,ve:c.getAsJson(),eventType:e},"UNDEFINED_CSN"===b?Tw("visualElementHidden",f,d):a?vt("visualElementHidden",d,a,f):Zn("visualElementHidden",d,f))}
function Ow(){if(P("enable_web_96_bit_csn"))var a=Lw();else if(P("enable_web_96_bit_csn_no_crypto"))a=Lw(!1);else{a=Math.random()+"";for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}a=cd(b,3)}return a}
function Tw(a,b,c,d){Nw.push({Nc:a,payload:c,Ta:d,options:b});Qw||(Qw=vq())}
function wq(a){if(Nw){for(var b=r(Nw),c=b.next();!c.done;c=b.next())if(c=c.value,P("il_via_jspb")&&c.Ta)switch(c.Ta.h(a.csn),c.Nc){case "screenCreated":Ht(c.Ta,c.options);break;case "visualElementAttached":It(c.Ta,c.options);break;case "visualElementShown":Dt(c.Ta,c.options);break;case "visualElementHidden":Et(c.Ta,c.options);break;case "visualElementGestured":Ft(c.Ta,c.options);break;case "visualElementStateChanged":Gt(c.Ta,c.options);break;default:Qt(new Q("flushQueue unable to map payloadName to JSPB setter"))}else c.payload&&
(c.payload.csn=a.csn,Zn(c.Nc,c.payload,c.options));Nw.length=0}Qw=0}
;function Xw(){this.l=new Set;this.h=new Set;this.m=new Map;this.client=Ur;this.csn=null}
function Yw(){Xw.h||(Xw.h=new Xw);return Xw.h}
Xw.prototype.j=function(a){this.client=a};
Xw.prototype.i=function(){this.clear();this.csn=ju()};
Xw.prototype.clear=function(){this.l.clear();this.h.clear();this.m.clear();this.csn=null};function Zw(){this.i=new Set;this.h=new Set;this.l=new Map;this.client=void 0;this.csn=null}
function $w(){Zw.h||(Zw.h=new Zw);return Zw.h}
Zw.prototype.j=function(a){P("safe_logging_library_killswitch")?this.client=a:vm(Yw().j).bind(Yw())(a)};
Zw.prototype.clear=function(){P("safe_logging_library_killswitch")?(this.i.clear(),this.h.clear(),this.l.clear(),this.csn=null):vm(Yw().clear).bind(Yw())()};function ax(){this.i=new Set;this.h=new Set;this.l=new Map}
ax.prototype.j=function(a){P("use_ts_visibilitylogger")&&$w().j(a)};
function bx(){var a=ax.getInstance();P("use_ts_visibilitylogger")?(a=$w(),P("safe_logging_library_killswitch")?(a.clear(),a.csn=ju()):vm(Yw().i).bind(Yw())()):a.clear()}
ax.prototype.clear=function(){P("use_ts_visibilitylogger")?$w().clear():(this.i.clear(),this.h.clear(),this.l.clear())};
Pa(ax);function cx(a,b){P("safe_logging_library_killswitch")?Vw(void 0,a,b):vm(Uw)(void 0,a,b,void 0,void 0,void 0)}
;function dx(){this.s=[];this.D=[];this.h=[];this.m=[];this.X=[];this.i=new Set;this.v=new Map}
dx.prototype.j=function(a){this.client=a};
function ex(a,b,c){c=void 0===c?0:c;b.then(function(d){a.i.has(c)&&a.l&&a.l();var e=ju(c),f=hu(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&Sw(a.client,e,f,[du(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&Sw(a.client,e,f,[du(d.playerResponse.trackingParams)])}})}
function fx(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.s.push([b,c]);else{var e=ju(d);c=c||hu(d);e&&c&&Sw(a.client,e,c,[b])}}
dx.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=ju(void 0===c?0:c)){a=this.client;var e=du(d);d={cttAuthInfo:mu(c)||void 0,sequenceGroup:c};P("il_via_jspb")?(b=(new Gl).h(c),e=e.getAsJspb(),b=G(b,ul,2,e),F(b,4,Vl.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK),"UNDEFINED_CSN"===c?Tw("visualElementGestured",d,void 0,b):Ft(b,d,a)):(e={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(e.clientData=b),"UNDEFINED_CSN"===
c?Tw("visualElementGestured",d,e):a?vt("visualElementGestured",e,a,d):Zn("visualElementGestured",e,d));b=!0}else b=!1;else b=!1;return b};
dx.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;0===c&&this.i.has(c)?this.D.push([a,b]):gx(this,a,b,c)};
function gx(a,b,c,d){d=void 0===d?0:d;var e=ju(d);d=b||hu(d);e&&d&&(a=a.client,b={cttAuthInfo:mu(e)||void 0,sequenceGroup:e},P("il_via_jspb")?(c=new Jl,c.h(e),d=d.getAsJspb(),G(c,ul,2,d),"UNDEFINED_CSN"===e?Tw("visualElementStateChanged",b,void 0,c):Gt(c,b,a)):(c={csn:e,ve:d.getAsJson(),clientData:c},"UNDEFINED_CSN"===e?Tw("visualElementStateChanged",b,c):a?vt("visualElementStateChanged",c,a,b):Zn("visualElementStateChanged",c,b)))}
function hx(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.l=function(){ix(a,b,c);var f=hu(c.layer);if(f){for(var g=r(a.s),h=g.next();!h.done;h=g.next())h=h.value,fx(a,h[0],h[1]||f,c.layer);f=r(a.D);for(g=f.next();!g.done;g=f.next())g=g.value,gx(a,g[0],g[1])}};
ju(c.layer)||a.l();if(c.ld)for(var d=r(c.ld),e=d.next();!e.done;e=d.next())ex(a,e.value,c.layer);else Pt(Error("Delayed screen needs a data promise."))}
function ix(a,b,c){c=void 0===c?{}:c;var d=void 0;c.layer||(c.layer=0);d=void 0!==c.Ke?c.Ke:c.layer;var e=ju(d);d=hu(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=M("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=Rw(a.client,b,f,c.kd,c.cttAuthInfo,g,c.Lt)}catch(p){St(p,{Vt:b,rootVe:d,St:void 0,Ht:e,Rt:f,kd:c.kd});Pt(p);return}nu(k,b,c.layer,
c.cttAuthInfo);e&&"UNDEFINED_CSN"!==e&&d&&!ku(e)&&Ww(a.client,e,d);a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=k||"");gw({clientScreenNonce:k});bx();var m=hu(c.layer);e&&"UNDEFINED_CSN"!==e&&m&&(P("web_mark_root_visible")||P("music_web_mark_root_visible"))&&cx(k,m);a.i.delete(c.layer||0);a.l=void 0;var n;null==(n=a.v.get(c.layer))||n.forEach(function(p,v){p?fx(a,v,p,c.layer):m&&fx(a,v,m,c.layer)});
jx(a)}
function jx(a){for(var b=0;b<a.m.length;b++){var c=a.m[b];try{c()}catch(d){Pt(d)}}for(b=a.m.length=0;b<a.X.length;b++){c=a.X[b];try{c()}catch(d){Pt(d)}}}
;function kx(){var a,b,c;return x(function(d){if(1==d.h)return a=Cs().resolve(vw),a?w(d,qw(a),2):(Qt(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return Qt(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.It;return d.return(c)}Qt(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var lx=z.caches,mx;function nx(a){var b=a.indexOf(":");return-1===b?{Cd:a}:{Cd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function ox(){return x(function(a){if(void 0!==mx)return a.return(mx);mx=new Promise(function(b){var c;return x(function(d){switch(d.h){case 1:return za(d,2),w(d,lx.open("test-only"),4);case 4:return w(d,lx.delete("test-only"),5);case 5:Aa(d,3);break;case 2:if(c=Ba(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(mx)})}
function px(a){var b,c,d,e,f,g,h;x(function(k){if(1==k.h)return w(k,ox(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return w(k,lx.keys(),3)}c=k.i;d=r(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=nx(f),h=g.datasyncId,!h||a.includes(h)||b.push(lx.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(n){return n})}))})}
function qx(){var a,b,c,d,e,f,g;return x(function(h){if(1==h.h)return w(h,ox(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=Pn("cache contains other");return w(h,lx.keys(),3)}b=h.i;c=r(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=nx(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function rx(){try{return!!self.localStorage}catch(a){return!1}}
;function sx(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function tx(a){if(rx()){var b=Object.keys(window.localStorage);b=r(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=sx(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function ux(){if(!rx())return!1;var a=Pn(),b=Object.keys(window.localStorage);b=r(b);for(var c=b.next();!c.done;c=b.next())if(c=sx(c.value),void 0!==c&&c!==a)return!0;return!1}
;function vx(){kx().then(function(a){a&&(mp(a),px(a),tx(a))})}
function wx(){var a=new Ir;ki.fa(function(){var b,c,d,e;return x(function(f){switch(f.h){case 1:if(P("ytidb_clear_optimizations_killswitch")){f.A(2);break}b=Pn("clear");if(b.startsWith("V")){var g=[b];mp(g);px(g);tx(g);return f.return()}c=ux();return w(f,qx(),3);case 3:return d=f.i,w(f,np(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.ma()?vx():a.l.add("publicytnetworkstatus-online",vx,!0,void 0,void 0),f.h=0}})})}
;var Qh=ia(["data-"]);function xx(a){a&&(a.dataset?a.dataset[yx("loaded")]="true":Ph(a))}
function zx(a,b){return a?a.dataset?a.dataset[yx(b)]:a.getAttribute("data-"+b):null}
var Ax={};function yx(a){return Ax[a]||(Ax[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Bx=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Cx=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Dx(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Bx,""),c=c.replace(Cx,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Ex(a,b,c)}
function Ex(a,b,c){c=void 0===c?null:c;var d=Fx(a),e=document.getElementById(d),f=e&&zx(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=os(d,b),b=""+Ta(b),Gx[b]=f),g||(e=Hx(a,d,function(){zx(e,"loaded")||(xx(e),rs(d),Nm($a(ss,d),0))},c)))}
function Hx(a,b,c,d){d=void 0===d?null:d;var e=mf("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Sh(e,mk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Ix(a){a=Fx(a);var b=document.getElementById(a);b&&(ss(a),b.parentNode.removeChild(b))}
function Jx(a,b){a&&b&&(a=""+Ta(b),(a=Gx[a])&&qs(a))}
function Fx(a){var b=document.createElement("a");ec(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+jc(a)}
var Gx={};var Kx=[],Lx=!1;function Ox(){if(!P("disable_biscotti_fetch_for_ad_blocker_detection")&&!P("disable_biscotti_fetch_entirely_for_all_web_clients")&&zu()){var a=M("PLAYER_VARS",{});if("1"!=tb(a)&&!Au(a)){var b=function(){Lx=!0;"google_ad_status"in window?km("DCLKSTAT",1):km("DCLKSTAT",2)};
try{Dx("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Kx.push(ki.fa(function(){if(!(Lx||"google_ad_status"in window)){try{Jx("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Lx=!0;km("DCLKSTAT",3)}},5E3))}}}
function Px(){var a=Number(M("DCLKSTAT",0));return isNaN(a)?0:a}
;function Qx(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Nn():d;this.l=c;this.j=d;this.i=new Hh;this.h=a;a={};c=r(this.h.entries());for(d=c.next();!d.done;a={Ab:a.Ab,Qb:a.Qb},d=c.next()){var e=r(d.value);d=e.next().value;e=e.next().value;a.Qb=d;a.Ab=e;d=function(f){return function(){f.Ab.Gc();b.h[f.Qb].oc=!0;b.h.every(function(g){return!0===g.oc})&&b.i.resolve()}}(a);
e=Kn(d,Rx(this,a.Ab));this.h[a.Qb]=Object.assign({},a.Ab,{Gc:d,jobId:e})}}
function Sx(a){var b=Array.from(a.h.keys()).sort(function(d,e){return Rx(a,a.h[e])-Rx(a,a.h[d])});
b=r(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.oc||(a.j.Ca(c.jobId),Kn(c.Gc,10))}
Qx.prototype.cancel=function(){for(var a=r(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.oc||this.j.Ca(b.jobId),b.oc=!0;this.i.resolve()};
function Rx(a,b){var c;return null!=(c=b.priority)?c:a.l}
;function Tx(a){this.state=a;this.plugins=[];this.j=void 0}
Tx.prototype.install=function(){this.plugins.push.apply(this.plugins,ja(Ka.apply(0,arguments)))};
Tx.prototype.uninstall=function(){var a=this;Ka.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
Tx.prototype.transition=function(a,b){var c=this,d=this.D.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.K===a}):f.from===c.state&&f.K===a});
if(d){this.l&&(Sx(this.l),this.l=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Ux(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Ux(a,b){return function(){var c=Ka.apply(0,arguments),d=b.filter(function(h){var k,m;return 10===(null!=(m=null!=(k=a.j)?k:h.priority)?m:0)}),e=b.filter(function(h){var k,m;
return 10!==(null!=(m=null!=(k=a.j)?k:h.priority)?m:0)});
Nn();var f={};d=r(d);for(var g=d.next();!g.done;f={Rb:f.Rb},g=d.next())f.Rb=g.value,Ln(function(h){return function(){h.Rb.callback.apply(h.Rb,ja(c))}}(f));
e=e.map(function(h){var k,m;return{Gc:function(){h.callback.apply(h,ja(c))},
priority:null!=(m=null!=(k=a.j)?k:h.priority)?m:0}});
e.length&&(a.l=new Qx(e))}}
ea.Object.defineProperties(Tx.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Vx(a){Tx.call(this,void 0===a?"document_active":a);var b=this;this.j=10;this.h=new Map;this.D=[{from:"document_active",K:"document_disposed_preventable",action:this.X},{from:"document_active",K:"document_disposed",action:this.m},{from:"document_disposed_preventable",K:"document_disposed",action:this.m},{from:"document_disposed_preventable",K:"flush_logs",action:this.s},{from:"document_disposed_preventable",K:"document_active",action:this.i},{from:"document_disposed",K:"flush_logs",action:this.s},
{from:"document_disposed",K:"document_active",action:this.i},{from:"document_disposed",K:"document_disposed",action:function(){}},
{from:"flush_logs",K:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
u(Vx,Tx);Vx.prototype.X=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Vx.prototype.m=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Vx.prototype.s=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Vx.prototype.i=function(){this.h=new Map};function Wx(a){Tx.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.D=[{from:"document_visibility_unknown",K:"document_visible",action:this.i},{from:"document_visibility_unknown",K:"document_hidden",action:this.h},{from:"document_visibility_unknown",K:"document_foregrounded",action:this.s},{from:"document_visibility_unknown",K:"document_backgrounded",action:this.m},{from:"document_visible",K:"document_hidden",action:this.h},{from:"document_visible",K:"document_foregrounded",action:this.s},
{from:"document_visible",K:"document_visible",action:this.i},{from:"document_foregrounded",K:"document_visible",action:this.i},{from:"document_foregrounded",K:"document_hidden",action:this.h},{from:"document_foregrounded",K:"document_foregrounded",action:this.s},{from:"document_hidden",K:"document_visible",action:this.i},{from:"document_hidden",K:"document_backgrounded",action:this.m},{from:"document_hidden",K:"document_hidden",action:this.h},{from:"document_backgrounded",K:"document_hidden",action:this.h},
{from:"document_backgrounded",K:"document_backgrounded",action:this.m},{from:"document_backgrounded",K:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
P("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
u(Wx,Tx);Wx.prototype.i=function(a,b){a(null==b?void 0:b.event);P("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Wx.prototype.h=function(a,b){a(null==b?void 0:b.event);P("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Wx.prototype.m=function(a,b){a(null==b?void 0:b.event)};
Wx.prototype.s=function(a,b){a(null==b?void 0:b.event)};function Xx(){this.h=new Vx;this.i=new Wx}
Xx.prototype.install=function(){var a=Ka.apply(0,arguments);this.h.install.apply(this.h,ja(a));this.i.install.apply(this.i,ja(a))};function Yx(){Xx.call(this);var a={};this.install((a.document_disposed={callback:this.j},a));a={};this.install((a.flush_logs={callback:this.l},a))}
var Zx;u(Yx,Xx);Yx.prototype.l=function(){if(P("web_fp_via_jspb")){var a=new tl,b=ju();b&&F(a,1,b);b=new Tl;Vd(b,tl,380,Ul,a);Ct(b);P("web_fp_via_jspb_and_json")&&Zn("finalPayload",{csn:ju()})}else Zn("finalPayload",{csn:ju()})};
Yx.prototype.j=function(){Ut(Vt)};function $x(){}
$x.getInstance=function(){var a=B("ytglobal.storage_");a||(a=new $x,A("ytglobal.storage_",a));return a};
$x.prototype.estimate=function(){var a,b,c;return x(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(ay()):d.return()})};
function ay(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
A("ytglobal.storageClass_",$x);function Xn(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=nm("ytidb_transaction_ended_event_rate_limit_session",.2)}
Xn.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":P("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":P("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":by(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=nm("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function by(a,b){$x.getInstance().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:cy(null==c?void 0:c.usage),deviceStorageQuotaMbytes:cy(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function cy(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function dy(a,b,c){J.call(this);var d=this;c=c||M("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.i="widget";this.R=!!a;this.N=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.R&&(d.sessionId&&d.sessionId!=f.id||d.i&&d.i!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.s&&(!d.v||0<=gb(d.v,f.func))&&d.s(f.func,f.args,e.origin)}}};
this.v=this.j=this.s=null;window.addEventListener("message",this.N)}
u(dy,J);dy.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.i&&(a.channel=this.i);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){xm(d)}}};
dy.prototype.L=function(){window.removeEventListener("message",this.N);J.prototype.L.call(this)};function ey(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new dy(!!M("WIDGET_ID_ENFORCE")),b=this.Me.bind(this);a.s=b;a.v=null;this.h.i="widget";if(a=M("WIDGET_ID"))this.h.sessionId=a}
l=ey.prototype;l.Me=function(a,b,c){"addEventListener"===a&&b?this.Fc(b[0],c):this.Wc(a,b,c)};
l.Wc=function(){};
l.xc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
l.Fc=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.xc(a,b)),this.j[a]=!0)};
l.addEventListener=function(){};
l.pe=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Ac());this.sendMessage("onReady");hb(this.i,this.Jd,this);this.i=[]};
l.Ac=function(){return null};
function fy(a,b){a.sendMessage("infoDelivery",b)}
l.Jd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
l.sendMessage=function(a,b){this.Jd({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.h=null};var gy={},hy=(gy["api.invalidparam"]=2,gy.auth=150,gy["drm.auth"]=150,gy["heartbeat.net"]=150,gy["heartbeat.servererror"]=150,gy["heartbeat.stop"]=150,gy["html5.unsupportedads"]=5,gy["fmt.noneavailable"]=5,gy["fmt.decode"]=5,gy["fmt.unplayable"]=5,gy["html5.missingapi"]=5,gy["html5.unsupportedlive"]=5,gy["drm.unavailable"]=5,gy["mrm.blocked"]=151,gy);var iy=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function jy(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function ky(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=r(iy);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function ly(a,b,c,d){if(Sa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function my(a){ey.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.We.bind(this));this.addEventListener("onVolumeChange",this.Xe.bind(this));this.addEventListener("onApiChange",this.Re.bind(this));this.addEventListener("onPlaybackQualityChange",this.Te.bind(this));this.addEventListener("onPlaybackRateChange",this.Ue.bind(this));this.addEventListener("onStateChange",this.Ve.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Ye.bind(this))}
u(my,ey);l=my.prototype;
l.Wc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&jy(a)){var d=b;if(Sa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=ky(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=ky(e);break;case "loadPlaylist":case "cuePlaylist":e=ly(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);jy(a)&&fy(this,this.Ac())}};
l.Fc=function(a,b){("onReady"===a||"onError"===a&&this.l)&&this.api.logApiCall(a+" invocation",b);this.api.logApiCall(a+" registration",b);ey.prototype.Fc.call(this,a,b)};
l.xc=function(a,b){var c=this,d=ey.prototype.xc.call(this,a,b);return function(e){c.api.logApiCall(a+" invocation",b);d(e)}};
l.onReady=function(){var a=this.pe.bind(this);this.h.j=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.sendMessage("onError",(a?hy[a]||b:b).toString())}};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.Ac=function(){if(!this.api)return null;var a=this.api.getApiInterface();mb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.Ve=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());fy(this,a)};
l.Te=function(a){fy(this,{playbackQuality:a})};
l.Ue=function(a){fy(this,{playbackRate:a})};
l.Re=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.Xe=function(){fy(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.We=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());fy(this,a)};
l.Ye=function(){var a={sphericalProperties:this.api.getSphericalProperties()};fy(this,a)};
l.dispose=function(){ey.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function ny(a){J.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.Fd,this)}
u(ny,J);l=ny.prototype;l.start=function(){this.started||this.h()||(this.started=!0,this.connection.lb("RECEIVING"))};
l.lb=function(a,b){this.started&&!this.h()&&this.connection.lb(a,b)};
l.Fd=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=oy(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=py(a,c))&&this.lb(a,c))}}};
l.addListener=function(a){if(!(a in this.i)){var b=this.Se.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
l.Se=function(a,b){this.started&&!this.h()&&this.connection.lb(a,this.zc(a,b))};
l.zc=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
l.L=function(){var a=this.connection;a.h()||Ii(a.i,"command",this.Fd,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);J.prototype.L.call(this)};function qy(a,b){ny.call(this,b);this.api=a;this.start()}
u(qy,ny);qy.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
qy.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function oy(a,b){switch(a){case "loadVideoById":return a=ky(b),[a];case "cueVideoById":return a=ky(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=ly(b),[a];case "cuePlaylist":return a=ly(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function py(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
qy.prototype.zc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return ny.prototype.zc.call(this,a,b)};
qy.prototype.L=function(){ny.prototype.L.call(this);delete this.api};function ry(a){a=void 0===a?!1:a;J.call(this);this.i=new Hi(a);te(this,this.i)}
ab(ry,J);ry.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
ry.prototype.m=function(a,b){this.h()||this.i.cb.apply(this.i,arguments)};function sy(a,b,c){ry.call(this);this.l=a;this.j=b;this.id=c}
u(sy,ry);sy.prototype.lb=function(a,b){this.h()||this.l.lb(this.j,this.id,a,b)};
sy.prototype.L=function(){this.j=this.l=null;ry.prototype.L.call(this)};function ty(a,b,c){J.call(this);this.i=a;this.origin=c;this.j=cs(window,"message",this.l.bind(this));this.connection=new sy(this,a,b);te(this,this.connection)}
u(ty,J);ty.prototype.lb=function(a,b,c,d){this.h()||a!==this.i||(a={id:b,command:c},d&&(a.data=d),this.i.postMessage(JSON.stringify(a),this.origin))};
ty.prototype.l=function(a){if(!this.h()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.h()||c.m("command",b.command,b.data,a.origin)}}}};
ty.prototype.L=function(){ds(this.j);this.i=null;J.prototype.L.call(this)};function uy(){this.state=1;this.h=null}
l=uy.prototype;
l.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript;Eb("From proto message. b/166824318");d=d.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=Bb();d=f?f.createScript(d):d;d=new Gb(d,Fb)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,Eb("From proto message. b/166824318"),e=Kb(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());vy(this,d,e,
a.program,b,c)}else Qt(Error("Cannot initialize botguard without program"))};
function vy(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Dx(c,function(){window[g]?wy(a,d,g,e):(a.state=3,Ix(c),Qt(new Q("Unable to load Botguard","from "+c)))},f)):b?(f=mf("SCRIPT"),b instanceof Gb?(b instanceof Gb&&b.constructor===Gb?b=b.j:(Qa(b),b="type_error:SafeScript"),f.textContent=b,Rh(f)):f.textContent=b,f.nonce=hc(),document.head.appendChild(f),document.head.removeChild(f),window[g]?wy(a,d,g,e):(a.state=4,Qt(new Q("Unable to load Botguard from JS")))):Qt(new Q("Unable to load VM; no url or JS provided"))}
function wy(a,b,c,d){a.state=5;try{var e=new Ih({program:b,te:c,Ne:P("att_web_record_metrics")});e.af.then(function(){a.state=6;d&&d(b)});
a.Rc(e)}catch(f){a.state=7,f instanceof Error&&Qt(f)}}
l.invoke=function(a){a=void 0===a?{}:a;return this.Uc()?this.Rd({jd:a}):null};
l.dispose=function(){this.Xc()};
l.Xc=function(){this.Rc(null);this.state=8};
l.Uc=function(){return!!this.h};
l.Rd=function(a){return this.h.Ld(a)};
l.Rc=function(a){re(this.h);this.h=a};function xy(){var a=B("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function yy(){uy.apply(this,arguments)}
u(yy,uy);yy.prototype.Xc=function(){this.state=8};
yy.prototype.Rc=function(a){var b;null==(b=xy())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Ld.bind(a)},A("yt.abuse.playerAttLoader",b),A("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(A("yt.abuse.playerAttLoader",null),A("yt.abuse.playerAttLoaderRun",null))};
yy.prototype.Uc=function(){return!!xy()};
yy.prototype.Rd=function(a){return xy().bgvmc(a)};var zy=new yy;function Ay(){return zy.Uc()}
function By(a){a=void 0===a?{}:a;return zy.invoke(a)}
;function Cy(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||vb(b);this.assets=a.assets||{};this.attrs=a.attrs||vb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Cy.prototype.clone=function(){var a=new Cy,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Qa(c)?a[b]=vb(c):a[b]=c}return a};var Dy=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Ey(a){a=a||"";if(window.spf){var b=a.match(Dy);spf.style.load(a,b?b[1]:"",void 0)}else Fy(a)}
function Fy(a){var b=Gy(a),c=document.getElementById(b),d=c&&zx(c,"loaded");d||c&&!d||(c=Hy(a,b,function(){zx(c,"loaded")||(xx(c),rs(b),Nm($a(ss,b),0))}))}
function Hy(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=mk(a);fc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Gy(a){var b=mf("A");ec(b,new Nb(a,Ob));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+jc(a)}
;function Iy(){J.call(this);this.i=[]}
u(Iy,J);Iy.prototype.L=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.L.call(this)};function Jy(){Iy.apply(this,arguments)}
u(Jy,Iy);function Ky(a,b,c,d,e){J.call(this);var f=this;this.v=b;this.webPlayerContextConfig=d;this.Wb=e;this.Aa=!1;this.api={};this.oa=this.s=null;this.V=new Hi;this.i={};this.aa=this.qa=this.elementId=this.eb=this.config=null;this.Z=!1;this.l=this.N=null;this.Pa={};this.Xb=["onReady"];this.lastError=null;this.Cb=NaN;this.R={};this.Yb=new Jy(this);this.ia=0;this.j=this.m=a;te(this,this.V);Ly(this);My(this);te(this,this.Yb);c?this.ia=Nm(function(){f.loadNewVideoConfig(c)},0):d&&(Ny(this),Oy(this))}
u(Ky,J);l=Ky.prototype;l.getId=function(){return this.v};
l.loadNewVideoConfig=function(a){if(!this.h()){this.ia&&(window.clearTimeout(this.ia),this.ia=0);var b=a||{};b instanceof Cy||(b=new Cy(b));this.config=b;this.setConfig(a);Oy(this);this.isReady()&&Py(this)}};
function Ny(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.j)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.eb=a;this.config=Qy(a);Ny(this);if(!this.qa){var b;this.qa=Ry(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.j&&(this.j.style.width=bi(Number(b)||b)),(a=a.height)&&this.j&&(this.j.style.height=bi(Number(a)||a))};
function Py(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Sy(a){var b=!0,c=Ty(a);c&&a.config&&(a=Uy(a),b=zx(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function Oy(a){if(!a.h()&&!a.Z){var b=Sy(a);if(b&&"html5"===(Ty(a)?"html5":null))a.aa="html5",a.isReady()||Vy(a);else if(Wy(a),a.aa="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Vy(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.N=function(){c=!0;var d=Xy(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?Qy(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.Wb);Vy(a)};
a.Z=!0;b?a.N():(Dx(Uy(a),a.N),(b=Yy(a))&&Ey(b),Zy(a)&&!c&&A("yt.player.Application.create",null))}}}
function Ty(a){var b=lf(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Vy(a){if(!a.h()){var b=Ty(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Z=!1;if(!Xy(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}$y(a)}else a.Cb=Nm(function(){Vy(a)},50)}}
function $y(a){Ly(a);a.Aa=!0;var b=Ty(a);if(b){a.s=az(a,b,"addEventListener");a.oa=az(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=az(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.s&&a.s(g,a.i[g]);Py(a);a.qa&&a.qa(a.api);a.V.cb("onReady",a.api)}
function az(a,b,c){var d=b[c];return function(){var e=Ka.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Qt(f))}}}
function Ly(a){a.Aa=!1;if(a.oa)for(var b in a.i)a.i.hasOwnProperty(b)&&a.oa(b,a.i[b]);for(var c in a.R)a.R.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.R={};a.s=null;a.oa=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.eb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.Aa};
function My(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){rs("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){rs("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=Ry(this,b);d&&(0<=gb(this.Xb,a)||this.i[a]||(b=bz(this,a),this.s&&this.s(a,b)),this.V.subscribe(a,d),"onReady"===a&&this.isReady()&&Nm(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.h()||(b=Ry(this,b))&&Ii(this.V,a,b)};
function Ry(a,b){var c=b;if("string"===typeof b){if(a.Pa[b])return a.Pa[b];c=function(){var d=Ka.apply(0,arguments),e=B(b);if(e)try{e.apply(z,d)}catch(f){Pt(f)}};
a.Pa[b]=c}return c?c:null}
function bz(a,b){var c="ytPlayer"+b+a.v;a.i[b]=c;z[c]=function(d){var e=Nm(function(){if(!a.h()){try{a.V.cb(b,null!=d?d:void 0)}catch(h){Qt(new Q("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.R,g=String(e);g in f&&delete f[g]}},0);
sb(a.R,String(e))};
return c}
l.getPlayerType=function(){return this.aa||(Ty(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function Wy(a){a.cancel();Ly(a);a.aa=null;a.config&&(a.config.loaded=!1);var b=Ty(a);b&&(Sy(a)||!Zy(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.N&&Jx(Uy(this),this.N);window.clearTimeout(this.Cb);this.Z=!1};
l.L=function(){Wy(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Pt(b)}this.Pa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(z[this.i[a]]=null);this.eb=this.config=this.api=null;delete this.m;delete this.j;J.prototype.L.call(this)};
function Zy(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Uy(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Yy(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Xy(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Am(c||"","&")[b]}
function Qy(a){for(var b={},c=r(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?vb(e):e}return b}
;var cz={},dz="player_uid_"+(1E9*Math.random()>>>0);function ez(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?lf(c):c;var e=dz+"_"+Ta(c),f=cz[e];if(f&&d)return fz(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Ky(c,e,a,b,void 0);cz[e]=f;rs("player-added",f.api);ue(f,function(){delete cz[f.getId()]});
return f.api}
function fz(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var gz=null,hz=null,iz=null;function jz(){kz()}
function lz(){kz()}
function kz(){var a=gz.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function mz(){gz&&gz.sendAbandonmentPing&&gz.sendAbandonmentPing();M("PL_ATT")&&zy.dispose();for(var a=ki,b=0,c=Kx.length;b<c;b++)a.Ca(Kx[b]);Kx.length=0;Ix("//static.doubleclick.net/instream/ad_status.js");Lx=!1;km("DCLKSTAT",0);se(iz,hz);gz&&(gz.removeEventListener("onVideoDataChange",jz),gz.destroy())}
;function nz(a,b,c){a="ST-"+jc(a).toString(36);b=b?uc(b):"";c=c||5;zu()&&sn(a,b,c)}
;function oz(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=M("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=M("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=pc(window.location.href);g&&f.push(g);g=pc(d);if(0<=gb(f,g)||!g&&0==d.lastIndexOf("/",0))if(P("autoescape_tempdata_url")&&(f=document.createElement("a"),ec(f,d),d=f.href),d&&(d=qc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:ju()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
nz(d,b,h)}else nz(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var n=void 0===n?window:n;c=n.location;a=wc(a,k)+m;var p=void 0===p?Vh:p;a:{p=void 0===p?Vh:p;for(k=0;k<p.length;++k)if(m=p[k],m instanceof Th&&m.Be(a)){p=new Nb(a,Ob);break a}p=void 0}p=p||Tb;if(p instanceof Nb)var v=Pb(p);else{b:if(Lh){try{v=new URL(p)}catch(t){v="https:";break b}v=v.protocol}else c:{v=document.createElement("a");try{v.href=p}catch(t){v=void 0;break c}v=
v.protocol;v=":"===v||""===v?"https:":v}v="javascript:"!==v?p:void 0}void 0!==v&&(c.href=v)}return!0}
;A("yt.setConfig",km);A("yt.config.set",km);A("yt.setMsg",pu);A("yt.msgs.set",pu);A("yt.logging.errors.log",Pt);
A("writeEmbed",function(){var a=M("PLAYER_CONFIG");if(!a){var b=M("PLAYER_VARS");b&&(a={args:b})}Ju(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=M("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);aw("embed",["ol"]);c=M("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Fm(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;P("embeds_web_enable_watch_on_autoplay")&&(null==(e=a.args)?0:e.autoplay)&&aw("watch",["pbs","pbu","pbp"]);gz=ez(a,c);gz.addEventListener("onVideoDataChange",jz);gz.addEventListener("onReady",lz);a=M("POST_MESSAGE_ID","player");M("ENABLE_JS_API")?iz=new my(gz):M("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(hz=new ty(window.parent,a,b),iz=new qy(gz,hz.connection));Ox();P("ytidb_create_logger_embed_killswitch")||
P("embeds_web_disable_nwl")||Wn();a={};Zx||(Zx=new Yx);Zx.install((a.flush_logs={callback:function(){ct()}},a));
P("embeds_web_disable_nwl")||Tr();P("ytidb_clear_embedded_player")&&ki.fa(function(){var f;if(!Kw){var g=Cs(),h={Oc:Jw,Pd:Iw};g.h.set(h.Oc,h);h={hd:{feedbackEndpoint:Xu(Ew),modifyChannelNotificationPreferenceEndpoint:Xu(Fw),playlistEditEndpoint:Xu(Gw),subscribeEndpoint:Xu(Cw),unsubscribeEndpoint:Xu(Dw),webPlayerShareEntityServiceEndpoint:Xu(Hw)}};var k=Tu.getInstance(),m={};k&&(m.client_location=k);if(void 0===n){Lu.h||(Lu.h=new Lu);var n=Lu.h}void 0===f&&(f=g.resolve(Jw));pw(h,f,n,m);n={Oc:vw,Qd:ow.h};
g.h.set(n.Oc,n);Kw=g.resolve(vw)}wx()})});
var pz=vm(function(){iw();Ku();dx.h||(dx.h=new dx);var a=dx.h;var b=16623;var c=void 0===c?{}:c;Object.values(qu).includes(b)||(Qt(new Q("createClientScreen() called with a non-page VE",b)),b=83769);c.isHistoryNavigation||a.h.push({rootVe:b,key:c.key||""});a.s=[];a.D=[];c.ld?hx(a,b,c):ix(a,b,c)}),qz=vm(function(a){a.persisted||(iw(),Ku())}),rz=vm(function(a){P("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?mz():a.persisted||mz()}),sz=vm(mz);
window.addEventListener?(window.addEventListener("load",pz),window.addEventListener("pageshow",qz),window.addEventListener("pagehide",rz)):window.attachEvent&&(window.attachEvent("onload",pz),window.attachEvent("onunload",sz));A("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||Ay);A("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||By);A("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||Px);
A("yt.player.exports.navigate",B("yt.player.exports.navigate")||oz);A("yt.util.activity.init",B("yt.util.activity.init")||gs);A("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||js);A("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||hs);}).call(this);
