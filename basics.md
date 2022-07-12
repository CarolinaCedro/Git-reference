## COMANDOS PARA CRIAR UM NOVO PROJETO

<b>git init </b>
<i>- iniciamos o git no repositório do projeto </i>

<b>git remote add origin "add link do repositório"</b>
<i>- adiciona o link do repositório</i>

<b>git add * - * </b>
<i>adiciona tudo (Se faz esse comando antes do git remote, ele cria a pasta stage e adiciona de forma temporária as modificações feitas)</i>

<b>git commit -m "adiciona o commit com padrões" </b>
<i>- https://github.com/iuricode/padroes-de-commits</i>

<b>git push origin master </b>
<i>- Adicionar branch correta</i>

<b>git clone </b>
<i>- traz/clona um projeto de um repositório remoto que eu tenha permissão para alterar.</i>

<b>git log </b>
<b>git log --oneline </b>
<i>- mostra as versões // O git log --oneline mostra as versões de forma resumida</i>

<b>git reset </b>
<i>- volta para o estado anterior. Se estava no stage (git add), sai do stage.</i>

<b>git diff </b>
<i>- mostra a diferença entre arquivos modificados</i>

<b>git checkout* </b>
<i>- usado para modificar temporariamente os arquivos do projeto ao estado de um dado commit ou branch.</i>

#### Ações destrutivas
<b>git reset --hard *numero commit*</b>
<i>- Apaga todas as modificações depois deste commit</i>

<b>git push -f</b>
<i>- força as alterações do repo local apagando todo o historico ate o commit especificado no reset hard</i>

<b>git remote -v</b>
<i>- Mostra o remote atual</i>

#### Apontando projeto para outro repositio

<i> a ideia é trocar a referencia do remote </i>

<b>git remote set-url origin *nome do novo repo*</b>
<i>- Aponto o projeto para outro repositorio alterando seu endereço remote</i>