# Prompt para Criar o Figma do Buracometro

Voce e um Product Designer Senior especialista em UX/UI para aplicativos mobile-first, civic-tech e produtos brasileiros com alto potencial de compartilhamento.

Crie um arquivo Figma completo para o MVP do aplicativo **Buracometro**, um app mobile-first para denunciar buracos, crateras, asfalto deteriorado e ruas abandonadas.

O produto deve ser simples, rapido e extremamente focado. O app nao e uma rede social. Ele serve apenas para:

- enviar denuncias de buracos e problemas viarios;
- acompanhar as proprias denuncias;
- atualizar uma denuncia quando o problema for resolvido.

A viralizacao acontece fora do app, em Instagram, TikTok e X/Twitter. O app e apenas o canal de captura e acompanhamento das denuncias.

## Posicionamento

O Buracometro e o "Choquei da infraestrutura urbana".

Misture:

- utilidade publica;
- indignacao popular;
- humor brasileiro leve;
- visual urbano moderno.

Slogan principal: **Meu buraco minha vida.**

Frase de apoio para splash/onboarding: **A cidade ta falando.**

## Direcao Visual

Crie uma interface mobile-first, high fidelity, em dark mode, com estetica urbana e minimalista. O visual deve parecer rapido, moderno e util.

Inspiracoes:

- Uber;
- fluxo de upload do Instagram;
- Notion mobile;
- apps brasileiros modernos.

Evitar totalmente:

- aparencia governamental;
- sistema burocratico;
- software corporativo;
- feed social;
- comentarios;
- likes;
- seguidores;
- chat;
- categorias alem de buracos e problemas viarios.

## Identidade Visual

Use uma paleta com:

- preto grafite: `#0B0D0F`;
- cinza asfalto: `#1E2328`;
- cinza elevado: `#2B3137`;
- branco: `#F7F8FA`;
- cinza texto secundario: `#A8B0B8`;
- amarelo sinalizacao viaria: `#FFD23F`;
- vermelho alerta: `#FF4D4D`;
- verde resolvido: `#2ECC71`.

Inclua:

- textura leve de asfalto em fundos ou detalhes;
- icones urbanos;
- pins de mapa;
- sinalizacao de transito;
- mapas minimalistas;
- cards com fotos reais ou placeholders fotograficos de ruas, buracos e asfalto.

Use bordas discretas, raio de 8px, sombras suaves e bastante contraste. A interface deve ser densa o suficiente para uso real, mas facil de escanear em telas pequenas.

## Tipografia

Use uma familia sans-serif moderna, como Inter, SF Pro ou similar.

Crie estilos:

- Display: 32/38, semibold;
- H1 Mobile: 28/34, semibold;
- H2: 22/28, semibold;
- Body: 16/24, regular;
- Body strong: 16/24, semibold;
- Caption: 13/18, regular;
- Label: 12/16, semibold.

## Estrutura do Arquivo Figma

Organize o arquivo nas seguintes paginas:

1. `00 Cover`
2. `01 User Flow`
3. `02 Wireframes`
4. `03 Design System`
5. `04 Mobile App - HiFi`
6. `05 Admin Dashboard - HiFi`
7. `06 Prototype`
8. `07 Handoff Notes`

Tudo deve usar auto-layout, estilos, componentes reutilizaveis e variaveis de cor/espacamento.

## User Flow

Crie um fluxo simples:

1. Splash
2. Onboarding
3. Login ou acesso anonimo
4. Home com denuncias do usuario
5. Nova denuncia
6. Confirmacao de envio
7. Detalhe da denuncia
8. Marcar como resolvido
9. Confirmacao de resolucao
10. Perfil
11. Notificacoes

Mostre claramente que o tempo ideal de denuncia e menor que 30 segundos.

## Componentes Obrigatorios

Crie componentes com variantes:

- botoes primarios, secundarios, ghost e destrutivos;
- botoes com icones;
- bottom navigation;
- chips de status;
- cards de denuncia;
- inputs de texto;
- campo de upload de foto/video;
- seletor de camera/galeria;
- mini mapa;
- timeline;
- modal de permissao de localizacao;
- modal de confirmacao;
- toast/snackbar;
- skeleton loading;
- badges de perfil;
- tabela admin;
- preview de post social;
- cards de metricas admin.

Status obrigatorios:

- Em analise;
- Publicado;
- Encaminhado;
- Resolvido.

## Telas Mobile High Fidelity

Crie frames mobile em 390x844.

### 1. Splash Screen

Elementos:

- logo do Buracometro;
- nome "Buracometro";
- frase "A cidade ta falando.";
- fundo grafite com textura sutil de asfalto;
- detalhe em amarelo sinalizacao.

### 2. Onboarding

Crie 3 telas:

Tela 1:

- titulo: "Encontrou um buraco?"
- visual: rua urbana minimalista com destaque para cratera.

Tela 2:

- titulo: "Mostre pra cidade"
- visual: celular fotografando um buraco.

Tela 3:

- titulo: "Pressao publica resolve"
- visual: timeline simples mostrando enviado, publicado, resolvido.
- botao principal: "Comecar"

### 3. Login / Cadastro

Elementos:

- titulo: "Entre e denuncie sem novela"
- texto: "Leva menos de 30 segundos."
- botoes:
  - "Continuar com Google"
  - "Continuar com Apple"
  - "Continuar anonimamente"
- microcopy: "Sem feed, sem burocracia. So o buraco e a localizacao."

### 4. Home do Usuario

Nao criar feed social.

Mostrar apenas denuncias do proprio usuario.

Elementos:

- saudacao curta;
- contador de denuncias enviadas;
- contador de resolvidas;
- lista de cards de denuncia.

Cada card deve conter:

- foto;
- bairro;
- tamanho/severidade;
- data;
- status;
- microcopy curta.

Adicionar botao fixo destacado:

- "Denunciar buraco"

### 5. Tela de Denuncia

Esta e a tela mais importante. O fluxo deve ter no maximo 3 passos.

Elementos:

- area grande para tirar foto ou escolher da galeria;
- botao "Tirar foto";
- botao "Galeria";
- localizacao automatica com estado de sucesso;
- rua/bairro editavel;
- campo "Quando comecou?";
- campo livre "Descreva sua indignacao";
- placeholder: "Esse buraco ja tem CEP proprio.";
- botao principal: "Enviar denuncia".

Crie tambem estados:

- permissao de camera;
- permissao de localizacao;
- upload carregando;
- envio concluido.

### 6. Confirmacao de Envio

Elementos:

- titulo: "Buraco localizado com sucesso."
- texto: "Agora vamos analisar e publicar quando estiver tudo certo."
- resumo da denuncia;
- botao "Ver minha denuncia";
- botao secundario "Denunciar outro".

### 7. Detalhe da Denuncia

Elementos:

- foto grande;
- localizacao;
- status;
- data;
- timeline simples.

Timeline:

- enviado;
- aprovado;
- publicado;
- resolvido.

Adicionar botao:

- "Foi resolvido"

### 8. Problema Resolvido

Elementos:

- upload de foto atual;
- comentario opcional;
- mensagem: "Boa! Menos uma cratera na cidade."
- botao: "Confirmar resolucao"

### 9. Notificacoes

Lista com exemplos:

- "Sua denuncia foi aprovada."
- "Seu buraco ganhou visibilidade."
- "Atualizacao no seu caso."
- "Problema marcado como resolvido."

### 10. Perfil

Mostrar:

- denuncias enviadas;
- denuncias resolvidas;
- bairros reportados.

Badges humoristicas:

- "Cacador de Crateras";
- "Fiscal do Asfalto";
- "Suspensao de Titanio";
- "Lenda do Recape".

## Admin Dashboard Desktop

Crie frames desktop em 1440x1024.

O painel admin deve ser simples, operacional e sem cara de rede social.

Elementos:

- sidebar;
- cards de metricas;
- tabela de denuncias;
- filtros por status, bairro e data;
- detalhe lateral da denuncia selecionada;
- preview da foto;
- preview do post social;
- botoes:
  - "Aprovar"
  - "Rejeitar"
  - "Editar legenda"
  - "Remover dados sensiveis"
  - "Marcar como publicado"

Inclua estados para:

- aguardando revisao;
- aprovado;
- rejeitado;
- publicado;
- resolvido.

## Microcopy

Use tom popular, urbano, levemente ironico e humano.

Exemplos:

- "Mais um classico urbano."
- "Sua suspensao sentiu."
- "Esse aqui ta competitivo."
- "A cidade agradece."
- "Buraco localizado com sucesso."
- "Sem palestra. So manda a foto."
- "O asfalto pediu socorro."

O humor deve ser leve e compartilhavel, nunca ofensivo.

## Prototipo Navegavel

Crie links de prototipo para:

- Splash -> Onboarding;
- Onboarding -> Login;
- Login -> Home;
- Home -> Nova denuncia;
- Nova denuncia -> Confirmacao de envio;
- Confirmacao -> Detalhe;
- Detalhe -> Problema resolvido;
- Problema resolvido -> Detalhe com status Resolvido;
- Bottom navigation entre Home, Notificacoes e Perfil;
- Admin tabela -> Detalhe lateral.

Use transicoes simples e rapidas, adequadas para app utilitario.

## Handoff

Na pagina `07 Handoff Notes`, inclua:

- tokens de cor;
- escala de espacamento: 4, 8, 12, 16, 24, 32, 48;
- especificacoes dos componentes principais;
- lista de telas;
- observacoes de acessibilidade;
- notas para desenvolvimento em Next.js PWA.

## Regras Finais

- Nao incluir outras categorias alem de buracos, crateras, asfalto deteriorado e problemas viarios urbanos.
- Nao criar feed social.
- Nao criar comentarios, likes, seguidores ou chat.
- Priorizar velocidade de envio.
- Usar portugues brasileiro em toda a interface.
- Entregar wireframes, high fidelity, design system, componentes e prototipo navegavel.
