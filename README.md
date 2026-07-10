# Cidade da Leitura

Ferramenta pessoal de apoio à alfabetização, feita para uso doméstico com uma criança
autista em processo de alfabetização — não é um produto comercial nem substitui
acompanhamento fonoaudiológico/psicopedagógico.

## O que é

Uma única página HTML, sem backend, que roda direto no navegador (funciona bem num
tablet, adicionada à tela de início):

- **Aba "Sons das letras"**: cartões de fonema com ensino sem erro (o ajuda aparece
  sozinha se a criança não responder, nunca uma tela de "errado"). O conteúdo em
  `FONEMA_TRIALS` é só um exemplo de partida — deve ser substituído pela sequência
  fônica real indicada pelo profissional que acompanha a criança.
- **Aba "Nomes da família"**: reconhecimento de nome ouvido → palavra escrita, com foto
  da pessoa como apoio visual.
- Cada acerto constrói uma casinha numa "cidade" que cresce e persiste entre sessões
  (armazenada no navegador do aparelho).

## Privacidade

Nenhum dado real vai para o código publicado neste repositório:

- Os **nomes reais** da família e o **nome de exibição do app** são preenchidos uma
  vez pelos responsáveis, direto no aparelho, via o painel de configurações (⚙️) —
  ficam salvos só em `localStorage`, nunca em texto no código.
- As **fotos** da família seguem o mesmo princípio: escolhidas da galeria do próprio
  aparelho, nunca enviadas a nenhum servidor.
- Não há conta, login, analytics ou requisição de rede de nenhum tipo.

## Uso

Abra `index.html` num navegador (ou visite a versão publicada via GitHub Pages).
Toque na engrenagem ⚙️ para configurar nomes, fotos e o nome de exibição do app.
