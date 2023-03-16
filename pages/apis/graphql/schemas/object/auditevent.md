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
  AuditEvent
  <span class="pill pill--object pill--normal-case pill--large"><code>OBJECT</code></span>
</h1>
<!-- vale on -->


<p>Audit record of an event which occurred in the system</p>


<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Fields</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>actor</code><a href="/docs/apis/graphql/schemas/object/auditactor" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT AuditActor"><code>AuditActor</code></a></h3><p>The actor who caused this event</p></td></tr><tr><td><h3 class="is-small has-pills"><code>context</code><a href="/docs/apis/graphql/schemas/union/auditcontext" class="pill pill--union pill--normal-case pill--medium" title="Go to UNION AuditContext"><code>AuditContext</code></a></h3><p>The context in which this event occurred</p></td></tr><tr><td><h3 class="is-small has-pills"><code>data</code><a href="/docs/apis/graphql/schemas/scalar/json" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR JSON"><code>JSON</code></a></h3><p>The changed data in the event</p></td></tr><tr><td><h3 class="is-small has-pills"><code>id</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>occurredAt</code><a href="/docs/apis/graphql/schemas/scalar/datetime" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR DateTime"><code>DateTime</code></a></h3><p>The time at which this event occurred</p></td></tr><tr><td><h3 class="is-small has-pills"><code>subject</code><a href="/docs/apis/graphql/schemas/object/auditsubject" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT AuditSubject"><code>AuditSubject</code></a></h3><p>The subject of this event</p></td></tr><tr><td><h3 class="is-small has-pills"><code>type</code><a href="/docs/apis/graphql/schemas/enum/auditeventtype" class="pill pill--enum pill--normal-case pill--medium" title="Go to ENUM AuditEventType"><code>AuditEventType</code></a></h3><p>The type of event</p></td></tr><tr><td><h3 class="is-small has-pills"><code>uuid</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3><p>The public UUID for the event</p></td></tr>
  </tbody>
</table>




<h2 data-algolia-exclude>Interfaces</h2>
<a href="/docs/apis/graphql/schemas/interface/node" class="pill pill--interface pill--normal-case pill--large" title="Go to INTERFACE Node"><code>Node</code></a>