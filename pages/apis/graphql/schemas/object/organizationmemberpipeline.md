---
toc: false
---
<!--
  _____   ____    _   _  ____ _______   ______ _____ _____ _______
  |  __  / __   |  | |/ __ __   __| |  ____|  __ _   _|__   __|
  | |  | | |  | | |  | | |  | | | |    | |__  | |  | || |    | |
  | |  | | |  | | | . ` | |  | | | |    |  __| | |  | || |    | |
  | |__| | |__| | | |  | |__| | | |    | |____| |__| || |_   | |
  |_____/ ____/  |_| _|____/  |_|    |______|_____/_____|  |_|
  This file is auto-generated by script/generate_graphql_api_content.sh,
  please build the schema.json by running `rails api:graph:export`
  with https://github.com/buildkite/buildkite/,
  replace the content in data/graphql_data_schema.json
  and run the generation script `./scripts/generate-graphql-api-content.sh`.
-->
<!-- vale off -->
<h1 class="has-pills" data-algolia-exclude>
  OrganizationMemberPipeline
  <span class="pill pill--object pill--normal-case pill--large"><code>OBJECT</code></span>
</h1>
<!-- vale on -->


<p>Represents the connection between a user an a pipeline within an organization</p>


<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Fields</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>pipeline</code><a href="/docs/apis/graphql/schemas/object/pipeline" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT Pipeline"><code>Pipeline</code></a></h3><p>The pipeline the user has access to within the organization</p></td></tr>
  </tbody>
</table>