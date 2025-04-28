
> The limits of language are the limits of one's world

## Vocabulary
- `conversely`: in an opposite way.
- `intuit`: know about something that from your feeling, rather than from the fact
- `devious`: using indirect to get what you want, without showing your real purpose.
- `devious code`: intentionally designed to be hard to understand or guess.
- `compromise`: an agreement in an argument in which people involved reduce their demand or change their option in other to agree.
- `stout of heart`: brave and resolute, courageous and determined 

## Why is domain language important?
Each programming language has their own buzzwords, philosophy. Each of them can solve a different problem or can be obscured when tackling a problem. Therefore without knowing a lot of them, we might choose an incorrect approach.

## Internal domain languages vs External domain languages
- Internal domain languages are the language that will run the developer's code directly without converting into any transient languages. Like the RSpec router example.
- External domain languages are the language that will convert the developer's code into other form of code before running. Like Cucumber and Ansible.
### Trade-offs
- Write tests, automation: internal domain languages will help
- Compromise with the semantic syntax of the languages. This is true for internal languages. And less for the external languages because they usually provide a way to extend the parser, but we still need to compromise to the parser rules some point.
- Should not invest more than you saving. Therefore the external languages only should be used for allowing end user to editing.