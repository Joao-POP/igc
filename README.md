# igc
Uma interface escolar unificada para professores e alunos

## Visão
Providenciar um meio *acessível*, *robusto* e *direto* de visualizar notas,
distribuir avisos e planejar a sala de aula. 

### Acessível
O ambiente escolar exige ferramentas que possam ser utilizadas tanto por leigos
em tecnologia, quanto pelos profissionais mais exigentes. Por esse motivo, o
IGC foi projetado para fornecer o mínimo ao usuário por padrão, mas podendo ser
extendido através de sua própria interface. Esse princípio é o que guia todo o
design tanto da backend quanto da frontend do projeto.

### Robusto
Cada segundo na sala de aula é tempo que poderia ser utilizado para lecionar.
Panes no sistema são inaceitáveis, por isso o IGC é programado completamente
em Rust. Nenhum erro é deixado de lado, e toda a base de código é construída
nos princípios da redundância e recuperabilidade, consertando problemas como
corrupção de dados automaticamente.

### Direto
Em qualquer dispositivo, de qualquer fator, deve haver somente a necessidade de
conectá-lo a internet e acessar o IGC. Não se preocupe com páginas com texto
minúsculo porque alguém se esqueceu de escrever uma `meta` tag. Em outras
palavras, o sistema se adequa ao usuário, não o contrário.
