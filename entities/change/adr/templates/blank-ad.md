# {{title}}
id: **{{id}}**

status: **{{status}}**

story: [{{story}}](https://tracker.yandex.ru/{{story}})

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
{{^blocked}}This decision doesn't block any other issue.{{/blocked}}
 
# Deciders
{{#deciders}}
* {{.}}
{{/deciders}}