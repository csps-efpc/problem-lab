---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/little-prince.jpg
image: assets/little-prince.jpg
---
This site is an example of how Markdown might be used to coordinate the work of the CSPS with the Problem Lab in writing content that creates a common framework for Innovation in the Federal Public Service. 

Topics:

<!--  Topis styles below      -->

<style>
.grid {
 display: grid;
 grid-template-columns: 1fr 1fr;
 justify-content: center;
 grid-gap: 0.25rem;
 padding: 0rem 10rem 0rem 10rem;
}

.theme {
  display: flex;
  align-items: center;
  height: 30vw;
  width: 40vw;
  max-width: 290px;
  max-height: 200px;
  background: black;
  text-overflow: ellipsis;
  overflow: hidden;
  word-wrap: break-word;
  line-height: 2vw;
  font-size: 1.5vw;
  color: white;
  font-weight: bold;
}

.theme:hover {
  opacity:0.5;
}

.text {
  display: inline-block;
  margin: 5%;
  align-item: center;
  text-decoration: none;
}


</style>


<!--  Topics below      -->

<div class="grid">
  <div class="theme" id ="theme-1">
   <span class = "text"><a href ="defining-innovation" class ="link">Defining innovation</a></span> 
  </div>

  <div class="theme" id ="theme-2">
   <span class = "text"> <a href ="risk-enablement" class ="link">Enabling us to jump: risk enablement</a></span> 
  </div>

  <div class="theme" id ="theme-3">
   <span class = "text"><a href ="experimentation-for-great-purpose" class ="link">Experimentation for great purpose</a></span> 
  </div>

  <div class="theme" id ="theme-5">
   <span class = "text"><a href ="generating-innovative-solutions" class ="link">Generating innovative solutions</a></span> 
  </div>

  <div class="theme" id ="theme 6">
   <span class = "text"><a href ="advocating-for-innovation" class ="link">Advocating within the Organizational context for innovation</a></span> 
  </div>
</div>
