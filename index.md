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
        The Workflows Community of Practice aims to build a long-lasting local community of developers of pipelines, associated tools and informatics infrastructure, as well as Nextflow users.

        "As bioinformatics continues to evolve quickly we recognise how essential communities, such as this one, are," said John Boyle, Associate Director of Science Solutions at the Wellcome Sanger Institute. "This community provides the means for us to share and advance knowledge with our peers. It also provides a forum for us to understand best practice, so that we can improve how we use workflow tools to rapidly put together state of the art analysis pipelines, which are required for us to undertake cutting-edge science."
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
