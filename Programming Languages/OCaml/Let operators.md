
### Useful links:
	
* https://ocaml.org/manual/bindingops.html 	
* https://jobjo.github.io/2019/04/24/ocaml-has-some-new-shiny-syntax.html 


In OCaml you can define some custom infix and prefix[^1] operators, this is heavily used in languages like haskell, where it is pretty normal to see some operators like: `>>=`, for example, in OCaml we could define the pipe operator like this:

```ocaml
let ( |> ) x f = f x;;
val ( |> ) : 'a -> ('a -> 'b) -> 'b = <fun> 
```

In OCaml 4.08


[^1]: https://ocaml.org/manual/expr.html#ss:precedence-and-associativity 