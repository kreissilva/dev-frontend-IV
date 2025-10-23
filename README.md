# Plataforma para ONGs - Transforma Vida

## Descrição
Plataforma web completa para ONGs, desenvolvida com foco em acessibilidade, otimização e boas práticas de desenvolvimento. Este projeto implementa uma interface responsiva e acessível para uma organização não governamental fictícia, seguindo padrões modernos de desenvolvimento front-end.

## Funcionalidades
- Página institucional com informações sobre a ONG
- Gestão de projetos e iniciativas
- Cadastro de voluntários e doadores
- Sistema de doações
- Modo escuro e alto contraste para acessibilidade
- Navegação completa por teclado
- Suporte a leitores de tela

## Tecnologias
- HTML5 semântico
- CSS3 com variáveis e design responsivo
- JavaScript modular
- Otimização para produção (minificação)

## Acessibilidade (WCAG 2.1 Nível AA)
Este projeto implementa as seguintes características de acessibilidade:

- **Navegação por teclado**: Todos os elementos interativos são acessíveis via teclado
- **Estrutura semântica**: Uso adequado de elementos HTML5 semânticos
- **Contraste**: Garantia de contraste mínimo de 4.5:1 para texto normal
- **Suporte a leitores de tela**: ARIA roles e labels implementados
- **Modos de visualização alternativos**:
  - Modo escuro para redução de fadiga visual
  - Modo de alto contraste para usuários com baixa visão
- **Skip link**: Permite pular diretamente para o conteúdo principal

## Controle de Versão
Este projeto utiliza a estratégia GitFlow para gerenciamento de branches:

- **main**: Versão estável em produção
- **develop**: Branch de desenvolvimento
- **feature/**: Branches para novas funcionalidades
- **hotfix/**: Branches para correções urgentes
- **release/**: Branches para preparação de releases

### Versionamento Semântico
O projeto segue o padrão de versionamento semântico (SemVer):
- **X.Y.Z** onde:
  - **X**: Versão maior (mudanças incompatíveis)
  - **Y**: Versão menor (novas funcionalidades compatíveis)
  - **Z**: Patch (correções de bugs compatíveis)

## Otimização para Produção
Foram implementadas as seguintes otimizações:

- **Minificação**: Arquivos CSS, JavaScript e HTML minificados
- **Compressão de imagens**: Otimização de tamanho sem perda significativa de qualidade
- **Carregamento eficiente**: Recursos carregados de forma otimizada

## Estrutura do Projeto
```
/
├── css/
│   ├── style.css       # Arquivo CSS principal
│   └── style.min.css   # Versão minificada para produção
├── js/
│   ├── app.js          # JavaScript principal
│   └── app.min.js      # Versão minificada para produção
├── html/
│   ├── index.html      # Página inicial
│   ├── index.min.html  # Versão minificada para produção
│   ├── projetos.html   # Página de projetos
│   └── cadastro.html   # Página de cadastro
└── images/
    ├── logo_ong.png    # Logo da ONG
    └── ...             # Outras imagens
```

## Como executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/plataforma-ongs.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd plataforma-ongs
   ```
3. Abra o arquivo `html/index.html` no navegador para desenvolvimento
4. Para produção, utilize os arquivos minificados (`*.min.*`)

## Contribuição
1. Crie um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Faça commit das alterações (`git commit -m 'feat: adiciona nova funcionalidade'`)
4. Faça push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## Desenvolvido por
[Kauã Reis da Silva]