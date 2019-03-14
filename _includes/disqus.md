
<div class="container mb-3 border rounded">
   {% if page.comments %}
   <div id="disqus_thread"></div>
   <script>

   var disqus_config = function () {
   this.page.url = {page.permalink};  
   this.page.identifier = {page.title}; 
   };

   (function() { 
   var d = document, s = d.createElement('script');
   s.src = 'https://mohammedkn-com.disqus.com/embed.js';
   s.setAttribute('data-timestamp', +new Date());
   (d.head || d.body).appendChild(s);
   })();
   </script>
   {% endif %}   
 </div>
