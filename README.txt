JOVEM PAN NACIONAL PLAYER

PUBLICAR NO RENDER
1. Extraia o ZIP e envie os arquivos a um repositório GitHub.
2. Crie um Web Service no Render ligado ao repositório.
3. Build Command: npm install
4. Start Command: npm start
5. Em Environment Variables, defina LOCUTOR_PASSWORD com uma senha forte.
6. Publique e abra a URL fornecida.

USAR
- Abra Painel do Locutor, digite seu nome e a senha.
- Adicione até 4 músicas e até 10 arquivos de efeitos, vinhetas ou anúncios.
- Na mesa de som, ajuste microfone, músicas/efeitos e volume geral. O compressor ajuda a controlar picos de áudio.
- Use “Baixar música e próxima” para reduzir o volume suavemente antes de passar para a próxima faixa.
- Na área “VINHETA E ANÚNCIO”, aperte “Disparar” para tocar rapidamente um efeito cadastrado.
- Entre ao vivo e permita acesso ao microfone.
- Ouvintes abrem o mesmo endereço e apertam Ouvir rádio.

IMPORTANTE
A transmissão de áudio usa WebRTC: o navegador do locutor mistura microfone e arquivos e envia o áudio aos ouvintes. Mantenha a aba e o dispositivo ligados. A conexão entre algumas redes pode exigir um servidor TURN; para grande audiência, use infraestrutura de streaming/SFU ou Icecast/SHOUTcast. Arquivos ficam no dispositivo do locutor e não são enviados para o servidor. Use somente áudio que você tenha autorização para transmitir. Configure LOCUTOR_PASSWORD antes de publicar; a senha de desenvolvimento padrão não é segura.