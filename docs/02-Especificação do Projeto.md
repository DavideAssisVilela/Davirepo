## Personas

Persona 1

![image](https://github.com/user-attachments/assets/03282e53-0998-44f7-a059-43b246bb61be)


Persona 2 

![image](https://github.com/user-attachments/assets/c5625a9a-1f8a-4f11-b82a-bd23a9000336)


Persona 3 

![image](https://github.com/user-attachments/assets/77caef37-5c88-4da4-853e-26e5f7467421)


Persona 4 

![image](https://github.com/user-attachments/assets/f38839ec-03a4-4de9-9907-a710bb8a8b32)


Persona 5

![image](https://github.com/user-attachments/assets/9a5669e0-c47f-4b75-a4db-f347131db0a0)



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|ORGANIZADOR DE EVENTOS   | Criar um evento.           | Atrair novos clientes e contratos para o organizador, especialmente se o evento for um sucesso e gerar boas recomendações. |
|ORGANIZADOR DE EVENTOS        | Gestão de recursos | Gerenciar o orçamento, fornecedores, equipe e materiais necessários para o evento.  |
|PARTICIPANTE      | Me inscrever em um evento.   | Como participante, eu quero me inscrever em um evento para ter passar por novas experiências.  |
|PARTICIPANTE  | Receber lembretes sobre o evento.   | Como participante, eu preciso receber lembretes sobre o evento para garantir que eu não esqueça de comparecer e estar ciente da existência de novos eventos.  |
|ORGANIZADOR DE EVENTOS  | Coordenar a comunicação com os participantes    | Como organizador de eventos, eu quero coordenar a comunicação com os participantes para garantir que todas as informações relevantes, como atualizações e avisos importantes, sejam transmitidas de maneira clara e eficiente, melhorando a experiência geral do evento.  |
|ORGANIZADOR DE EVENTOS   | Visualizar relatórios do evento  | Como organizador de eventos, eu quero acessar relatórios do evento para acompanhar e avaliar seu andamento e a participação dos convidados, permitindo-me ajustar futuras estratégias e melhorar a execução de eventos.  |
|PATROCINADOR  | Examinar perfis dos eventos   | Como patrocinador, eu quero examinar os perfis dos eventos para escolher aqueles que melhor correspondem à minha estratégia de marketing e garantir que meus recursos sejam aplicados de forma eficaz  |
|PATROCINADOR   | Poder interagir mais com os participantes| Ter a oportunidade de interagir diretamente com os participantes do evento, coletando feedback, promovendo produtos ou serviços, e criando uma conexão mais pessoal com o público  |   |
|ORGANIZADOR DE EVENTOS   | Visualizar os eventos programados no meu local.   |Como dono do local, eu preciso consultar os eventos programados em meu espaço para organizar a logística e a preparação.  |
|ORGANIZADOR DE EVENTOS  | Atualizar a disponibilidade do espaço para eventos   | Como dono do local, eu quero atualizar a disponibilidade do espaço para eventos em tempo real para garantir que os organizadores tenham acesso às informações mais recentes sobre a disponibilidade do local e possam planejar seus eventos de acordo.  |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| usuários conseguirem realizar cadastro no sistema  | ALTA | 
|RF-002| Usuários conseguirem realizar a recuperação de senha.   | ALTA |
|RF-003| Organizador ter acesso a criação de eventos, edição e exclusão.  | ALTA |
|RF-004| Organizador efetuar o gerenciamento de usuário.   | MÉDIA |
|RF-005| Usuários terem acesso à um calendário mensal para visualização dos eventos da data.  | ALTA |
|RF-006| Participante conseguir visualizar a inscrição no evento.    | MÉDIA|
|RF-007| Participantes efetuarem comentários e avaliarem eventos aos quais o mesmo participou.   | MÉDIA |
|RF-008| Participante receber notificações sobre confirmação da inscrição em eventos.  | MÉDIA |
|RF-009| O organizador ter acesso a um dashboard (Relatório de vendas, quantidade de participantes).   | ALTA |
|RF-010| Organizador e patrocinador terem acesso ao histórico de eventos.  | ALTA |
|RF-011| Patrocinadores visualizarem organizadores de demais eventos.   | MÉDIA |
|RF-012| Usuários favoritarem eventos.   | BAIXA |
|RF-013| Organizador realizar a gestão de patrocinadores   | MÉDIA |
|RF-014| Organizador e patrocinador realizarem filtragem de participantes   | MÉDIA|
|RF-015| Participante realizar a retirada de Ticket pelo sistema |Média|

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser disponibilizada em um ambiente acessível ao público na Internet.  | ALTA | 
|RNF-002| A aplicação deverá ser responsivo, possibilitando a visualização otimizada em diversos dispositivos, tais como computadores, celulares, entre outros.  |  MÉDIA | 
|RNF-003| A aplicação deve apresentar compatibilidade com diversos navegadores ex: Opera GX, Opera tradicional, Mozilla Firefox 71.0.   |  ALTA | 
|RNF-004| A aplicação deve otimizar o desempenho do site a fim de assegurar tempos de carregamento rápidos  “3s”.   |  ALTA | 
|RNF-005| O site deve ser fácil de usar, com uma interface intuitiva que permita aos usuários encontrar rapidamente as informações e funcionalidades que procuram máximo 5 clicks .  |  ALTA | 
|RNF-006| Deverá conseguir incluir o modo escuro na aplicação.   |  ALTA | 
|RNF-007| O site deve seguir padrões de codificação e design web, como HTML5, CSS3, C# e JavaScript moderno, para garantir a compatibilidade e a manutenção futura  |  ALTA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O sistema deverá ter 3 ou mais CRUD.  |
|02| O projeto deve ser construído apenas por pessoas da equipe.         |
|03| As decisões pertinentes ao projeto devem ser tomadas por meio democrático de votação.        |
|04| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de entrega.         |
|05| Os eventos não desfrutaram de sub-eventos      |
|06| O evento não divulgará nomes de participantes mantendo sigílo do mesmo.     |

## Diagrama de Casos de Uso

![image](https://github.com/user-attachments/assets/0b5977d6-d437-455d-98ac-62ea81a6e001)

