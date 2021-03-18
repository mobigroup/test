<!-- Import the component -->
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
<style>
model-viewer {
  display: block;
  width: 500px;
  height: 300px;
  --poster-color: transparent;
}
</style>

<script>
document.querySelector("header h1").textContent = '21st Geology'
this.img = document.createElement("img");
this.img.src = "https://avatars.githubusercontent.com/u/7342379?s=460&u=37e514700d78db61a39b9b298b7e70b63b1f390a&v=4";
src = document.querySelector("p.view");
src.appendChild(this.img);
this.div = document.createElement("div");
this.div.innerHTML = `
<svg style="float: left; margin: 4px;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" width="24px" height="24px" viewBox="0 0 24 24" enable-background="new 0 0 24 24" xml:space="preserve">
<rect id="Bounding_Box" x="0" y="0" fill="none" width="24" height="24"></rect>
<g id="Art_layer">
	<path d="M3,4c0-0.55,0.45-1,1-1h2V1H4C2.35,1,1,2.35,1,4v2h2V4z"></path>
	<path d="M20,3c0.55,0,1,0.45,1,1v2h2V4c0-1.65-1.35-3-3-3h-2v2H20z"></path>
	<path d="M4,21c-0.55,0-1-0.45-1-1v-2H1v2c0,1.65,1.35,3,3,3h2v-2H4z"></path>
	<path d="M20,21c0.55,0,1-0.45,1-1v-2h2v2c0,1.65-1.35,3-3,3h-2v-2H20z"></path>
	<g>
		<path d="M18.25,7.6l-5.5-3.18c-0.46-0.27-1.04-0.27-1.5,0L5.75,7.6C5.29,7.87,5,8.36,5,8.9v6.35c0,0.54,0.29,1.03,0.75,1.3
			l5.5,3.18c0.46,0.27,1.04,0.27,1.5,0l5.5-3.18c0.46-0.27,0.75-0.76,0.75-1.3V8.9C19,8.36,18.71,7.87,18.25,7.6z M7,14.96v-4.62
			l4,2.32v4.61L7,14.96z M12,10.93L8,8.61l4-2.31l4,2.31L12,10.93z M13,17.27v-4.61l4-2.32v4.62L13,17.27z"></path>
	</g>
</g>
</svg>
Recent iOS/iPadOS/Android devices assure the best <a href="https://www.apple.com/augmented-reality/">AR experience</a>`;
src.appendChild(this.div);
</script>

## Augmented Reality (AR) Geological Model of Lahendong Geothermal Reservoir on Minahasa Compartment, North Sulawesi, Indonesia
<div><model-viewer
    id="modelviewer1"
    loading="eager"
    src="Minahasa08.glb?time=1"
    ios-src="Minahasa08.m.usdz"
    poster="screenshot.jpg"
    ar
    ar-modes="webxr scene-viewer quick-look fallback"
    camera-controls
    alt="3D model"
/></div>

## Augmented Reality (AR) Geological Model of Rinjani and Tambora volcanoes area, Indonesia (test 2)

<!-- page content -->
<div><model-viewer
    id="modelviewer2"
    loading="eager"
    src="Minahasa08.glb?time=1"
    ios-src="Minahasa08.m.usdz"
    poster="screenshot.jpg"
    ar
    ar-modes="webxr scene-viewer quick-look fallback"
    camera-controls
    alt="3D model"
/></div>
