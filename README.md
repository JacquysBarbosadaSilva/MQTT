1 - Instale a biblioteca necessária para utilizar o MQTT, a pho-mqtt, digite no terminal o seguinte código: pip install paho-mqtt

2 - Nos arquivos em python para realizar os testes já possuem a importação dessa biblioteca, porém, se por algum acaso não estiver implementado ou apagou sme querer, a importação é simples: import paho.mqtt.client as mqtt

3 - Para realizar os teste deve seguir uma ordem de depuração dos códigos(lembranco que os dois arquivos precisam estar no mesmo diretório), inicalmente, o arquivo subscribe.py deve ser inicializado primeiro, 
aperte ctrl + J para abrir o terminal e digite: .\subscribe.py

4 - No canto superior direito do terminal existe um símbolo de +, clique nele e crie outro PowerShell, para ficar mais fácil a vizualização dos códigos.

5 - Digite nesse novo PowerShell o seguinte comando: .\publisher.py

6 - Se tudo ocorreu bem, ao digitar algo no terminal ao lado da mensagem "Digite uma menssgem para enviar:", mude para o outro terminal PowerShell e verá q foi publicada uma mensagem no tópico

7 - Lembre-se de estar com a porta correta e no broker correto também
