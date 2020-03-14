# night-cat
<a href="https://murchim.ru/kototema/koshki_html/kot_html_css_svg_guljajushhij_nochju/2-1-0-2" target="_blank">Ночной котик прогуливается по городу</a>
## code
<code>
<style>
 html{
 font-size:20px;
 margin:0;
 background: #0c0207;
 }
 #marco{
 width: 1325px;
 height: 500px;
 margin: 0 auto;
 overflow: hidden;
 border-radius: 16px;
 margin-top: 2em;
 }
 #cielo{
 border-radius: 16px;
 width: 1325px;
 height: 500px;
 background: linear-gradient(to bottom, #0B4C5F 0%,#04B4AE 52%,#0c0207 100%); 
 position: absolute;
 z-index: -30;
 top: 0;
 margin-top: 2em;
 }
 #edificios{
 background: url('https://murchim.ru/koto-tema/images/2020/gk/doma.svg');
 height: 500px; 
 width: 1325px;
 z-index: -10;
 top: 6.5em;
 background-position: 0px 0px;
 background-repeat: repeat-x;
 -webkit-animation: animar_edificios 120s linear infinite;
 -ms-animation: animar_edificios 120s linear infinite;
 -moz-animation: animar_edificios 120s linear infinite;
 position: absolute;
 }
 @keyframes animar_edificios {
 from { background-position: 0 0; }
 to { background-position: 100% 0; }
 }
 @-webkit-keyframes animar_edificios {
 from { background-position: 0 0; }
 to { background-position: 100% 0; }
 }
 @-ms-keyframes animar_edificios {
 from { background-position: 0 0; }
 to { background-position: 100% 0; }
 }
 @-moz-keyframes animar_edificios {
 from { background-position: 0 0; }
 to { background-position: 100% 0; }
 }
 #luna {
 width: 6em;
 height: 6em;
 -moz-border-radius: 50%;
 -webkit-border-radius: 50%;
 border-radius: 50%;
 -moz-box-shadow: 30px 10px 0 #F7F8E0;
 -webkit-box-shadow: 30px 10px 0 #F7F8E0;
 box-shadow: 30px 10px 0 #F7F8E0;
 margin-top: 1em;
 margin-left: 50%;
 position: absolute;
 z-index: -19;
 }
 #muro{
 height: 23em;
 width: 100%;
 background: -moz-linear-gradient(top, #416663 0%, #0c0207 19%); 
 background: -webkit-linear-gradient(top, #416663 0%,#0c0207 19%); 
 background: linear-gradient(to bottom, #416663 0%,#0c0207 19%); 
 bottom:0px; 
 }
 #gato{
 background: url('https://murchim.ru/koto-tema/images/2020/gk/kot.svg');
 height: 297px; 
 width: 507.5px;
 margin-top: 2em;
 margin-left: 2em;
 z-index: 10;
 -webkit-animation: sprite-animation 1.2s steps(16,end) infinite;
 -moz-animation: sprite-animation 1.2s steps(16,end) infinite; 
 -ms-animation: sprite-animation 1.2s steps(16,end) infinite; 
 animation: sprite-animation 1.2s steps(16,end) infinite;
 }
 @-webkit-keyframes sprite-animation { 
 from { background-position: 0 0; }
 to { background-position: -8120px 0; } 
 }
 @-ms-keyframes sprite-animation { 
 from { background-position: 0 0; }
 to { background-position: -8120px 0; }
 }
 @-moz-keyframes sprite-animation { 
 from { background-position: 0 0; }
 to { background-position: -8120px 0; }
 }
 @keyframes sprite-animation { 
 from { background-position: 0 0; }
 to { background-position: -8120px 0; }
 }
</style>
<div id="marco">
 <div id="cielo"></div>
 <div id="luna"></div>
 <div id="gato"></div>
 <div id="muro"></div>
 <div id="edificios"></div>
</div>  
</code>  
