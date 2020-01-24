<!DOCTYPE html>
<html>
	<head>
		<title>My Portfolio</title>
	</head>
	<body>
		<nav id="top-navbar">
			<a href="#section-showcase"><strong>Portfolio Name</strong></a>
			<ul>
				<li>	<a href="#section-home"> Home </a>	</li>
				<li>	<a href="#section-about"> About </a>	</li>
				<li>	<a href="#section-projects"> Projects </a>	</li>
				<li>	<a href="#section-blog"> Blog </a>	</li>
				<li>	<a href="#section-contact">Contact</a>	</li>
			</ul>
		</nav>
		<section id="section-showcase">
			<div>
				<h1> My Title Here. </h1>
				<p> description goes here </p>
			</div>
		</section>
		<aside id="sidebar">
			<div>
				<h3> News: </h3>
				<p> This is a place for some placeholder text. </p>
			</div>
		</aside>
		<section id="section-home">
			<h1> Welcome </h1>
			<hr>
			<p>
				This section welcomes people to your page and summarizes what the page is about and what the purpose of it is for. Add your own comments here.
			</p>
		</section>
		<section id="section-about">
			<h1> About </h1>
			<hr>
			<div>
				<img src="images/profile.png">
			</div>
			<div>
				<h4> First Last </h4>
				<p> This is info about me. </p>
			</div>
			<table>
				<thead>
					<tr>
						<th colspan='2'> Technical Skills </th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<th> Programming tools </th>
						<td> Java, Javascript </td>
					</tr>
					<tr>
						<th>Frontend tools</th>
						<td> HTML, CSS </td>
					</tr>
					<tr>
						<th>Database tools</th>
						<td>MongoDB, Mongoose, SQL</td>
					</tr>
					<tr>
						<th> Version Control & Deployment tools </th>
						<td>git, github, gitlab</td>
					</tr>
					<tr>
						<th>Architecture & Design</th>
						<td>OOP, MEAN Stack, REST, Agile, TDD</td>
					</tr>
				</tbody>
			</table>
		</section>
		<section id="section-projects">
			<h1>Projects</h1>
			<hr>
			<p>Summary of all the projects you have worked on.</p>
			<div>
				<div id="projects">
					<a href='#' target="_blank">
						<div>
							<p>Project</p>
						</div>
						<img src='images/logo.png'>
						<div>
							<h4>Project Name</h4>
						</div>
						<div>
							<small>by Evan Fogg</small>
'						</div>
					</a>
				</div>
			</div>
		</section>
		<section id="section-blog">
			<h1>Blog</h1>
			<hr>
			<p>Explain what your blog will be about.</p>
			<hr>
			<article>
				<h3>Topic 1</h3>
				<small>Posted by Evan Fogg on 1/21/2020</small>
				<p>Summary of this blog post</p>
				<a href="post1.html">Read More</a>
				<hr>
			</article
		</section>
		<section id="section-contact">
			<h1>Contact</h1>
			<hr>
			<h4>Send Message</h4>
			<form>
				<div>
					<input type="text" id="name" placehoder="Your Name">
				</div>
				<div>
					<input type="email" id="email" placeholder="Your Email">
				</div>
				<div>
					<input type="subject" id="subject" placeholder="Subject">
				</div>
				<div>
					<textarea rows="4" id="message" placeholder="Message">
					</textarea>
				</div>
				<button type="submit"> Submit </button>
			</form>
		</section>
		<footer>
			<div>
				<p>Copyright &copy; 2020 Evan Fogg</p>
			</div>
		</footer>
	</body>
</html>
