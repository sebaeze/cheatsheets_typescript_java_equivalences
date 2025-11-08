# cheatsheets_typescript_java_equivalences

This repository is a collections of equivalencies of labels and commands between Typescript and Java

## Safe null / absent handling

|Description|Typescript|Java|
|The goal is to have a function or method safe null/absent value handling|N/A|Optional<T>|
|Safety accessing nested properties|address?.street?.zipcode|Optional.ofNullable(address).orElse(..)|