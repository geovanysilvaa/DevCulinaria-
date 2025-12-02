# Guia de Contribuição – DevCulinária

Obrigado por contribuir com o *Livro de Receitas – DevCulinária*!  
Siga este guia para manter o projeto organizado e padronizado.

---

## 🪄 Padrão de Branch
Cada nova receita deve ser criada em uma branch específica, baseada na branch principal (main ou principal).

*Formato:*  
feature/<categoria>-<nome-da-receita>

*Exemplos:*  
feature/acompanhamentos-batata-gratinada  
feature/sopas-sopa-abobora  
feature/massas-lasanha

---

## 💬 Padrão de Commit
Use mensagens curtas e padronizadas para identificar o tipo de alteração.

*Formato:*  
<tipo>: <descrição curta>

*Tipos comuns:*  
- feat: adiciona nova receita  
- fix: corrige links ou formatação  
- docs: atualiza documentação

*Exemplos:*  
feat: adiciona receita Batata Gratinada  
fix: corrige links da receita Lasanha  
docs: atualiza instruções do CONTRIBUTING.md

---

## 🔀 Regras de Pull Request (PR)
- Cada PR deve estar *vinculado a uma issue* correspondente.  
- Cada PR precisa de *3 aprovações* antes do merge na branch main.  
- *Nenhum commit direto* deve ser feito na branch main.  
- Ao abrir o PR, descreva claramente as alterações e referências à issue, por exemplo:

---

feat: adiciona receita Batata Gratinada
Closes #104

---

- Após o merge, o autor deve *atualizar o menu.md* com o link da nova receita.

---

## 🧩 Passos para Contribuir
1. Crie uma issue no repositório original com o nome da receita que deseja adicionar.  
2. Faça *fork* do repositório para sua conta, se ainda não tiver feito.  
3. Clone o fork no seu computador:
 ```bash
 
---

1. git clone https://github.com/seu-usuario/DevCulinaria.git
2. cd DevCulinaria
3. Crie uma branch nova baseada na principal:
4. git checkout -b feature/<categoria>-<nome-da-receita>
5. Adicione sua receita na categoria correta (.md) seguindo a estrutura do repositório:
6. Título da receita
7. Lista de ingredientes
8. Modo de preparo
9. Links de navegação:

---

[Voltar ao MENU](../MENU.md)  
[Voltar ao README](../README.md)

---

- Faça commit da alteração seguindo o padrão:
- git add .
- git commit -m "feat: adiciona receita Batata Gratinada

- Closes #104"

- Envie sua branch para o fork:
- git push origin feature/<categoria>-<nome-da-receita>
- Abra um Pull Request do seu fork para o repositório original e peça revisões.
- Aguarde as aprovações (mínimo 3) e o merge pelo time responsável.
- Após o merge, atualize o menu.md no seu fork e faça commit se necessário.

---

🌟 Boas Práticas

---

- Revise a ortografia e a formatação antes do PR.
- Teste todos os links no preview do GitHub.
- Evite conflitos, verificando se alguém editou arquivos semelhantes recentemente.
- Mantenha comunicação constante com a equipe ou mantenedores do repositório.
- Sempre siga os padrões de branch, commit e estrutura de arquivos do repositório.

---

## 📌 Observações Finais

- Conflitos podem ocorrer e devem ser resolvidos antes de abrir ou atualizar o PR.
- Ao trabalhar em grupo, sincronize sempre sua branch com a principal antes de começar alterações.
- Esse guia deve ser seguido por todos os colaboradores, garantindo padronização e qualidade no projeto.
