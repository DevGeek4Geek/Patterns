## Padrões de commit

### **Guia de estilo**

```
<tipo>(<escopo>): <assunto>`

<descricao>

<rodape>
```

* <tipo> Obrigatório
* <scope> Opcional
* <subject> Obrigatório
* <description> Obrigatório
* <footer> -> Opcional (com exceção de bugs, neste caso torna-se obrigatório)

#### **<tipo>**
Abaixo são listadas todas os tipos disponíves para as mensagens de commit:

- `feat`: É usado quando um novo recurso para o usuário for implementado
- `fix`: É usado para uma correção de bugs para o usuário
- `docs`: É usado quando houver alteração na documentação
- `style`: É usado para ajustar/adicionar formatação do código
- `refactor`: É usado para refatoração de código
- `update`: É usado para alterações não relacionadas a algum tipo de melhoria ou novo recurso.
- `test`: É usado quando é adicionado novos testes e/ou quando o teste sofre uma refatoração
- `chore`: É usado para atualização de tarefas como: deploy, grunt, etc.

#### **<escopo>**
Mesmo sendo opcional, este item pode ajudar a idententificar mais rapidamente o módulo que será afetado pelo commit.
Cada projeto deve (ou deveria) ter sua lista de escopos disponíveis, que pode crescer conforme a necessidade e discussão com o time responsável.

#### **<assunto>**
Este bloco deve descrever de forma clara e objetiva o propósito do commit.

#### **<descricao>**
Muito importante que toda atividade de commit seja detalhada, dessa forma melhora a compreensão do propósito do commit.

#### **<rodape>**
Pode ser adicionado um comentário ou uma fonte para referenciar algo.

### **Regras de commit**

- Todo `commit` devem ter apenas um propósito.
- O `assunto` deve conter no máximo 70 caracteres.
- O `assunto` deve descrever de maneira clara e objetiva o propósito do commit.
- O `assunto` deve ser escrito no passado.
- Após o `assunto` a próxima linha deve ser em branco.
- A `assunto` deve ter a primeira letra maiúscula.
- A `assunto` não deve terminar com ponto final.
- A `assunto` não deve conter acentuação ou caracteres especiais.

Referencia: https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716

## Estilos

#### Cores base:
