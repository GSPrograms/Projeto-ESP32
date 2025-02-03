# FECAP - Fundação Escola de Comércio Álvares Penteado

<p align="center">
<a href= "https://www.fecap.br/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhZPrRa89Kma0ZZogxm0pi-tCn_TLKeHGVxywp-LXAFGR3B1DPouAJYHgKZGV0XTEf4AE&usqp=CAU" alt="FECAP - Fundação de Comércio Álvares Penteado" border="0"></a>
</p>

# Irrigação Inteligente

## Sistema de Irrigação Inteligente para Agricultura

## Integrantes: <a href="http://linkedin.com/in/gustavo-henrique-da-silva-santos-453822326/?trk=opento_sprofile_topcard">Gustavo Henrique da Silva Santos</a> & <a href="https://www.linkedin.com/in/lucas-alves-bernardo-093871252/">Lucas Alves Bernardo</a> 

## Professores Orientadores: <a href="https://br.linkedin.com/in/victorbarq">Dr. Victor Rosetti de Queiroz</a>, <a href="https://br.linkedin.com/in/lucymari">Dra. Lucy Mari Tabuti</a>, <a href="https://www.linkedin.com/in/eduardo-savino-gomes-77833a10/">Dr. Eduardo Savino Gomes</a>, <a href="https://www.linkedin.com/in/remuniz/">Dra. Renata Muniz do Nascimento</a>, <a href="https://www.linkedin.com/in/ronaldo-araujo-pinto-3542811a/">Me. Ronaldo Araujo Pinto</a>

## <b>Descrição</b>

<p align="center">
<img src="https://gtagenda2030.org.br/wp-content/uploads/2019/10/objetivos_port.png?w=1024" alt="17 ORS" border="0">
  Origem da imagem: <a href="https://brasil.un.org/pt-br">ONU</a> <a rel="license" href="https://brasil.un.org/pt-br">
</p>


De acordo com uma pesquisa do Instituto Brasileiro de Geografia e Estatística (IBGE), divulgada em maio de 2020, <a href="https://www.estadao.com.br/economia/agropecuaria-fica-com-97-4-do-consumo-total-de-agua-em-2017-aponta-ibge/">o agronegócio foi responsável por 97,4% do total de água consumida no Brasil em 2017</a>, com pelo menos metade desse volume sendo desperdiçado e que previsto pelas pesquisas da Agência Nacional de Águas (<a href="https://www.gov.br/ana/pt-br">ANA</a>), o consumo de água no Brasil deve aumentar 24% nos próximos 10 anos. Pensando em auxiliar a agricultura e promover o uso sustentável dos recursos hídricos, o projeto "Irrigação Inteligente" foi criado com o objetivo de otimizar o uso da água de maneira econômica e eficiente.  
<br><br>
<p align="center">
<img src="https://github.com/user-attachments/assets/d7e12810-1299-4194-9441-f5c7c86e2c3d">
</p>
<br><br>
A adaptabilidade é o ponto forte do projeto, permitindo sua aplicação em pequenas e grandes escalas, além de possibilitar outras utilizações além da irrigação. O sistema utiliza um sensor de umidade do solo para monitorar as condições de umidade e, conforme a necessidade, aciona a bomba d'água, direcionando o recurso para a área predeterminada por um período específico de tempo.
<br><br>


## 🛠 <b>Estrutura de pastas</b>

-Raiz<br>
|<br>
|-->Documentos<br>
  &emsp;|-->Entregas 1<br>
  &emsp;|-->Entregas 2<br>
  &emsp;|-->Entregas 3<br>
  &emsp;|-->Entregas 4<br>
|-->Imagens<br>
|-->SRC<br>
  &emsp;|-->Frontend<br>
  &emsp;|-->Backend<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Toda a documentação estará nesta pasta.

<b>executáveis</b>: Binários e executáveis do projeto devem estar nesta pasta.

<b>imagens</b>: Imagens do sistema

<b>src</b>: Pasta que contém o código fonte.

## ⚙ <b>Hardware</b>
  - Arduino ESP32 Dev Module;<br>
  - Sensor de Umidade de Solo HL-69;<br>
  - Mini Bomba D'água Submersível 3.3v/5v;<br>
  - LM393 Comparator Module - ADIY;<br>
  - Relé FL-3FF-S-Z 5VDC;<br>
  - Protoboard (preferência Long);<br>
  - Jumpers MxF e Jumpers MxM;<br>
  - Mangueira Cristal Pvc 4mm;<br>
  - PowerBank AlphaGold 10000 mAh;<br>

## 🖥 <b>Software</b>
- Arduino IDE;<br>
- VSCode. <br>

## 💾 <b>Instalação<b>
C++
- Acessar o site do <a href="https://www.arduino.cc/en/software"> Arduino IDE</a> e instalar a IDE.<br>
- Após a instalação da IDE, será necessário adicionar as bibliotecas e placas para próprioas para o Arduino ESP32 e suas aplicações utilizadas:<br>
    <br>° <a href="https://github.com/arduino-libraries/Arduino_ESP32_OTA">Arduino_ESP32_OTA</a> (biblioteca por Arduino);</br>
    <br>° <a href="https://docs.arduino.cc/libraries/wifi/">WiFi</a> (biblioteca por Arduino);<br>
    <br>° <a href="https://www.arduino.cc/">Arduino ESP32 Boards</a> (placa por Arduino);<br>
    <br>° <a href="https://github.com/espressif/arduino-esp32">esp32</a> (placa por Espressif Systems).</br>
    
- Na IDE, clique em File > Preferences > Additional boards Managers URLs, e adicione os links das placas e bibliotecas.<br>
- Após a instalação da IDE e das bibliotecas e placas, o software está pronto para rodar o código C++.<br>

<br>HTML</br>
- Acessar o site do <a href="https://code.visualstudio.com"> Visual Studio Code</a> e instalar o VSCode.<br>
- Após a instalação do VSCode, será necessário adicionar uma extensão para executar o código do servidor:<br>
    <br>° Baixe a extensão <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer">Live Server</a> (extensão por Ritwick Dey) no VSCode.</br>
    
- Após a instalação do VSCode e da biblioteca, baixe o código HTML do projeto e estará pronto para o uso com o Live Server.<br>

## 📔 <b>Referências<b>
- Artigo feito pela CONBEA usado para obtenção de informações sobre o sensor de umidade de solo:<a href="https://conbea.org.br/anais/publicacoes/conbea-2018/livros-2018/eas-engenharia-de-agua-e-solo-10/1687-sensor-de-umidade-do-solo-em-diferentes-profundidaes/file"> SENSOR DE UMIDADE DO SOLO EM DIFERENTES PROFUNDIDADE</a>
