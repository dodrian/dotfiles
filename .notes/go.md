# Go tips and tricks

[Effective Go](https://go.dev/doc/effective_go)

`go fmt` to format code

## For
`for init; condition; post { }`  Like a C for
`for condition { }`  Like a C while
`for { }`  Like a C for(;;)
`for key, value := range myMap { }` for : in / foreach
`for index := range myArray`  drop the value
`for _, value := range myArray` drop the key


## Initializing Types
`new(Type)` returns *Type zero value (equivilant to `&Type{}`)
Define a `func NewType() *Type { }` to initialize a type to non-zero values
