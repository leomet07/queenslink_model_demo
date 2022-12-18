<script>
</script>

<main>
	<h1>QueensLink model demo</h1>
	<p>
		Feel free to zoom in and pan around. (scroll to zoom in, click and drag
		to pan)
	</p>
	<p>
		Source code: <a href="https://github.com/leomet07/queenslink_model_demo"
			>github.com/leomet07/queenslink_model_demo</a
		>
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
		padding-top: 10px;
	}
	#model_viewer_parent,
	#model_viewer {
		width: 95vw;
		height: 85vh;
		margin: auto;
	}
	#model_viewer {
		border: 1px solid green;
	}

	h1 {
		text-align: center;
	}
	main p {
		text-align: center;
	}
</style>
