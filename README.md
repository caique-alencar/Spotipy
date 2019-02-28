<h1>Treino de Spotipy</h1>

Eu uso o GitHub para armazenar os códigos de projetos que eu faço. Nesse repositório você encontra exercícios que eu já fiz para treinar raspagem de dados usando a API do Spotify.

Para acessar a API, usei minhas credenciais em um arquivo separado que não subi para o repositório. Para definir as credenciais, rode o seguinte o código antes:

<pre><code>import json<br>
spotify_credentials = {}<br>
spotify_credentials['username'] = 'DIGITE AQUI SEU URI'<br>
spotify_credentials['client_id'] = 'DIGITE AQUI SEU CLIENT'<br>
spotify_credentials['client_secret'] = 'DIGITE AQUI SEU CLIENT SECRET'<br>
spotify_credentials['redirect_uri'] = 'http://localhost:8000/'<br>
spotify_credentials['scope'] = 'playlist-modify-public'<br>
with open('credenciais_spotify.json', 'w') as secret_info:<br>
  json.dump(spotify_credentials, secret_info, indent=4, sort_keys=True)<br></code></pre>
