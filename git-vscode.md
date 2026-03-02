# 🖥️ Como usar o Git pelo VS Code

Guia prático para realizar o fluxo completo do Git usando a interface 
gráfica do VS Code.

---

## ✅ Pré-requisitos

- Git instalado na máquina
- VS Code instalado
- Repositório já clonado na sua máquina
- Conta no GitHub configurada

---

## 📋 O Fluxo Completo

### Passo 1 — Abrir o Source Control

1. Abra o VS Code com a pasta do seu repositório
2. Clique no ícone de **ramificação** na barra lateral esquerda
   *(ou pressione `Ctrl + Shift + G`)*
3. O painel **"Source Control"** será aberto

> 💡 É aqui que você gerencia todas as alterações do Git de forma visual!

---

### Passo 2 — Fazer uma alteração

1. Abra qualquer arquivo do seu projeto
2. Faça a alteração desejada
3. Salve o arquivo com `Ctrl + S`

Você verá que o arquivo aparece na seção **"Changes"** com a letra **`M`** 
(Modified) ao lado.

---

### Passo 3 — Fazer o Stage (git add)

1. No painel **Source Control**, localize o arquivo alterado em **"Changes"**
2. Clique no ícone **`+`** ao lado do arquivo
3. O arquivo será movido para **"Staged Changes"**

> 💡 Equivalente ao comando: `git add nome-do-arquivo`  
> Para adicionar todos os arquivos de uma vez, clique no `+` ao lado de "Changes"

---

### Passo 4 — Escrever a mensagem do Commit

1. No campo **"Message"** no topo do painel, escreva uma mensagem descritiva
2. A mensagem deve resumir claramente o que foi alterado

**Exemplos de boas mensagens:**
- ✅ `adiciona funcionalidade de login`
- ✅ `corrige bug no botão de cadastro`
- ✅ `atualiza documentação do projeto`
- ❌ `alteração` *(muito vago)*
- ❌ `asdfgh` *(sem sentido)*

> ⚠️ **Atenção:** Não pressione `Enter` no campo de mensagem!  
> Use `Ctrl + Enter` apenas para confirmar o commit.

---

### Passo 5 — Fazer o Commit

1. Após escrever a mensagem, clique no botão azul **"Commit"**
   *(ou pressione `Ctrl + Enter`)*
2. O arquivo sairá de "Staged Changes" e o commit será salvo localmente

> 💡 Equivalente ao comando: `git commit -m "sua mensagem aqui"`

---

### Passo 6 — Fazer o Push (Sync Changes)

1. Após o commit, o botão azul mudará para **"Sync Changes 1↑"**
2. Clique nesse botão para enviar o commit ao GitHub
3. Aguarde a sincronização finalizar

> 💡 Equivalente ao comando: `git push origin main`

✅ **Pronto! Sua alteração está no GitHub!**

---

## 🔍 Como verificar se funcionou

1. Acesse [github.com](https://github.com)
2. Entre no seu repositório
3. Verifique se o arquivo foi atualizado
4. Confirme se a mensagem do commit aparece corretamente

---

## 📊 Tabela Resumo

| Passo | Ação no VS Code | Equivalente no Terminal |
|-------|----------------|------------------------|
| 1 | Abrir Source Control (`Ctrl+Shift+G`) | — |
| 2 | Editar e salvar o arquivo (`Ctrl+S`) | — |
| 3 | Clicar no `+` ao lado do arquivo | `git add .` |
| 4 | Escrever a mensagem no campo "Message" | — |
| 5 | Clicar em **"Commit"** (`Ctrl+Enter`) | `git commit -m "mensagem"` |
| 6 | Clicar em **"Sync Changes"** | `git push origin main` |

---

## 💡 Dicas Extras

| Indicador | Significado |
|-----------|------------|
| Letra **M** ao lado do arquivo | Arquivo **M**odificado |
| Letra **U** ao lado do arquivo | Arquivo novo (**U**ntracked) |
| Letra **A** ao lado do arquivo | Arquivo em **A**stage |
| **`0↓ 1↑`** na barra inferior | 1 commit pendente para enviar |
| **`0↓ 0↑`** na barra inferior | Tudo sincronizado ✅ |

---

## 🔗 Links Úteis

- [Download VS Code](https://code.visualstudio.com/)
- [Download Git](https://git-scm.com/)
- [GitHub](https://github.com/)

---

*Documentação criada com base em prática real no repositório `meu-primeiro-repo`* 🚀
