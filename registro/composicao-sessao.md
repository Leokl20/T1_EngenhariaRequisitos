# Composição da sessão de elicitação

## 1. Composição inicial (proposta do BMAD)
| Participante / persona | Papel no sistema | Interesses relacionados ao NeoAtlas | Contribuição esperada |
|---|---|---|---|
| **Dono ou gestor da AzLink** | Patrocinador e responsável pelo negócio | Substituir os controles dispersos, acompanhar fornecedores, aumentar a escala do negócio e controlar a receita SaaS e as comissões | Explicar objetivos estratégicos, prioridades, regras comerciais, critérios de sucesso e decisões de negócio |
| **Especialista em importação da AzLink** | Usuário operacional que pesquisa fornecedores e acompanha importações | Registrar informações completas e confiáveis sobre fornecedores, produtos, catálogos e negociações | Descrever o processo atual, dificuldades do caderninho, dados necessários e fluxo de avaliação dos fornecedores |
| **Pessoa responsável por visitar feiras** | Coletor de informações em feiras e eventos | Registrar dados rapidamente, mesmo em condições de pouco tempo ou internet instável | Detalhar o que é observado no estande, quais dados são coletados, quando o registro ocorre e quais informações são mais importantes |
| **Analista ou curador de fornecedores** | Organizador e avaliador dos fornecedores cadastrados | Comparar fornecedores de um mesmo produto, manter dados atualizados e identificar opções adequadas | Definir critérios de qualidade, classificação, comparação, aprovação e atualização dos fornecedores |
| **Cliente comprador da AzLink** | Usuário que procura produtos e fornecedores para realizar uma importação | Encontrar fornecedores confiáveis, consultar catálogos, comparar opções e iniciar uma compra com segurança | Informar necessidades, expectativas, dificuldades de uso, dados que considera sensíveis e critérios para escolher um fornecedor |
| **Administrador de empresa cliente** | Responsável por gerenciar usuários de uma organização cliente | Controlar os acessos da sua equipe e proteger informações comerciais | Ajudar a definir papéis, permissões, compartilhamento interno e separação entre dados da empresa e dados de outros clientes |
| **Usuário cliente com acesso restrito** | Funcionário ou colaborador que consulta apenas parte dos dados | Acessar as informações necessárias ao seu trabalho sem visualizar dados sensíveis indevidamente | Validar se a hierarquia de acesso é compreensível e suficiente para as atividades reais |
| **Fornecedor chinês** | Fonte dos dados de produtos, catálogos, preços e condições comerciais | Apresentar seus produtos, receber solicitações e manter comunicação com a AzLink ou com clientes autorizados | Esclarecer quais informações fornece, como envia catálogos ZIP, quais canais utiliza e quais dados podem ser compartilhados |
| **Responsável financeiro/comercial** | Administra pagamentos, mensalidades e comissões | Garantir cobrança recorrente, registro das compras, cálculo das porcentagens e rastreabilidade financeira | Definir regras de pagamento, faturamento, comissão, cancelamento, inadimplência e conciliação |
| **Administrador da plataforma / suporte** | Opera o sistema e atende usuários | Manter cadastros, resolver problemas, controlar contas e investigar ocorrências | Especificar rotinas administrativas, suporte, auditoria, recuperação de acesso e tratamento de erros |
| **Responsável por segurança e LGPD** | Define e verifica proteção de dados | Impedir exposição de dados pessoais e comerciais, garantir rastreabilidade e atender direitos dos titulares | Identificar dados pessoais e sensíveis, definir permissões, retenção, consentimento, auditoria e respostas a incidentes |
| **Responsável técnico ou arquiteto** | Avalia viabilidade e restrições da solução | Garantir escalabilidade para cerca de 50.000 usuários, integração com pagamentos, armazenamento de catálogos e disponibilidade | Transformar necessidades em restrições técnicas, levantar integrações, riscos, requisitos de desempenho e segurança |

## 2. Questionamentos do grupo ao BMAD
Por que você propôs 12 participantes e não incluiu nenhum agente do BMAD? Quais são essenciais e quais são opcionais?

<details>
<summary>Resposta completa do BMAD</summary>
A proposta de 12 participantes foi ampla demais para a etapa de elicitação inicial. Ela tentou representar todos os possíveis interesses do NeoAtlas — negócio, operação, clientes, fornecedores, financeiro, segurança e tecnologia — mas isso não significa que todos sejam necessários ao mesmo tempo, nem que todos tenham sido confirmados pelo cliente.

Também não incluí agentes do BMAD porque eles não são participantes reais do negócio. Eles podem atuar como facilitadores, analistas ou revisores das informações coletadas, mas não devem ser tratados como fonte de requisitos do cliente. Incluir um agente do BMAD como se fosse usuário ou stakeholder poderia misturar interpretação do grupo com declaração do cliente.

## Participantes essenciais para a elicitação

Estes são os participantes que deveriam ser priorizados para esclarecer as principais lacunas identificadas na entrevista:

| Participante | Por que é essencial |
|---|---|
| **Dono ou gestor da AzLink** | Pode confirmar objetivos, prioridades, modelo SaaS, porcentagem sobre compras, regras comerciais e o que significa substituir a AzLink pelo NeoAtlas. |
| **Pessoa que registra ou organiza informações de fornecedores** | É necessária para entender quem registra os dados, quais dados são coletados, quando o registro ocorre e como o problema da dispersão acontece na prática. Essa função ainda não foi claramente identificada na entrevista. |
| **Pessoa que pesquisa ou avalia fornecedores** | Pode esclarecer como os fornecedores são encontrados, como são comparados e como se escolhe entre vários fornecedores do mesmo produto. |
| **Cliente comprador da AzLink** | É necessário para entender quem usa o banco de fornecedores compartilhado, quais informações consulta e quais necessidades o NeoAtlas deve atender. O perfil dos clientes ainda está pendente. |
| **Responsável por acesso e proteção de dados** | Pode esclarecer a hierarquia de acesso, os papéis, os dados sensíveis e a aplicação prática da LGPD. A entrevista confirmou que essas regras existem, mas não detalhou como funcionam. |

A pessoa que pesquisa, avalia ou registra fornecedores pode ser a mesma pessoa. Esses papéis foram separados na tabela apenas para garantir que todas as responsabilidades sejam investigadas; não há evidência de que sejam pessoas diferentes.

## Participantes opcionais ou necessários em etapas posteriores

| Participante | Motivo para ser opcional neste momento |
|---|---|
| **Pessoa responsável por visitar feiras** | Torna-se importante se o sistema precisar apoiar o registro durante a feira. Como as feiras são o principal meio de descoberta, ela pode ser priorizada depois, mas ainda não há confirmação sobre quantidade de pessoas, tempo disponível ou condições de internet. |
| **Fornecedor chinês** | Pode esclarecer o formato dos catálogos, dados dos produtos, canais de comunicação e eventual interação com o sistema. Porém, não é indispensável para a primeira rodada com a AzLink. |
| **Responsável financeiro/comercial** | É importante para detalhar mensalidade, porcentagem sobre compras, pagamentos, cancelamentos e conciliação. O cliente confirmou a existência desses elementos, mas não explicou suas regras. |
| **Administrador de empresa cliente** | Só é necessário se os clientes forem organizações com vários usuários e se houver administração de acessos por empresa. Isso não foi confirmado na entrevista. |
| **Usuário cliente com acesso restrito** | Pode validar os níveis de permissão depois que os papéis e regras de acesso forem definidos. |
| **Administrador da plataforma/suporte** | É relevante para operação, recuperação de acesso, suporte e tratamento de ocorrências, mas esses temas não foram explorados na entrevista. |
| **Responsável técnico ou arquiteto** | Pode transformar os requisitos em restrições de capacidade, armazenamento, pagamento e integração. A capacidade de aproximadamente 50.000 usuários foi confirmada, mas a elicitação inicial deve primeiro esclarecer a necessidade de negócio. |
| **Responsável específico por segurança e LGPD** | Pode ser consultado em uma etapa de validação e conformidade. Para a primeira entrevista, o responsável por acessos e dados da AzLink já pode esclarecer as regras de negócio conhecidas. |

## Composição recomendada

Para uma próxima sessão de elicitação, eu reduziria a composição para:

1. Dono ou gestor da AzLink;
2. Pessoa que registra ou organiza fornecedores;
3. Pessoa que pesquisa ou avalia fornecedores;
4. Cliente comprador da AzLink;
5. Responsável por acesso e proteção de dados;
6. Pessoa de feiras, caso o foco inclua o registro durante eventos.

Os demais participantes podem ser chamados conforme o tema específico. Assim, a sessão fica menor, evita discussões especulativas e concentra-se exatamente nas pendências registradas em `contexto.md` e `Entrevista.md`.

</details>





## 3. Alterações feitas pelo grupo

    Participantes que ficaram: 
**Dono ou gestor da AzLink** 
   O representante da AzLink citou que as informações ficam “na cabeça do dono” e no computador dele, e confirmou o modelo SaaS, a porcentagem sobre as compras e o objetivo de substituir a AzLink. Alguém precisa esclarecer essas regras.

**Pessoa que registra ou organiza informações de fornecedores**(HIPOTESE)
    O cliente não disse quem registra os dados nem quando (pendência). O grupo mantém para investigar quais informações são guardadas e em que padrão.

**Pessoa que pesquisa ou avalia fornecedores** (HIPOTESE)
    Como o cliente escolhe entre vários fornecedores do mesmo produto não foi respondido (pendência). Este participante ajuda a explorar essa comparação.
  
**Cliente comprador da AzLink** (HIPOTESE)
O representante disse que existe um banco de fornecedores compartilhado com os clientes, mas o perfil deles ficou pendente. Esta persona só gera hipóteses sobre o que eles precisam consultar, não mede aceitação real.

**Responsável por acesso e proteção de dados**
   O cliente confirmou a hierarquia de acesso e a LGPD, mas não disse quais papéis existem nem quem vê o quê.


    Participantes que sairam:

**Especialista em importação**
	Sobrepõe-se a quem registra e a quem avalia fornecedores.


**Analista/curador de fornecedores** (UNIFICADO)
    Unificado em “Pessoa que pesquisa ou avalia fornecedores”.

**Responsável por segurança e LGPD**(UNIFICADO)
    Unificado em “Responsável por acesso e proteção de dados”.


**Pessoa responsável por visitar feiras**
    As feiras são o principal meio de descoberta, mas quem vai e em que condições ficou pendente. O grupo prefere esclarecer isso com quem registra os dados. Pode voltar numa rodada futura.


**Responsável financeiro/comercial**
    O cliente confirmou mensalidade, porcentagem sobre as compras e pagamento no app, mas não explicou as regras. Fica como lacuna a validar com ele, e não precisa de uma persona agora.

**Administrador de empresa cliente**
    Pressupõe clientes com vários usuários e papéis, o que o cliente não disse.

**Usuário cliente com acesso restrito**
    Mesma razão: os papéis de acesso ainda não foram definidos.

**Aministrador da plataforma/suporte**
    O cliente não falou de suporte nem de operação do sistema.

**Responsável técnico ou arquiteto**
    A elicitação é de requisitos. A capacidade de 50.000 usuários fica registrada como restrição.

**Fornecedor chinês**
O cliente disse que a fábrica não entra em contato com o cliente, e ele não é usuário do sistema.

## 4. Composição final

Agentes BMAD: a definir.

Personas (stakeholders simulados):

Dono ou gestor da AzLink
Pessoa que registra ou organiza informações de fornecedores (hipótese)
Pessoa que pesquisa ou avalia fornecedores (hipótese)
Cliente comprador da AzLink (hipótese)
Responsável por acesso e proteção de dados

## 5. Justificativa geral
    A composição foi filtrada a partir dos iniciais 12 participantes feitos pelo bmad. E a partir deste ponto inicial, o própio bmad assumiu que eram muitos participantes e nosso grupo chegou a conclusão de escolher estas personas. Cada um se liga a pendencia do cliente. Os demais foram exluidos e/ou unificados por falta de informação ou que dependiam de suposições não confirmadas pelo representante da AzLink, As personas marcadas como hipótese serão tratadas como hipóteses ou premissas nos artefatos. Como não há previsão de novo contato com o representante da AzLink, ficam registradas como pendências de validação.