---
title: OpenAPI reference example
permalink: /docs/openapi/
---

DOCS UPDATE 3:33PM


<!-- <div class="intrinsic-container">

	<iframe src="/sample-dev-portal/dist/"></iframe>

</div> -->
<div id="swagger-ui" class="intrinsic-container"></div>
<!-- <script src="https://unpkg.com/swagger-ui-dist@4.5.0/swagger-ui-bundle.js" crossorigin></script> -->
<script src="https://unpkg.com/swagger-ui-dist@5.10.0/swagger-ui-bundle.js" crossorigin></script>
<script>
  window.onload = () => {
    window.ui = SwaggerUIBundle({
      url: '/sample-dev-portal/openapi2.json',
      dom_id: '#swagger-ui',
    });
  };
</script>