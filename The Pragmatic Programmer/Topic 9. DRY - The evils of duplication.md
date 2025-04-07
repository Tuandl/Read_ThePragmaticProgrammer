
#### Vocabulary:
- `Subtly nudge someone` to the right direction
- `Premise`: a claim used to infer or follow.
- `Accentuate`: emphasize, make noticeable, prominent
- `Cue`: a signal to do something
- `Harness knowledge`: effectively use knowledge to control something or to reach the target
- `Capsule of knowledge`: a knowledge module, video or documentation to bootstrap of a module
- `Authoritative representation`: a depiction that is considered as official.
- `Acid test`: the proof value of something, or the standard that something must meet in order to prove its value.
- `Implication`: the conclusion draws from something without explicitly saying.

#### DRY
- DRY literally means do not copy and paste code
- Why is it important? It's about maintenance. The maintenance starts very early, even before product goes live. It starts since the requirement changed, requirement changed since the meetings, designing, implementation.
- DRY also means not duplication of knowledge, intent. It's about expressing the same thing in different places, possibly in two totally different ways.

#### Representation duplication
When exposing code via API, both producers and consumers need to store knowledge of these APIs. That's inevitable, but we can mitigate some issues by the following approaches

##### Duplicate across internal APIs
Adopt a tool that helps specify APIs in a neutral format.
These tools will help generate functions, mock APIs, functional tests, and API clients
The point is to be able to share across the team

##### Duplicate across external APIs
Same as internal APIs; if a neutral format does not exist, let's create one to share with others.

##### Duplicate with data source
Can use a tool like ORM to create a container for a table schema

##### Inter-developer duplication
Communication will help, like scrum meeting