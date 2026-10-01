# 🏢 SpaceAdmin ERP — Gestão Inteligente de Espaços e Locação

![SpaceAdmin Logo](https://raw.githubusercontent.com/Slyyd/spaceadmin-erp/main/docs/logo.png)

> **Projeto Acadêmico** — UNICID (Universidade Cidade de São Paulo)  
> **Curso:** Engenharia de Software
> **Disciplina:** Modelagem de Banco de Dados e Desenvolvimento Front-End
> **Campus:** Tatuapé — 2026  

---

## 👥 Integrantes do Grupo

- Alecsandro Sabino da Silva
- Felipe Alves de Souza
- Gustavo José da Silva
- Joao Victor Aversoni Branco Morais
- Jonathan Nilmar Mamani Chino
- Kauê Duarte Simões
- Nicolas Resende da Silva
- Pablo Ferreira de Lira
- Pedro Ricardo Lopes Bernardo
- Victor Araújo Biffe
- Vinicius Gonçalves de Magalhães

---

## 📌 Sobre o Projeto

O **SpaceAdmin ERP** é uma plataforma de gestão voltada para o setor imobiliário comercial e coworkings, desenvolvida para centralizar e otimizar a administração de imóveis e salas de locação flexível (por hora, diária ou período).

A solução conecta a oferta de espaços à demanda crescente por serviços *pay-per-use*, permitindo a monetização do tempo ocioso de salas comerciais e eliminando falhas operacionais como *overbooking*, descontrole de estoque e falta de integração entre setores.

---

## 🚀 Principais Módulos do Sistema

1. **Gestão de Acesso (RBAC):** Autenticação por perfis e permissões granulares.
2. **Pessoas e Clientes:** Cadastros validados de Clientes, Funcionários e Proprietários.
3. **Imóveis e Infraestrutura:** Gestão hierárquica (Proprietário ➔ Imóvel ➔ Sala ➔ Equipamentos) e controle de disponibilidade.
4. **Reservas e Operações:** Agendamentos flexíveis com checkout integrando automaticamente a vistorias e liberação do espaço.
5. **Limpeza e Manutenção:** Abertura de ordens de serviço, interdição automática de salas e rastreabilidade de consumo de insumos.
6. **Estoque e Compras:** Controle de movimentações, cadastro de fornecedores, alerta de estoque mínimo e pedidos de compra.
7. **Financeiro:** Gestão de contas a pagar/receber, conciliação de pagamentos e cálculo de repasse aos proprietários.
8. **Dashboard & Relatórios:** Indicadores em tempo real de ocupação, faturamento e custos operacionais.

---

## 📂 Estrutura do Projeto

```text
SpaceAdmin/
│
├── index.hml                         # Página principal do site
│
├── docs/                             # Documentações do projeto e diagramas
│   ├── SpaceAdmin.docx               # Documento descritivo completo
│   ├── DER.pdf                       # Diagrama Entidade-Relacionamento
│   └── fluxograma.png               # Fluxogramas dos processos de negócio
│
└── src/
    ├── assets/                       # Recursos estáticos do sistema
    │   └── images/                   # Imagens utilizadas nas páginas HTML (Logos, Ícones, Banners)
    │
    └── pages/                        # Interfaces HTML do protótipo web
        ├── agenda.html
        ├── clientes.html
        ├── compras.html
        ├── configuracoes.html
        ├── estoque.html               
        ├── financeiro.html            # (Pendente)
        ├── funcionarios.html
        ├── imoveis.html               # (Pendente)
        ├── limpeza.html
        ├── locadores.html
        ├── manutencao.html
        ├── relatorios.html
        ├── reservas.html
        ├── usuarios.html              # (Pendente)
        └── portifolio.html