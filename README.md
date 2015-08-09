# lisp-phonelist
Phone list in LISP (made for Programming Paradigms)
  
Interaction example:

````lisp
> (setq AGENDA ‘nil)
> (setq AGENDA (incluir AGENDA ‘(Bel 32338778)))
> (setq AGENDA (incluir AGENDA ‘(Rose 32666556)))
> (setq AGENDA (incluir AGENDA ‘(Rose 91919191)))
> (setq AGENDA (incluir AGENDA ‘(Beto 32529119)))
> (Telefones AGENDA ‘Jose)
INEXISTENTE
> (Telefones AGENDA ‘Rose)
(32666556 91919191)
> (setq AGENDA (excluir AGENDA ‘Rose 91919191))
> (Telefones AGENDA ‘Rose)
(32666556)
> (setq AGENDA (excluir AGENDA ‘Rose 91919191))
> (Telefones AGENDA ‘Rose)
(32666556)
> (setq AGENDA (excluir AGENDA ‘Rose 32666556))
> (Telefones AGENDA ‘Rose)
INEXISTENTE
````
