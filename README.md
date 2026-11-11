# PRO GRÁFICA — Portal

Portal web de demonstração para gestão de pedidos de uma gráfica.

## Site público

Quando o GitHub Pages estiver ativado, o site estará disponível em:
https://filipeamerico14-sketch.github.io/Pro-gr-fica-/

## Como publicar no GitHub Pages

No repositório, abre **Settings → Pages**. Em **Build and deployment**, seleciona **Deploy from a branch**, escolhe a branch `main` e a pasta `/ (root)`, e guarda. Aguarda alguns minutos pela publicação.

## Funcionalidades

- **Clientes**: enviar pedidos, acompanhar estado, ver pagamentos e documentos
- **Funcionários**: gerir pedidos e atendimento
- **Administrador**: equipa, relatórios, publicidade, configurações e pagamentos

Os dados ficam guardados no `localStorage` do navegador (demonstração offline).

## Estrutura do projeto

- `index.html` — página principal
- `styles.css` — estilos
- `app.js` — lógica da aplicação
- `data.json` — configuração e serviços padrão

## Nota

Esta é uma versão de demonstração. Os ficheiros e dados ficam apenas no navegador e não são enviados para um servidor. O acesso de funcionário/administrador não é seguro para uso real. Para produção, é necessário implementar backend, autenticação e armazenamento de ficheiros.
