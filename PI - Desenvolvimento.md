**SERVIÇO NACIONAL DE APRENDIZAGEM COMERCIAL SENAC**

**CURSO DE TECNOLOGIA EM ANÁLISE E DESENVOLVIMENTO DE SISTEMAS**









**PROJETO INTEGRADOR: DESENVOLVIMENTO DE SISTEMAS ORIENTADO A OBJETOS**





Professor: Enoque Felipe dos Santos Leal

Tutor: Claudio Santos de Almeida


Integrantes do grupo:

Samuel Lucas e Silva C. de Paula

Mylena Torres Flores

João Rodrigo Lapsky

Pâmela Ramos Martins




![](Aspose.Words.8aeb3a92-4f24-46cf-aba7-9f77479ae48f.001.png)![](Aspose.Words.8aeb3a92-4f24-46cf-aba7-9f77479ae48f.002.png)

**Resumo**

O presente trabalho tem por objetivo realizar a construção e descrição de Diagrama de Casos de Uso e o Diagrama de Classe – UML para fins de idealizar um sistema orientado a objetos onde o exemplo a ser observado nas etapas de desenvolvimento representam um sistema de uma instituição de ensino superior, cuja funções estarão delimitadas nos diagramas apresentados no presente trabalho.

![](Aspose.Words.8aeb3a92-4f24-46cf-aba7-9f77479ae48f.003.png)
# Sumário
[1.	Contextualização e objetivos	5](#_toc162263927)

[2.	Ciclo de Vida de Desenvolvimento	5](#_toc162263928)

[2.1	Planejamento:	5](#_toc162263929)

[2.2	Análise:	5](#_toc162263930)

[2.3	Projeto:	6](#_toc162263931)

[2.4	Implementação:	6](#_toc162263932)

[2.5	Testes:	6](#_toc162263933)

[2.6	Implantação:	6](#_toc162263934)

[3.	Protótipo funcional e experimentos de usabilidade:	7](#_toc162263935)

[4.	Diagrama de Classe de Uso	8](#_toc162263936)

[4.1	Descrição do Diagrama de Caso de Uso	8](#_toc162263937)

[5.	Diagrama de Classe – UML	11](#_toc162263938)

[5.1	Descrição do Diagrama de Classe – UML	11](#_toc162263939)

















1. # <a name="_toc162263927"></a>**Contextualização e objetivos**

A modalidade de Ensino a Distância (EAD) tem crescido significativamente nos últimos anos, representando uma alternativa viável e acessível para milhões de estudantes em todo o mundo. As Escolas de Ensino Superior que adotam essa modalidade enfrentam desafios específicos em relação ao ensino presencial, mas também desfrutam de oportunidades únicas para inovar e atender a uma demanda diversificada de alunos.

Neste contexto, nossa pesquisa tem como foco uma Escola de Ensino Superior EAD fictícia, que oferece uma variedade de cursos de graduação e pós-graduação totalmente online. Esta instituição busca proporcionar uma educação de qualidade, acessível e flexível, atendendo a alunos de diferentes perfis e regiões geográficas.

Desenvolver um sistema de gestão acadêmica específico para uma Escola de Ensino Superior EAD é crucial para garantir a eficiência operacional, a qualidade do ensino e a satisfação dos alunos e professores. O sistema proposto deve ser capaz de gerenciar matrículas, disponibilizar aulas e cursos complementares que são fornecidos por outras instituições parceiras.

1. # <a name="_toc162263928"></a>**Ciclo de Vida de Desenvolvimento**

1. ## <a name="_toc162263929"></a>**Planejamento:**
- Definimos os objetivos do projeto, como melhorar a experiência do aluno na realização das matrículas e acesso às aulas.
- Identificamos os requisitos iniciais, como cadastro de alunos, oferta de disciplinas e gestão de turmas.
- Estabelecemos os critérios de sucesso, como aumento na taxa de matrículas e satisfação dos alunos.

1. ## <a name="_toc162263930"></a>**Análise:**
- Coletamos e analisamos detalhadamente os requisitos do sistema, como cadastro de alunos, matrícula em disciplinas e acesso às aulas.
- Elaboramos os casos de uso, representando as interações dos usuários com o sistema, como realizar matrícula, visualizar grade curricular, assistir aulas, entre outros.

1. ## <a name="_toc162263931"></a>**Projeto:**
- Definimos a arquitetura do sistema, identificando os principais componentes e suas responsabilidades.
- Elaboramos os diagramas de classe e de caso de uso, representando a estrutura de classes e as interações entre os objetos do sistema.
- Defineremos a estrutura do banco de dados para armazenar informações dos alunos, disciplinas, turmas, entre outros.

1. ## <a name="_toc162263932"></a>**Implementação:**
- Desenvolvemos o código-fonte do sistema, seguindo as especificações e padrões estabelecidos.
- Realizamos testes unitários para garantir o funcionamento correto de cada componente.

  1. ## <a name="_toc162263933"></a>**Testes:**
- Realizamos testes em várias frentes, como testes de unidade, integração, sistema e aceitação do usuário.
- O objetivo é identificar e corrigir possíveis defeitos, garantindo que o sistema atenda aos requisitos definidos e às expectativas dos usuários.

1. ## <a name="_toc162263934"></a>**Implantação:**
- Disponibilizamos o sistema para uso em um ambiente de produção, realizando ajustes finais e configurações necessárias.
- Monitoramos o desempenho do sistema e realiza-se ajustes conforme necessário para garantir a sua estabilidade e eficiência

O desenvolvimento de um sistema baseado em Orientação a Objetos para gestão de matrículas e disponibilização de aulas online na Escola de Ensino Superior EAD representa um passo importante para melhorar a qualidade e eficiência dos serviços oferecidos aos alunos. Por meio de um ciclo de vida de desenvolvimento bem estruturado e alinhado com as necessidades da instituição, busca-se proporcionar uma experiência de aprendizagem mais fluida e satisfatória, contribuindo assim para o sucesso acadêmico e profissional dos estudantes.

1. # <a name="_toc162263935"></a>**Protótipo funcional e experimentos de usabilidade:**

Inicialmente o produto deverá atender as seguintes demandas: Permitir o acesso da plataforma via rede mundial de internet; Conter as informações necessárias para que cada agente identifique as funções desempenhadas pelo software; Permitir o cadastro de pessoas físicas e jurídicas na plataforma, bem como, o armazenamento de dados e informações no seu SGBD; Distinguir os cadastros realizados, se aluno, professor, funcionário, prestador de serviços e fornecedor; Delimitar o acesso de funções pertinentes a cada tipo de cadastro; Permitir o acesso ao curso, grade curricular, grade de docentes, grade de notas, grade de avaliações e grade de aulas; Permitir o acesso a biblioteca digital e todo conteúdo disponível na mesma; Permitir que cursos complementares sejam regularmente ofertados; Permitir que insumos sejam repostos comforme a necessidade e devidamente relacionados; Disponibilizar o conteúdo programático, tais como: aulas, webconferências, material didático e material complemetar; Realizar serviços financeiros como emissão de boletos ou outros métodos de pagamento; Disponibilizar um canal de comunicação entre a comunidade de usuários, sejam alunos, professores, tutores, coordenadores e diretores; Disponibilizar canais de ajuda a fim de sanar eventuais dúvidas.


1. # ![](Aspose.Words.8aeb3a92-4f24-46cf-aba7-9f77479ae48f.004.png)<a name="_toc162263936"></a>**Diagrama de Classe de Uso**














1. ## <a name="_toc162263937"></a>**Descrição do Diagrama de Caso de Uso**

No presente diagrama, é possível verificar que o sistema aceita o acesso e o cadastro em sua plataforma por qualquer agente externo que o pesquise na rede mundial de internet, não importando em um primeiro momento se o acesso que está sendo realizado decorre de pessoa física ou jurídica, se aluno ou professor, se fornecedor ou prestador de serviços. Essa primeira distinção é importante, tendo em vista que, pela saúde do próprio negócio, tenha a plataforma da instituição de ensino bastante visibilidade na rede mundial de internet.

Já em um segundo momento, em específico, na fase cadastral, o ator interagente deverá especificar sua natureza e condição, se pessoa física ou jurídica, se aluno ou professor, se prestador de serviços ou fornecedor, uma vez que, as etapas subsequentes serão diferentes para cada tipo de ator, naturalmente por suas especificidades e também por uma questão de segurança e organização do sistema, será delimitado a cada tipo de ator o seu nível de acesso e as funções que deverão executar.

No caso do aluno, até que este efetue o pagamento da matrícula, o mesmo será considerado pelo sistema apenas como pessoa física. O procedimento se repete com o professor, enquanto o mesmo não for incluído dentro de uma disciplina também será considerado como pessoa física. Essa distinção é importante, pois ao realizar a matrícula ou o cadastro em alguma disciplina, o sistema identificará precisamente qual o vínculo foi criado por aquele ator com a instituição de ensino, o que também permite o acesso a outros recursos como a biblioteca digital ou a cursos complementares oferecidos pelos fornecedores, por exemplo.

Por fim e de forma cíclica, o sistema irá fornecer informações para os atores da relação conforme a necessidade e nível de acesso de cada, visando a entrega otimizada de suas funções e garantindo a segurança, efetividade e manutenibilidade do mesmo, que por uma análise final, garantem o sucesso das operações da instituição de ensino.















1. # <a name="_toc162263938"></a>**Diagrama de Classe – UML**
![](Aspose.Words.8aeb3a92-4f24-46cf-aba7-9f77479ae48f.005.png)















##
1. ## <a name="_toc162263939"></a>**Descrição do Diagrama de Classe – UML**

No presente diagrama temos a definição das classes com seus respectivos atributos e métodos, abstraindo num maior nível, a visão mais prática contida no Diagrama de Casos de Uso e focando mais na sua futura representação codificada.

Nesse sentido, as classes foram devidamente estabelecidas e receberam atributos específicos que as distinguem umas das outras, de acordo com suas próprias características, o que facilitará pelo sistema o reconhecimento de quem o está acessando, manuseando e demandando suas funções. Também foram determinados os métodos que definem o comportamento de cada classe ao serem demandadas pelo sistema exatamente para que a resposta ao usuário ocorra de maneira satisfatória.

Ademais, compulsório salientar o relacionamento estabelecido entre as classes. Parte importante deste diagrama, uma vez que o relacionamento entre as classes constituí entre elas determinado grau de dependência e que por si justificam a existência do próprio sistema, logo, o relacionamento havido entre as classes, seja uma associação ou composição, delimita não somente a hierarquia entre as classes, como também o nível de acesso e também as funções que a mesma irá exercer dentro do sistema, tornando-se possível assim, auferir sua efetividade, a escalabilidade, a segurança e a iteração do sistema com os usuários.
