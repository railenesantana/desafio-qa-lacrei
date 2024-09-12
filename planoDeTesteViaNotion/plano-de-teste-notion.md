# Plano de Teste

| Analista de Teste Responsável | Railene de Santana Chaves |
| --- | --- |
| Data de Inicio | 04-set.-24 |
| Data de Fim | 09-set.-24 |
| Prioridade | Alta |
| Severidade | Alta |
| Implementação Manual | Sim |
| Implementação Automatizada | Não |

## Propósito

Este plano de teste visa executar testes do tipo funcional com base em critérios de aceite  para o Sistema Lacrei Saúde, uma plataforma que busca conectar pessoas LGBTQIAPN+, onde visa proporcionar a experiência de cuidado e inclusão proporcionando atendimento com profissionais da área da saúde.

## Público Alvo

O público alvo são usuários  LGBTQIAPN+, a plataforma oferece acessibilidade, onde inclui pessoas com deficiência, tanto sensoriais quanto físicas, e oferece segurança onde a plataforma segue **a Lei Geral de Proteção de Dados Pessoais (LGPD).**

## Escopo

No escopo de validação teremos:

1. Suíte Animação ao abrir o site
2. Suíte Cadastro da pessoa usuária
3. Suíte de Boas vindas | Pós cadastro
4. Suíte Login de pessoa usuária
5. Suíte Reset de senha
6. Suíte Buscar por uma pessoa profissional
7. Suíte Editar perfil de usuário(a)
8. Suíte Reset de senha em segurança de perfil
9. Suíte Atualização de contato
10. Suíte de Privacidade (Atualização de contato)

## Definições, Acrônimos e Abreviações

- US - User Story
- CT - Caso de Teste
- ID - Identificador
- PO - Product Owner
- QA - Quality Assurance

## Ambiente do Teste

| Nome do device | Modelo | CPU | Armazenamento | Resolução da tela | Versão |
| --- | --- | --- | --- | --- | --- |
| Pixel 2 API 29 | Pixel_2_API_29 | 4 núcleos (Quad-core) |  6 GB  | 1080 x 1920 pixels (420 dpi) | Android 10 (API 29) |
| Xiaomi Redmi Note 12 | 23021RAAEG / 23028RA60L | Qualcomm Snapdragon 685 (Octa-core) | 64 GB / 128 GB | 1080 x 2400 pixels | Android 12 |
| Google Pixel 7 | Pixel 7 (GQML3, GE2AE) | Google Tensor G2 | 128 GB ou 256 GB | 2400 x 1080 pixels ( | Android 13 |

## Estratégia de Teste

Nesta aba, apresento as estratégias adotadas para testar o sistema, com foco específico no Teste de Sistema. O objetivo é garantir que os critérios de aceite sejam atendidos e que o sistema funcione conforme o esperado do ponto de vista do usuário final.
Tipos de teste utilizados:

- Funcional: Verificação se as funcionalidades do sistema estão funcionando de acordo com os requisitos especificados pelo PO através de regras de negócio e critérios de aceite.

- Exploratório: Avaliação das funcionalidades do sistema sem um roteiro pré-definido, permitindo a descoberta de problemas não previstos inicialmente. A implementação de teste será Manual: os testes serão executados manualmente para garantir uma análise detalhada das funcionalidades e interações do usuário.

- Desempenho: foi realizada uma avaliação com base na velocidade do carregamento e tempo de resposta do sistema garantindo que as métricas como **First Contentful Paint** e **Largest Contentful Paint** estejam dentro dos padrões recomendados.

- Acessibilidade: verificação de usabilidade do sistema para pessoas que possuem deficiência, incluindo testes com a ferramenta VLibras, para garantir que os usuários possam navegar e interagir com o sistema de forma inclusiva.

- Responsividade: são testes para assegurar que o sistema se adapte corretamente em diferentes tamanhos de telas de dispositivos mobile, os testes de responsividade incluem layout flexível e avalia se os botões se adaptam e estão dispostos corretamente na página.

<aside>


</aside>