---
layout: inner
title: Index Settings
permalink: /refs/index-settings/
---

# Index Settings

You can apply index settings to the entity properties in the Data Hub Framework. The settings and their corresponding icons are:

| Icon | Name | If selected, |
|------|------|--------------|
| <i class="fa fa-key"></i> | Primary Key | The property is used as the primary key for indexing. Exactly one property must be selected as the primary key. <br>See [Identifying the Primary Key Entity Property](https://docs.marklogic.com/guide/entity-services/models#id_43651). |
| <i class="fa fa-bolt"></i> | Element Range Index | The property is backed by an element range index in the database. This affects the query options you can generate from a model. <br>See [Identifying Entity Properties for Indexing](https://docs.marklogic.com/guide/entity-services/models#id_25826). |
| <i class="fa fa-code"></i> | Path Range Index | The property is backed by a path range index in the database. This affects the query options you can generate from a model. <br>See [Identifying Entity Properties for Indexing](https://docs.marklogic.com/guide/entity-services/models#id_25826). |
| <i class="fa fa-won"></i> | Word Lexicon | The property is backed by a word lexicon in the database. This affects the query options you can generate from a model. <br>See [Identifying Entity Properties for Indexing](https://docs.marklogic.com/guide/entity-services/models#id_25826). |
| <i class="fa fa-exclamation"></i> | Required Field | The property must be in every instance of the entity type. You can set multiple properties as required. See [Distinguishing Required and Optional Entity Properties](https://docs.marklogic.com/guide/entity-services/models#id_92216). |
| <i class="fa fa-lock"></i> | Personally Identifiable Information | The property's value must be safeguarded and handled according to PII protection rules and policies. You can set multiple properties as PII. <br>See [Identifying Personally Identifiable Information (PII)](https://docs.marklogic.com/guide/entity-services/models#id_33998). |

## See Also
- [Range Indexes and Lexicons](https://docs.marklogic.com/guide/admin/range_index)