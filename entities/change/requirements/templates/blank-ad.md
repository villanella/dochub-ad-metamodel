## {{title}}
* ID: **{{id}}**
{{#type}}* Type: **{{type}}**{{/type}}
{{#priority}}* Priority: **{{priority}}**{{/priority}}
* Story: [{{story}}](https://tracker.yandex.ru/{{story}})
{{#status}}* Status: **{{status}}**{{/status}}

### Description
{{&description}}

### Related use cases
{{#usecases}}
* [{{title}}](/entities/seaf.change.uc/blank?seaf-uc-id={{id}})
{{/usecases}}

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

