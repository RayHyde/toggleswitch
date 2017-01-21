<h1>A slide toggle switch based on an empty label</h1>
<h2>CSS-only and adhering to W3C standards</h2>
<p>Most toggle switches are based on a &lt;label&gt; tag containing all the elements needed to make things work. However you may come across a platform in which this is not allowed (Outsystems for one).</p>

<p>The trick is to rely on sequential elements in your css, allowing every element that follows a checked checkbox to be changed:</p>
<code>input[type="checkbox"]:checked + div > div + div</code>

<p>See it in action: <a href="https://rayhyde.github.io/toggleswitch/">https://rayhyde.github.io/toggleswitch/</a>

<h2>My Playground</h2>

<p>This project is part of my Playground - a collection of fun (and <em>ahem</em>, dare I say it: clever) stuff I made in the past, from jQuery games and plugins to CSS animation tricks.</p>

<p>Please drop in on my portfolio site <a href="http://www.rayhyde.nl">www.rayhyde.nl</a>!</p>