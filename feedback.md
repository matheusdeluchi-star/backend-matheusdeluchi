# Feedback - Aula 03

Matheus, o seu servidor.js tem um problema grave de estrutura: as rotas de POST, PUT, DELETE e até o app.listen estão escritas dentro do corpo da rota GET /treinos/:id, em vez de serem rotas separadas. Isso faz o servidor nem subir direito. Preciso lançar a nota até sexta-feira, vale reescrever puxando essas rotas pra fora, cada uma com seu próprio app.get/post/put/delete.
