# Chat com Flask e SocketIO

Este é um projeto simples para criar um chat usando o Flask e o SocketIO. O chat permite que várias pessoas se conectem ao mesmo site e troquem mensagens em tempo real.

## Instalações necessárias

Antes de executar o código, certifique-se de ter as seguintes bibliotecas instaladas. Você pode instalar todas elas usando o pip, que é o gerenciador de pacotes do Python:

```bash
pip install flask
pip install python-socketio
pip install flask-socketio
```

## Instruções de Uso

1. Clone o repositório ou faça o download dos arquivos do projeto.
2. Instale as bibliotecas necessárias conforme indicado acima.
3. Abra o arquivo `app.py` em um ambiente de desenvolvimento Python.
4. Execute o arquivo `app.py`.
5. O servidor estará disponível localmente em `http://localhost:5000/`.

## Notas

- O servidor está configurado para rodar localmente no endereço `http://localhost:5000/`. Para torná-lo acessível em uma rede local ou na internet, você precisará configurar o host apropriadamente.
- A chave de segurança (`SECRET`) é usada para fins de segurança e autenticação. Escolha uma chave forte e única para o seu aplicativo.
- Este é apenas um exemplo simples de chat usando Flask e SocketIO. Para um aplicativo de produção mais robusto, você deve considerar questões de segurança, gerenciamento de usuários, persistência de mensagens, entre outros.
