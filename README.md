[![](https://jitpack.io/v/kavapps/incognito_mode.svg)](https://jitpack.io/#kavapps/incognito_mode)

<h1>
Incognito mode
</h1>
<p>
The library changes all characters of the string to emoji
</p>
<h2>
Installation
</h2>

<ul>
<li>Gradle
Add it in your root <code>build.gradle</code> at the end of repositories:
<pre><code>allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
</code></pre>
add the dependency
<pre><code>dependencies {
        implementation 'com.github.kavapps:incognito_mode:v1.0.0'
}
</code></pre>
</li>
<li><a href="https://jitpack.io/#kavapps/incognito_mode/" rel="nofollow">More ways to add it</a></li>
</ul>


<h2><a id="user-content-usage" class="anchor" aria-hidden="true" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Usage</h2>
<ul><pre><code>Incognito.changeAllSymbolToEmoji(string); // change each character in the string to emoji
</code></pre>
</ul>

<ul><pre><code>Incognito.changeToEmoji(); // replace the whole line with one emoji
</code></pre>
</ul>


