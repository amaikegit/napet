# Na Pet — Agenda de banho e tosa

Aplicação web responsiva em HTML, CSS e JavaScript, sem dependências externas.

## Recursos

- Agenda diária e semanal com cadastro e edição de atendimentos.
- Cadastro de tutores e pets.
- Bloqueio de horários sobrepostos.
- Registro de pagamentos e gráficos de entradas semanais e mensais.
- Menu recolhido automaticamente após cinco segundos, com ícones de navegação.
- Configurações para selecionar a imagem do logo.

## Executar

Abra `dist/index.html` em um navegador ou use um servidor estático:

```bash
python3 -m http.server 8080 --directory dist
```

Acesse http://localhost:8080.

## Dados

Esta é uma prévia com dados fictícios. Cadastros e logo ficam no armazenamento local do navegador, sem banco de dados ou sincronização entre dispositivos. Não há autenticação implementada no código da aplicação.

## Código

Inclui a atualização local `d5ebd3c`, que mantém os quatro ícones visíveis quando o menu está recolhido. O histórico do GitHub é criado pela integração conectada.
