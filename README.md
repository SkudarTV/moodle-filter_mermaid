# Plugin Filter Mermaid
Plugin filter to create Mermaid diagrams from text ([Mermaid](http://mermaid.js.org/) format).

It uses [Mermaid](https://mermaid.js.org/) tool made by Knut Sveidqvist.
Complete syntax is available at [http://mermaid.js.org/](http://mermaid.js.org/).

This plugin is distributed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) license.

## Use:
Add Mermaid format text between [mermaid]...[/mermaid]

Example:
```
[mermaid]
sequenceDiagram
    Alice ->> Bob: Hello Bob, how are you?
    Bob-->>John: How about you John?
    Bob--x Alice: I am good thanks!
    Bob-x John: I am good thanks!
    Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    Bob-->Alice: Checking with John...
    Alice->John: Yes... John, how are you?
[/mermaid]
```
```mermaid
sequenceDiagram
    Alice ->> Bob: Hello Bob, how are you?
    Bob-->>John: How about you John?
    Bob--x Alice: I am good thanks!
    Bob-x John: I am good thanks!
    Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    Bob-->Alice: Checking with John...
    Alice->John: Yes... John, how are you?
```
```
[mermaid]
pie title What Voldemort doesn't have?
         "FRIENDS" : 2
         "FAMILY" : 3
         "NOSE" : 45
[/mermaid]
```
```mermaid
pie title What Voldemort doesn't have?
         "FRIENDS" : 2
         "FAMILY" : 3
         "NOSE" : 45
```
## Attribution:

Thanks to [Erwan Gallenne](https://github.com/erwang) and his [DBconcept filter](https://github.com/erwang/filter_dbconcept) for the inspiration.