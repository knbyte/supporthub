<nav>
<div class="header">
<div class="grid-nav">
	<div class="grid-nav1">
        <a href="/" class="nav-link">Home</a>
	</div>
	<div class="grid-nav2">
        <a href="/templib" class="nav-link">Template Library</a>
	</div>
	<div class="grid-nav3">
		<a href="/resources" class="nav-link">Resources</a>
	</div>
	<div class="grid-nav4">
		<a href="/about" class="nav-link">About & Contact</a>
	</div>
</div>
</nav>
<style>

/*.header {
        background-color: #333; /* Example background color
        color: white; /* Example text color
		padding: 20px;
        width: 100%; /* Make header span the entire width of the viewport
        box-sizing: border-box; /* Include padding in width calculation
    }*/

.nav-link {
	font-family: "Sniglet", system-ui;
	font-weight: 600;
	font-style: normal;
	color: #444349;
	text-shadow: -1px -1px 0 #fdebf3, 1px -1px 0 #fdebf3, -1px 1px 0 #fdebf3, 1px 1px 0 #fdebf3;	
	font-size: 1.5rem;
	line-height: 1.1;
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 20px;
	text-decoration: none;

}

.nav-link:hover {
  filter: drop-shadow(0 0 1em #fdebf3);
}

.nav-link:visited {
  color: #444349;
}
.grid-nav {
  display: grid;
  grid-template-areas:
    'nav1 nav2 nav3 nav4';
  background: transparent;
  gap: 10px;
  padding: 10px;
  padding-right: 50px;
  padding-left: 30px;
  }

.grid-nav1, .grid-nav2, .grid-nav3, .grid-nav4{
  background: transparent;
  text-align: center;
  margin: 0;
}

.grid-nav1 { grid-area: nav1;}
.grid-nav2 { grid-area: nav2;}
.grid-nav3 { grid-area: nav3;}
.grid-nav4 { grid-area: nav4;}
  
</style>
  