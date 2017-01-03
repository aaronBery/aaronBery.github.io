---
layout: bootstrap-detail
title:  "Institute of Education website"
date:   2016-02-01 19:00:00 +0000
categories: Backbone
---
<div class="row">
  <span class="col-md-6">
    UCL recently launched the new IOE website and at the cornerstone of the site
    was the new search facility.

    Our team worked with an external agency who produced the IOE sites design based upon our responsive framework.
    My main responsibility in this project was putting together the search facility
    (in the form of a single page  application) integrating into our CMS and
    configuring our enterprise search facility Funnelback that provides the REST API.

    To make the functionality as reusable as possible I have made the core
    mechanics availble in
    <a href="https://github.com/UCL-WAMS/indigo/blob/master/js/app/search-page.js">Indigo</a>.

    The application is highly flexible and is used throughout the site in the
    <a href="//www.ucl.ac.uk/ioe/courses/undergraduate" title="Undergraduate">Undergraduate</a>, <a href="//www.ucl.ac.uk/ioe/courses/graduate-taught" title="Graduate Taught">Graduate Taught</a>, <a href="//www.ucl.ac.uk/ioe/courses/graduate-research" title="Graduate Research">Graduate Research</a> Prospectus and the <a href="http://www.ucl.ac.uk/ioe/clients-partners/consultancy-services/case-studies" title="case studies">Case studies</a> pages. It utilizes Backbone.js for the MV and Underscore as the templating engine.
  </span>
  <span class="col-md-6">
    <figure class="figure">
      <img src="/assets/images/ioe-prospectus.png" alt="IOE Prospectus" class="figure-img img-thumbnail"/>
      <figcaption class="figure-caption">IOE Online Prospectus</figcaption>
    </figure>
  </span>
</div>
