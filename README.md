# Quick links that are helpful to have:

<ul>
	<li><a href="http://studentdemo-lblakej.cloudapps.unc.edu/" target="_blank">My Example Site as a finished site</a></li>
	<li><a href="http://php-site-lblakej.cloudapps.unc.edu/" target="_blank">My Example PHP Site with lots of background images</a></li>
	<li><a href="https://sc.unc.edu/lblakej/2017-fall-inls161-website" target="_blank">My Example Source Control Repository</a></li>
	<li><a href="http://getskeleton.com/" target="_blank">Skeleton CSS instructions</a></li>
	<li><a href="http://editor.method.ac/" target="_blank">Method Draw: Free online image editor</a></li>
	<li><a href="http://htmlandcssbook.com/code-samples/" target="_blank">Valuable code samples!</a> Navigate to the code you need, right click to see the code and copy and paste as you need.</li>
</ul>

<p>This above demo site is built entirely with the skeleton boilerplate and a responsive menu snagged from codepen. Those two items are the basis for the 2.1 theme. Here are links specific to the 2.1 theme:</p>

<ul>
	<li><a href="https://codepen.io/lisa_c/pen/akjiy">Navigation Code Link</a></li>
	<li>Skeleton uses rem units, so read this over:<br />
	<a href="https://www.sitepoint.com/understanding-and-using-rem-units-in-css/">Understanding rem units</a></li>
	<li><a href="http://www.unc.edu/~lblakej/">I used skeleton here for a UNC page.</a></li>
	<li><a href="http://thecarterbuilding.com/">I built this site for the Carter Building using skeleton.</a></li>
</ul>


<p>Below is the html code for alignment; put these in your <code>.html</code>and they will connect with the css in your <code>custom.css</code> file.</p>

<div>
<pre>
<code>&lt;img class="align-right" src="images/clock.jpg" alt="clock image"&gt;</code></pre>
</div>

<div>
<pre>
<code>&lt;img class="align-left" src="images/clock.jpg" alt="clock image"&gt;</code></pre>
</div>

<div>
<pre>
<code>&lt;img class="align-center" src="images/clock.jpg" alt="clock image"&gt;</code></pre>
</div>

<p>The CSS code for alignment should be in your <code>custom.css</code> file.</p>

<p>If you have a larger image, and you want to contain it to a column, and you want it to resize when the browser size is minimized, use the below image class. This image class was created by the author of the skeleton theme, and if you have linked to the skeleton.css file, then it should work for you.</p>

<div>
<pre>
<code>&lt;img class="u-max-full-width" src="images/image.jpg" alt="Image Description"&gt;</code></pre>
</div>

<p><i>The name of the class is important to breakdown: <b>u</b> is for utility. So this is not a foundational css rule; it is a useful utility. The <b>max-full-width</b> part of the name describes what it does. It makes sure that an image will resize and fill up the column.</i></p>
