/* ================================= 
  Base Element Styles
==================================== */

* {
	box-sizing: border-box;
}
body {
	font-family: 'Varela Round', sans-serif;
	line-height: 1.6;
	color: #3a3a3a;
	margin: 0;
}
ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
p {
	font-size: .95em;
}
h2,
h3,
a {
	color: #093a58;
}
h1,
h2,
h3 {
	margin-top: 0;
}
a {
	text-decoration: none;
}
img {
	max-width: 100%;
}

/* ================================= 
  Base Layout Styles
==================================== */

/* ---- Navigation ---- */

.name {
	font-size: 1.35em;
	margin: 0;
}
.main-nav {
	margin-top: 5px;
}
.name a,
.main-nav a {
	text-align: center;
	display: block;
	padding: 10px 15px;
}
.main-nav a {
	font-size: .95em;
	color: #3acec2;
	text-transform: uppercase;
}
.main-nav a:hover {
	color: #093a58;
}

/* ---- Layout Containers ---- */

.main-header {
	padding-top: .35em;
	padding-bottom: .35em;
}
.banner,
.main-footer {
	text-align: center;
}
.banner {
	color: #fff;
	background: #3acec2;
	padding: 1em 0;
	margin-bottom: 24px;
}
.col {
	padding-right: 1em;
	padding-left: 1em;
}
.main-footer {
	background: #d9e4ea;
	padding: 2em 0;
	margin-top: 30px;
}

/* ---- Page Elements ---- */

.logo {
	width: 132px;
}
.headline {
	margin-bottom: 0;
}
.feat-img {
	border-radius: 5px;
}

/* ================================= 
  Media Queries
==================================== */

@media (min-width: 769px) {
	.main-header,
	.row,
  .footer-inner{
		width: 80%;
		margin: 0 auto;
		max-width: 1150px;
	}
	.tagline {
		font-size: 1.4em;
	}
}
