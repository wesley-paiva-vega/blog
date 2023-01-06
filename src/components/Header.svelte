<script>
	import Moon from '../icons/moon.svg';
	import rocket_icon from '../icons/rocket.png';
</script>

<header class="main_header">
	<div>
		<ul class="list_left">
			<li>
				<img src={rocket_icon} width="20px" alt="Logo do Blog" />
			</li>
			<li>
				<span>Wesley Snybool</span>
			</li>
		</ul>
	</div>
	<div>
		<ul class="list_right">
			<li>Sobre Mim</li>
			<li>Artigos</li>
			<li>Contatos</li>
			<li>
				<img src={Moon} alt="" />
			</li>
		</ul>
	</div>
</header>

<style lang="text/scss">
	.main_header {
		display: flex;
		background-color: rgb(213, 213, 213);
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 15px;
	}

	.list_left {
		display: flex;
		justify-content: center;
		align-items: center;
		gap: 15px;
	}

	.list_left li {
		list-style: none;
		cursor: pointer;
	}

	.list_right {
		background-color: rgb(181, 180, 180);
		display: flex;
		gap: 60px;
	}

	.list_right li {
		list-style: none;
		cursor: pointer;
	}
</style>
