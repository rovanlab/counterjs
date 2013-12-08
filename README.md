<h2>CounterJS</h2>
<p>Counter.js helps you to integrate stylish counter for your website. It automaticaly starts couting from zero to your given limit.</p>

<h1>Live Demo</h1>
<p><b><a href="http://rovanlab.com/counterjs/index.html">Basic Counter</a></b></p>
<p><b><a href="http://rovanlab.com/counterjs/index2.html">Counter using waypoint.js</a></p></p>
<h2>How to use counter.js</h2>
<p>Create an element (HTML)</p>
<pre><code>&lt;span id="counter"&gt;&lt;/span&gt; and counting ....
</code></pre>

<p>Include counter.js to your page:</p>
<pre><code>&lt;script src="counter.js"&gt;&lt;/script&gt;
</code></pre>
<p>call counter function</p>
<pre><code>&lt;script&gt;
    $('#counter').counter({
                        limit:500,      // Your count limit
                        speed:10000     // Counting speed
                        },
                        function(){     // Callback function
                          alert("completed")

                        });
&lt;/script
</code></pre>

