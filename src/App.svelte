<script>
</script>

<main>
	<h1>Queenslink demo</h1>
	<p>
		Feel free to zoom in and pan around. (scroll to zoom in, click and drag
		to pan)
	</p>
	<div id="model_viewer_parent">
		<model-viewer
			id="model_viewer"
			alt="A basic old render of QueensLink"
			src="/models/rbb.glb"
			shadow-intensity="1"
			camera-controls
			touch-action="pan-y"
			auto-rotate
		/>
		<!-- <model-viewer
			id="model_viewer"
			alt="Neil Armstrong's Spacesuit from the Smithsonian Digitization Programs Office and National Air and Space Museum"
			src="/NeilArmstrong.glb"
			shadow-intensity="1"
			camera-controls
			touch-action="pan-y"
		/> -->
	</div>
</main>

<style>
	main {
		width: 100vw;
		min-height: 100vh;
	}
	#model_viewer_parent {
		width: 100vw;
		height: 95vh;
	}
	#model_viewer {
		width: 100%;
		height: 100%;
	}
	h1 {
		margin-top: 10px;
		text-align: center;
	}
	main p {
		text-align: center;
	}
</style>
