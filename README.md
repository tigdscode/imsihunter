# imsihunter
Essa é a principal interface gráfica para análise de redes GSM, com o IMSI-HUNTER você poderá analisar redes GSM de forma prática e intuitiva, além de poder aproveitar as várias outras funcionalidade, você poderá usar até 4 tipos de SDR's diferentes para a recepção.

Básicamente o IMSI-HUNTER trabalha com  a mesma lógica de funcionamento do IMSI-CACTCHER script desenvolvido em Python e que se 
encontra disponivél no GitHub. A diferença é que esse novo projeto é composto por uma interface gráfica que abrange algumas funcio-
nalidades a mais da anterior. O IMSI-HUNTER suporta 4 modelos diferentes de hardwares no momento, sendo que os drives e depências de 
cada modelo em espeficifico é instalado no momento da conexão entre a máquino e o hardware especifico via porta usb.

TOOLS IMSI-HUNTER:

- IMSI SCAN: Faz uma análise de números imsi disponivéis na área de conexão gsm onde o hardware sdr está operando. Essa função usa o 
própio script imsi-catcher.py rodando nos fundos da interface gráfica e imprimindo os valores de forma organizada para a análise.

-GSM SPOOFING: Cria um canal de escuta na rede GSM explorando pontos fracos e brechas de protocolo SS7. Gera informações sobre o sinal 
e dispositivos vúlneraveis encontrados. Podendo ser usado posteriormente para análise de captura de pacotes de dados.

-SDR LIVEMON: Abre a interface gráfica do sdrlivemon, para que seja usado a função de análise de espectro dos sinais gsm visíveis.

-IMSI GEOLOCATION: Traça uma localização em tempo real do dispositivo selecionado, tomando como referência a etsção base ao qual o dis-
positivo está conectado.
