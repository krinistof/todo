# Here is `todo`! 

A process framework for collaboration.
Had you ever wanted to automate tasks (eg. AIOps) which need a proof-of-quality process?
Have you ever used a issue tracking service like jira, and thought why isn't that handled in files, on version control? 

Do you like simplicity combined with extensibility?
- modular system with modules, which can interact with each other.
- allows for definition of state machines, to coordinate teamwork, support implenentation, documentation, review tasks with drafts, policy checkers.

## Structure

### The simplest arragement
The most minimal layout for a new todo project is `.todo` hidden directory, which should contain task management materials, such as state, rules, services. 
Have you ever used an Excel for managing things `to do`? It's working, right?.

## Modules
`todo` doesn't require someone to use any language, technology, ai or human actors, digital or phisical. There is no restriction about what defines the state and the rules.   
Any system which stores the state of processes is compliant to be part of a `todo` system. If you have a paper notebook and a pencil, you take notes and follow promises, your process is `todo` compatable. Following that same mentality we can create automations that work by the same logic following the unix principles where possible.
The following subchapters contain details about some modules. The real power of this framework is in the combination of different modules.
Each of those modules can be a subdirectory in the project's root `.todo` directory. 

### `todo` - store tasks to do
Any format can be used. Other modules operate on, mutate those.

### `rules` - define actions
A fancy way to name your scripts dir. Any language, calling convection can be used. API endpoints can be included for dynamic behaviour.

### `rules/new` - process new assets.
Imagine the following: Ask your team to leave todos. Using pattern recognition for each new task, and triggers an action to track and help resolve them efficiently.

### `coherent` - tracking for references
Handle task based on changing assets, such as requirements, implementations, documentation, and enforce clarity.


## Advantages
The world is changing. We need stability to create secure processes, thus rules with requirements, but in critical contexts it's important to have requirements with traceable changes using version control systems like `git`. From boring sample responses to code reviews, assisting with ai generated drafts and human validated final results can improve teamwork and required effort.
