## Reporte de Bugs 

Nesta seção irei descrever sobre o modelo de **Reporte de Bugs** que utilizei para o reporte de Bugs encontrados no **Sistema Lacrei**.

## Formato de Reporte de Bug 

- **Passos para Reproduzir** 
  
    Neste tópico você descreve o passo a passo necessário para reproduzir um bug, descreva de forma que qualquer pessoa interessada compreenda os passos descritos.

- **Resultado Esperado:** 
  
    Neste tópico é descrito o que você esperava que ocorresse, neste caso, o comportamento adequado do sistema que utilizou para o teste.

- **Resultado Observado:**
  
    Neste tópico é descrito o resultado observado, para o momento em que foi realizado um teste e encontrado o Bug.

- **Severidade:** 
  
    A severidade indica o impacto técnico que o bug tem no sistema. Ela é avaliada com base no quanto o problema interfere no funcionamento ou usabilidade do software. Quanto maior o impacto no desempenho do sistema ou na experiência do usuário, maior a severidade.

    **Classificações de Severidade**

    - **Baixa:** O bug é pequeno e não afeta as funcionalidades principais do sistema.  
    Exemplo: Um botão que está ligeiramente desalinhado na interface, mas ainda funcional.

    - **Média:** O bug afeta algumas funcionalidades do sistema, mas há alternativas ou soluções temporárias para o problema. O impacto é moderado, porém a falha não impede completamente o uso.  
    Exemplo: Um campo de formulário que aceita entrada de dados, mas tem comportamento inconsistente.

    - **Alta:** O bug afeta funcionalidades críticas do sistema, causando sérios problemas para o usuário ou impedindo a execução correta de uma tarefa importante.  
    Exemplo: O sistema não salva informações de perfil mesmo após preencher todos os campos obrigatórios.

    - **Crítica:** O bug impede o uso completo do sistema ou causa falhas graves, como perda de dados ou travamento do aplicativo. O sistema ou funcionalidade é inoperável.  
    Exemplo: O aplicativo trava ou fecha inesperadamente ao tentar realizar uma ação principal, como login ou transação.

- **Prioridade:** 
  
    A prioridade indica a urgência com que o bug precisa ser corrigido. Ela leva em consideração o impacto no negócio, nos prazos e na necessidade dos usuários. Enquanto a severidade é uma medida técnica, a prioridade é uma decisão de negócio.

    **Classificações da Prioridade**

    - **Baixa:** O bug pode ser corrigido em um momento posterior, já que seu impacto é mínimo e não há urgência. Normalmente, são problemas que não afetam diretamente os usuários ou os negócios.  
    Exemplo: Pequenas correções de interface ou falhas que afetam uma parte muito pequena dos usuários.

    - **Média:** O bug deve ser corrigido em um prazo razoável, pois ele tem impacto relevante no sistema, mas não é uma emergência.  
    Exemplo: Problemas que afetam o desempenho ou causam inconvenientes que podem ser contornados, mas que ainda precisam de atenção.

    - **Alta:** O bug precisa ser corrigido com urgência, pois afeta significativamente o sistema ou a experiência do usuário, mesmo que o sistema ainda esteja funcional.  
    Exemplo: Falhas que afetam uma parte importante do sistema, como a incapacidade de completar uma transação.

    - **Urgente (Crítica):** O bug deve ser corrigido imediatamente, pois causa falhas graves no sistema e impede seu uso completo. Isso pode estar diretamente relacionado a funcionalidades cruciais ou de segurança.  
    Exemplo: Vulnerabilidades de segurança que expõem dados de usuários ou causam travamentos massivos.

- **Especificações do Sistema:** 
  
    Esta seção descreve o ambiente em que o bug foi encontrado. Essas informações ajudam a equipe de desenvolvimento a reproduzir o problema no mesmo contexto para facilitar a correção. Inclui informações como dispositivo, sistema operacional, versão do aplicativo, e o ambiente de teste.

    **Informações que devem ser incluídas:**

    - **Dispositivo:** O modelo exato do dispositivo onde o bug foi encontrado.  
    Exemplo: Redmi Note 12

    - **Sistema Operacional:** A versão do sistema operacional em que o bug foi reproduzido.  
    Exemplo: Android 14

    - **Aplicativo:** O nome e a versão exata do aplicativo onde o problema ocorreu.  
    Exemplo: Sistema Lacrei, versão 4.4.35

    - **Ambiente:** O ambiente onde o bug foi identificado, como produção, staging, ou homologação.  
    Exemplo: Homologação

- **Evidências:**
  
    Incluir evidências como vídeos ou screenshots é crucial para a validação e entendimento do bug. Essas evidências ajudam a equipe de desenvolvimento a visualizar o problema de maneira mais clara e a reproduzi-lo com maior precisão. Além disso, elas podem acelerar o processo de correção, uma vez que fornecem uma representação visual do erro.

    **Tipos de Evidências:**

    - **Screenshots:** Capturas de tela que mostram a interface do aplicativo no momento do erro. Elas são úteis para evidenciar problemas visuais e erros de layout.

    - **Vídeos:** Gravações de tela que demonstram o comportamento do aplicativo passo a passo. Eles são úteis para mostrar a sequência de ações que levam ao erro e para fornecer um contexto mais completo.

    **Como Anexar Evidências:**

    - **Screenshots:** Anexe as imagens diretamente ao relatório ou inclua links para um repositório de imagens acessível à equipe de desenvolvimento.

    - **Vídeos:** Faça upload dos vídeos em uma plataforma de compartilhamento de vídeos ou em um serviço de armazenamento em nuvem e forneça o link no relatório.

    **Exemplo de Evidência:**

  **Screenshot:** 
  
  ![Exemplo de Screenshot](../evidencias/screenshot/id-13-primeiro-device.png)
  
**Vídeo:**
[Link do vídeo](../evidencias/videos/id-13-primeiro-device.mp4)
