<nav>
	<h1>Basix</h1>
	<ul>
		<li><a href="/">Home</a></li>
		<li>Contact</li>
	</ul>
</nav>

<style>
	nav {
		display: flex;
		padding: 2em;
	}
	h1 {
		font-size: large;
		flex: 1;
		display: flex;
		align-items: center;
		margin: 0;
	}
	h1::after {
		display: block;
		flex: 1;
		margin-left: 1em;
		content: '';
		height: 1px;
		width: 100%;
		background-color: #000;
	}
	ul {
		display: flex;
		list-style-type: none;
		padding: 0;
		margin: 0;
	}
	li {
		margin-left: 1em;
	}
	a {
		text-decoration: none;
		color: var(--oc-blue-5);
	}
	a:visited {
		color: var(--oc-blue-5);
	}
	a:focus,
	a:hover {
		color: var(--oc-blue-7);
	}
</style>
