# Contexto do caso – T1 Engenharia de Requisitos

> Regra deste arquivo: tudo aqui foi dito pelo cliente na entrevista, ou está marcado como PENDÊNCIA.
> Nada aqui é suposição do grupo ou da IA. Quem ler (agentes inclusive) não deve inventar além disso.

## 1. O caso
- **Cliente:** AzLink, assessoria de importação.
- **O que faz:** inspeciona o produto e ajuda o cliente a importar (encontrar fornecedor, envio, curadoria dos materiais).
- **Sistema a ser desenvolvido:** NeoAtlas. O objetivo final é substituir a AzLink pela NeoAtlas.
- **Objetivo do sistema:** criar um sistema único que elimine o caderninho e unifique as anotações sobre fornecedores.

## 2. Informações confirmadas pelo cliente

### Negócio
- Fornecedores são da China (deu a entender que é apenas a China).
- Exemplo de produto citado: cadeira.
- Fornecedores são descobertos principalmente em feiras, mas não é necessário ir presencialmente.
- A fábrica não entra em contato com o cliente.
- Idioma com fornecedores: geralmente inglês.

### Modelo de negócio
- O sistema será vendido como SaaS: o cliente paga mensalidade.
- A empresa fica com uma porcentagem do que o cliente compra.
- O sistema de pagamento deve estar dentro do aplicativo.

### Situação atual (como funciona hoje)
- Dados ficam dispersos: caderninho, cabeça do dono, computador dele, e-mails e um servidor com uma pasta por fornecedor.
- Catalogação: lista de produtos (ex.: cadeira) com os fornecedores dentro de cada um.
- Comunicação: telefone, e-mail, WeChat e, em alguns casos, WhatsApp.
- Existe um banco de dados de fornecedores compartilhado com os clientes (usuários do aplicativo).
- O fornecedor envia o catálogo em um arquivo zip.

### Regras e restrições
- Existe hierarquia de acesso: alguns dados sensíveis só podem ser vistos por certas pessoas.
- LGPD deve ser considerada: dados pessoais não podem ser vistos por outros usuários.
- Capacidade esperada: cerca de 50.000 usuários.

## 3. Pendências (o cliente não respondeu com clareza)
- Perfil dos clientes da AzLink.
- Demais produtos além da cadeira.
- Quantas pessoas vão às feiras e quantas feiras por ano.
- O que querem descobrir ou conseguir no estande do fornecedor.
- Quem usa cada informação depois da feira e para quê.
- Como escolhem entre vários fornecedores do mesmo produto.
- Quem registra os dados e em que momento (estande, hotel, escritório).
- Internet no local da feira e tempo disponível por contato.
- Critério de sucesso: como saber que o problema foi resolvido.
- Nenhum caso concreto de problema no registro foi relatado.
- Quais papéis existem na hierarquia de acesso e quem vê o quê.

## 4. Interpretações do grupo (preencher depois)
- (nada ainda)
