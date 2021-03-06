# [Lógica proposicional e de predicados](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq)

- [Implicação](implicacao/)
  - [Exercício 01](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-1)
    - `A -> B -> A` [Resolução](implicacao/exercicio_01.v)
  - [Exercício 02](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-2)
    - `(A -> B) -> (B -> C) -> A -> C` [Resolução](implicacao/exercicio_02.v)
- [Conjunção](conjuncao/)
  - [Exercício 03](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-3)
    - `(A /\ B) /\ C -> A /\ (B /\ C)` [Resolução](conjuncao/exercicio_03.v)
  - [Exercício 04](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-4)
    - `((A /\ B) -> C) -> (A -> B -> C)` [Resolução](conjuncao/exercicio_04.v)
  - [Exercício 05](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-5)
    - `(A -> B -> C) -> ((A /\ B) -> C)` [Resolução](conjuncao/exercicio_05.v)
  - [Exercício 06](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-6)
    - `((A -> B) /\ (A -> C)) -> A -> (B /\ C)` [Resolução](conjuncao/exercicio_06.v)
- [Disjunção](disjuncao/)
  - [Exercício 07](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-7)
    - `((A \/ B) /\ ~ A) -> B` [Resolução](disjuncao/exercicio_07.v)
  - [Exercício 08](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-8)
    - `(A \/ (B /\ C)) -> (A \/ B) /\ (A \/ C)` [Resolução](disjuncao/exercicio_08.v)
- [Quantificadores universal e existencial](quantificadores_universal_existencial/)
  - [Exercício 09](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-9)
    - `forall x : U, P x -> exists y : U, P y` [Resolução](quantificadores_universal_existencial/exercicio_09.v)
  - [Exercício 10](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-10)
    - `(forall x : U, P x -> ~ Q x) -> ~ exists y : U, P y /\ Q y` [Resolução](quantificadores_universal_existencial/exercicio_10.v)
  - [Exercício 11](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-11)
    - `(forall x : U, P x -> Q x) -> (forall x : U, ~ Q x) -> (forall x : U, ~ P x)` [Resolução](quantificadores_universal_existencial/exercicio_11.v)
  - [Exercício 12](https://rodrigogribeiro.github.io/posts/2018/01/logic-in-coq#exerc%C3%ADcio-12)
    - `"Todo homem é mortal. Sócrates é um homem. Logo, Sócrates é mortal"` [Resolução](quantificadores_universal_existencial/exercicio_12.v)
