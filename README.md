justyouknow
===========
[Hello World!][1]
[1]:javascript:(function(){if(!window.jQuery){script=document.createElement('script');script.src='//lib.sinaapp.com/js/jquery/1.7.2/jquery.min.js';script.onload=youknow;document.body.appendChild(script);}else{youknow();}function youknow(){$('h3 a').each(function(){var a=$(this);$.get('http://208.94.244.98/bt/'+a.attr('href'),function(data){$(data).find('img').each(function(){var img=$(this).css('max-width','200px').css('max-height','300px').css('margin','10px 10px 10px 0');var img_link=$('<a href=&quot;'+img.attr('src')+'&quot;></a>');a.after(img_link);img.appendTo(img_link);});a.after('<br>');});});}})();
