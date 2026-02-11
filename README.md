**Descrição:** Aplicativo que sugere receitas com base em ingredientes selecionados.

**Funcionalidades:**

 - Seleção de ingredientes disponíveis

 - Desselecionar os ingredientes

 - Exibição de receitas filtradas de acordo com os ingredientes escolhidos

 - Componente de card de receita com imagem e nome

 - Informar quando nenhuma receita é encontrada.

 - Botão para editar a lista de ingredientes e refazer a busca.


**Tecnologias utilizadas:**

 - Vue 3 + Options API

 - TypeScript

 - Vite

 - Estrutura modular: Separação em pastas (components, interface, http) para manter o projeto organizado e escalável.

**Preview**

Mostrar lista vazia quando não houver nenhum ingrediente selecionado.
<img width="1919" height="819" alt="image" src="https://github.com/user-attachments/assets/7c65f9bd-e098-415d-a158-c65cc2b4ac93" />


Mostrar os ingredientes selecionados
<img width="1886" height="820" alt="image" src="https://github.com/user-attachments/assets/8da88e14-0277-47bc-9347-98b13bfc6db1" />


Desselecionar os ingredientes
<img width="1897" height="823" alt="image" src="https://github.com/user-attachments/assets/20f28098-6459-4dc2-9233-4887276df0d1" />


Mensagem de resultados não encontrados, caso não encontre nenhuma receita
<img width="1884" height="820" alt="image" src="https://github.com/user-attachments/assets/b061256d-2ec6-4969-a05a-365676233015" />


Exibir as receitas encontradas
<img width="1888" height="822" alt="image" src="https://github.com/user-attachments/assets/3a0d0505-6f26-440f-bdd3-990cb05f6207" />



# Ponto de partida

Essa parte deve ajudar você a desenvolver aplicações usando Vue 3 com Vite.

## Ambiente de desenvolvimento recomendado
[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (e desabilitar o Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Configuração

Veja a documentação do Vite para personalizar as configurações [Vite Configuration Reference](https://vitejs.dev/config/).

## Como rodar o projeto

1. Instale as dependências:
```sh
npm install
```

2. Para rodar em modo desenvolvimento (com atualização automática):
```sh
npm run dev
```

3. Para gerar a versão final (otimizada para produção)
```sh
npm run build
```
