# Formulário de Cadastro - MFBooks

![Status do Projeto](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=ORANGE&style=for-the-badge)

## Descrição

Este projeto consiste em um formulário de cadastro responsivo para a MFBooks, utilizando HTML, CSS e JavaScript. Ele inclui funcionalidades para preenchimento automático de endereço via CEP utilizando a API ViaCEP.

## Visão Geral

O formulário de cadastro da MFBooks é uma interface amigável e responsiva para que novos usuários possam se registrar na plataforma. Ele coleta dados pessoais e informações de endereço, com um recurso de preenchimento automático para o endereço baseado no CEP fornecido, otimizando a experiência do usuário. Após o cadastro, o usuário é redirecionado para uma página de sucesso.

## Tecnologias utilizadas

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="40" height="40"/> 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="40" height="40"/> 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="40" height="40"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/json/json-original.svg" width="40" height="40"/>

## Funcionalidades

- **Design Responsivo**: Adapta-se a diferentes tamanhos de tela (mobile, tablet, desktop) utilizando media queries.
- **Validação de CEP**: Preenche automaticamente campos de endereço (logradouro, bairro, cidade, estado) ao digitar um CEP válido, utilizando a API ViaCEP.
- **Mensagens de Erro**: Exibe mensagens visuais para CEPs inválidos.
- **Navegação no Cabeçalho**: Menu hambúrguer para dispositivos móveis e menu de navegação completo para telas maiores.
- **Página de Sucesso**: Redirecionamento para uma página de confirmação após o envio bem-sucedido do formulário.
- **Estilização Moderna**: Utiliza variáveis CSS para padronização de cores e fontes, e gradientes para elementos visuais.
- **Reset CSS**: Inclui um reset CSS para garantir consistência de estilo entre navegadores.

## Estrutura e Detalhes Técnicos do Pojeto

- **HTML5**: Estrutura da página e do formulário.
- **CSS3**: Estilização e responsividade da interface.
    * **`reset.css`**: Normalize a renderização de elementos HTML em diferentes navegadores.
    * **`styles.css`**: Importa todos os outros arquivos CSS e define variáveis de cor e fonte globais.
    * **`header.css`**: Estiliza o cabeçalho, incluindo o menu hambúrguer e a navegação.
    * **`banner.css`**: Estiliza a seção de banner.
    * **`formulario.css`**: Estiliza o formulário de cadastro, campos de entrada e botões.
    * **`cadastro.css`**: Estiliza a página de cadastro finalizado.
    * **`rodape.css`**: Estiliza o rodapé da página.
- **JavaScript**: Lógica para consumo da API ViaCEP e manipulação do DOM.
    * **`script.js`**: Contém a função `buscaEndereco` que interage com a API ViaCEP para buscar dados de endereço.

## Instruções

1. Abra o arquivo index.html em seu navegador. 
2. Preencha os campos de "Dados pessoais", como "Nome Completo", "Nascimento", "Contato" e "E-mail". 
3. Na seção "Endereço", preencha o campo "CEP". Ao sair do campo, o sistema tentará preencher automaticamente "Endereço", "Bairro", "Cidade" e "UF" utilizando a API ViaCEP. 
**Caso o CEP seja inválido, uma mensagem de erro será exibida.** 
4. Preencha os campos restantes do endereço, como "Numero" e "Complemento" (opcional). 
5. Clique no botão "Enviar formulário" para finalizar seu cadastro. 
6. Após o envio bem-sucedido, você será redirecionado para a página de confirmação de cadastro **(cadastro-finalizado.html)**.

## Desenvolvedor do Projeto:

[<img loading="lazy" src="https://github.com/user-attachments/assets/f5d9a326-b2a9-4839-84da-ec4b6fedf0fc" width=115><br><sub>Mateus Rodrigues da Fonseca</sub>](https://github.com/MateusFonseca19)