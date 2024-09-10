# Suítes de Teste

---

## **1. Suíte Animação ao abrir o site**

### **Tipo de Teste**

**Teste de interface de usuário (UI)**

### **User Story**

**US 1: Animação ao abrir o site**

- Como uma pessoa usuária(o)
- Gostaria de quando eu acessa o site Lacrei ver o carregamento da página com a animação
- Porque quero ver a página carregando com a animação na palavra "LS Lacrei Saúde" de forma iterativa e aguardar até que a página carregue completamente

### **Pré-condição**

**O usuário acessa o link:** [](https://paciente-staging.lacreisaude.com.br/)https://paciente-staging.lacreisaude.com.br/ **do site pelo dispositivo mobile, com uma conexão estável.**

### Dados necessários:

Não possui

---

### **ID: 1**

### Título:

Verifica animação e cores

### **Caso de Teste:**

- DADO que eu acesse o link: [https://paciente-staging.lacreisaude.com.br/](https://paciente-staging.lacreisaude.com.br/)
- QUANDO a página iniciar o carregamento

### **Resultado Esperado:**

- ENTÃO durante a animação, uma palavra por vez será preenchida com a cor de referência Rgb (0, 119, 86) #FFFFFF
- E deve exibir a mensagem "Carregando”
- E : "Estamos quase lá”

### **Prioridade**

Alta

### **Severidade**

Alta

### **Cobertura**

Verificar o comportamento visual da animação da palavra "LS Lacrei Saúde" ao carregar a página.

### **Resultado Obtido**

A palavra "LS Lacrei Saúde" inicia com a cor de fonte e durante a animação, a palavra é preenchida e exibe as mensagens

### **Defeitos:**

Não possui

### **Status**

Passou

---

## **2. Suíte Cadastro da pessoa usuária**

### **Tipo de Teste**

**Teste funcional**

### **User Story**

US 2: **Cadastro da pessoa usuária(o)**

- Como uma pessoa usuária(o)
- Gostaria de realizar o meu cadastro na Lacrei Saúde
- Porque quero ter experiência no acesso à profissionais da saúde

### **Pré-condição:**

Não possui.

### Dados necessários:

Nome civil ou social: Teste

Sobrenome: Qualidade

E-mail: [kintuillang6927@uorak.com](mailto:kintuillang6927@uorak.com)

Senha: r41MaR22*

---

### **ID: 2**

### **Título:**

**Cadastro bem-sucedido com todos os campos preenchidos corretamente**

### **Caso de Teste:**

- DADO que me encontro em cadastro do sistema Lacrei
- QUANDO eu preencher todos os campos obrigatórios com dados válidos
- E selecionar todas as caixas de marcação obrigatórias,
- E clicar no botão de criar conta

### **Resultado Esperado:**

- ENTÃO o sistema retorna com o link de verificação
- E confirmo em meu e-mail
- E o cadastro é bem sucedido

### **Prioridade: Alta**

### **Severidade: Alta**

### **Cobertura:**

Formulário de cadastro de usuário

### **Resultado Obtido:**

O cadastro de usuário foi bem sucedido e o e-mail de confirmação foi recebido corretamente.

### **Defeitos:**

Não possui

### **Status:**

Passou

---

### **ID: 3**

### Título:

 Cadastro com senha inválida

### **Caso de Teste:**

- DADO que me encontro em cadastro do sistema Lacrei
- QUANDO eu preencher todos os campos obrigatórios com dados válidos
- E inserir nos campos de senha (ex: senha com menos de 8 caracteres)
- E clicar no botão de criar conta

### **Resultado Esperado:**

- ENTÃO o sistema deve exibir uma mensagem: “A senha deve ter no mínimo 8 caracteres”

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Valida se o sistema verifica corretamente quando o usuário tenta cadastrar-se utilizando uma senha com menos de 8 caracteres.

### **Resultado Obtido:**

O sistema exibe a mensagem indicando que a senha contém menos de 8 caracteres.

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

### ID: 4

### Título:

Cadastro sem preencher campos obrigatórios

### **Caso de Teste:**

- DADO que me encontro em cadastro do sistema Lacrei
- QUANDO eu deixar todos os campos obrigatórios vazios
- E deixar as caixas de seleção obrigatórias sem marcação
- E clicar no botão de criar conta

### **Resultado Esperado:**

- ENTÃO o sistema deve exibir mensagens de erro ao lado dos campos que estão em branco
- E deve exibir as mensagens de erro abaixo das caixas obrigatórias de seleção

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o sistema valida corretamente caso o usuário deixe os campos vazios.

### **Resultado Obtido:**

As mensagens de validação de erro são exibidas corretamente.

### **Defeitos:**

Não possui

### **Status:**

Passou

---

### ID: 5

### Título:

Cadastro com e-mail inválido

### **Caso de Teste:**

- DADO que me encontro em cadastro do sistema Lacrei
- QUANDO eu inserir em todos os campos obrigatórios dados válidos
- MAS inserir um endereço de e-mail inválido: usuário@invalido

### **Resultado Esperado:**

- ENTÃO o sistema deve exibir uma mensagem de erro informando que o e-mail não é válido

### **Prioridade:**

Alta

### **Severidade:**

Média

### **Cobertura:**

Verifica se a a validação de e-mail está correta quanto ao formato de e-mail inserido.

### **Resultado Obtido:**

O sistema retorna: “Insira um e-mail inválido.”

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

### Tipo de Teste: Teste de acessibilidade (Pertence a Suíte de cadastro)

### **Tipo de Teste**

**Teste de acessibilidade**

### **User Story**

**US 3: VLibras em cadastro da pessoa usuária(o)**

- Como uma pessoa usuária
- Gostaria de ter a opção poder visualizar o conteúdo da plataforma em Libras
- Porque quero compreender as informações e interagir com a plataforma de forma acessível e inclusiva

### **Pré-condição:**

Não possui.

### Dados necessários:

Não possui.

---

### ID: 6

### Título:

Usuário acessa a ferramenta VLibras durante o cadastro

### **Caso de Teste:**

- DADO que eu esteja na página de cadastro do sistema Lacrei
- E o botão VLibras está visível na interface
- QUANDO eu clico no botão VLibras

### **Resultado Esperado:**

- ENTÃO eu devo ver o conteúdo da plataforma traduzido para Libras
E eu devo ser capaz de compreender as informações do sistema através da tradução em Libras

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o sistema está com a acessibilidade corretamente através da ferramenta VLibras.

### **Resultado Obtido:**

O usuário consegue traduzir para libras através da ferramenta Vlibras e é capaz de compreender as informações traduzidas corretamente.

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

## **3. Suíte de Boas vindas | Pós cadastro**

### **Tipo de Teste**

**Teste Funcional**

### **User Story**

US 4: **Boas vindas | Pós cadastro**

- Como uma pessoa usuária
- Gostaria de quando eu logar no sistema pela primeira vez
- Porque quero ter a experiência personalizada na Lacrei

### **Pré-condição:**

- Ser um usuário cadastrado no sistema
- Possuir uma senha
- Logar pela primeira vez

### Dados necessários:

- e-mail: [hallouma5972@uorak.com](mailto:hallouma5972@uorak.com)
- senha: r41MaR22*

---

### ID: 7

### Título:

Preenchimento válido e correto das perguntas

### **Caso de Teste:**

- DADO que eu sou uma pessoa usuária logada no sistema Lacrei pela primeira vez
- E eu estou na tela de personalização com perguntas sobre Pronome, Etnia, Gênero, Sexualidade e Deficiência
- QUANDO eu preencho todas as perguntas e clico em "Próximo" ou "Concluir"

### **Resultado Esperado:**

- ENTÃO eu devo ser direcionado para a página inicial do sistema de busca

### **Prioridade:**

Alta

### **Severidade:**

Média

### **Cobertura:**

Valida e verifica se os campos de boas vindas na personalização são preenchidos corretamente.

### **Resultado Obtido:**

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

### ID: 8

### Título:

Validação de mensagens de erro ao não preencher todas as perguntas

### **Caso de Teste:**

- DADO que eu sou uma pessoa usuária logada no sistema Lacrei pela primeira vez
- E eu estou na tela de personalização com perguntas sobre Pronome, Etnia, Gênero, Sexualidade e Deficiência
- QUANDO eu não preencho a primeira pergunta
- E clico em "Próximo

### **Resultado Esperado:**

- ENTÃO eu devo ver uma mensagem de erro informando "Existem opções que não foram selecionadas. Por favor, verifique”

### **Prioridade:**

Alta

### **Severidade:**

Média

### **Cobertura:**

Verifica se o usuário prossegue para a próxima pergunta sem marcar a opção na pergunta, pois todas as perguntas são obrigatórias.

### **Resultado Obtido:**

A mensagem de erro é exibida e o usuário não passa para a próxima pergunta sem antes respondê-la.

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

## **4. Suíte Login de pessoa usuária**

### **Tipo de Teste:**

**Teste funcional**

### **User Story**

US 4: Login de pessoa usuária

- Como uma pessoa usuária
- Gostaria gostaria de fazer login no sistema
- Porque quero ter acesso a todas as funções que o sistema Lacrei pode me proporcionar

US 4: Responsividade 

- Como uma pessoa usuária
- Gostaria que a página seja responsiva
- Porque quero que se adapte a diferentes tipos de dispositivos móveis
- E o layout deve ser flexível

### **Pré-condição:**

- Ser um usuário cadastrado
- Possuir uma senha válida

### Dados necessários:

E-mail: [kintuillang6927@uorak.com](mailto:kintuillang6927@uorak.com)

Senha: r41MaR22*

---

### **ID: 9**

### **Título:**

**Autenticação bem-sucedida com credenciais válidas**

### **Caso de Teste:**

- DADO que me encontro em login do sistema Lacrei
- QUANDO eu inserir no campo e-mail, um e-mail válido
- E no campo de senha, uma senha válida
- E clicar no botão de entrar

### **Resultado Esperado:**

- ENTÃO devo ser autenticado com sucesso
E devo ser redirecionado para a página de boas-vindas do sistema

### **Prioridade: Alta**

### **Severidade: Alta**

### **Cobertura:**

Cobre a autenticação válida do login bem sucedido.

### **Resultado Obtido:**

O usuário realiza o login corretamente e é direcionado para boas vindas na tela principal do sistema Lacrei.

### **Defeitos:**

Não possui

### **Status:**

Passou

---

### ID: 10

### Título:

Tentativa de login com e-mail inválido

### **Caso de Teste:**

- DADO que me encontro em login do sistema Lacrei
- QUANDO eu inserir um e-mail inválido: teste@teste
- E a senha válida: r41MaR22*
- E clicar no botão de entrar

### **Resultado Esperado:**

- ENTÃO o sistema deve exibir a mensagem: "Por favor. Utilize um formato de e-mail válido. Por exemplo: email@dominio.com.br

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Tentativa de login com e-mail inválido no sistema.

### **Resultado Obtido:**

O sistema exibe corretamente a mensagem: "Por favor. Utilize um formato de e-mail válido. Por exemplo: email@dominio.com.br

### **Defeitos:**

Não possui

### **Status:**

Passou.

---

### ID: 11

### Título:

Tentativa de login com senha inválida

### **Caso de Teste:**

- DADO que me encontro em login do sistema Lacrei
- QUANDO eu inserir um e-mail válido:

[kintuillang6927@uorak.com](mailto:kintuillang6927@uorak.com)

- MAS inserir a senha inválida: “senhaerrada”
- E clicar no botão de entrar

### **Resultado Esperado:**

- ENTÃO o sistema deve exibir a mensagem "E-mail ou senha incorretos. Esqueceu a sua senha? Clique em Esqueci minha senha para recuperá-la.”

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Tentativa de login com e-mail inválido ou com senha inválida no sistema.

### **Resultado Obtido:**

O sistema exibe a mensagem corretamente, sendo a mensagem "E-mail ou senha incorretos. Esqueceu a sua senha? Clique em Esqueci minha senha para recuperá-la.”

### **Defeitos:**

Não possui

### **Status:**

Passou.

---

### ID: 12

### Título:

Campos obrigatórios vazios

### **Caso de Teste:**

- DADO que me encontro em login do sistema Lacrei
- QUANDO eu deixo todos os campos obrigatórios vazios
- E clico no botão de entrar

### **Resultado Esperado:**

- ENTÃO o sistema retorna abaixo de e-mail que o campo é obrigatório,
- E do campo de senha que é obrigatório

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Tentativa de usuário prosseguir sem preencher os campos requeridos, sendo de : e-mail e senha.

### **Resultado Obtido:**

O sistema retorna abaixo dos campos de e-mail e de senha que são obrigatórios para o preenchimento.

### **Defeitos:**

Não possui

### **Status:**

Passou.

---

### ID: 13

### Título:

Responsividade na página de Login do sistema Lacrei 

### **Caso de Teste:**

- DADO que eu estou acessando o sistema Lacrei em um dispositivo mobile
- QUANDO eu navego até a página de login

### **Resultado Esperado:**

- ENTÃO o layout da página deve se ajustar corretamente sendo flexível
- E os botões devem estar posicionados corretamente

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se a página se adapta com responsividade, se o layout é flexível e os botões estão posicionados corretamente.

### **Resultado Obtido:**

Em ambos os dispositivos, ao clicar para entrar no sistema com os campos vazios, os elementos de erros são exibidos sem flexibilidade e responsividade na página, no dispositivo de número 1 listado em evidência exibe os botões de “Entrar” e de “Criar Conta”, dispostos próximos um do outro sem uma distância adequada, a página com os elementos e  os botões não seguem padrões de responsividade.

### **Defeitos:**

Evidência de Identificador de número 13, sendo: “id-13-primeiro-device” e “id-13-segundo-device”, o mesmo nome é válido para evidência em screenshot e vídeo, listado nos registros da pasta de evidências.

### **Status:**

Falhou.

---

## 5. Suíte Reset de senha

### **Tipo de Teste**

**Teste funcional**

### **User Story**

US 12: Reset de senha

Como uma pessoa usuária
Gostaria de solicitar redefinição de senha
Porque esqueci a minha senha anterior

### **Protótipo:**

### **Pré-condição:**

- Ter um usuário cadastrado
- Ter uma senha cadastrada

### Dados necessários:

E-mail: [qualidade@uorak.com](mailto:kintuillang6927@uorak.com)

Senha: r41MaR22*

---

### **ID: 14**

### Título:

Alteração de senha com sucesso

### **Caso de Teste:**

- DADO que estou na página de login
- E esqueci a minha senha
- QUANDO eu clicar no botão de esqueci a minha senha
- E inserir no campo obrigatório o e-mail cadastrado válido
- E clicar no botão de enviar link

### **Resultado Esperado:**

- ENTÃO sou direcionado para a página onde é exibida uma mensagem de verifique o e-mail para redefinir a senha
- E verifico o meu e-mail
- E insiro no campo obrigatório a nova senha
- E insiro a nova senha no campo de nova senha
- E clico no botão de redefinir senha
- E o sistema retorna que a senha foi alterada com sucesso

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o usuário consegue solicitar a alteração de senha.

### **Resultado Obtido:**

O usuário é direcionado para a página onde é exibida a mensagem de que “Verifique o e-mail para redefinir a senha.”

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 15

### Título:

Solicitar redefinição de senha com e-mail inválido

### **Caso de Teste:**

- DADO que estou na página de login
- E esqueci a minha senha
- QUANDO eu clicar no botão de esqueci a minha senha
- E inserir no campo obrigatório um e-mail inválido: teste.com
- E clicar no botão de enviar link

### **Resultado Esperado:**

- ENTÃO uma mensagem é exibida: “Por favor, utilize um formato de e-mail válido. Por exemplo: email@dominio.com.br

### **Prioridade:**

Média

### **Severidade:**

Média

### **Cobertura:**

Verifica o formato de entrada de e-mail no campo de e-mail.

### **Resultado Obtido:**

Uma mensagem é exibida: “Por favor, utilize um formato de e-mail válidp. Por exemplo: email@dominio.com.br

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 16

### Título:

Usuário deseja voltar para a tela de login

### **Caso de Teste:**

- DADO que estou na página de login
- E esqueci a minha senha
- QUANDO eu clicar no botão de esqueci a minha senha
- MAS optar por voltar
- E clicar no botão de voltar

### **Resultado Esperado:**

- Então devo ser redirecionado para a tela inicial de login

### **Prioridade:**

Média

### **Severidade:**

Média

### **Cobertura:**

Verifica se o usuário consegue retornar para a página de login do sistema.

### **Resultado Obtido:**

O usuário é direcionado para a seção de login.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 17

### Título:

Reenviar link de redefinição de senha

### **Caso de Teste:**

- DADO que me encontro página "Esqueci minha senha"
- E eu já solicitei o envio do link de redefinição
- QUANDO eu clicar no botão "Reenviar"
- E inserir o e-mail válido no campo obrigatório
- E clicar no botão de enviar link

### **Resultado Esperado:**

- ENTÃO sou direcionado para a página onde é exibida uma mensagem de verifique o e-mail para redefinir a senha

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o reenvio 

### **Resultado Obtido:**

O usuário é direcionado para a página onde é exibida uma mensagem de verifique o e-mail para redefinir a senha

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

## **6. Suíte Buscar por uma pessoa profissional**

### **Tipo de Teste**

**Teste funcional**

### **User Story**

US 6: **Buscar por uma pessoa profissional**

- Como uma pessoa usuária
- Gostaria de buscar um(a) profissional
- Porque quero ser direcionado(a) para a lista de profissionais cadastrados e contatar o(a) profissional

- Como uma pessoa administradora do sistema
- Gostaria de garantir que a página de cadastro seja carregada rapidamente
- Porque quero proporcionar uma boa experiência para os usuários

### **Pré-condição:**

- Ter um usuário cadastrado
- Ter uma senha cadastrada

### Dados necessários:

Inserção de dado na caixa de pesquisa: odontologia

---

### ID: 18

### Título:

Exibição de resultados de busca com filtros

### **Caso de Teste:**

- Dado que estou na tela de busca de profissionais
- QUANDO  eu insiro os filtros desejados, exemplo: Odontologia
- E clico na lupa de pesquisa

### **Resultado Esperado:**

- ENTÃO o sistema deve exibir uma lista de profissionais com informações relacionados à minha pesquisa

### **Prioridade:**

Alta

### **Severidade:**

Média

### **Cobertura:**

Verifica se a pesquisa por preferências do usuário, exemplo: Odontologia é exibida conforme a escolha.

### **Resultado Obtido:**

O sistema retorna corretamente a pesquisa relacionada ao filtro de odontólogos do sistema.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 19

### Título:

Validação do código SMS e telefone válidos para visualizar dados de um profissional escolhido

### **Caso de Teste:**

- DADO que já escolhi um profissional: “Thiago Prof Online”
- E me encontro na seção de atendimento
- E clico no botão de exibir contato
- E quero ver os dados da pessoa profissional
- QUANDO insiro o meu número de celular cadastrado válido
- E clico no botão de enviar código
- E insiro o código de sms válido
- E clico no botão de confirmar

### **Resultado Esperado:**

- ENTÃO o sistema retorna os dados de contato de WhatsApp
- E telefone do profissional

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o telefone e sms válidos são aplicados corretamente para visualizar os dados de contato do profissional de saúde.

### **Resultado Obtido:**

O sistema retorna os dados de contato de WhatsApp do profissional.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 20

### Título:

Campo de número de celular vazio

### **Caso de Teste:**

- DADO que já escolhi um profissional: “Thiago Prof Online”
- E me encontro na seção de atendimento
- E clico no botão de exibir contato
- E quero ver os dados da pessoa profissional
- QUANDO deixa o campo de número de celular vazio
- E clico no botão de enviar código

### **Resultado Esperado:**

- ENTÃO o sistema retorna que o campo é obrigatório

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verificação se o sistema passa a próxima etapa com campos vazios.

### **Resultado Obtido:**

A mensagem requerida de campo obrigatório é exibida.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 21

### Título:

Campo de sms vazio

### **Caso de Teste:**

- DADO que já escolhi um profissional: Thiago Prof Online
- E me encontro na seção de atendimento
- E clico no botão de exibir contato
- E quero ver os dados da pessoa profissional
- QUANDO insiro o meu número de celular cadastrado válido
- E clico no botão de enviar código
- MAS deixo o campo de código de sms vazio
- E clico no botão de confirmar

### **Resultado Esperado:**

ENTÃO o sistema exibe a mensagem: “Código incorreto. Verifique se digitou corretamente ou solicite um novo código.

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o sistema passa a próxima etapa com campos de código de sms vazio.

### **Resultado Obtido:**

 O sistema exibe a mensagem: “Código incorreto. Verifique se digitou corretamente ou solicite um novo código.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 22

### Título:

Reenvio de código de segurança

### **Caso de Teste:**

- DADO que já escolhi um profissional: Thiago Prof Online
- E me encontro na seção de atendimento
- E clico no botão de exibir contato
- E quero ver os dados da pessoa profissional
- E insiro o meu número de celular cadastrado válido
- E clico no botão de enviar código
- MAS o código não chega no meu dispositivo
- QUANDO eu clico no botão de reenviar código de segurança

### **Resultado Esperado:**

- ENTÃO o sistema exibe a mensagem de que o código foi enviado por SMS
- E o código chega no dispositivo mobile

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se o sistema reenvia o código de sms mais de uma vez corretamente.

### **Resultado Obtido:**

O sistema exibe a mensagem de que o código foi enviado por SMS e o código chega no dispositivo mobile.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### Tipo de teste: Desempenho

### ID: 23

### Título:

Verifica métricas de desempenho da página de busca de profissionais

### **Caso de Teste:**

- DADO que me encontro na página de busca por profissionais
- QUANDO clico na lupa diretamente para pesquisar por um profissional

### **Resultado Esperado:**

- ENTÃO o Primeiro Pint de Conteúdo deve ser ≤ 1,6 segundos
- E o Maior Pint de Conteúdo deve ser ≤ 7,3 segundos
- E o Tempo Total de Bloqueio deve ser ≤ 5.500 milissegundos
- E o Deslocamento Acumulado de Layout deve ser ≤ 0,001
- E o Índice de Velocidade deve ser ≤ 13,8 segundos

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica o desempenho na busca por profissionais do sistema.

### **Resultado Obtido:**

O teste de desempenho na busca por profissionais do sistema Lacrei passou, pois as métricas estão dentro dos limites esperados. Sendo:

- **First Contentful Paint (FCP):** 1,3 segundos
    - **Comparação:** 1,3 s (≤ 1,6 s) – **Passou**
    - **Explicação:** O tempo necessário para exibir o primeiro conteúdo visível da página está dentro do limite aceitável.
- **Largest Contentful Paint (LCP):** 7,1 segundos
    - **Comparação:** 7,1 s (≤ 7,3 s) – **Passou**
    - **Explicação:** O tempo para o maior elemento de conteúdo visível ser exibido está dentro do limite estabelecido.
- **Total Blocking Time (TBT):** 2.780 milissegundos
    - **Comparação:** 2.780 ms (≤ 5.500 ms) – **Passou**
    - **Explicação:** O tempo total em que a página estava bloqueada é bem abaixo do limite máximo permitido, indicando que a página responde rapidamente às interações do usuário.
- **Cumulative Layout Shift (CLS):** 0,001
    - **Comparação:** 0,001 (≤ 0,001) – **Passou**
    - **Explicação:** O deslocamento de layout acumulado durante o carregamento da página é mínimo, atendendo ao critério de estabilidade visual.
- **Speed Index:** 11,0 segundos
    - **Comparação:** 11,0 s (≤ 13,8 s) – **Passou**
    - **Explicação:** O índice de velocidade, que indica quão rapidamente o conteúdo visível é exibido, está dentro do intervalo aceitável.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

## **7. Suíte Editar perfil de usuário(a)**

### **Tipo de Teste**

**Teste funcional**

### **User Story**

US 5: **Buscar por uma pessoa profissional**

- Como uma pessoa usuária
- Gostaria de editar meus dados pessoais no sistema
- Porque quero manter as minhas informações atualizadas

### **Pré-condição:**

- Ter um usuário cadastrado
- Ter uma senha cadastrada

### Dados necessários:

### ID: 24

### Título:

Alteração de informação em perfil

### **Caso de Teste:**

- DADO que me encontro em informações pessoais do meu perfil no sistema Lacrei
- QUANDO eu clico no botão de editar dados
- E altero as informações dos campos obrigatórios corretamente, exemplo: campo de sexualidade para “Pansexual”
- E clico no botão de salvar

### **Resultado Esperado:**

- ENTÃO a informação deve ser salvo no sistema com sucesso
- E as informações são atualizadas

### **Prioridade:**

Alta

### **Severidade:**

Média

### **Cobertura:**

Verifica se as informações com base na escolha do usuário, como: campo de sexualidade para “Pansexual” é salvo no sistema corretamente.

### **Resultado Obtido:**

As informações é atualizada, porém, mesmo com o preenchimento de todos os campos obrigatórios, o sistema retorna a mensagem: “Algo deu errado. Por favor tente novamente.” e no campo de data de nascimento a data foi preenchida e é exibido a mensagem: “Campo obrigatório”.

### **Defeitos:**

Os ID de evidência na pasta em vídeo e screenshot com os nomes.: 

- id-24-defeito-1
- id-24-defeito-2

### **Status:**

Falhou

---

## 8. Suíte Reset de senha em segurança de perfil

### **Tipo de Teste**

**Teste funcional**

### **User Story**

US 5: **Buscar por uma pessoa profissional**

- Como uma pessoa usuária
- Gostaria de alterar minha senha"
- Porque quero manter a segurança da minha conta"

### **Protótipo:**

### **Pré-condição:**

- Ter um usuário cadastrado
- Ter uma senha cadastrada

### Dados necessários:

Senha atual: r41MaR22*

Nova senha: r41MaR22**

---

### ID: 25

### Título:

 Alteração de senha bem-sucedida

### **Caso de Teste:**

- DADO que me encontro em alterar senha, na aba de segurança de meu perfil no sistema Lacrei
- E clique no botão de alterar senha
- E preencho o campo de senha atual válida
- E preencho o campo de nova senha válida
- E preencho o campo de confirme a nova senha válida
- QUANDO eu clicar no botão de salvar senha

### **Resultado Esperado:**

- ENTÃO o sistema salva a alteração corretamente

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Valida se alteração de senha em perfil está sendo bem sucedida.

### **Resultado Obtido:**

A senha é alterada corretamente.

### **Defeitos:**

Não possui

### **Status:**

Passou

---

### ID: 26

### Título:

Nova senha igual a anteriormente cadastrada

### **Caso de Teste:**

- DADO que me encontro em alterar senha, na aba de segurança de meu perfil no sistema Lacrei
- E clique no botão de alterar senha
- E insiro senha atual válida
- E preencho o campo de nova senha com a mesma senha anteriormente cadastrada no sistema
- E preencho o campo em confirme a nova senha com a mesma senha anteriormente cadastrada no sistema
- QUANDO eu clicar no botão de salvar senha

### **Resultado Esperado:**

ENTÃO o sistema retorna a mensagem: "Uma nova senha não pode ser igual à atual”

### **Prioridade:**

Alta

### **Severidade:**

Média

### **Cobertura:**

Verifica se o usuário cadastra a nova senha igual a anteriormente cadastrada no sistema.

### **Resultado Obtido:**

O sistema retorna a mensagem: "Uma nova senha não pode ser igual à atual”

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 27

### Título:

Senhas diferentes

### **Caso de Teste:**

- DADO que me encontro em alterar senha, na aba de segurança de meu perfil no sistema Lacrei
- E clique no botão de alterar senha
- E preencho o campo de senha atual com a minha senha atual
- E preencho o campo de nova senha válida com uma nova senha válida
- E preencho o campo de confirme a nova senha com uma senha diferente
- QUANDO eu clicar no botão de salvar senha

### **Resultado Esperado:**

- ENTÃO o sistema exibe a mensagem de erro: “As senhas não coincidem.”

### **Prioridade:**

Média

### **Severidade:**

Média

### **Cobertura:**

Verifica se o usuário insere senhas diferentes nos campos correspondentes e consegue salvar os dados dessa forma.

### **Resultado Obtido:**

 O sistema exibe a mensagem de erro: “As senhas não coincidem.”

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

## 9. Suíte Atualização de contato

### **Tipo de Teste**

**Teste funcional**

### **User Story**

US 9: **Buscar por uma pessoa profissional**

- Como uma pessoa usuária
- Gostaria de alterar meu número de telefone"
- Porque preciso garantir que meus dados de contato estejam atualizados

### **Pré-condição:**

- Ter um usuário cadastrado
- Ter uma senha cadastrada

### Dados necessários:

Telefone fictício: (92) 99315-2424

---

### ID: 28

### Título:

Atualizar número de telefone com sucesso

### **Caso de Teste:**

- DADO que me encontro em alterar senha, na aba de segurança de meu perfil no sistema Lacrei
- E clico no botão de editar dados
- QUANDO eu insiro no campo de telefone um número de telefone válido
- E clico no botão de salvar dados

### **Resultado Esperado:**

- ENTÃO o sistema deve atualizar os dados de contato corretamente

### **Prioridade:**

Média

### **Severidade:**

Média

### **Cobertura:**

Verifica de o sistema atualiza corretamente o telefone de usuário.

### **Resultado Obtido:**

O sistema deve atualizar os dados de contato corretamente

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

### ID: 29

### Título:

Campo de telefone vazio

### **Caso de Teste:**

- DADO que me encontro em alterar senha, na aba de segurança de meu perfil no sistema Lacrei
- E clico no botão de editar dados
- MAS deixo o campo de telefone vazio
- QUANDO clico no botão de salvar dados

### **Resultado Esperado:**

- ENTÃO o sistema exibe a mensagem: “DDD ou número de telefone incorreto. Digite novamente.”

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica se sistema exibe a mensagem de erro para que o usuário não salve sem preencher o campo corretamente.

### **Resultado Obtido:**

O sistema exibe a mensagem: “DDD ou número de telefone incorreto. Digite novamente.”

### **Defeitos:**

Não possui.

### **Status:**

Passou

---

## 10. Suíte de **Privacidade (Atualização de contato)**

### ID: 30

### Título:

Solicitação de dados  pessoais

### **Caso de Teste:**

- DADO que me encontro na seção de privacidade do sistema Lacrei
- QUANDO eu clico no botão de solicitar meus dados

### **Resultado Esperado:**

- ENTÃO sou direcionado para a aba de Direitos de Titular

### **Prioridade:**

Alta

### **Severidade:**

Alta

### **Cobertura:**

Verifica o direcionamento válido da solicitação de dados para a seção de Direitos de Titular

### **Resultado Obtido:**

- O direcionamento é válido para a aba de Direitos de Titular

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---

### ID: 31

### Título:

Exclusão de conta com sucesso

### Dados necessários:

Nome: teste

Sobrenome: teste

E-mail: [vilmar3022@uorak.com](mailto:vilmar3022@uorak.com)

Senha: r41MaR22*

### **Caso de Teste:**

- DADO que me encontro na seção de privacidade do sistema Lacrei
- QUANDO eu clico no botão de apagar minha conta
- E em confirmação absoluta, clico no botão de sim

### **Resultado Esperado:**

- ENTÃO a conta é excluída do sistema

### **Prioridade:**

Alta

### **Severidade:**

Altíssima

### **Cobertura:**

Verificação de exclusão de conta de usuário do sistema.

### **Resultado Obtido:**

A conta é excluída corretamente.

### **Defeitos:**

Não possui.

### **Status:**

Passou.

---