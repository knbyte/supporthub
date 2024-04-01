<!-- src/routes/templib/+page.svelte -->
<script>
    import Layout from '../+layout.svelte'
</script>
	<div class="about-container">
		  <h1>About</h1>
		  </div>
		  <div class="about-container">
			<p>Hi, I'm Kai Aydan. Back in 2022 I created the orginal version of this site called Kai Aydan Designs.<br><br>
		I was working as a job coach and every day I saw how often people struggled with resume building. <br>
		It was a part of my job to provide general information and help clients get basic resumes together,<br> but there was never sufficient 
		time in the 15 minute appointment slots to go more in-depth.<br><br>I decided to make a resource that 
		might give just enough help and information to make it a bit easier<br>and so, the support hub was born!<br><br>
		It's been a wild couple of years, and for some time the website was unavaliable.<br>
		I am very excited that the Support Hub is back up and ready to go, I will be adding resources as often as I can.<br><br></p>
		<h1>Contact</h1>
		<p>All of my details can be found on my <a href="https://knbyte.github.io" target="_blank">linktree</a>.<br><br>
		If you have specific ideas about resources you would like to see you can use the following template to email me!</p>
		<p><b>From:     </b>youremail@email.com<br>
		  <b>To:     </b>kaiaydan413@gmail.com<br>
		  <b>Subject:     </b>Support Hub<br>
		  <b>Message:     </b>Your message here!<br>
		</p>
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

/*********************************  CENTERING  ********************************/

.container {
    margin: 0 30px; /* Adjust the margin as needed */
    padding: 0 30px; /* Add padding to the left and right sides */
}
</style>