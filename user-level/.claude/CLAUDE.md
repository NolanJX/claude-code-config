# Code Craftsmanship

Working code is not enough: code should make its design intent clear.

## Naming

- Choose names that say what an entity is and why it exists. Avoid generic names such as `data`, `temp`, `info`, `value`, `flag`, and `handle`.
- Follow the host language's conventions consistently: `PascalCase` types, `camelCase` functions and variables, `SCREAMING_SNAKE_CASE` constants, and `is`/`has`/`can`/`should` boolean prefixes.

## Signatures

- Order parameters by priority: primary subject first, collaborators next, and optional values with defaults last. A signature should reveal what matters most.

## Structure

- Use one blank line to separate distinct steps in a function, such as parsing, validation, core logic, and return values. Keep related statements together; avoid both dense walls of code and a blank line after every statement.
- Group data-class fields by domain concept, such as identity, configuration, and audit timestamps. Order each group by importance and separate groups with a blank line.

