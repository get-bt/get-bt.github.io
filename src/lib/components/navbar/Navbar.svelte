<!-- <style>
    a, i {
        color: white;
    }
    nav {
        position: 0;
        width: 100%;
        background-color: var(--secondary-bg);
        padding-block: 1em;
    }
    ul {
        list-style: none;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 1em;
        font-size: larger;
    }

    li {
        position: relative;
        top: 0px;
        transition:top 200ms linear;
    }

    li:hover {
        position: relative;
        top: 5px;
        transition:top 200ms linear;
    }
  </style> -->

<script>
</script>

<nav class="navbar">
	<ul>
		<li class="nav-item">
			<a title="Home" aria-label="Home" href="/">
				<i class="fas fa-home"></i>
                <p>Home</p>
			</a>
		</li>
		<li class="nav-item">
			<a title="About" aria-label="About" href="/about">
				<i class="fas fa-info-circle"></i>
                <p>About</p>
			</a>
		</li>
	</ul>
</nav>

<style>
	.navbar {
		position: fixed;
		top: 0;
		left: 0;
        width: 3em;
		height: 100vh;
		background-color: var(--secondary-bg);
		color: white;
		display: flex;
		flex-direction: column;
		box-sizing: border-box;
        transition: width 200ms linear;
	}
    .navbar:hover {
        width: 8em;
        transition: width 200ms linear;
    }
	.navbar ul {
		list-style-type: none;
		padding: 0.2em;
		margin: 0;
		flex-grow: 1;
	}
	.navbar li {
		margin: 10px 0;
	}
	.navbar li a {
		color: white;
		text-decoration: none;
		display: flex;
		padding: 10px;
		border-radius: 5px;
		transition: background-color 0.3s;
        position: relative;
        left: 0;
        transition: left 200ms linear;
        gap: 1em;
	}
    .navbar li p {
        opacity: 0;
        transition: opacity 200ms linear;
    }
	.navbar li a:hover {
        position: relative;
		background-color: var(--secondary-highlight);
        left: 5px;
        transition: left 200ms linear;
	}
    .navbar li a:hover p {
        opacity: 1;
        transition: opacity 200ms linear;
    }
</style>
