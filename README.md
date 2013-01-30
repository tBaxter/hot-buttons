<!doctype html>
<!-- paulirish.com/2008/conditional-stylesheets-vs-css-hacks-answer-neither/ -->
<!--[if lt IE 7]> <html class="no-js lt-ie9 lt-ie8 lt-ie7" lang="en"> <![endif]-->
<!--[if IE 7]>    <html class="no-js lt-ie9 lt-ie8" lang="en"> <![endif]-->
<!--[if IE 8]>    <html class="no-js lt-ie9" lang="en"> <![endif]-->
<!--[if gt IE 8]><!--> <html class="no-js" lang="en"> <!--<![endif]-->
    <head>
        <meta charset="utf-8">
        <meta charset=utf-8>
        <title>Hot Buttons</title>
        <!--[if lt IE 9]> HTML5Shiv
            <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
        <![endif]-->
        <link rel="stylesheet" href="https://raw.github.com/tBaxter/capo/master/static/css/site.css">
        <link rel="stylesheet" href="css/hot-buttons.css">
        <style>
          * { 
            -webkit-box-sizing: border-box; 
            -moz-box-sizing:    border-box; 
            box-sizing:         border-box; 
            padding: 0;
            font-family:Helvetica;
          }

          html {
            color: #444;
            font-size: 100%;
            background: #f7f7f7;
          }

          body {
            text-rendering: optimizeLegibility;
            -webkit-font-smoothing: antialiased; 
            font-size:1.125rem;
            margin:1em 3em;
          }

          dl { margin:3em; }
          dt { float:left; width:8em; margin-top:.75em; border-bottom:1px dotted #ccc; }
          dd {
            position: relative;
            margin-left:8em; 
            border-left:1px dotted #ccc;
            padding: 0 1em 2em;
          }
          code, small {display:block; font-size:80%; color:#999; margin-left:20px;}
          small {font-size:65%;}
          .columned > div {display:inline-block; width:48%; vertical-align: top; 
            padding-bottom .5em; border-top:1px solid #ddd; margin-bottom:.5em;

          }
          #main {float:left; width:65%;}
          #secondary {margin-left:67%;}
      </style>
    </head>
    <body>
      <h1>Hot Buttons</h1>
      <p>Are based on the work of <a href="http://dribbble.com/shots/220353-Round-Button-Navigation">Wouter</a> and <a href="http://css-tricks.com/examples/RoundButtons/">CSS Tricks</a>, implemented in SASS, and designed to be quickly configurable and reusable in a variety of situations.</p>

      <p>They support font icons, sub-buttons, sub-navigation, dividers and more. They are designed to be easily configurable, with sensible defaults you can easily override for your project.</p>
      <p>Plus, they're designed to easily plug in your own icon fonts and SASS variables.</p>

      <h2>A brief overview...</h2>
      <small>Note: all buttons are shown using default settings.</small>
      <div class="columned" id="main">
        <div>
          <h3>Text buttons</h3>
          <a href="#" class="button">Monkeys</a>
          <a href="#" class="button">Bears</a>
          <a href="#" class="button">Fish</a>
          <code>class="button"</code>
        </div>
        <div>
          <h3>Simple icon buttons</h3>
          <a href="#" class="button icon-cog"></a>
            <a href="#" class="button icon-cw"></a>
            <a href="#" class="button icon-home"></a>
            <a href="#" class="button icon-location"></a>
          <code>class="button icon-cog"</code>
          <code>class="button icon-home"</code>
        </div>
        <div>
          <h3>Icon and text</h3>
          <a href="#" class="button icon-home icon-text">Umbrella</a>
          <a href="#" class="button icon-cog icon-text">Settings</a>
          <code>class="button icon-home icon-text"</code>
          <code>class="button icon-cog icon-text"</code>
          <small>Note: icon-text is necessary to ensure correct padding.</small>
        </div>
        <div>
          <h3>Sub-buttons</h3>
          <div class="button sub-buttons">
            Main
              <a href="#">1</a>
              <a href="#">2</a>
              <a href="#">3</a>
              <a href="#">4</a>
          </div>
        </div>
        <div>
          <h3>Thinline</h3>
          <a href="#" class="button icon-cw icon-text thinline">Around</a>
          <div class="button sub-buttons thinline">
            Main
              <a href="#">1</a>
              <a href="#">2</a>
              <a href="#">3</a>
          </div>
        </div>
        <div>
          <h3>Sub-navigation</h3>
          <ul class="button sub-nav">
            <li>Menu <span class="button-trigger divide-left">⚙</span>
              <ul class="button-target">
                <li>sub-item one</li>
                <li>sub-item two</li>
                <li>sub-item three</li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
      <div id="secondary">
      <h2>Options</h2>
      <code>
        <pre>
// Should buttons be inset in page.

// Should buttons have a drop shadow.   

// Should buttons use a gradient or be flat.

// Should inset buttons highlight the background when active.

// Button background color.

// Button text color.

// Button font size.  

// Hover and active colors

// Button radius

// Button margin

// button inset

// Sub-button background and color

// Button highlight color. Used for depth effects.

// Button lowlight color (the opposite of highlight)
</pre></code>
</div>
    </body>
</html>
