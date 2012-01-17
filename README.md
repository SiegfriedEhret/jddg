# Duck Duck Go Zero Info search box
I always wanted to do a jQuery plugin. Now, it's done !

This is a jQuery plugin for [Duck Duck Go Zero-click Info API](https://duckduckgo.com/api.html).
For those who are not familiar with [Duck Duck Go](https://duckduckgo.com/), it's my new favorite search engine. Go try it !

It provides a box with some basic info (like... From wolfram alpha, wikipedia etc.).

I will make some tests to make it better (but I don't like tests... Sorry) and add more parameters soon.
Stay tuned !

And don't forget to use [Duck Duck Go](https://duckduckgo.com/) !
## I want to use it (like a boss)
First, include [jQuery](http://jquery.com/).
Then, get the plugin and include it.
You should have something like this:
<code javascript>
<script type='text/javascript' src='/path/to/jquery.min.js'></script>
<script type='text/javascript' src='/path/to/jquery.ddg.min.js'></script>
</code>

Then, create a div in your html page, and DDGize it using :
<code javascript>
<script type='text/javascript'>
  $(function() {
    $('#search-ddg').ddg({secure:true});
  });
</script>
</code>
That's it !
## I want to customize it (like a boss)
Later son, later.
For now, there are 2 parameters:
  * secure : true or false. To use https or simple http to call the Duck Duck Go service
  * width : define the width of the searchbox + results window
## I want to try it (like a boss)
Yep. [Here](http://dev.federalbureauofinhumanity.org/jddg/v0.3/demo/) - v0.3  
The version here is commented, the downloadable version is not.
You can choose the version you want.
## I want to say something (like a boss)
You can contact me at siegfried.ehret@gmail.com
Please write "jddg" or something in your subject.
## I want to read the license (like a boss)
This plugin is licensed under the terms of the WTF Public License (see [here](http://en.wikipedia.org/wiki/WTFPL) and [here](http://sam.zoy.org/wtfpl/)) :
<pre>
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                    Version 2, December 2004 

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

 Everyone is permitted to copy and distribute verbatim or modified 
 copies of this license document, and changing it is allowed as long 
 as the name is changed. 

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

  0. You just DO WHAT THE FUCK YOU WANT TO. 
</pre>