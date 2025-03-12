## 📌 Descrição
Este projeto tem como objetivo desenvolver um aplicativo para compra de ingressos de teatro. O sistema permitirá aos usuários visualizar eventos, selecionar ingressos e efetuar compras de maneira simples e eficiente.

---

## 🚀 Fluxo de Trabalho no Git
Para garantir organização e evitar conflitos no código, seguimos este fluxo de trabalho:

### 🔹 **1. Branches Principais**
- `main` → Contém a versão estável e final do projeto.
- `develop` → Onde o desenvolvimento acontece antes de ir para `main`.

### 🔹 **2. Como Cada Pessoa Deve Trabalhar**
#### ✅ **Antes de Começar a Programar**
Antes de iniciar qualquer nova funcionalidade, atualize seu repositório local:
```sh
git checkout develop
git pull origin develop
```

#### ✅ **Criando um Branch para Funcionalidade**
Cada funcionalidade deve ser desenvolvida em um branch separado:
```sh
git checkout -b feature/nome-da-funcionalidade
```
**Exemplo:**
```sh
git checkout -b feature/tela-login
```

#### ✅ **Desenvolvendo e Fazendo Commit**
Após finalizar a funcionalidade:
```sh
git add .
git commit -m "Implementando a tela de login"
```

#### ✅ **Enviando o Código para o GitHub**
```sh
git push origin feature/nome-da-funcionalidade
```

#### ✅ **Criando um Pull Request**
1. Vá até o **GitHub → Repositório → Pull Requests**.
2. Clique em **New Pull Request**.
3. Escolha `feature/nome-da-funcionalidade` como origem e `develop` como destino.
4. Descreva as mudanças e solicite revisão.

#### ✅ **Mesclando `develop` no `main` (Quando Tudo Estiver Pronto)**
Quando todas as funcionalidades estiverem testadas e aprovadas:
```sh
git checkout main
git merge develop
git push origin main
```
Agora, `main` terá a versão estável do projeto. 🎉

---

## 🔥 Regras Importantes
✅ **Nunca** trabalhe diretamente no `main`.
✅ Sempre crie um **branch separado** para cada funcionalidade.
✅ **Puxe as atualizações do `develop` antes de começar** para evitar conflitos.
✅ Após enviar um branch `feature/`, **abra um Pull Request no GitHub**.
✅ **Revisões são importantes!** Sempre revise antes de mesclar no `develop`.

---

Agora, podemos trabalhar de forma organizada e eficiente! 🚀

