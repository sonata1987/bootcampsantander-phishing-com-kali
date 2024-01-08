# bootcampsantander-phishing-com-kali
Repositório com a entrega do desafio de código da trilha de cybersecurity da DIO bootcamp santander

Utilizando a ferramenta SETOOLKIT do Kali, o desafio propõe a criação de uma pagina web falsa para ter acesso a credenciais, 
dessa forma iremos seguir os seguintes passos no kali para ter êxito no fluxo de trabalho;

1) utilize uma maquina virtual com kali linux, certifique-se de que a placa de rede esteja em modo bridge pois será necessário utilizar a internet na maquina virtual.
2) abra um terminal no kali linux e digite o comando "setoolkit", o menu da ferramenta será disponibilizado 
![image](https://github.com/sonata1987/bootcampsantander-phishing-com-kali/assets/78008345/68e79603-6eee-4e99-b999-b8d4253ade25)
3)escolha a opção 2 "website attack vectors" e no menu subsequente escolha a opção 3 "credential harvester attack method"
![image](https://github.com/sonata1987/bootcampsantander-phishing-com-kali/assets/78008345/43aeef80-56ac-4a76-9425-75c7d39857b3)
em seguida a opção 2 "site cloner"
![image](https://github.com/sonata1987/bootcampsantander-phishing-com-kali/assets/78008345/83c710ac-46b8-4f18-863b-bd72dd7ea7ae)
4)selecione o ip da maquina
![image](https://github.com/sonata1987/bootcampsantander-phishing-com-kali/assets/78008345/113cfe63-fbd9-4390-986e-0d47248beba1)
5)digite o endereço da pagina a ser clonada http://www.facebook.com e acesse o endereço ip de outra maquina que não seja a do Kali
![image](https://github.com/sonata1987/bootcampsantander-phishing-com-kali/assets/78008345/42901ece-30b1-4c38-b6be-fbbe817accac)
6)digite as credenciais de acesso e volte novamente ao setoolkit que as credenciais digitadas estarão disponíveis.
![image](https://github.com/sonata1987/bootcampsantander-phishing-com-kali/assets/78008345/ae6a8e8d-e918-411b-acba-dc5f1d240753)

obs: aparentemente os novos navegadores possuem camada de proteção contra este tipo de ataque, o ataque somente foi possível utilizando um internet explorer em sua versão 8.0.7600.16385
