<!-- src/routes/templib/+page.svelte -->
<script>
    import Layout from '../+layout.svelte'
</script>
	<div class="container">
		  <h1>Disclaimer</h1>
		  </div>
		  <div class="container">
			          <p>The information provided by Kai Aydan Support Hub is for general information purposes only. All information on the site is provided in good faith; however, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability with respect to the website or the information, products, services, or related graphics contained on the website for any purpose. Any reliance you place on such information is therefore strictly at your own risk.<br>
                <br>
                This site may contain links to other websites or content belonging to third parties. Such links are provided for your convenience and do not signify our endorsement of such websites or their content. We have no control over the nature, content, and availability of those sites. The inclusion of any links does not necessarily imply a recommendation or endorse the views expressed within them.<br> 
                <br>
                This site does not and cannot contain mental health advice. The mental health information provided is for general informational and educational purposes only and is not a substitute for professional advice. We encourage you to consult with relevant professionals before taking action based on this information.</p>
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
  
  h1 {
	font-family: "Sniglet", system-ui;
	font-weight: 400;
	font-style: normal;
	font-size: 2.5rem;
	text-transform: uppercase;
	color: #fdebf3;
	margin-top: 30px;
  }
  
  p {
	color: #fdebf3;
	font-size: 1.2rem;
    font-family: "Mulish", sans-serif;
  }

/*********************************  CENTERING  ********************************/

.container {
    margin: 0 30px; /* Adjust the margin as needed */
    padding: 0 30px; /* Add padding to the left and right sides */
}
</style>
