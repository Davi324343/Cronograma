# Meu Cronograma Perfeito 💜

Site responsivo com chat de IA, avaliação capilar, cronograma de quatro semanas, acompanhamento local e exportação em TXT.

## Executar

1. Instale Node.js 18 ou superior.
2. Na pasta do projeto, execute `npm install`.
3. Copie `.env.example` para `.env` e preencha `OPENAI_API_KEY` com sua chave de API.
4. Execute `npm start`.
5. Abra `http://localhost:3000`.

A chave da API **nunca** deve ser colocada no HTML nem publicada no GitHub. A API da OpenAI é cobrada separadamente do ChatGPT. Para publicar, use hospedagem com servidor Node.js e configure as variáveis de ambiente no painel do provedor.

## Observações

- A conversa e o progresso ficam no `localStorage` do navegador (sem login nem sincronização entre aparelhos).
- O servidor aplica um limite simples de 12 mensagens/minuto por IP. Em produção, adicione autenticação, limites de gasto, controles de abuso e política de privacidade.
- O cronograma é educativo e não substitui avaliação dermatológica.
