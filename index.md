---
---
<style>

.column {
  float: left;
  width: 25%;
}

.column10 {
  float: center;
  width: 10%;
}

.column33 {
  float: left;
  width: 33.33%
}

.column45 {
  float: left;
  width: 45%;
}

.column45r {
  float: right;
  width: 45%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.image {
    padding: 10px;
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<hr />

<div class='row'>
    <div class='column45'>
      <a href="{{site.baseUrl}}/docs/AboutUs.html"><h3> About Us </h3></a>
      <p> 
        Something Something Something
        Blah Blah Blah
      </p>
    </div>
    <div class='column10'></div>
    <div class='column45r'>
      <h3> Our Program </h3>
      <dl>
          <dt>Seminars</dt>
          <dd> Based on a series of specific topics, leaving time for discussions.</dd>
          <dt>Hackathons</dt>
          <dd> Dedicated time to sit down and hack out a pipeline, module, simple task or complete a community challenge.</dd>
          <dt>Meet ups</dt>
          <dd> Getting together experts to showcase where these workflows can go! So far they're used anywhere from DNA pipelines to Radio Astronomy!</dd>
      </dl>
    </div>
</div>

<div class='row'>

---
<p>Sponsored by:</p>
<div class="row">
  <div class="column33">
    <a href="https://www.ebi.ac.uk/"><img src="logos/colour/Ebi_official_logo.png" alt="EMBL-EBI logo" height=75em class="image" align='right'/></a>
  </div>
  <div class="column33">
    <a href="https://www.sanger.ac.uk/"><img src="logos/colour/Wellcome_Sanger_Institute_Logo_Landscape_Digital_RGB_Full_Colour.svg" alt="Wellcome Sanger Logo" height=75em class="image" align='left'/></a>
  </div>
  <div class="column33">
    <a href="https://www.wellcomegenomecampus.org/"><img src="logos/colour/WGC_Logo_Landscape_Strapline.png" alt="Wellcome Genome Campus Logo" height=75em class="image" align='center'/></a>
  </div>
</div>