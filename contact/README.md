---
layout: full-width-breadcrumb
title: Contact
permalink: /contact/
js-vendor: contact
css-pack: contact
---
<div id="contact-thanks">
    <div class="jumbotron">
        <h3 class="text-center animated fadeIn">Join the AI movement.</h3>
    </div>
</div>

<div class="container-fluid">
    <div class="container">
        <!-- Tab panes -->
      <div class="row">
      <div class="col-md-4">
          <h1>Contact Info</h1>
          <address>
            96Boards.ai c/o Linaro<br />
            Harston Mill<br />  
            Royston Rd<br />
            Harston<br />
            Cambridge<br />
            CB22 7GG<br />
          </address>
      </div>
      <div class="col-md-8">
          <div class="cognito">
              <script src="https://services.cognitoforms.com/s/KvRQmIn2dku6k6gGP711jw"></script>
              <script>
                  Cognito.load("forms", { id: "11", entry: {
                    "PageUrl": "{{site.url}}{{page.url}}" ,
                    "RedirectUrl" : "{{site.url}}/thank-you/?ref={{page.url}}"
                  }});
              </script>
          </div>
      </div>
      </div>
    </div>
</div>