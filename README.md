# Weatherman-Sistema Inteligente de Prevenção e Apoio em Desastres Naturais
DISRUPTIVE ARCHITECTURES: IOT, IOB &amp; GENERATIVE IA

# Descrição do Projeto
Este projeto foi desenvolvido com o objetivo de reduzir os impactos causados por desastres naturais no Brasil, como enchentes, deslizamentos, queimadas e secas. O AlertaClima é um aplicativo mobile que utiliza inteligência artificial, dados climáticos oficiais, colaboração entre usuários e geolocalização para oferecer uma resposta rápida e eficiente em situações de emergência.
Utilizando o microcontrolador ESP32 e a plataforma Wokwi, os dados são capturados periodicamente pelo DHT22 e enviados ao broker MQTT no tópico fiap/led/temp. Com base na temperatura recebida, o sistema ativa um LED para alertar sobre calor excessivo (temperatura acima de 30°C), simulando ações de controle automatizado.

# Vídeo Pitch

# Link do Projeto Wokwi

# Funcionalidades
* Leitura Ambiental com Precisão: Captura da temperatura e umidade via DHT22.
* Publicação MQTT: Envio automático dos dados para um broker MQTT público.
* Alerta Visual: Ativação de LED em caso de temperatura superior a 30°C.
* Código Modular e Simples: Fácil de adaptar para aplicações reais.
* Simulação Online: Permite testes sem necessidade de hardware físico.
* Alertas Inteligentes: Notificações personalizadas baseadas na localização e no tipo de evento.

# Tecnologias Utilizadas
**Hardware**
* ESP32
* Sensor DHT22
* LED
* Resistores e Jumpers
* 
**Linguagem**
* C++ / Arduino
  
**Software**
* Wokwi – simulação completa do circuito
* Broker MQTT (test.mosquitto.org)
* PubSubClient – biblioteca para comunicação MQTT
* DHTesp – biblioteca para leitura do sensor DHT22

# Execução do projeto via APP mobile
Para a o envio de comando json via MOBILE, acesse o link do repositorio da aplicação MOBILE

# Próximos Passos
* Desenvolvimento do MVP funcional com testes reais de APIs e notificações push.
* Criação de banco de dados e rotas seguras com base em mapas e histórico de ocorrências.
* Parceria com Defesa Civil e órgãos locais para validação das funcionalidades.
* Campanhas de engajamento comunitário para incentivar o uso do sistema colaborativo.
* Versões offline e inclusivas para ampliar o alcance da solução.

# Autores
Leonardo Botelho - RM: 556110 - Turma: 2TDSB - GitHub: https://github.com/Wanderluzter
Mirian Bronzati - RM: 555041 - Turma: 2TDSB - GitHub: https://github.com/nakedmimi
Raul Clauson| - RM: 555006 - Turma: 2TDSB - GitHub: https://github.com/RaulClauson


