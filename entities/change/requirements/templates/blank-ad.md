## {{title}}
* ID: **{{id}}**
* Type: {{type}}
* Priority: {{priority}}
* Story: [{{story}}](https://tracker.yandex.ru/{{story}})

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

