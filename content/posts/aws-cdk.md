---
title: "aws-cloud-developement-kit"
date: 2020-08-22T00:00:00-04:00
draft: false 
mermaid: true
---
1. manual in console
2. scripted via aws-cli or aws-sdk
3. declarative JSON/YAML via cloudformation
4. document-obj-model (DOM) via troposphere
5. componentized via aws-cdk 

{{< mermaid >}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

{{ if (.Params.mermaid) }}
<!-- MermaidJS support -->
<script async src="https://unpkg.com/mermaid@8.2.3/dist/mermaid.min.js"></script>
{{ end }}

