<!-- src/routes/+page.svelte -->
<script>
    import Layout from './+layout.svelte'
</script>

<h1>Kai Aydan Support Hub</h1>

<div>
	<p> It's not easy to get a document just right or find the right resource when there is so much pressure resting on it.<br>
        It's my job to take some of that pressure off of you, so that you have the energy to take it from there.<br>
        <br>
        The goal is to give you the materials you need to get your foot in the door.<br>
        You don't need the skills to make a fancy resume to work in a store or a warehouse, but you do need<br>
        something that will catch an employer's eye and make them want to learn more about you and your skills.<br>
        <br>
        My hope is that something here, whether it be a resource, template, or just some helpful information you<br>
        didnt have before, can help put you on an even playing field and get you where you want to be.
        </p>
</div>
<style>

/********************************  GOOGLE FONTS  ********************************/

@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Sniglet:wght@400;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Mulish:ital,wght@0,200..1000;1,200..1000&display=swap');


/***********************************  GLOBAL  ***********************************/

:global(body) {
    background-image: url('../lib/images/stardust.png') !important;
    background-size: cover;
    background-position: center;
    margin: 0;
    place-items: center;
    min-width: 320px;
    min-height: 100vh;
    text-align: center;
}

/*********************************  TYPEOGRAPHY  ********************************/
p {
	color: #fdebf3;
	font-size: 1.2rem;
    font-family: "Mulish", sans-serif;

  }

  h1 {
	font-family: "Sniglet", system-ui;
	font-weight: 600;
	font-style: normal;
	/*color: #7394db;*/
	color: #444349;
	text-shadow: -1px -1px 0 #fdebf3, 1px -1px 0 #fdebf3, -1px 1px 0 #fdebf3, 1px 1px 0 #fdebf3;	
	font-size: 3.2rem;
	line-height: 1.1;
	margin-top: 0;
  }
  
  h2 {
	margin-bottom: 45px;
	font-family: "Sniglet", system-ui;
	font-weight: 400;
	font-style: normal;
	color: #444349;
	text-shadow: -1px -1px 0 #fdebf3, 1px -1px 0 #fdebf3, -1px 1px 0 #fdebf3, 1px 1px 0 #fdebf3;
	font-size: 2.3rem;
	line-height: 1.1;
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
  
  h4 {
	font-family: "Sniglet", system-ui;
	font-weight: 400;
	font-style: normal;
	font-size: 1.5rem;
	text-transform: uppercase;
	color: #c673db;
	margin-top: 30px;
  }
  
  p {
	color: #fdebf3;
	font-size: 1.2rem;
  }
  
  p3 {
	color: gray;
	font-size: 1.2rem;
	
  }
  
  .borderexample {
	border-width:3px;
	border-style:solid;
	border-color:#287EC7;
   }
  
  a {
	font-weight: 500;
	color: #646cff;
	text-decoration: inherit;
  }
  a:hover {
	color: #535bf2;
  }
  
  h5 {
	font-family: "Sniglet", system-ui;
	font-weight: 600;
	font-style: normal;
	/*color: #7394db;*/
	color: #444349;
	text-shadow: -1px -1px 0 #fdebf3, 1px -1px 0 #fdebf3, -1px 1px 0 #fdebf3, 1px 1px 0 #fdebf3;	
	font-size: 1.5rem;
	line-height: 1.1;
	margin-top: 0;
  }
  
  h5:hover {
	filter: drop-shadow(0 0 1em #fdebf3);
    transition: text-shadow 0.3s ease-in-out; /* Adjust these values as needed */
  }
  
  h6 {
	font-family: "Sniglet", system-ui;
	font-weight: 400;
	font-style: normal;
	/*color: #7394db;*/
	color: #444349;
	text-shadow: -1px -1px 0 #fdebf3, 1px -1px 0 #fdebf3, -1px 1px 0 #fdebf3, 1px 1px 0 #fdebf3;	
	font-size: 2rem;
	line-height: 1.1;
	margin-top: 0;
	margin-bottom: 0;
  }
  
  h7 {
	font-family: "Sniglet", system-ui;
	font-weight: 400;
	font-style: normal;
	/*color: #7394db;*/
	color: #fdebf3;
	text-shadow: -1px -1px 0 #444349, 1px -1px 0 #444349, -1px 1px 0 #444349, 1px 1px 0 #444349;	
	font-size: 1.5rem;
	line-height: 1.1;
	margin-top: 0;
  }
  
  h6:hover, h7:hover {
	filter: drop-shadow(0 0 1em #fdebf3);
    transition: text-shadow 0.3s ease-in-out; /* Adjust these values as needed */

  }
</style>