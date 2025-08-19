# Projeto Pistola de Abastecimento de Óleo Inteligente - Grupo New

<div align="center">
  <p>
    <img src="https://embarcatech.cepedi.org.br/img/logo-embarcatech.png" width="300" alt="Logo do Programa EmbarcaTech">
    <img src="https://private-user-images.githubusercontent.com/159396360/479581156-91c31407-dda5-4849-937d-9974016fbb65.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTU2MTY0OTksIm5iZiI6MTc1NTYxNjE5OSwicGF0aCI6Ii8xNTkzOTYzNjAvNDc5NTgxMTU2LTkxYzMxNDA3LWRkYTUtNDg0OS05MzdkLTk5NzQwMTZmYmI2NS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgxOVQxNTA5NTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00MTM4M2YwYThmNDhhNjE5ZTViM2QxMzdjZDk4MjIzZWU3ZTk4OTcwOWRhOGFlZjkwZGMxMGE2MWI3Y2JiNWQ5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.aqfxHcboizvzt3O9ljoQOKLgjQw7wqpojL7aG0bqqyw" width="300" style="margin-left:80px; margin-bottom:20px" alt="Logo da Toyota Newland">
  </p>
</div>

Bem-vindo à organização do GitHub para o projeto **Pistola de Abastecimento de Óleo Inteligente**. Esta é uma iniciativa desenvolvida dentro do programa de **Residência Tecnológica em Sistemas Embarcados - EmbarcaTech**, uma parceria entre os residentes do Instituto Federal do Piauí (IFPI) e a empresa receptora Newland Veículos LTDA.

## Sobre o Projeto

O objetivo principal deste projeto é desenvolver um sistema de dispersão de óleo lubrificante autônomo, realizando uma engenharia reversa nas pistolas existentes na Toyota Newland. O plano envolve substituir o microcontrolador original e reprogramar as pistolas com um software próprio para replicar e aprimorar as funcionalidades atuais. A finalidade é eliminar a dependência de terceiros para manutenção e suporte, permitindo que a própria empresa tenha autonomia na gestão da solução.

**Duração do Projeto:** 01 de Junho de 2025 até 09 de Março de 2026.

## O Desafio

A visita inicial à Newland permitiu diagnosticar os principais desafios do sistema atual de dispersão de óleo:

* **Dependência Externa:** O principal problema é a dependência de empresas externas para a manutenção e suporte técnico das pistolas de dispersão.
* **Obsolescência:** O sistema atual, embora funcional, apresenta desempenho avariado tanto no hardware quanto no software. Os equipamentos estão obsoletos e não possuem mais suporte da empresa de origem.
* **Desgaste Físico:** A estrutura das pistolas demonstra bastante desgaste pelo tempo de uso, o que resulta em mau funcionamento.
* **Falta de Autonomia:** A equipe interna não possui controle para gerenciar ou manter o sistema de forma autônoma.

## Nossa Solução

Nossa missão é desenvolver um sistema de dispersão de óleo que seja **autônomo, preciso, moderno e econômico**. A solução proposta inclui:

* **Hardware:** Substituição do microcontrolador original das pistolas por uma plataforma moderna como o **ESP32 ou PICO W**, que possui Wi-Fi integrado, baixo consumo de energia e capacidade de processamento adequada. Sensores de vazão serão utilizados para garantir a precisão.
* **Firmware:** Desenvolvimento de um firmware do zero em **linguagem C**. Este firmware controlará todas as funcionalidades da pistola, incluindo a interface com o usuário, sensores e atuadores.
* **Software (Back-end):** O sistema se comunicará via Wi-Fi com um servidor externo (também desenvolvido pela equipe) para gerenciar Ordens de Serviço (OS), autenticação de mecânicos e registros de aplicação.
* **Funcionalidades Planejadas:**
  * Liberação automática do óleo até que a quantidade exata definida na Ordem de Serviço seja atingida.
  * Monitoramento preciso do volume e da vazão do óleo dispensado.
  * Emissão de aviso sonoro ao final da aplicação.
  * Exibição do número da OS e do nível de bateria na interface da pistola.

## Etapas do Projeto

O projeto está organizado em etapas bem definidas para garantir a construção e integração do sistema:

1. **Imersão e Diagnóstico:** Entendimento do hardware e escopo do projeto. **(Concluída)**.
2. **Desenvolvimento de Software/Firmware:** Foco no firmware da pistola e na estrutura do back-end. **(Em andamento)**.
3. **Montagem e Teste do Protótipo:** Integração dos componentes na pistola e início dos testes de bancada.
4. **Produção do Protótipo Funcional:** Construção de uma unidade para apresentação e testes em ambiente real na oficina.
5. **Documentação Final e Treinamento:** Entrega de toda a documentação do projeto (código-fonte, esquemáticos, manuais) e capacitação da equipe Newland.

## Equipe

### Residentes

* Arthur Vieira Melo Silva
* Francisco Alexandro Conceição de Sousa
* Islânio Pablo dos Santos Luz
* Nícolas Rafael Silva Alves
* Yan Pereira de Lima

### Orientadores

* **Instrutor:** Daniel Ferreira da Ponte
* **Monitor:** João Paulo da Silveira Pinheiro
* **Monitor:** José Ritomar Carneiro Torquato
* **Monitor:** Márcio Antônio Dias Pereira

### Empresa Receptora

* **Responsável Técnico:** Moisés Santos e Santos (Gerente de Pós-Vendas)

## Repositórios
