<!DOCTYPE HTML>
<html lang="en-US">
<head>
	<meta charset="UTF-8">
	<title></title>
	
	<link rel="stylesheet" href="style.css" />
</head>
<body>
	<div class="container">
	<header>
		<h1 id="name">Your Name</h1>
		
		<div id="designation">
		
			<span class="title">your designation</span>
			<span class="organization">The organisation name</span>
		
		</div>
		
		<div class="contact">
			<div class="email">john@example.com</div>
		</div>
		
	</header>
	
	<div class="content" role=main>
	
		<section id="objective">
			<h2 class="title">Objective</h2>
			<div class="description">
				<p>
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
				</p>			
			</div> <!-- end description -->
		</section>
		
		
		<section id="Education">
			<h2 class="title">Education</h2>
			<div class="description">
				
				<table>
					<thead>
						<td>Duration</td>
						<td>Qualification</td>
						<td>Institute/School</td>
						<td>Result</td>
					</thead>
					
					<!-- edit this/ row-wise-->
					<tr>
						<td>abc</td>
						<td>abc</td>
						<td>abc</td>
						<td>abc</td>
					</tr>
					
					<tr> <!-- row2 -->
						<td>abc</td>
						<td>abc</td>
						<td>abc</td>
						<td>abc</td>
					</tr>					
					
				</table>
			
			
			</div> <!-- end description -->
		</section>
			
		<section id="projects">
			<h2 class="title">Projects Undertaken</h2>
			<div class="description">
				
				<!-- Project 1 -->
				<section class="project">
					<h3 class="title">Title of the project</h3>
					<div class="meta">
						<span class="field">Project Field</span> <span class="date">Aug 2010 - Nov2010</span>
					</div>
					<p class="description"> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. </p>
				</section> <!-- end project description -->
				
				<!-- project 2 -->
				<section class="project">
					<h3 class="title">Title of the project</h3>
					<div class="meta">
						<span class="field">Project Field</span> <span class="date">Aug 2010 - Nov2010</span>
					</div>
					<p class="description">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. </p>
				</section> <!-- end project description -->


				<!-- project 3 -->
				<section class="project">
					<h3 class="title">Title of the project</h3>
					<div class="meta">
						<span class="field">Project Field</span> <span class="date">Aug 2010 - Nov2010</span>
					</div>
					<p class="description">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. </p>
				</section> <!-- end project description -->				
				
				</div> <!-- end description -->
		</section>	
	

		<!-- Training/ seminars -->
		
		
		
		<!-- Scholistics Achievements -->
		
		
		
		<!-- Technical Skills -->
		
		
		<!-- Extra-Curricular Activities -->
		
		
		<!-- Personal Informations -->
		
		
		<!-- References -->
		
		
		
		<!-- Declarations -->

	
		<!-- signatory -->
	
	
	
	
	</div> <!-- end main content -->
	
	
	
	
	
	
	
	
	
	
	
	
	
	</div> <!-- end container -->
	
</body>
</html>

/* =============================================================================
   HTML5 display definitions
   ========================================================================== */

article, aside, details, figcaption, figure, footer, header, hgroup, nav, section { display: block; }
audio, canvas, video { display: inline-block; *display: inline; *zoom: 1; }
audio:not([controls]) { display: none; }
[hidden] { display: none; }


/* =============================================================================
   Base
   ========================================================================== */

/*
 * 1. Correct text resizing oddly in IE6/7 when body font-size is set using em units
 * 2. Force vertical scrollbar in non-IE
 * 3. Prevent iOS text size adjust on device orientation change, without disabling user zoom: h5bp.com/g
 */

html { font-size: 100%; overflow-y: scroll; -webkit-text-size-adjust: 100%; -ms-text-size-adjust: 100%; }

body { margin: 0; font-size: 0.8em; line-height: 1.4; }

body, button, input, select, textarea { font-family: sans-serif; color: #222; }

/*
 * Remove text-shadow in selection highlight: h5bp.com/i
 * These selection declarations have to be separate
 * Also: hot pink! (or customize the background color to match your design)
 */

::-moz-selection { background: #fe57a1; color: #fff; text-shadow: none; }
::selection { background: #fe57a1; color: #fff; text-shadow: none; }


/* =============================================================================
   Links
   ========================================================================== */

a { color: #00e; }
a:visited { color: #551a8b; }
a:hover { color: #06e; }
a:focus { outline: thin dotted; }

/* Improve readability when focused and hovered in all browsers: h5bp.com/h */
a:hover, a:active { outline: 0; }


/* =============================================================================
   Typography
   ========================================================================== */

abbr[title] { border-bottom: 1px dotted; }

b, strong { font-weight: bold; }

blockquote { margin: 1em 40px; }

dfn { font-style: italic; }

hr { display: block; height: 1px; border: 0; border-top: 1px solid #ccc; margin: 1em 0; padding: 0; }

ins { background: #ff9; color: #000; text-decoration: none; }

mark { background: #ff0; color: #000; font-style: italic; font-weight: bold; }

/* Redeclare monospace font family: h5bp.com/j */
pre, code, kbd, samp { font-family: monospace, serif; _font-family: 'courier new', monospace; font-size: 1em; }

/* Improve readability of pre-formatted text in all browsers */
pre { white-space: pre; white-space: pre-wrap; word-wrap: break-word; }

q { quotes: none; }
q:before, q:after { content: ""; content: none; }

small { font-size: 85%; }

/* Position subscript and superscript content without affecting line-height: h5bp.com/k */
sub, sup { font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; }
sup { top: -0.5em; }
sub { bottom: -0.25em; }


/* =============================================================================
   Lists
   ========================================================================== */

ul, ol { margin: 1em 0; padding: 0 0 0 40px; }
dd { margin: 0 0 0 40px; }
nav ul, nav ol { list-style: none; list-style-image: none; margin: 0; padding: 0; }


/* =============================================================================
   Embedded content
   ========================================================================== */

/*
 * 1. Improve image quality when scaled in IE7: h5bp.com/d
 * 2. Remove the gap between images and borders on image containers: h5bp.com/e
 */

img { border: 0; -ms-interpolation-mode: bicubic; vertical-align: middle; }

/*
 * Correct overflow not hidden in IE9
 */

svg:not(:root) { overflow: hidden; }


/* =============================================================================
   Figures
   ========================================================================== */

figure { margin: 0; }


/* =============================================================================
   Forms
   ========================================================================== */

form { margin: 0; }
fieldset { border: 0; margin: 0; padding: 0; }

/* Indicate that 'label' will shift focus to the associated form element */
label { cursor: pointer; }

/*
 * 1. Correct color not inheriting in IE6/7/8/9
 * 2. Correct alignment displayed oddly in IE6/7
 */

legend { border: 0; *margin-left: -7px; padding: 0; }

/*
 * 1. Correct font-size not inheriting in all browsers
 * 2. Remove margins in FF3/4 S5 Chrome
 * 3. Define consistent vertical alignment display in all browsers
 */

button, input, select, textarea { font-size: 100%; margin: 0; vertical-align: baseline; *vertical-align: middle; }

/*
 * 1. Define line-height as normal to match FF3/4 (set using !important in the UA stylesheet)
 */

button, input { line-height: normal; }

/*
 * 1. Display hand cursor for clickable form elements
 * 2. Allow styling of clickable form elements in iOS
 * 3. Correct inner spacing displayed oddly in IE7 (doesn't effect IE6)
 */

button, input[type="button"], input[type="reset"], input[type="submit"] { cursor: pointer; -webkit-appearance: button; *overflow: visible; }

/*
 * Consistent box sizing and appearance
 */

input[type="checkbox"], input[type="radio"] { box-sizing: border-box; padding: 0; }
input[type="search"] { -webkit-appearance: textfield; -moz-box-sizing: content-box; -webkit-box-sizing: content-box; box-sizing: content-box; }
input[type="search"]::-webkit-search-decoration { -webkit-appearance: none; }

/*
 * Remove inner padding and border in FF3/4: h5bp.com/l
 */

button::-moz-focus-inner, input::-moz-focus-inner { border: 0; padding: 0; }

/*
 * 1. Remove default vertical scrollbar in IE6/7/8/9
 * 2. Allow only vertical resizing
 */

textarea { overflow: auto; vertical-align: top; resize: vertical; }

/* Colors for form validity */
input:valid, textarea:valid {  }
input:invalid, textarea:invalid { background-color: #f0dddd; }


/* =============================================================================
   Tables
   ========================================================================== */

table { border-collapse: collapse; border-spacing: 0; }
td { vertical-align: top; }


/* ==|== primary styles =====================================================
   Author: Saurabh Kumar (http://saurabhworld.in)
   ========================================================================== */

.container {
	width: 80%;
	max-width: 600px;
	margin: 0 auto;	
}

table{
	width: 100%;
}

thead{
	font-weight: bold;
}

td{	
	border: 1px solid #ddd;
	padding: 2px;
}


.project > .title {
	margin-bottom: 0px;
}

.project > .meta {
	font-size: 0.8em;
}

.project > .meta > .date {
	float: right;

}













/* ==|== media queries ======================================================
   PLACEHOLDER Media Queries for Responsive Design.
   These override the primary ('mobile first') styles
   Modify as content requires.
   ========================================================================== */

@media only screen and (min-width: 480px) {
  /* Style adjustments for viewports 480px and over go here */

}

@media only screen and (min-width: 768px) {
  /* Style adjustments for viewports 768px and over go here */

}



/* ==|== non-semantic helper classes ========================================
   Please define your styles before this section.
   ========================================================================== */

/* For image replacement */
.ir { display: block; border: 0; text-indent: -999em; overflow: hidden; background-color: transparent; background-repeat: no-repeat; text-align: left; direction: ltr; *line-height: 0; }
.ir br { display: none; }

/* Hide from both screenreaders and browsers: h5bp.com/u */
.hidden { display: none !important; visibility: hidden; }

/* Hide only visually, but have it available for screenreaders: h5bp.com/v */
.visuallyhidden { border: 0; clip: rect(0 0 0 0); height: 1px; margin: -1px; overflow: hidden; padding: 0; position: absolute; width: 1px; }

/* Extends the .visuallyhidden class to allow the element to be focusable when navigated to via the keyboard: h5bp.com/p */
.visuallyhidden.focusable:active, .visuallyhidden.focusable:focus { clip: auto; height: auto; margin: 0; overflow: visible; position: static; width: auto; }

/* Hide visually and from screenreaders, but maintain layout */
.invisible { visibility: hidden; }

/* Contain floats: h5bp.com/q */
.clearfix:before, .clearfix:after { content: ""; display: table; }
.clearfix:after { clear: both; }
.clearfix { *zoom: 1; }



/* ==|== print styles =======================================================
   Print styles.
   Inlined to avoid required HTTP connection: h5bp.com/r
   ========================================================================== */

@media print {
  * { background: transparent !important; color: black !important; box-shadow:none !important; text-shadow: none !important; filter:none !important; -ms-filter: none !important; } /* Black prints faster: h5bp.com/s */
  a, a:visited { text-decoration: underline; }
  a[href]:after { content: " (" attr(href) ")"; }
  abbr[title]:after { content: " (" attr(title) ")"; }
  .ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after { content: ""; }  /* Don't show links for images, or javascript/internal links */
  pre, blockquote { border: 1px solid #999; page-break-inside: avoid; }
  thead { display: table-header-group; } /* h5bp.com/t */
  tr, img { page-break-inside: avoid; }
  img { max-width: 100% !important; }
  @page { margin: 0.5cm; }
  p, h2, h3 { orphans: 3; widows: 3; }
  h2, h3 { page-break-after: avoid; }
}
