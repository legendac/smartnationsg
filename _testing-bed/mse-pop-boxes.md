---
title: Initiatives Overview
permalink: /initiatives/overview
breadcrumb: Initiatives
---

<style>
/*--------------------------------------------------------------
CODE FROM MSE: START OF policies PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/

/* refrain from using pure img selector as it changes the MSE logo size */
#policies-container > section > div > a > img {
	display: block;
	border: 0;
	width: 100%;
    height: 150px;
    padding: 1em;
    border-radius: 15px 15px 0px 0px;
}

.card {
    flex: 1 0 500px;
    box-sizing: border-box;
    margin: 1rem .25em;
	background: white;
    margin-bottom: 1em;
    /* border: 0.13em solid rgba(0,0,0,.2); */
    border-radius: 15px;
    /* box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3); */
}

.card a {
  color: inherit;
  text-decoration: none; /* no underline */
}

.card-content h6 {
	padding: .5em;
	margin-top: 0.5em;
	margin-bottom: .5em;
    font-weight: bold;
    color: inherit;
    text-decoration: none;
}

.card:hover {
    transition: all 0.0s ease-out;
    box-shadow: 0px 4px 8px rgba(38, 38, 38, 0.2);
    /* top: -4px; */
    border: 2px solid #cccccc;
    background-color: white;
    margin-top: 0.5em;
	margin-bottom: .5em;
  }

.card a:hover {
  color: black;
  text-decoration: none; /* no underline */
}

/* Flexbox stuff */

.cards {
    display: flex;
    flex-wrap: wrap;
    margin: 0 auto;
    /* padding: 0 1em; */
    text-align: center;
 }

@media screen and (min-width: 40em) {
    .card {
       max-width: calc(50% -  1em);
    }
}

@media screen and (min-width: 60em) {
    .card {
        max-width: calc(33% - 1em);
    }
}

@media screen and (min-width: 52em) {
    .img {
        max-width: 52em;
    }
}

@media screen and (max-width : 480px) {
	.card { 
        max-width: 100%; }
}

/*--------------------------------------------------------------
CODE FROM MSE: END OF policies PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
</style>



<main id="policies-container">
<section class="cards">
    <div class="card">
        <a href="/initiatives/strategic-national-projects">
                <img src="/images/initiatives/snp.png">
            <div class="card-content">
                <h6>Strategic National Projects</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
        <div class="card">
        <a href="/initiatives/urban-living">
                <img src="/images/initiatives/urbanliving.png">
            <div class="card-content">
                <h6>Urban Living</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/initiatives/transport">
                <img src="/images/initiatives/transport.png">
            <div class="card-content">
                <h6>Transport</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/initiatives/health">
                <img src="/images/initiatives/health.png">
            <div class="card-content">
                <h6>Health</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/initiatives/digital-government-services">
                <img src="/images/initiatives/digitalgovt.png">
            <div class="card-content">
                <h6>Digital Government Services</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/initiatives/businesses">
                <img src="/images/initiatives/businesses.png">
            <div class="card-content">
                <h6>Businesses</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
</section><!-- .cards -->



</main>
