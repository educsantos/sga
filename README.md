# sga
Sistema de Gerenciamento Acadêmico (exemplo para treinamento em desenvolvimento de sistemas)

Este projeto foi criado para ilustrar para os alunos de Programação e Desenvolvimento de Sistemas como utilizar o github.

Consideraremos caso de estudo o desenvolvimento de um Sistema de Gerenciamento Acadêmico.

--------

## Descrição do problema

A Instituição de Ensino oferece cursos em diferentes áreas de formação, contrata professores com diferentes especialidades para lecionar nos cursos e capta estudantes. Diferentes disciplinas constituem os cursos. Um estudante pode se matricular concomitantemente em um número de disciplinas que vai de um a cinco. A matrícula em uma disciplina deve respeitar o limite máximo de inscrições que um aluno pode acumular e os pré-requisitos, quando houver, que formam uma lista de disciplinas que o aluno já deve ter concluído com sucesso. Cada curso tem um coordenador, que é um dos professores que acumula a função de coordenador além da função de professor. As funções do coordenador do curso são: apoiar professores e orientar alunos, emitir circulares institucionais, resolver eventuais casos especiais e manter contato com pais e responsáveis nos casos de alunos menores. Cada turma refere-se a uma disciplina de determinado curso, tem um professor e pode conter até 40 alunos, devendo ainda conter um mínimo de 20 alunos para garantir a viabilidade financeira. Em alguns casos, o professor catedrático da disciplina conta com a ajuda de um professor assistente que é quem corrige as avaliações e lança notas e frequências no sistema. Nos casos em que não há um professor assistente, cabe ao próprio professor da disciplina, denominado professor adjunto nesse caso, as tarefas de correções de avaliações e lançamento de notas e frequência. O próprio aluno pode emitir seu próprio boletim. O professor pode emitir o relatório de notas e frequências de suas turmas. O coordenador pode emitir relatórios de desempenho gerais sob diferentes contextos: por estudante, por professor, por disciplina, por curso. O estudante pode requisitar declaração ao coordenador que é quem a emite. Todos os documentos (declarações, circulares, boletins etc.) podem ser visualizados diretamente no console, ou convertidos para o formato PDF. O documento no formato PDF pode, então, ser impresso ou enviado por e-mail. No caso das circulares elas podem ser enviadas por e-mail como anexo PDF ou diretamente no corpo da mensagem.

## Estrutura de diretórios

    data/           (Para conter arquivos de dados)
    docs/           (Para conter arquivos de documentação)
    include/        (Para conter arquivos de cabeçalho - .hpp)
    screenshots/    (Para conter arquivos de screenshots)
    src/            (Para conter arquivos fonte .cpp)
    tests/          (Para conter arquivos de testes)

Foi colocado um arquivo vazio (.gitkeep) dentro de cada um desses diretórios 
porque o git ignora diretórios vazios.


