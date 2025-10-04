---
layout: default
title: Home
description: Green Valley College Foundation, Inc. - Shaping Tomorrow Through Quality Education
---

<section data-bs-version="5.1" class="header18 cid-uXRxD0BubM" data-bg-video="assets/video/video-background.mp4" id="header18-1k">
  <div class="mbr-overlay" style="opacity: 0.6; background-color: rgb(0, 0, 0);"></div>
  <div class="container-fluid">
    <div class="row">
      <div class="content-wrap col-12 col-md-12">
        <h1 class="mbr-section-title mbr-fonts-style mbr-white mb-4 display-1">
          <strong><br>Shaping Tomorrow Through Quality Education</strong></h1>
        
        <p class="mbr-fonts-style mbr-text mbr-white mb-4 display-7">#UpodKitasaGreenValley&nbsp;</p>
        <div class="mbr-section-btn"><a class="btn btn-white-outline display-7" href="#">Explore</a></div>
      </div>
    </div>
  </div>
</section>

<section data-bs-version="5.1" class="content3 cid-uXRGa4IEU3" id="content3-1m">
    
    
    <div class="container">
        <div class="mbr-section-head">
            <h4 class="mbr-section-title mbr-fonts-style align-center mb-0 display-2"><strong>Latest news and updates</strong></h4>
            <h5 class="mbr-section-subtitle mbr-fonts-style align-center mb-0 mt-2 display-5">Read the latest events and updates about Green Valley College</h5>
        </div>
        <div class="row mt-4">
            {% for post in site.posts limit:3 %}
            <div class="item features-image col-12 col-md-6 col-lg-4">
                <div class="item-wrapper">
                    <div class="item-img">
                        {% if post.image %}
                        <img src="{{ post.image }}" alt="{{ post.title }}" title="">
                        {% else %}
                        <img src="assets/images/the-1046x877.jpg" alt="{{ post.title }}" title="">
                        {% endif %}
                    </div>
                    <div class="item-content">
                        <h5 class="item-title mbr-fonts-style display-4"><em>{{ post.date | date: "%B %d, %Y" }}</em></h5>
                        <h6 class="item-subtitle mbr-fonts-style mt-1 display-7"><strong>{{ post.title }}</strong></h6>
                        <p class="mbr-text mbr-fonts-style mt-3 display-7">{{ post.excerpt | strip_html | truncate: 150 }}</p>
                    </div>
                    <div class="mbr-section-btn item-footer mt-2"><a href="/news" class="btn item-btn btn-primary-outline display-7">Read More &gt;</a></div>
                </div>
            </div>
            {% endfor %}
        </div>
        
        {% if site.posts.size == 0 %}
        <div class="row justify-content-center mt-5">
            <div class="col-12 col-md-8 text-center">
                <h4 class="mbr-section-title mbr-fonts-style display-4">No news posts yet</h4>
                <p class="mbr-text mbr-fonts-style display-7">Check back soon for the latest updates from Green Valley College!</p>
            </div>
        </div>
        {% endif %}
    </div>
</section>

<section data-bs-version="5.1" class="header1 cid-tJS9vXDdRK" id="header01-7">
	

	
	

	<div class="container">
		<div class="row justify-content-center">
			<div class="col-12 col-md-12 col-lg-7 image-wrapper">
				<img class="w-100" src="assets/images/gallery01.jpg" alt="Mobirise Website Builder">
			</div>
			<div class="col-12 col-lg col-md-12">
				<div class="text-wrapper align-left">
					<h1 class="mbr-section-title mbr-fonts-style mb-4 display-2"><strong>About us</strong></h1>
					<p class="mbr-text mbr-fonts-style mb-4 display-7">
						Most blocks can be used with various types of backgrounds: color, pictures, or videos. It can be set in Block Parameters.&nbsp;You can show/hide the title, subtitle, text, button in the Block Parameters (blue gear icon at the top right corner of the block).&nbsp;</p>
					<div class="mbr-section-btn mt-3"><a class="btn btn-primary display-7" href="#">Start now</a></div>
				</div>
			</div>
		</div>
	</div>
</section>

<section data-bs-version="5.1" class="features15 cid-tLek7gQhG7" id="features015-m">
	

	
	
	<div class="container">
		<div class="mbr-section-head mb-5">
			<h4 class="mbr-section-title mbr-fonts-style align-center mb-0 display-2">
			  <strong>Why us?</strong></h4>
			
		  </div>
		<div class="row justify-content-center">
			<div class="item features-without-image col-12 col-lg-4">
				<div class="item-wrapper">
					<div class="img-wrapper">
						<img src="assets/images/shop1.jpg" alt="Mobirise Website Builder">
					</div>
					<div class="card-box">
						<h4 class="card-title mbr-fonts-style mb-3 display-5">
							<strong>Free</strong></h4>
						<h5 class="card-text mbr-fonts-style display-7">
							Mobirise is a free website builder. Mobirise is a free website builder. Mobirise is a free website builder.</h5>
					</div>
				</div>
			</div>
			<div class="item features-without-image col-12 col-lg-4">
				<div class="item-wrapper">
					<div class="img-wrapper">
						<img src="assets/images/shop2.jpg" alt="Mobirise Website Builder">
					</div>
					<div class="card-box">
						<h4 class="card-title mbr-fonts-style mb-3 display-5">
							<strong>Easy</strong></h4>
						<h5 class="card-text mbr-fonts-style display-7">
							Create landing pages with ease. Create landing pages with ease. Create landing pages with ease.<br><br></h5>
					</div>
				</div>
			</div>
			<div class="item features-without-image col-12 col-lg-4">
				<div class="item-wrapper">
					<div class="img-wrapper">
						<img src="assets/images/shop3.jpg" alt="Mobirise Website Builder">
					</div>
					<div class="card-box">
						<h4 class="card-title mbr-fonts-style mb-3 display-5">
							<strong>Beautiful</strong></h4>
						<h5 class="card-text mbr-fonts-style display-7">
							Build a website with Mobirise. Build a web page with Mobirise. Create a website with Mobirise.</h5>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>