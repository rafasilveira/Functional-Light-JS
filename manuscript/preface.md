# Functional-Light JavaScript
# Prefácio

> *Uma monada é um monoide na categoria dos endofuntores.*

Você se perdeu ? Não se preocupe, eu também estaria perdido! Todos aqueles termos que significam apenas algo para o já iniciado em Programação Funcional&trade; (FP) são apenas bobagens confusas para muitos de nós.

Este livro não vai ensinar o que essas palavras significam. Se é isso que você está procurando, continue procurando. Na verdade, já existem muitos livros ótimos que ensinam o FP * do jeito certo *, de cima para baixo. Essas palavras têm significados importantes e, se você estudar formalmente o PF em profundidade, você vai querer se familiarizar com elas.

Mas este livro abordará o tópico de maneira bem diferente. Eu vou apresentar conceitos fundamentais de FP a partir do zero, com menos termos especiais ou não-intuitivos do que a maioria das abordagens para FP. Vamos tentar adotar uma abordagem prática para cada princípio em vez de um ângulo puramente acadêmico. ** Haverá termos **, sem dúvida. Mas teremos cuidado e deliberado sobre apresentá-los e explicar por que eles são importantes.

Infelizmente, eu não sou um membro de carteirinha do FP Cool Kids Club. Eu nunca fui formalmente ensinado sobre FP. E embora eu tenha uma formação acadêmica em CS e eu seja decente em matemática, a notação matemática não é como meu cérebro entende de programação. Eu nunca escrevi uma linha de Scheme, Clojure ou Haskell. Eu não sou um Lisp'r old-school.

Eu participei de incontáveis ​​conferências sobre FP, cada uma com a desesperada esperança de que finalmente, desta vez, seria o momento em que eu entendi o que é todo esse misticismo de programação funcional. E a cada vez, eu saía frustrado e lembrava que esses termos se confundiam na minha cabeça e eu não tinha ideia se ou o que eu aprendi. Talvez eu tenha aprendido coisas. Mas eu não conseguia descobrir o que essas coisas eram por mais tempo.

Pouco a pouco, ao longo dessas várias exposições, lancei pedaços de conceitos importantes que parecem vir tão naturalmente ao FPer formal. Aprendi-os lentamente e aprendi de forma pragmática e experimental, não academicamente com terminologia apropriada. Você já conheceu uma coisa por um longo tempo, e só mais tarde descobriu que tinha um nome específico que você nunca conheceu!

Talvez você seja como eu; Eu ouvi termos como "map-reduce" em torno de segmentos da indústria como "big data" por anos sem nenhuma idéia do que eles eram. Eventualmente eu aprendi o que a função `map (..)` fazia - muito antes de eu ter alguma idéia de que as operações de lista eram a base do caminho do FPer e o que as torna tão importantes. Eu sabia o que * map * era muito antes de eu saber que era chamado `map (..)`.

Por fim, comecei a reunir todos esses detalhes de compreensão no que agora chamo de "Programação de Luz Funcional" (FLP, Functional-Light Programming).

## Missão

Mas por que é tão importante aprender programação funcional, mesmo a forma leve?

Eu passei a acreditar em algo muito profundamente nos últimos anos, tanto que você poderia * quase * chamar isso de crença religiosa. Eu acredito que a programação é fundamentalmente sobre humanos, não sobre código. Acredito que o código é, antes de tudo, um meio de comunicação humana, e apenas como um * efeito colateral * (ouve minha risada auto-referencial) instrui o computador.

Do jeito que eu vejo, a programação funcional é essencial sobre o uso de padrões em seu código que são bem conhecidos, compreensíveis, * e * comprovados para afastar os erros que tornam o código mais difícil de entender. Nessa visão, FP - ou, ahem, FLP! - pode ser uma das coleções mais importantes de ferramentas que qualquer desenvolvedor pode adquirir.

> A maldição da mônada é que ... uma vez que você entenda ... você perde a capacidade de explicar isso para qualquer outra pessoa.
>
> Douglas Crockford 2012 "Mônadas e gônadas"
>
> https://www.youtube.com/watch?v=dkZFtimgAcM

Espero que este livro "Talvez" quebre o espírito dessa maldição, mesmo que não falemos sobre "mônadas" até o final nos apêndices.

O FPer formal freqüentemente afirma que o * valor real * do FP está usando essencialmente 100%: é uma proposta de tudo ou nada. A crença é que, se você usar o FP em uma parte do seu programa, mas não em outro, todo o programa é poluído pelo material não-FP e, portanto, sofre o suficiente para que o FP provavelmente não valha a pena.

Eu direi inequivocamente: ** Eu acho que o absolutismo é falso **. Isso é tão tolo para mim quanto sugerir que este livro só é bom se eu usar a gramática perfeita e a voz ativa por toda parte; se eu cometer algum erro, isso degrada a qualidade de todo o livro. Absurdo.

Quanto melhor eu escrever uma voz clara e consistente, melhor será a sua experiência de leitura. Mas eu não sou um autor 100% perfeito. Algumas partes serão melhor escritas que outras. As partes em que eu ainda posso melhorar não invalida as outras partes deste livro que são úteis.

E assim vai com o nosso código. Quanto mais você puder aplicar esses princípios a mais partes do seu código, melhor será o seu código. Use-os bem 25% do tempo e você terá um bom benefício. Use-os 80% do tempo e você verá ainda mais benefícios.

Com talvez algumas exceções, não acho que você encontrará muitos absolutos neste texto. Em vez disso, falaremos sobre aspirações, metas, princípios pelos quais lutar. Nós vamos falar sobre equilíbrio e pragmatismo e trade-offs.

Bem-vindo a esta jornada nos fundamentos mais úteis e práticos do FP. Nós dois temos muito a aprender!
