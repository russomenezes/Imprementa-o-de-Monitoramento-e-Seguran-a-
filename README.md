Monitoramento-de-Banco-de-dados

Objetivo 
O objetivo desse projeto é iniciar a implantação de um ambiente virtual com intuito de simular uma infraestrutura de redes que contenha um Firewall para compor uma política de segurança realizando comunicação com o Zabbix que é um sistema de monitoramento e o banco de dados Mysql para armazenar informações de uma loja virtual criada no opencart.
Objetivo Alcançados: 
Foi realizado inicialmente a instalação de maquinas virtuais através do software Virtual box versão 5.2.18 que está sendo rodado em uma máquina Windows 10 com as seguintes configurações:
	Intel(R) Core(TM) i5-3330 CPU @ 3.00GHz  8 gigas de memória RAM HD 1TB 
	que recebeu incialmente a criação dos seguintes sistemas; 
	Pfsense versão 2.3.5 
	Linux Ubuntu Server  16.04 
	Zabbix 3.2 
	Opencart 3.2.0 
	Xamp 3.2.2 
   Também foi instalado um servidor virtual utilizando o software xamp para emular o servidor onde foi implantado a loja virtual (e-comerce ) com o nome domino “iesb”,. 
O sistema Operacional ubunbu recebeu a instalação do software zabbix versão 3.2

   Para melhor comunicação todas as maquinas foram criadas em duas redes com comunicação wan e Lan . 
As maquinas por uma placa de rede comunicavam com a rede  192.168.1.0  e por outra placa com a rede 192.168.56.2  e ficou com a seguinte configuração. 
Endereços de rede; 

	Gateway padrão: 192.168.1.1 
	Windows 10:  192.168.1.3  e 192.168.56.1 
	Opencart: 127.0.0.1 dentro do Windows 10
	PfSense :192.168.56.2 
	Zabbix: 192.168.1.7
	Servidor Linux:192.168.1.7 
 Justificativa 
•	A escolha do Firewall Pfsense se deu pelo fato de pesquisas realizado na internet mostrarem a alta aceitação em empresas de grande porte, do mesmo modo as outras ferramentas que compõem a estrutura. Zabbix(Sistema de monitoramento), Banco de Dados Mysql, Opencart, Apache2, PHP7.0 (sistema de E-Commerce Open Source utilizando a linguagem de programação PHP ). -Etapas O projeto da inicio e segue as seguintes etapas: 1º Instalação de Ambiente de virtualização Virtual box 4.3.6 2º instalação do firewall PfSense 2.3.5 (32 bits) 3º instalação de um desktop com Windows 7 ultimate para teste e visualização do ambiente. 4º Instalação Linux ubuntu-server versão 16.04 (32 bits) 5º Instalação Zabbix versão 3.2 6º Instalação do apache 7º Instalação do Mysql 8º Instalação do PHP 7.0 9º Instalação do Opencart
Sobre os Sistemas e Ferramentas 
Windows 10:  Ao implantar os procedimentos não Windows 10  foi de fácil acesso e fácil usabilidade o maior problema encontrado foi achar a ferramenta de virtualização sem bugs e com melhor reconhecimento das interfaces de redes que foi instalada na maquina. 
Virtual box: A ferramenta foi testada em vários sistemas operacionais como Linux ubuntu , Linux mint , Windows 7 e Windows 10 e o melhor desempenho e compatibilidade para reconhecimento de interfaces foi no Windows 7 e 10.   No Linux a ferrramenta ganhou agilidade porém o problema foi reconhecer placa de rede externa.  
Linux Server: sistema muito fácil instalação porém tive uma dificuldade ao usar as linha de comando então busquei algumas informações na internet para dar continuidade no projeto 
PfSense: inicialmente tem pouco material gratuito falando sobre a ferramenta porém muito aceita no mercado nesse caso interessei pela ferramenta e como tem haver com a minha área de formação tive o prazer de realizar um curso de básico e avançado na UDEMY  excelente curso e aprendi muito. 
Zabbix: O Sistema no  segundo semestre tive o prazer de conhecê-lo então surgiu a ideia de relembrar sua usabilidade e instalar novamente desse modo tive facilidade de seu uso e configuração. 
Xamp: servidor muito simples de utilizar a instalação no Windows é bem clara e rápida. 
Opencart: Essa Ferramenta conheço a algum tempo pois trabalho desenvolvendo lojas virtuais para alguns clientes então foi curioso realizar o seu monitoramento. 
Obs: O Sistema Operacional Windows 7 foi desativado pois não era mais necessário para teste no ambiente. 
Forma de obter conhecimento para implantação do projeto 
Nome Curso de Pf Sense  
Link :  https://www.udemy.com/aprenda-o-firewall-pfsense-do-zero-ao-avancado 

Nome Implantação do Zabbix 
Link : https://www.youtube.com/watch?v=6x4x9V9Evco 

Nome utilizar o Xamp 
Link : https://www.youtube.com/watch?v=VhQk--V1934 

Nome Instalação opencart 
Link : https://www.youtube.com/watch?v=o3IkhDoogGA 

Nome Curso Linux 
Link :  https://www.youtube.com/watch?v=u16ZDPcf8Rc&list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7 

Dificuldades 
Ao iniciar o projeto o maior problema foi conseguir os softwares que não estava com algum bug , sistema operacionais sem nenhuma erro e também a primeira máquina de teste que foi um notebook de 2 gigas não suportou as virtualizações, também os softwares de virtualização não reconhecia as placas wireless para completar as duas placas necessárias foi ai que decidi implantar 1 placa via cabo e 2 via wireless no pc para dar continuidade no projeto. 
Conclusão 
•	Conclusão. O intuito do projeto é simular uma estrutura de rede que componha segurança, com usabilidade de um servidor web que comporte uma aplicação E-Commerce com monitoramento em tempo real das atividade realizadas em banco do banco de dados do próprio zabbix e do E-commerce.
Instação do Opencart 
 
Instalação do Banco de dados Opencart 

Instalação PF Sense 

Instalação do Zabbix 

Sistema Em execução 
