# demonstrativostudiog85

## Painel de assinaturas (`painel-assinaturas.html`)

Programa interno para o dono do Studio G85 gerenciar o clube de assinantes mensais.
É um arquivo HTML único: basta abrir no navegador (funciona sem internet; só as fontes vêm do Google Fonts).

- **Visão geral**: receita recorrente do mês, quanto já entrou, quem está atrasado, quem vence nos próximos dias, mensalidades dos últimos 6 meses, assinantes por plano e uso dos benefícios.
- **Assinantes**: cadastro com WhatsApp, carro, placa, plano e dia do vencimento; busca por nome ou placa; painel de cada cliente com benefícios do mês, mensalidades e histórico; pausar, cancelar e reativar.
- **Registrar uso**: escolhe o cliente e clica no benefício usado (lavagem, higienização…). O painel mostra quanto ainda resta da cota do mês.
- **Mensalidades**: mês a mês, quem pagou e quem falta; receber, desfazer, cobrar ou lembrar pelo WhatsApp com mensagem pronta; exportação para Excel.
- **Planos**: valores fixos e benefícios de cada plano (quantidade por mês, desconto ou vantagem), editáveis, e texto pronto da tabela de planos para o WhatsApp.
- **Ajustes**: chave Pix, tolerância de atraso, textos das mensagens, backup e restauração.

Os dados ficam salvos no navegador do aparelho em que o painel é usado (`localStorage`). Por isso o painel lembra de baixar o backup: o arquivo `.json` restaura tudo em outro computador.
Na primeira abertura ele vem com assinantes de exemplo, que podem ser apagados com um clique; os planos iniciais são uma sugestão para ajustar.
