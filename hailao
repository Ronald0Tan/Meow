// ==UserScript==
// @name         Set Cookie-Haidilao
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://*.zhilandaren.com/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=tampermonkey.net
// @grant        none

// @require http://zl.zhilandaren.com/hdl_view/js/jquery.cookie.js
// ==/UserScript==

/* global $ */

$(document).ready(function() {
    'use strict';
    var maxDate = 365*10;//cookie
    $.removeCookie('zl_freeCount', { path: '/' });
    $.removeCookie('zl_uid', { path: '/' });
    $.removeCookie('shopId', { path: '/' });
    $.removeCookie('zl_token', { path: '/' });

    $.cookie('zl_freeCount', 2, {
		expires: maxDate
	});

    $.cookie('zl_uid' , Math.floor(100000 + Math.random() * 306000), {
		expires: maxDate
	});

    $.cookie('shopId' , 2, {
		expires: maxDate
	});

    $.cookie('zl_token' , 'cdb8a3d2e4e14588f3ac1d588d968e17' , {
		expires: maxDate
	});

    //alert($.cookie('shopId') ) ;
});
