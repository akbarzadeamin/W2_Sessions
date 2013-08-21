<h1>SVG</h1>
http://www.w3schools.com/svg/ <br />
<pre>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 93">

<pattern id="grid" x="6" y="6" width="6" height="6" patternUnits="userSpaceOnUse">
    <rect width="6" height="6" fill="white"/>
    <rect x="1" y="1" width="5" height="5" fill="red"/>
</pattern>

<!-- Heart -->
<path fill="red" d="
    M33.5,70.65
    L51.69,88.84
    l37.16-37.16
    c.32-.31,.64-.62,.94-.94
    l2.3-2.84
    c2.62-3.8,4.15-8.4,4.15-13.37
    c0-13.04-10.57-23.61-23.61-23.61
    c-3.72,0-7.23,.86-10.36,2.39
    z"/>

<path d="M12.5,24.5h6v-6h6v-6h18v6h6v6h6v-6h6
    v6h6v24h-6v12h-12v6h-18v-6h-6v-6h-6v-6h-6z
    m12,0v12h12v-12z" fill="url(#grid)"/>

<circle fill="none" stroke="white" stroke-width="9" cx="36" cy="36" r="31"/>
<circle fill="none" stroke="black" stroke-width="6" cx="36" cy="36" r="31"/>

</svg>
</pre>
Demo1 : http://jsbin.com/arafek/1/edit <br />
Demo2 : http://jsbin.com/ivotel/2/edit<br />
Demo3 : http://jsbin.com/emagig/1/edit<br />
<h1>Web Fonts</h1>
@font-face
<pre>
@font-face {
  font-family: 'font_name';
  src: url('font_file_name.eot'); /* old browser like ie6 */
  src: url('font_file_name.eot?#iefix') format('embedded-opentype'),
       url('font_file_name.woff') format('woff'),
       url('font_file_name.ttf') format('truetype'),
       url('font_file_name.svg#tangerineregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
</pre>
<pre>
body{
    font-family: 'local font name', 'font_name' ,arial ,sans;
}
</pre>
Sample : https://github.com/AliMD/1Tuts/blob/WebDesign-Old/%5Bcss3%5D%20Fonts/Custome%20web%20fonts.html <br />
<h1>Google Web Font</h1>
GWF : http://www.google.com/fonts/<br />
sample : http://jsbin.com/ucupuq/1/edit<br />
<h1>Persian</h1>
ali.md/1fonts<br />

http://jsbin.com/oqugij/1/edit<br />
<h1>Icon</h1>
http://fortawesome.github.io/Font-Awesome/

http://cdnjs.cloudflare.com/ajax/libs/font-awesome/3.2.1/css/font-awesome.min.css <br />

http://cdnjs.cloudflare.com/ajax/libs/font-awesome/3.2.1/css/font-awesome-ie7.min.css<br />

<i class="icon-book"></i> <br />
http://jsbin.com/emocic/1/edit

<h1>CSS3 Animate</h1>
https://developer.mozilla.org/en-US/docs/Web/CSS/animation<br />
http://docs.webplatform.org/wiki/tutorials/css_animations<br />
http://jsbin.com/box/28/edit<br />
tips: http://daneden.me/animate/ <br />
<h3>age khastin reset beshe na normalize yani maslan margin ha hame 0 beshan !</h3>
http://alimd.github.io/libs/1reset/1.0/1reset_eric.css <br />
<h1>CSSMIN</h1>
<pre>
install

npm install -g cssmin
usage

cssmin < style.css > style.min.css
</pre>