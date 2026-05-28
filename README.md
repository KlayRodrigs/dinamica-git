Bem-vindos ao repositório da prática de Git. Este projeto estático serve como ponto de partida para cada calouro criar seu próprio card na página e enviar a contribuição via Pull Request.

## Como participar

1. Clone o repositório:

```bash
git clone https://github.com/KlayRodrigs/dinamica-git.git
```

2. Entre na pasta do projeto:

```bash
cd dinamica-git
```

3. Crie uma branch com seu nome:

```bash
git checkout -b "codigo da branch"
```

4. Edite `index.html` e adicione seu card onde está o comentário `<!-- ADICIONE SEU CARD AQUI -->`.

5. Salve as mudanças e veja o resultado no navegador.

6. Faça o commit com a mensagem no padrão:

```bash
git add index.html
git commit -m "feat: add card [seu-nome]"
```

7. Envie sua branch para o remoto:

```bash
git push origin feat/add-card-seu-nome
```

8. Abra um Pull Request no GitHub para que seus colegas possam revisar.

## Padrão de commits

Use sempre uma mensagem em português e seguindo estes padrões:

- `feat: add card [seu-nome]`
- `fix: corrige [o-que]`
- `style: ajusta [o-que]`

## Regras da dinâmica

1. Nunca commitar direto na `main`.
2. Todo PR precisa de ao menos 1 aprovação antes de ser mesclado.
3. Mensagens de commit em português e no padrão acima.

## Tabela de issues da dinâmica

| Nº | Descrição | Fase |
|---|---|---|
| 1 | Adicionar card de exemplo | 1 |
| 2 | Criar link para GitHub no card | 1 |
| 3 | Criar link para LinkedIn no card | 1 |
| 4 | Ajustar o texto do subtítulo | 1 |
| 5 | Fazer o layout responsivo | 2 |
| 6 | Adicionar animação de hover nos cards | 2 |
| 7 | Ajustar cores do tema escuro | 2 |
| 8 | Corrigir espaçamento do rodapé | 2 |
| 9 | Criar seção de links úteis da turma | 3 |
| 10 | Criar seção de eventos do semestre | 3 |
| 11 | Revisar e corrigir comentários no HTML | 3 |
| 12 | Ajustar padrão de commits no README | 3 |
| 13 | Validar o PR com revisão de colega | 4 |
| 14 | Mesclar branch com aprovação | 4 |
| 15 | Testar o site no browser | 4 |
| 16 | Atualizar tabela de issues com progresso | 4 |
