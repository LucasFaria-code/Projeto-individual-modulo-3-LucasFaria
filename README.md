# Projeto-individual-modulo-3-LucasFaria

# RESILIADATA

Descrição curta do projeto.

RESILIADATA é um sistema que auxilia na avaliação das tecnologias utilizadas por empresas parceiras e seus colaboradores.

## Funcionalidades:

- Cadastro de empresas parceiras
- Cadastro de tecnologias com suas respectivas áreas
- Registro das tecnologias utilizadas por cada empresa parceira
- Cadastro de colaboradores vinculados a empresas parceiras

## Fluxograma proposto:
1.	Entidades necessárias: a) Empresa parceira b) Tecnologia c) Registro de tecnologias utilizadas d) Colaborador
2.	Principais campos e tipos: a) Empresa parceira:
•	ID: Identificador único da empresa (inteiro ou alfanumérico)
•	Nome: Nome da empresa (texto)
•	Endereço: Endereço da empresa (texto)
•	Contato: Informações de contato da empresa (texto)
b) Tecnologia:
•	ID: Identificador único da tecnologia (inteiro ou alfanumérico)
•	Nome: Nome da tecnologia (texto)
•	Área: Área da tecnologia (texto)
c) Registro de tecnologias utilizadas:
•	ID: Identificador único do registro (inteiro ou alfanumérico)
•	ID da Empresa: ID da empresa parceira relacionada (inteiro ou alfanumérico)
•	ID da Tecnologia: ID da tecnologia utilizada (inteiro ou alfanumérico)
d) Colaborador:
•	ID: Identificador único do colaborador (inteiro ou alfanumérico)
•	Nome: Nome do colaborador (texto)
•	Cargo: Cargo do colaborador na empresa (texto)
•	ID da Empresa: ID da empresa parceira relacionada (inteiro ou alfanumérico)
3.	Relacionamentos entre as entidades:
•	Uma empresa parceira pode ter várias tecnologias registradas (relação um para muitos entre Empresa e Registro de tecnologias utilizadas, usando o ID da empresa).
•	Uma tecnologia pode estar presente em vários registros de tecnologias utilizadas (relação um para muitos entre Tecnologia e Registro de tecnologias utilizadas, usando o ID da tecnologia).
•	Um colaborador pertence a uma empresa parceira (relação um para muitos entre Empresa e Colaborador, usando o ID da empresa).


