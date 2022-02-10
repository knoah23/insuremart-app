<svelte:head>
	<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;700;800&display=swap" rel="stylesheet">
</svelte:head>

<main>
	<div class="skip">
		<a href="#a">Skip</a>
	</div>
	
	<div class="image">
		<div class="sect1">
			<img src="https://i.postimg.cc/KvrnwH7P/Group-619.png" alt="img">
		</div>
	</div>
	
	<div class="sect2">
		<h1>Faster claims processing and payment</h1>
		<p>With real-time processing and updating technology, your claims are guaranteed to be settled within 24 hours</p>
		<div class="indicator">
			<div class="ie"></div>
			<div class="ie"></div>
			<div class="ie active"></div>
		</div>
	</div>

	<div class="buzz">
		<a href="/login">
			<button>Get started</button>
		</a>
		
	</div>
	
	
</main>

<style>
    @keyframes transitionIn {
        from {
            opacity: 0;
            transform: rotateX(-10deg);
        }

        to {
            opacity: 1;
            transform: rotateX(0);
        }
    }
	main {
		background: linear-gradient(180deg, #03588C 0%, #213267 100%);
		color: white;
		height: 100vh;
		padding: 0;
		margin: 0;
		font-family: 'Raleway';
		display: flex;
		justify-content: space-between;
		flex-direction: column;
	}
	.skip {
		display: flex;
		justify-content: flex-end;
		height: 60px;
		align-items: center;
		padding: 0 20px;
	}
	.skip a {
		text-decoration: none;
		font-weight: bold;
		font-size: 16px;
		color: #03A688;
	}
	.image {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-around;
        animation: transitionIn 2s ease;
	}
	.sect1 {
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 0 30px;
	}
	.sect1 img {
		width: 100%;
	}
	.sect2 {
		text-align: center;
		padding: 0 20px;
	}
	.sect2 h1 {
		font-size: 24px;
	}
	.sect2 p {
		font-size: 14px;
	}
	.indicator {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		margin-top: 30px;
	}
	.ie {
		background-color: #a1a1a1;
		border-radius: 50px;
		width: 6px;
		height: 6px;
		margin: 0 3px;
	}
	.active{
		width: 12px;
		height: 6px;
		border-radius: 50px;
		background: white;
	}
	.buzz {
		padding: 0 20px;
		margin: 20px 0;
	}
	button {
		width: 100%;
		padding: 6px 12px;
		border-radius: 8px;
		background-color: white;
		height: 50px;
		color: #023859;
		font-size: 14px;
		font-weight: 800;
		text-transform: uppercase;
		border: none;
		box-shadow: 0px 2px 34px rgba(29, 37, 45, 0.1);
	}
</style>