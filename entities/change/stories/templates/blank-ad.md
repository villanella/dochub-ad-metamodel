# {{title}}
id: **{{id}}**

status: **{{status}}**

issue: [{{issue}}](https://tracker.yandex.ru/{{issue}})

revision: **{{revision}}**

release: **{{release}}**


# Problem
{{problem}}

# Decision 
{{decision}}

# Requirements
{{#requirements}}
![{{title}}]({{link}})
{{/requirements}}


# To be done after
{{#dependencies}}
* [{{title}}]({{link}})
{{/dependencies}}
{{^dependencies}}No blockers{{/dependencies}}

# Blocks
{{#blocked}}
* [{{title}}]({{link}})
{{/blocked}}
{{^blocked}}This story doesn't block any other issue.{{/blocked}}
 
# Authors/Reviewers
{{#deciders}}
* {{.}}
{{/deciders}}
 
# Changelog
| Revision | Requirement | Type of change | Date | Comment |
|----------|:------------| -----------|------|----|
{{#changelog}}
| {{revision}} | {{requirement}} | {{change_type}} | {{date}} | {{comment}} |
{{/changelog}}
