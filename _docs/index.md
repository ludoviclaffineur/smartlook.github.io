--- 
layout: default 
permalink: /docs/index.html # show this page as index for collections: https://jekyllrb.com/docs/collections/#step3
---

<div class="container">

<div class="row intro">
  <div class="col-12">
      <h1>{{ site.title }}</h1>
      <p>Smartlook offers a number of extra features to you make your recordings even better.</p>
  </div>
</div>

  <div class="row">
    <div class="col-6">
      <div class="card">
        <a href="{{ '/docs/identify-visitor/' | relative_url }}">
          <h2>Identify visitor</h2>
        </a>
        <p>Display detailed information about visitor in dashboard.</p>
      </div>
    </div>
    <div class="col-6">
      <div class="card">
        <a href="{{ '/docs/sensitive-data-protection/' | relative_url }}">
          <h2>Sensitive data protection</h2>
        </a>
        <p>Do not record sensitive data. Mask forms and inputs.</p>
      </div>
    </div>
  </div>
  <!-- row -->

  <div class="row">
    <div class="col-6">
      <div class="card">
        <a href="{{ '/docs/custom-events/' | relative_url }}">
          <h2>Custom events</h2>
        </a>
        <p>Create your own specific events for tracking.</p>
      </div>
    </div>
    <div class="col-6">
      <div class="card">
        <a href="{{ '/docs/recording-info/' | relative_url }}">
          <h2>Recording info</h2>
        </a>
        <p>Get information about recording such as recording URL.</p>
      </div>
    </div>
  </div>
  <!-- row -->
</div>
<!-- container -->