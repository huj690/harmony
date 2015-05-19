---
layout: post
title:  "Hello World"
date:   2015-05-18 14:30:00
description: Hello World
categories:
- blog
- test
---

试试中文~  
试试代码  

<pre class="prettyprint linenums" >
$('#disqus_container .comment').on('click',function(){
        $(this).html('加载中...');
        var disqus_shortname = 'beiyuu';
        var that = this;
        BYB.includeScript('http://' + disqus_shortname + '.disqus.com/embed.js',function(){$(that).remove()}); //这是一个加载js的函数
});
</pre>

<pre class="prettyprint linenums">
#include <iostream>
using namespace std;
int main() {
	int a, int b;
	while (cin >> a >> b) {
		cout << a + b << endl;
	}
	return 0;
}</pre>

