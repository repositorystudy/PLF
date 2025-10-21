# Segurança da Informação

> Anotações de aula e questões comentadas sobre fundamentos de segurança da informação.

---

## Conceitos Fundamentais

A **Segurança da Informação** é o conjunto de práticas e políticas voltadas à **prevenção e controle** de riscos, danos e perdas em dados e sistemas de *hardware* e *software*.

Os **princípios básicos** (mnemônico **DICA**) são:

| Princípio | Descrição breve |
|------------|----------------|
| **Disponibilidade** | A informação deve estar acessível sempre que necessário. |
| **Integridade** | Garante a completude e a precisão das informações. |
| **Confidencialidade** | Somente pessoas autorizadas podem acessar os dados. |
| **Autenticidade** | Confirma a veracidade da autoria e impede o repúdio. |


## Detalhamento dos Princípios Primários

### Disponibilidade
A informação deve estar disponível **a qualquer momento** que for necessária, sem restrições indevidas.

### Integridade
Refere-se à **completude e correção** dos dados.  
Somente **usuários autorizados** podem modificá-los, preservando sua consistência.

### Confidencialidade
Assegura que apenas **pessoas com permissão** tenham acesso à informação.

### Autenticidade
Garante que a informação **vem de quem afirma ser o autor**, evitando falsificações.

## Aspectos dos princípios básicos

Para responder devemos questionar:

- Quais são os princípios?
- O que significam?
- Ferramentas?

A **Disponibilidade** significa que _"a informação estará disponível sempre que for necessário"_. As ferramentas são:
- **Firewall**: filtra a intromissão de conexões que tentam invadir a informação impedindo o ataque.
- **Nobreak** - dá autonomia de energia em caso de queda de energia mantendo a informação disponível
- **Backup**: permite que os dados fiquem salvos em uma segunda base de dados restaurando-os.
- **Equipamentos de redundância**: São ferramentas que duplicam dos dados para serem acessados de forma segura.

A **Integridade** significa que _"a informação só pode ser **alterada** por pessoas autorizadas"_. As ferramentas são:
- **Backup**: permite que os dados fiquem salvos em uma segunda base de dados restaurando-os garantindo também a integridade da informação.
- **Assinatura Digital**: Garante a autoria da informação é legitima bem como garante a identidade do auto.

A **Confidencialidade** significa que _"a informação só pode ser **acessada** por pessoas autorizadas"_. As ferramentas são:
- **Criptografia**: Garante o embaralhamento da informação.

A **Autenticidade** significa que _"garante a veracidade da da autoria da informação e o não repúdio"_. As ferramentas são:
- **Assinatura Digital**: Garante a autoria da informação é legitima bem como garante a identidade do auto.

- **Certificado Digital**:Ferramenta que permite a Assinatura Digital.

- **Biometria**: Tecnologia que autentica um usuário via dados bométricos únicos.

- **MFA**: Trata-se uma tecnologia de Autenticação de Multiplos Fatores (_Multi-Factor Authentication_).

# Ferramentas que Garantem os Princípios da Segurança da Informação

| **Ferramenta**         | **Disponibilidade** | **Integridade** | **Confidencialidade** | **Autenticidade** |
|:----------------------|:-----------------:|:---------------:|:-------------------:|:----------------:|
| **Backup**             | X                 | X               |                     |                  |
| **Firewall**           |   X                |                 |                    |                  |
| **Biometria**          |                   |                 |                     | X                |
| **Nobreak**            | X                 |                 |                     |                  |
| **Assinatura Digital** |                   | X               |                     | X                |
| **Certificado Digital**|                   |                 |                     | X                |
| **Criptografia**       |                   | X               | X                   | X                |

---

## Questões Comentadas

Questão XX)
> Qual dos princípios da segurança da informação garante que os dados só possam ser modificados por usuários autorizados?

**A)** Disponibilidade  
**B)** Integridade  
**C)** Confidencialidade  
**D)** Autenticidade

**Comentário:**  
A **integridade** assegura que a informação permanece **completa e inalterada**, exceto por pessoas autorizadas.

---

### Questão XX)
> O princípio que impede que alguém negue a autoria de uma ação é o da:

**Resposta:** Autenticidade

**Explicação:** Garante o **não repúdio**, ou seja, o autor **não pode negar** ter realizado determinada ação, também chamado de princípio da Irretratabilidade.

### Questão XX) FGV/Câmara dos Deputados/2023

A segurança da informação baseia-se em princípios como a confidencialidade, a integridade e a disponibilidade. 
A ação de proteger as informações contra acesso não autorizado está relacionada a qual princípio?

A) Disponibilidade  
B) Autenticidade  
C) Confidencialidade  
D) Integridade  

**Resposta**: C, pois a confidencialidade garante que somente pessoas autorizadas possam acessar os dados.

---

### Questão XX)
A segurança da informação tem como um de seus pilares a **integridade dos dados**.  
Esse princípio garante que:

A) A informação esteja disponível sempre que necessário.  
B) A informação seja acessada apenas por usuários autorizados.  
C) A informação não seja alterada indevidamente, mantendo-se completa e correta.
D) O autor da informação seja legítimo e não possa negar sua autoria.

|Gabarito|Comentário|
|---|---|
|C|A integridade protege o conteúdo contra modificações não autorizadas e garante sua consistência. A alternativa **B** trata da confidencialidade, e a **D**, da autenticidade.|

---

### Questão XX
O princípio da **confidencialidade** é violado quando:

A) Um usuário autorizado acessa dados em momento indevido.  
B) Um invasor obtém acesso a dados sigilosos.
C) Os dados são perdidos em razão de falha no servidor.  
D) A informação é modificada por erro de digitação.

**Gabarito:** B  
**Comentário:**  
A violação da confidencialidade ocorre quando há **acesso não autorizado**.  
A alternativa **C** refere-se à disponibilidade; **D**, à integridade.

---

### Questão XX
O princípio da **autenticidade** está relacionado principalmente à:

A) Possibilidade de restaurar dados perdidos.  
B) Verificação da identidade do autor ou emissor da informação.  
C) Garantia de que a informação está completa e sem erros.  
D) Prevenção de acesso indevido a informações.

**Gabarito:** B  
**Comentário:**  
A autenticidade garante que a informação **vem de quem diz ser o autor**, impedindo falsificações e o **repúdio** posterior.

---

### Questão XX
Um servidor de banco de dados falhou e ficou fora do ar por 12 horas, impedindo o acesso às informações.  
Qual princípio da segurança da informação foi afetado?

A) Autenticidade  
B) Integridade  
C) Disponibilidade  
D) Confidencialidade

**Gabarito:** C  
**Comentário:**  
A **disponibilidade** foi comprometida, pois as informações não puderam ser acessadas quando necessário.

---

### Questão XX
Analise as situações abaixo e marque a alternativa que **viola mais de um princípio** da segurança da informação:

A) Documento alterado por pessoa não autorizada.   
B) Sistema fora do ar por falha de energia.  
C) Acesso negado a usuário legítimo.  
D) Assinatura digital inválida em mensagem legítima.

**Gabarito:** A  
**Comentário:**  
Quando há alteração por não autorizado, **integra-se a violação de integridade e confidencialidade** simultaneamente.

---

### Questão XX
Sobre os princípios da segurança da informação, assinale a alternativa **INCORRETA**:

A) Confidencialidade impede o acesso de pessoas não autorizadas.  
B) Integridade assegura que os dados permaneçam inalterados.  
C) Disponibilidade assegura que o sistema esteja sempre acessível.  
D) Autenticidade garante que qualquer usuário possa modificar a informação.   

**Gabarito:** D  
**Comentário:**  
A alternativa D inverte o sentido do princípio — a autenticidade **não autoriza modificação**, apenas garante **identidade e autoria legítima**.

---

### Questão XX
A política de senhas fortes e autenticação multifator está diretamente relacionada à:

A) Confidencialidade e autenticidade.   
B) Disponibilidade e integridade.  
C) Integridade e confidencialidade.  
D) Autenticidade e disponibilidade.

**Gabarito:** A  
**Comentário:**  
Senhas e autenticação protegem **quem acessa** (autenticidade) e **o que é acessado** (confidencialidade).

---

### Questão XX
(PEGADINHA) Um funcionário autorizado exclui, por engano, arquivos importantes da empresa.  
O princípio violado foi:

A) Confidencialidade  
B) Integridade   
C) Disponibilidade  
D) Autenticidade  

**Gabarito:** B  
**Comentário:**  
Mesmo que o usuário seja autorizado, houve **alteração indevida do conteúdo**, o que atinge a integridade.

---

### Questão XX
A criptografia é um mecanismo de segurança que está mais diretamente ligado a qual princípio?

A) Autenticidade  
B) Confidencialidade   
C) Disponibilidade  
D) Integridade  

**Gabarito:** B  
**Comentário:**  
A criptografia protege o **conteúdo contra leitura não autorizada**, reforçando a confidencialidade.

---

### Questão XX
O uso de assinaturas digitais em documentos eletrônicos tem por objetivo principal:

A) Garantir a autenticidade e a integridade da informação.   
B) Garantir apenas a confidencialidade.  
C) Aumentar a disponibilidade do sistema.  
D) Impedir qualquer tipo de acesso remoto.

**Gabarito:** A  
**Comentário:**  
Assinaturas digitais asseguram **autenticidade (quem enviou)** e **integridade (não foi alterado após o envio)**.

---

### Questão XX)

> Com relação aos princípios de segurança da informação, aspectos como confidencialidade, integridade, disponibilidade, legalidade e a autenticidade são considerados pilares. Sobre estes princípios, é correto afirmar que a: 

a) autenticidade garante que a informação foi produzida em conformidade com a lei.  

b) confidencialidade garante que os dados sejam legítimos, assegurando que não sofram alterações por pessoas não autorizadas.  

c) legalidade garante que os dados tenham completeza e estejam disponíveis permanentemente para acesso quando desejados.  

d) disponibilidade está relacionada à privacidade e ao sigilo das informações, de modo a garantir o acesso apenas para pessoas autorizadas. 

e) integridade garante a completude e exatidão das informações, de modo que sejam preservadas, precisas e confiáveis durante todos os seus ciclos de vida.

**Gabarito:** E  
**Comentário:** De fato, a integridade assegura que os dados permaneçam íntegros, corretos e inalterados por pessoas não autorizadas, preservando sua confiabilidade ao longo de todo o ciclo de vida da informação.

---

### Questão XX)

> De acordo com o Princípio da Disponibilidade, a informação estará disponível
sempre que for preciso. Esse aspecto é de suma importância, principalmente,
para sistemas que não podem ter falhas na disponibilidade, pois essas falhas
comprometem o serviço. Assinale a alternativa que não garante o Princípio da
Disponibilidade:

a) Nobreak.  
b) Firewall.  
c) Backup.  
d) Assinatura Digital.  

**Gabarito:** D  
**Comentário:** A assinatura digital tem haver com a Autenticidade e não com a Disponibilidade.

---

### Questão XX)

> A segurança da informação compreende diversos aspectos ou objetivos, todos relevantes para a manutenção desse tipo de segurança. Portanto, considerando tais aspectos ligados à segurança da informação, é correto afirmar que o aspecto:

a) confidencialidade visa a utilização de mecanismos que não tornem as informações indisponíveis.  

b) integridade visa estabelecer mecanismos que protejam os dados contra acessos indevidos por parte de pessoas ou sistemas.  

c) disponibilidade visa a utilização de mecanismos que protejam os dados de modificações indevidas.   

d) disponibilidade visa a criação de mecanismos de registro de histórico de acessos.  

e) confidencialidade visa proteger as informações contra tentativas de acessos feitas por pessoas ou sistemas não autorizadas.

**Gabarito:** D  
**Comentário:** A assinatura digital tem haver com a Autenticidade e não com a Disponibilidade.

---

### Questão XX)

> A segurança de um sistema de computação pode ser expressa através de algumas propriedades fundamentais. A propriedade em que os recursos presentes no sistema só podem ser consultados por usuários devidamente autorizados para esse fim específico é denominada:  

a) confidencialidade  

b) irretratabilidade  

c) conformidade 

d) autenticidade 

e) integridade

**Gabarito:** A  
**Comentário:** A .

---

### Questão XX)

> Considerando que uma empresa tenha disponibilizado um website na Internet com as informações cadastrais de clientes e as de pagamentos com cartão de crédito de produtos vendidos, nessa situação hipotética, disponibilidade refere-se a pessoa não autorizada conseguir visualizar os dados dos clientes, o que configura violação de integridade. 

( ) Certo   
( ) Errado

**Gabarito:** Errado  
**Comentário:** Essa definição é do princípio da confidencialidade.

## Detalhamento dos Princípios Secundários

Entre os princípios têm-se o **Não Repúdio** (ou **Irretratabilidade**), que garante a impossibilidade de negar a autoria ou a origem de uma informação.  

- A **Irretratabilidade de Origem** assegura que a mensagem foi realmente enviada pelo remetente (autor).  
- A **Irretratabilidade de Destino** comprova que a mensagem foi recebida pelo destinatário.

O princípio da **Identificação** permite que uma entidade se declare e forneça informações sobre sua identidade.

O princípio da **Autenticação** que permite confirmar a identidade da entidade, por meio de diversas ferramentas. Para ser eficaz é usado o multifator ou duplo fator de autenticação (MFA) que exige confirmação secundária de uma outra fonte para confirmar a autenticidade.

O princípio da **Autorização** determina as ações e funcionalidades e permissões que uma entidade pode executar.

O princípio da **Confiabilidade** é a capacidade de cumprir o propósito para qual foi criado, entregar aquilo que promete, mantendo  a constância dos serviços sem interrupções ou falhas.

---

### Questão XX)

> Conforme o cert.br, para permitir que possam ser aplicados na internet cuidados similares aos do dia a dia, é necessário que os serviços disponibilizados e as comunicações realizadas pela internet garantam alguns requisitos básicos de segurança, como: 

a) autenticação, identificação e repúdio.  
b) confidencialidade, identificação e repúdio.  
c) autenticação, confidencialidade e identificação.  
d) autenticação, confidencialidade e repúdio.

**Gabarito:** C  
**Comentário:** O CERT é um órgão do Governo Federal que dissemina conceitos de Segurança da Informação. O correto  seria não repúdio e não apenas repúdio.

---

### Questão XX)

> Os serviços de segurança de uma empresa são implementados por mecanismos de segurança e visam a satisfazer os requisitos da política de segurança dessa empresa. Para aprimorar o serviço de segurança que controla o acesso aos sistemas de informação, o controle de autenticação em uma etapa de verificação está sendo substituído pelo controle de autenticação em mais de uma etapa de verificação. Esse controle em mais de uma etapa de verificação é conhecido como autenticação: 

a) complexa  
b) resistente  
c) qualificada  
d) estendida  
e) multifator

**Gabarito:** E   
**Comentário:** O mecanismo descrito se enquadra com a definição de Multifator, MFA ou ainda Duplo Fator de Autenticação.

---

### Questão XX)

> Sobre segurança da informação, é um princípio que garante que alguém não pode negar algo. Tipicamente, esse princípio se refere à habilidade em assegurar que uma parte de um contrato, ou de uma comunicação, não pode negar a autenticidade de sua assinatura em um documento ou o envio de uma mensagem que originou. Trata-se de qual princípio: 

a) Confidencialidade.  
b) Integridade.  
c) Legalidade.  
d) Não repúdio.  
e) Autenticidade. 

**Gabarito:** D   
**Comentário:** Essa definição retrata o conceito de Não Repúdio.

---

### Questão XX)

> Lucas é um trader profissional que trabalha em uma corretora de valores. Ele efetua muitas operações durante o período em que a bolsa negocia seus ativos. Após fazer uma revisão em suas operações do dia, não validou, como sendo efetuadas por ele, algumas das operações que obtiveram prejuízo. Lucas, então, entrou em contato com a corretora e esta demonstrou, a partir de registros de auditoria e garantia de identidade, que as operações em questão realmente foram executadas por ele. Para que a corretora prove que foi Lucas quem realmente executou as operações, ela deve fazer uso do conceito de segurança chamado:  

a) confidencialidade;  
b) autenticidade;  
c) integridade;  
d) disponibilidade;  
e) irretratabilidade.

**Gabarito:** B   
**Comentário:** Esse princípio de segurança garante que os registros ou informações realmente pertencem à pessoa que afirma tê-los gerado. No caso, a corretora usa mecanismos de autenticação e auditoria para comprovar que as operações foram de fato executadas por Lucas, evitando dúvidas ou fraudes sobre a autoria das ações.

---

### Questão XX)

> Irretratabilidade é o mecanismo de segurança que prova que a mensagem foi enviada pela origem especificada e que foi recebida pelo destino especificado. 

( ) Certo ( ) Errado

**Gabarito:** Certo  
**Comentário:** A irretratabilidade, também chamada de não repúdio, garante que o remetente não possa negar ter enviado a mensagem e que o destinatário não possa negar tê-la recebido. Ou seja, ela assegura tanto a autoria quanto o recebimento da informação.

## Ameaças Gerais

Ameaças são eventos, ações ou condições externas que podem comprometer a confidencialidade, integridade ou disponibilidade das informações. Exemplos: malware, phishing, ataques DDoS, acesso não autorizado, falhas físicas e erros humanos.

Vulnerabilidades são fragilidades em pessoas, processos ou sistemas que permitem que uma ameaça seja bem‑sucedida <sup>(por exemplo, software desatualizado, configuração incorreta, falta de treinamento)</sup>.

Risco é a combinação da probabilidade de uma ameaça explorar uma vulnerabilidade e do impacto resultante.  

Incidente é a materialização do risco <sup>(um ataque bem‑sucedido ou falha operacional)</sup> e dano é a consequência negativa desse incidente <sup>(perda de dados, indisponibilidade, prejuízo financeiro ou reputacional)</sup>.

O dado é o resultado negativo de um incidente de segurança que compromete todos o ativo de sistemas.

Medidas básicas de mitigação: identificação e avaliação de ativos e vulnerabilidades, aplicação de controles <sup>(prevenção, detecção e correção)</sup>, planos de resposta a incidentes e monitoramento contínuo.

---

### Questão XX)

> Vulnerabilidade é o grau de suscetibilidade de um objeto a uma ameaça?

|Gabarito|Comentário|
|---|---|
|Certo|De fato se trata da exposição a uma ameaça.|

### Ameaças Especializadas

Os Hackers são indivíduos com habilidades cibernéticas em programação e segurança digital, com capacidade de invadir dispositivos eletrônicos , sistemas e redes. Geralmente busca exibir seu potencial, exmplorar curiosidades de pessoas ou intelectuais, promovendo manifestações ideológicas que são HACTIVISTAS, WHITE HACKS & ANONYMOUS.

Os Crackers são individuos com as mesmas habilidades dos Hackers, mas visando o crime cibernético como fraudes, roubos, furtos digitais, vandalismos entre outras atividades criminosas.

Os SPAM são mensagens eletrônicas não solicitadas enviada em massa. Geralmente com links maliciosos para a prática de _Phishing_ (pesca).

---

### Questão XX)

> Mensagem eletrônica que chega ao usuário sem a sua permissão ou sem seu desejo de recebê-la. Geralmente é recebida por e-mail, mas também pode circular pelas redes sociais ou comentários de blogs. É enviada para uma quantidade muito grande de pessoas e tem um fundo geralmente comercial, mas também pode assumir um viés criminoso. Que tipo de mensagem é essa? 

a) Malware.  
b) Phishing.  
c) Spam.  
d) Spyware.  
e) Vírus.

|Gabarito|Comentário|
|---|---|
|Letra C|Essa é a definição do Spam.|

### Engenharia Social

A Engenharia Social é uma forma de ameaça se aproveiando da vulnerabilidade (fraqueza) humana. Utiliza técnicas de persuasão para se conectar a vítima onde o atacante manipula e engana a vítima.

---

### Questão XX)

> A engenharia social é o ataque mais difícil de ser identificado, logo não há como preveni-lo?

|Gabarito|Comentário|
|---|---|
|Errado|A engenharia social pode ser previnida não confiando em mensagens sem verificação de autenticiade.|

### Cookies

São arquivos de texto que guardam informações