## Idiomatic
Naming conventions refer to the identifier naming standards in the Python ecosystem. Idiomatic names refer to names that follow the Python standard. These names:
- start with a letter, never with a number
- can contain numbers
- use underscores to separate full words
- don't contain special characters
- only use standard ASCII characters

Examples: 
- `result`
- `number1`
- `http_status_code`

## Non-idiomatic
Non-idiomatic names do not follow standard naming conventions, but are still legal and available for use. Non-idiomatic names may 
- have other types of ASCII or unicode characters in them
- not separate words with underscores
- be vague

Examples: 
- `café`
- `niño`
- `httpstatuscode`

## Illegal
Illegal names are names that don't follow naming conventions. They will either cause syntax errors or Python will interpret them in unexpected ways. They may:
- start with numbers
- contain dashes instead of underscores
- use Python keywords like `def`, `while`, `if`

Examples:
- `https-status-codes`
- `def`
- `1hundred`