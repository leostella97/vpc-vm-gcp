# VPC e Máquina Virtual pelo Console GCP

## Criando VPC e Máquina Virtual no Google Cloud Platform
Como criar uma <b>VPC (Virtual Private Cloud)</b> e uma <b>Máquina Virtual (VM)</b> usando o <b>Console do Google Cloud Platform (GCP)</b>.

<table>
	<ol>
		<li><a href="https://github.com/leostella97/vpc-vm-gcp#pr%C3%A9-requisitos">Pré-requisitos</a>
		<li><a href="https://github.com/leostella97/vpc-vm-gcp#criando-uma-vpc">Criando uma VPC</a>
		<li><a href="https://github.com/leostella97/vpc-vm-gcp#criando-uma-m%C3%A1quina-virtual">Criando uma Máquina Virtual</a>
		<li>Conclusão
</table>

## Pré-requisitos
• Uma conta ativa no Google Cloud Platform.
<br>
• Acesso ao Console do GCP.

## Criando uma VPC
<table>
	<ol>
		<li>Acesse o Console do GCP em https://console.cloud.google.com/.
		<li>No painel de navegação à esquerda, clique em "VPC de rede".
		<li>Em seguida, clique em "Criar VPC de rede".
		<li>Preencha as informações necessárias, como nome da VPC, região, intervalo de IP e outras configurações.
		<li>Clique em "Criar" para criar a VPC.
	</ol>
</table>

Exemplo de configuração da VPC:

	Nome da VPC: minha-vpc
	Região: us-central1
	Intervalo de IP: 10.0.0.0/16

## Criando uma Máquina Virtual
<table>
	<ol>
		<li>Acesse o Console do GCP em https://console.cloud.google.com/.
		<li>No painel de navegação à esquerda, clique em "Compute Engine" (Engine de Computação).
		<li>Clique em "Criar instância".
		<li>Preencha as informações necessárias, como nome da instância, região, zona, tipo de máquina, disco, rede e outras configurações.
		<li>Clique em "Criar" para criar a Máquina Virtual.
	</ol>
</table>

Exemplo de configuração da Máquina Virtual:

	Nome da instância: minha-vm
	Região: us-central1
	Zona: us-central1-a
	Tipo de máquina: n1-standard-1
	Disco de inicialização: Ubuntu 20.04 LTS
	Rede: minha-vpc

## Conclusão
Neste tutorial estou ensinando como criar uma VPC e uma Máquina Virtual no Google Cloud Platform usando o Console do GCP. Agora você pode explorar mais recursos e personalizar suas configurações de acordo com as necessidades.

Lembre-se de verificar as permissões e configurações adequadas e estar ciente dos custos aos recursos criados.

## Recursos adicionais
<a href="https://cloud.google.com/docs">• Documentação do Google Cloud Platform</a>
<a href="https://console.cloud.google.com/">• Console do Google Cloud Platform</a>