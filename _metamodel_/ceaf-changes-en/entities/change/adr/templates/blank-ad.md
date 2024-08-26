# {{title}}
id: **{{id}}**

status: **{{status}}**

story: [{{story}}](https://tracker.yandex.ru/{{story}})

# Problem
{{issue}}

# Goal
{{decision}}

# Use cases
{{#usecases}}
![{{title}}]({{link}})
{{/usecases}}

# Requirements
{{#requirements}}
![{{title}}]({{link}})
{{/requirements}}

# To be done after
{{#dependencies}}
* [{{title}}]({{link}})
{{/dependencies}}

# Blocks
{{#blocked}}
* [{{title}}]({{link}})
{{/blocked}}

# Deciders
{{#deciders}}
* {{.}}
{{/deciders}}