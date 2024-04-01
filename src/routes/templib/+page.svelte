<!-- src/routes/templib/+page.svelte -->
<script>
    import Layout from '../+layout.svelte'
</script>
<div class="container">
    <h1>Template Library</h1>
    </div>
  <div class="grid-container">
    <div class="grid-title">
      <h3>Before Using the Templates:</h3>
    </div>
    <div class="grid-mid">
      <p>When choosing a template, keep in mind the Base Colour is easily changed using the Design tab in Microsoft Word. Click on the Colors option and choose a pre-designed theme or create your own custom colour scheme! This will completely transform the look and feel of your document.<br><br>
        Remember you can create a blank document and add elements from different templates if you want to get creative and guarantee yours is one of a kind!<br><br>
        Download the PDF below to have a look at one document with all the current templates available to help you choose which ones to try.<br><br>
        Remember to rename the document before sending it to employers/uploading it to job searching sites.Add your name and remove the (Resume Template #)<br><br>
        Now that's out of the way, go for it!!</p>
    </div>
    <div class="grid-note">
      <br><br><a href="src\lib\TemplatePDFS\templatedesigns_may2022.pdf" target="_blank"><i>You can view the designs prior to downloading here.</i></a><br><br><br><br>
    </div>
        <div class="grid-tem1">
            <a class="grid-tem1" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%201).docx" target="_blank">Template 1</a>
        </div>
        <div class="grid-tem2">
            <a class="grid-tem2" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%202).docx" target="_blank">Template 2</a>
        </div>
        <div class="grid-tem3">
            <a class="grid-tem3" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%203).docx" target="_blank">Template 3</a>
        </div>
        <div class="grid-tem4">
            <a class="grid-tem4" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%204).docx" target="_blank">Template 4</a> 
        </div>
        <div class="grid-tem5">
            <a class="grid-tem5" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%205).docx" target="_blank">Template 5</a>
        </div>
        <div class="grid-tem6">
            <a class="grid-tem6" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%206).docx" target="_blank">Template 6</a>
        </div>
        <div class="grid-tem7">
            <a class="grid-tem7" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%207).docx" target="_blank">Template 7</a>
        </div>
        <div class="grid-tem8">
            <a class="grid-tem8" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%208).docx" target="_blank">Template 8</a>
        </div>
        <div class="grid-tem9">
            <a class="grid-tem9" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%209).docx" target="_blank">Template 9</a>
        </div>
        <div class="grid-tem10">
            <a class="grid-tem10" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%2010).docx" target="_blank">Template 10</a>
        </div>
        <div class="grid-tem11">
            <a class="grid-tem11" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%2011).docx" target="_blank">Template 11</a>
        </div>
        <div class="grid-tem12">
            <a class="grid-tem12" href="src/lib/TemplatePDFS/YOUR%20NAME%20Resume%202022%20(Resume%20Template%2012).docx" target="_blank">Template 12</a>
        </div>

  </div>
		  	<style>
/********************************  GOOGLE FONTS  ********************************/

@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Sniglet:wght@400;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Mulish:ital,wght@0,200..1000;1,200..1000&display=swap');

/***********************************  GLOBAL  ***********************************/

:global(body) {
    background-image: url('../../lib/images/stardust.png') !important;
    background-size: cover;
    background-position: center;
    margin: 0;
    place-items: center;
    min-width: 320px;
    min-height: 100vh;
    text-align: center;
}

/*********************************  TYPEOGRAPHY  ********************************/
  
  h1 {
	font-family: "Sniglet", system-ui;
	font-weight: 400;
	font-style: normal;
	font-size: 2.5rem;
	text-transform: uppercase;
	color: #fdebf3;
	margin-top: 30px;
  }
  
  p, a, a:visited {
	color: #fdebf3;
	font-size: 1.2rem;
    font-family: "Mulish", sans-serif;
  }

  
  h3 {
	font-family: "Sniglet", system-ui;
	font-weight: 200;
	font-style: normal;
	font-size: 1.5rem;
	color: #444349;
	text-shadow: -1px -1px 0 #fdebf3, 1px -1px 0 #fdebf3, -1px 1px 0 #fdebf3, 1px 1px 0 #fdebf3;
	margin-top: 30px;
	margin-bottom: 0;
	
  }

/**********************************  GRIDS  **********************************/

.container {
  padding: 10px;
  padding-bottom: 0px;
  padding-top: 0px;
  background: transparent;
  align-items: center;
  text-align: center;
}

.grid-container {
  display: grid;
  grid-template-areas:
    'title title title title'
    'mid mid mid mid'
    'note note note note'
    'tem1 tem2 tem3 tem4'
    'tem5 tem6 tem7 tem8'
    'tem9 tem10 tem11 tem12';
  gap: 20px; /* Increased gap between grid items */
  background: transparent;
  padding: 10px;
}

/* Style for all grid-tem classes */
.grid-tem1,
.grid-tem2,
.grid-tem3,
.grid-tem4,
.grid-tem5,
.grid-tem6,
.grid-tem7,
.grid-tem8,
.grid-tem9,
.grid-tem10,
.grid-tem11,
.grid-tem12 {
  background-color: transparent;
  padding: 10px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  font-size: 1.2rem;
  font-family: "Sniglet", system-ui;
  font-weight: 400;
  font-style: normal;
  color: #fdebf3;
}

.grid-title {
  grid-area: title;
}

.grid-mid {
  grid-area: mid;
}

.grid-note {
  grid-area: note;
}

a:hover {
    text-shadow: #fdebf3 1px 0 10px;
    transition: text-shadow 0.3s ease-in-out;
}

</style>