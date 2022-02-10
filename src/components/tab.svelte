<svelte:head>
    <link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;700;800&display=swap" rel="stylesheet">
</svelte:head>

<nav class="nav1">
    <a href="/dash" class="nav__link active">
        <i class='bx bxs-home'></i>
  </a>
  <a href="/dash" class="nav__link">
    <i class='bx bxs-check-shield'></i>
  </a>
    <a href="/dash" class="nav__link">
        <i class='bx bxs-briefcase'></i>
    </a>
        <a href="/dash" class="nav__link">
            <i class='bx bxs-user'></i>
        </a>
  </nav>


<style>
	:root {
	--input: rgb(244,244,244);
	--red: rgb(209, 3, 3);
	--subtext: #8e8e8e;
	--main: #1C89A7;
	--black: #000;
	--white: #fff;
	--background: #fff;
	--border-color: #e1e0e0;
	--icon: #cccdcd;
	}
	a {
	color: #495057;
	text-decoration: none;
	background-color: transparent;
	}

	.nav1 {
	position: fixed;
	bottom: 0px;
	width: 100vw;
	height: 70px;
	background-color: #F9F9F9F0;
	display: flex;
	overflow-x: auto;
	border-top: .5px solid rgba(58, 38, 38, 0.11);
    padding-right: 30px;
	}

	.nav__link {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	flex-grow: 1;
	min-width: 50px;
	overflow: hidden;
	white-space: nowrap;
	font-family: sans-serif;
	font-size: 30px;
	color: #222;
	text-decoration: none;
	-webkit-tap-highlight-color: transparent;
	transition: background-color 0.1s ease-in-out;
	}

	.active path {
	stroke: var(--main);
	}

	a {
	color: #222;
	text-decoration: none;
	background-color: transparent;
	}

	a:hover {
	color: var(--main);
	}

	* {
	box-sizing: border-box;
	}

	a:hover {
	color: var(--main);
	}
</style>