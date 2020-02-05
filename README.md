# Style Commit

## Mensagens de commit styleguide

- Usar modo imperativo ("Adiciona feature" não "Adicionando feature" ou "Adicionada feature")
- Primeira linha deve ter no máximo 72 caracteres
- Considere descrever com detalhes no corpo do commit
- Considere usar um emoji no início da mensagem de commit

Emoji | Code | Commit Type
------------ | ------------- | -------------
:tada: | `:tada:` | initial commit
:art: | `:art:` | quando melhorar a estrutura/formato do código
:lipstick: | `:lipstick:` | quando melhorar UI/Cosmetic
:hammer: | `:hammer:` | quando refatorar código
:racehorse: | `:racehorse:` | quando melhorar a performance
:memo: | `:memo:` | quando escrever alguma documentação
:bug: | `:bug:` | quando corrigir um bug
:fire: | `:fire:` | quando remover códigos ou arquivos
:green_heart: | `:green_heart:` | quando corrigir uma build no CI
:white_check_mark: | `:white_check_mark:` | quando adicionar testes
:lock: | `:lock:` | quando melhorar a segurança
:arrow_up: | `:arrow_up:` | quando der upgrade em depedências
:arrow_down: | `:arrow_down:` | quando der downgrade em dependências
:poop: | `:poop:` | deprecated
:construction: | `:construction:` | em construção
:rocket: | `:rocket:` | nova feature
:see_no_evil: | `:see_no_evil:` | gambiarra
:bookmark: | `:bookmark:` | nova Tags
:gift: | `:gift:` | nova versão

### Exemplo
```bash
git commit -m ":memo: Adiciona instruções de contribuição
>
> Foi criado o arquivo CONTRIBUTING.md com as instruções de
> como fazer um bom commit"
``` 
