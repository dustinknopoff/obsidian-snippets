---
title: Variable Embed Heights
date: 2020-06-21

taxonomies:
  tags:
    - css
  kind:
    - styling
extra:
  author: foreveryone
---css
.markdown-preview-view .markdown-embed-content { 
  max-height: unset;
}

.internal-embed.is-loaded[alt="short"] {
  max-height: 45vh !important;
  overflow: auto !important;
  padding-right: 0px!important;
}

.internal-embed.is-loaded[alt="tall"] {
  max-height: 80vh !important;
  overflow: auto !important;
}
```
