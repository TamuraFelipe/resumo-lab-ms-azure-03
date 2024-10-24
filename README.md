# Tipos de Serviços: IaaS, PaaS e SaaS nas Azure

Esse contexto é genérico de nuvem

## IaaS → Infraestrutura como serviço

Crie uma infra de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

- O serviço de nuvem mais flexível
- Você configura e gerencia o hardware para seu aplicativo.

![image.png](/IaaS.png)

Imagen: https://tiagobigode.com.br/iaas-paas-saas/

## PaaS → Plataforma como Serviço

Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infra subjacente

- Focado no desenvolvimento de aplicativos
- O gerenciamento de plataforma é realizado pelo provedor de nuvem

![image.png](/PaaS.png)

Imagen: https://tiagobigode.com.br/iaas-paas-saas/

## SaaS → Software como Serviço

Os usuários se conectam e usam aplicativos com base em nuvem pela Internet: Por ex: MS Office 365, email e calendários.

- Modelo de preço de pagamento conforme o uso (licença)
- Os usuários pagam pelo software que utilizam em um modelo de assinatura

![image.png](/SaaS.png)

Imagen: https://tiagobigode.com.br/iaas-paas-saas/

## **Divisão de responsabilidade**

Em um datacenter local, você tem a propriedade da pilha inteira. À medida que você faz a migração para a nuvem, algumas responsabilidades são transferidas para a Microsoft. O diagrama a seguir ilustra as áreas de responsabilidade entre você e a Microsoft, de acordo com o tipo de implantação da pilha.

![image.png](/divsao.png)

imagem: https://learn.microsoft.com/pt-br/azure/security/fundamentals/media/shared-responsibility/shared-responsibility.svg

Para todos os tipos de implantação de nuvem, você tem seus dados e suas identidades. Você é responsável por proteger a segurança de seus dados e identidades, recursos locais e os componentes de nuvem que você controla. Os componentes de nuvem que você controla variam de acordo com o tipo de serviço.

Independentemente do tipo de implantação, você sempre mantém as seguintes responsabilidades:

- Dados
- Pontos de extremidade
- Conta
- Gerenciamento de acesso
