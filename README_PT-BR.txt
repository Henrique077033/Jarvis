JARVIS BRAIN — PROTÓTIPO PARA NUVEM

Este ZIP contém uma interface web, servidor Node.js/Express e conexão à API da OpenAI.
As instruções do sistema dão foco especial a programação e depuração.

ATENÇÃO
- A hospedagem gratuita pode dormir/reiniciar e ter limites; não é para produção nem para milhares de pessoas.
- A API da OpenAI é cobrada separadamente conforme modelo e uso. Confira preço e limites antes de ativar.
- Guarde OPENAI_API_KEY somente nas variáveis secretas do serviço de hospedagem. Nunca no HTML ou GitHub.
- Este protótipo ainda não tem memória permanente, autenticação, banco de dados, limite de uso robusto ou proteção de produção. Não divulgue publicamente antes de adicionar esses itens.
- O modelo padrão é gpt-6-astra neste protótipo. Se não estiver habilitado para sua conta, configure OPENAI_MODEL com um modelo disponível para você.

PUBLICAÇÃO (resumo)
1. Envie estes arquivos para um repositório GitHub.
2. No Render, crie um Web Service conectado ao repositório.
3. Build Command: npm install
4. Start Command: npm start
5. Nas variáveis secretas do serviço, adicione OPENAI_API_KEY.
6. Opcionalmente, defina OPENAI_MODEL para o modelo habilitado em sua conta.
7. Publique e abra a URL gerada.
8. /health verifica se o servidor está ativo.

Documentação oficial:
https://developers.openai.com/api/docs/quickstart
https://render.com/docs/your-first-deploy
https://render.com/docs/configure-environment-variables
