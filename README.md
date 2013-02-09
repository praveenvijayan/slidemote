slidemote
=========

[Slidemote](http://slidemote.jit.su/) is a web app created for easy integration of remote control facility for html5 presentations. 

##Integration
1. Add following script in your presentation.
```<script type="text/javascript" src="http://slidemote.jit.su/slidemote.js#slidemote"></script>```
2. Append your id at the end of the script (Eg: ...slidemote.js#YOUR_ID ).
3. Goto - [Slidemote](http://slidemote.jit.su).
4. Enter YOUR_ID & connect.
5. Slidemote currently supports (basic level) - [revealjs](http://lab.hakim.se/reveal-js/), [impressjs](http://bartaz.github.com/impress.js/#/bored), [deckjs](http://imakewebthings.com/deck.js/) and [flowtime](http://flowtime-js.marcolago.com/).

##Demo

Go to [Slidemote](http://slidemote.jit.su) and enter following key and press connect. Once connected you are able to control this presentation. It will take a few seconds to connect, be patient. Don't refresh page, result will be a new key and you have to enter it again on 'slidemote.jit.su' to establish connection.

Key: <input type="text" id="slidemoteCode" class="txtSlidemoteCode" placeholder="Your key">

<iframe id="iframeRevealjs" src="http://demos.decodize.com/slidemote/revealjs/index.php" frameborder="0" width="100%" height="600"></iframe>