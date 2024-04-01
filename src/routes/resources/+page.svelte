<script>
    import Layout from '../+layout.svelte'
</script>
	<div class="about-container">
		  <h1>Resources & Information</h1>
		  </div>
		  <div class="about-container">
			<p>The resource library is currently under development.<br>
        Thank you for your patience!<br></p></div>
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

/***********************************  OTHER  **********************************/

.container {
    margin: 0 30px; /* Adjust the margin as needed */
    padding: 0 30px; /* Add padding to the left and right sides */
}

.list {
		list-style: none;
	}
</style>