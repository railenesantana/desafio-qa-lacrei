## Reporte de Bugs 

Nesta seção irei descrever sobre o modelo de **Reporte de Bugs** que utilizei para o reporte de Bugs encontrados no **Sistema Lacrei**

## Formato de Reporte de Bug 

- **Passos para Reproduzir** 
  
    Neste tópico você descreve o passo a passo necessário para reproduzir um bug, descreva de forma que qualquer pessoa interessada compreenda os passos descritos.

- **Resultado Esperado:** 
  
    Neste tópico é descrito o que você esperava que ocorresse, neste caso, o comportamento adequado do sistema que utilizou para o teste.

- **Resultado Observado:**
  
  Neste tópico é descrito o resultado observado, para o momento em que foi realizado um teste e encontrado o Bug.

- **Severidade:** 
  
  A severidade indica o impacto técnico que o bug tem no sistema. Ela é avaliada com base no quanto o problema interfere no funcionamento ou usabilidade do software. Quanto maior o impacto no desempenho do sistema ou na experiência do usuário, maior a severidade.

**Classificações severidade**

**Baixa:** O bug é pequeno e não afeta as funcionalidades principais do sistema.

Exemplo: Um botão que está ligeiramente desalinhado na interface, mas ainda funcional.

**Média**: O bug afeta algumas funcionalidades do sistema, mas há alternativas ou soluções temporárias para o problema. O impacto é moderado, porém a falha não impede completamente o uso.

Exemplo: Um campo de formulário que aceita entrada de dados, mas tem comportamento inconsistente.

**Alta**: O bug afeta funcionalidades críticas do sistema, causando sérios problemas para o usuário ou impedindo a execução correta de uma tarefa importante.

Exemplo: O sistema não salva informações de perfil mesmo após preencher todos os campos obrigatórios.

**Crítica**: O bug impede o uso completo do sistema ou causa falhas graves, como perda de dados ou travamento do aplicativo. O sistema ou funcionalidade é inoperável.

Exemplo: O aplicativo trava ou fecha inesperadamente ao tentar realizar uma ação principal, como login ou transação.

- **Prioridade:** 
  
A prioridade indica a urgência com que o bug precisa ser corrigido. Ela leva em consideração o impacto no negócio, nos prazos e na necessidade dos usuários. Enquanto a severidade é uma medida técnica, a prioridade é uma decisão de negócio.

**Classificações da prioridade**

**Baixa**

O bug pode ser corrigido em um momento posterior, já que seu impacto é mínimo e não há urgência. Normalmente, são problemas que não afetam diretamente os usuários ou os negócios.

Exemplo: Pequenas correções de interface ou falhas que afetam uma parte muito pequena dos usuários.

**Média**

O bug deve ser corrigido em um prazo razoável, pois ele tem impacto relevante no sistema, mas não é uma emergência.

Exemplo: Problemas que afetam o desempenho ou causam inconvenientes que podem ser contornados, mas que ainda precisam de atenção.

**Alta**

O bug precisa ser corrigido com urgência, pois afeta significativamente o sistema ou a experiência do usuário, mesmo que o sistema ainda esteja funcional.

Exemplo: Falhas que afetam uma parte importante do sistema, como a incapacidade de completar uma transação.

**Urgente (Crítica)**

O bug deve ser corrigido imediatamente, pois causa falhas graves no sistema e impede seu uso completo. Isso pode estar diretamente relacionado a funcionalidades cruciais ou de segurança.

Exemplo: Vulnerabilidades de segurança que expõem dados de usuários ou causam travamentos massivos.

**Especificações do Sistema**

Esta seção descreve o ambiente em que o bug foi encontrado. Essas informações ajudam a equipe de desenvolvimento a reproduzir o problema no mesmo contexto para facilitar a correção. Inclui informações como dispositivo, sistema operacional, versão do aplicativo, e o ambiente de teste.

**Informações que devem ser incluídas:**

**Dispositivo:** O modelo exato do dispositivo onde o bug foi encontrado.
Exemplo: Redmi Note 12

**Sistema Operacional:** A versão do sistema operacional em que o bug foi reproduzido.
Exemplo: Android 14

**Aplicativo:** O nome e a versão exata do aplicativo onde o problema ocorreu.
Exemplo: Sistema Lacrei, versão 4.4.35

**Ambiente:** O ambiente onde o bug foi identificado, como produção, staging, ou homologação.
Exemplo: Homologação
