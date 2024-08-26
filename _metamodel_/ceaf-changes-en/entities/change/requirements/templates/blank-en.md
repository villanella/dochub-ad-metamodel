## {{title}}
* ID: **{{id}}**
* Type: {{type}}

### Description
{{&description}}

### Aspects
{{#functionality}}
* [{{title}}](/entities/aspects/blank?dh-aspect-id={{id}})
{{/functionality}}

### Acceptance criteria
| Test       | Expected result     |
| ---------- | :------------------ |
{{#verifications}}
| {{title}} | {{condition}} |
{{/verifications}}

