# Estatuto da SACIM

## Como sugerir edições

As alterações são sugeridas e discutidas através de Issues. Uma Issue é uma questão levantada sobre o documento, normalmente uma sujestão, crítica, dúvida ou até o levantamento de uma discussão. São importantíssimos para a documentação da motivação de se ter alterado ou não alterado algo e poupar re-discussão sobre a mesma coisa no futuro e perda de informação.

Caso uma sugestão de alteração em Issue seja aprovada é então necessário alterar o documento e submeter a versão alterada para aprovação, confirmação de que realmente foi alterado da forma correta. Esse processo é realizado através de uma Pull Request que deve ser linkada à Issue correspondente. A Pull Request pode ser vista por todos os interessados e uma vez aprovada a Issue linkada é fechada altomaticamente e a alteração é prontamente aplicada ao documento finalizando a edição.

## Sobre as Issues

### Sobre as Labels

Labels são rótulos/etiquetas que servem para fácil identificação e documentação do histórico sobre um documento.

#### Tipo de Issue

Essas labels rotulam o tipo de alteração que a Issue requesita ou põe em discussão.

| Label | Descrição |
| ----- | --------- |
| adição | Adicionar parte nova |
| remoção | Remover alguma parte |
| mudança | Alterar alguma parte já existente |
| clareza | Explicar e/ou especificar melhor |
| gramática/identação | Correção não semântica |
| incoerência | Contradição entre partes do documento |
| redundancia | Parte duplicada no documento |

`adição`, `remoção` e `mudança` tem os significados mais intuitívos.

`clareza` e `gramática/identação` são tipos expecíficos de mudança.

`incoerência` e `redundancia` apontam para problemas no documento, sem necessariamente sugerir a mudança que os corrija pois pode haver uma discussão sobre a melhor forma de correção.

#### Resolução

Essas labels simbolizam a decisão final sobre a Issue.

| Label | Descrição |
| ----- | --------- |
| alteração aceita | Foi decidido realizar a alteração |
| alteração negada | Foi decidido não fazer a mudança sugerida |
| issue duplicada | Já existe uma issue sobre a mesma coisa |

`issue duplicada` rotula Issues que devem ser fechadas pois a mesma questão já foi ou está sendo discutida em outro lugar. Caso a Issue original já está fechada para levantar novos pontos sobre questão é necessário reabri-la.

Issues marcadas como `issue duplicada` ou `alteração negada` devem ser fechadas imediatamente, enquanto as marcadas como `alteração aceita` devem ser fechadas altomaticamente ao ocorrer a aceitação de uma Pull Request linkada.

#### Especiais

| Label | Descrição |
| ----- | --------- |
| duvida | Perguntas sobre o estatuto |
| estrutural | Alteração no readme, labels ou outras partes do repositório que não sejam o estatuto. |

`duvida` não requisita necessariamente uma mudança no documento, ainda que possa vir a acarretar em uma. Pode ser usada para o registro de um FAQ.

### Referenciando o documento

Em uma Issue é possível referenciar o documento com um link para as partes em discussão possam ser facilmente acessadas.

O primeiro passo para isso é conseguir um link permante, isto é, que aponte sempre para a versão atual do documento mesmo quando ele vir a ser alterado futuramente. Isso evita a perda do alvo da referência ou desentendimentos por mudanças de versão. Para isso deve-se abrir o dumento, clicar nos 3 pontinhos na parte superior direita da aba atual e em "Copy permalink", e então cola-lo na barra de endereço no navegador e recarregar a página.

Agora vizulizando uma versão com acesso estático do documento você pode seguramente referenciar uma seção ou linhas.

#### Referenciar seção

Para conseguir o link para uma seção é preciso somente clicar no ícone de lista no lado esquerdo do cabeçalho do documento, selecionar a seção e então copiar o link da barra de endereço do navegador.

#### Referenciar linhas

Para conseguir o link para linhas é necessário adicionar "?plain=1" ao final do endereço da barra do navegador e recarregar a página. Agora o documento deve aparecer em texto plano. Então pode-se clicar no número da linha ao lado esquerdo para seleciona-la e caso seja necessário selecionar múltiplas linhas é possível clicar com shift precionado na última linha do intervalo e todas entre elas serão selecionadas. Agora é só copiar o link da barra de endereço.

## Pull Requests para membros da SACIM

Membros da organização SACIM no github podem editar o documento diretamente abrindo ele e clicando no ícone de lápis no cabeçalho.

Ao terminar as alterações é essencial selecionar a opção **Create a new branch for this commit and start a pull request.** para que a alteração seja sugerida em vez de aplicada imediatamente.

Não se esqueça de linkar a Pull Request a Issue correspondente.

## Pull Requests para não membros

Não membros não podem criar branchs no repositório principal, portanto devem criar um fork clicando na opção fork no canto superior direito da tela. Então deve realizar as alterações desejadas no fork e então criar o Pull Request na aba Pull Requests do fork.

Não se esqueça de linkar a Pull Request a Issue correspondente.
