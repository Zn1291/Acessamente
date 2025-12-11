# Acessamente
Aplicativo para facilitar acesso a apoio terapeutico com valores acessíveis

Protótipo navegavel:https://bit.ly/Prototipo_figma_acessamente
# Acessamente

Plataforma digital para intermediação de apoio psicológico, voltada à democratização do acesso à terapia para indivíduos das classes média e baixa. O projeto conecta profissionais da psicologia dispostos a oferecer atendimentos gratuitos ou com valores sociais a usuários que necessitam de suporte terapêutico, mas enfrentam barreiras financeiras ou geográficas.

---

## Objetivos

### Objetivo Geral
Desenvolver um aplicativo acessível e funcional que promova o atendimento psicológico online com valores sociais ou gratuitos.

### Objetivos Específicos
- Permitir o cadastro de psicólogos com CRP válido, especializações e disponibilidade.
- Facilitar o cadastro de pacientes com dados pessoais e socioeconômicos.
- Viabilizar atendimentos presenciais, online ou híbridos.
- Garantir triagem e critérios de elegibilidade para direcionar atendimentos.
- Promover inclusão social e democratização do acesso à saúde mental.
- Assegurar proteção de dados e confidencialidade (LGPD).

---

## Tecnologias Utilizadas

- Frontend: React Native  
- Backend: PHP  
- Banco de Dados: PostgreSQL ou Firebase  
- Integrações: Google Meet / Zoom  
- Analytics: Firebase Analytics  
- Prototipagem: Figma  
- Gestão de Projeto: Trello / GitHub Projects (Kanban)

---

## Funcionalidades Principais

- Cadastro de pacientes e psicólogos  
- Login seguro e recuperação de senha  
- Busca de profissionais com filtros (modalidade, especialidade, preço, região)  
- Agendamento de consultas e gerenciamento de agenda  
- Notificações automáticas de lembretes e confirmações  
- Mensagens diretas entre paciente e psicólogo  
- Área de conteúdos educativos (artigos, vídeos, dicas de bem-estar)  
- Avaliação e feedback após sessões  
- Relatórios gerenciais e métricas de impacto social  
- Armazenamento seguro e criptografia ponta a ponta  

---

## Requisitos Não Funcionais

- Comunicação segura via HTTPS
- Senhas criptografadas com bcrypt
- Conformidade com a LGPD
- Resposta em até 2 segundos em condições normais
- Suporte a até 10.000 usuários simultâneos
- Interface responsiva e intuitiva
- Uptime mínimo de *99,5%
- Backups automáticos diários (retenção de 30 dias)

---

## Casos de Uso

Principais atores:
- Paciente: busca, agenda e realiza sessões.  
- Profissional: oferece serviços, gerencia agenda e valores.  
- Administrador: gerencia cadastros, monitoramento e relatórios.  
- Sistema externo: integrações, lembretes e validações.

Exemplos de casos de uso:
- Entrar (Login)  
- Cadastrar-se como paciente/profissional  
- Buscar profissional e reservar consulta  
- Gerenciar reservas (confirmar, reagendar, cancelar)  
- Fazer sessão online (Google Meet/Zoom)  
- Avaliar atendimento  
- Acessar conteúdos educativos  

---

## Testes

### Testes de Caixa-Preta
- Login com credenciais inválidas → mensagem de erro.  
- Agendamento de horário já reservado → bloqueio e notificação.  
- Cadastro de profissional com CRP inválido → erro de validação.  
- Busca com múltiplos filtros → retorno apenas de profissionais compatíveis.  
- Sessão online → integração com Google Meet/Zoom.

### Testes de Aceitação
- Fluxo completo de busca, agendamento e cancelamento.  
- Criação e gerenciamento de agenda por profissional.  
- Suspensão de conta por administrador e bloqueio de login.  

---

## Cronograma

### Etapas Principais
- Requisitos iniciais: ago/2025 – out/2025  
- Documentação técnica: out/2025 – dez/2025  
- Desenvolvimento: mar/2026 – jul/2026  
- Testes e lançamento: jun/2026 – jul/2026  

---

## Resultados Esperados

- Impacto social: ampliar acesso à terapia psicológica para classes média e baixa.  
- Tecnologia: aplicativo multiplataforma estável e seguro.  
- Inclusão: fortalecimento da cultura de responsabilidade social na psicologia.  
- Monitoramento: métricas de uso e satisfação via Firebase Analytics.  

---

## Equipe

- Integrantes: Leandro Zeni, Vinicius Andrade Henrique  
- Orientadoras: Eliana Maria dos Santos, Lauriana Paludo  
- Instituição: Instituto Federal do Paraná – Campus Pinhais  

---

## Referências

- SILVA ET AL. (2021) – Saúde mental e desigualdade socioeconômica.  
- ANTUNES (2022) – Psicoterapia e economia do compartilhamento.  
- PEREIRA & OLIVEIRA (2023) – Barreiras de acesso à psicologia.  
- WALTER & OLIVEIRA (2025) – Inclusão digital em saúde mental.  
- FRANKL, Viktor (2022) – Reflexões sobre saúde mental e sentido da vida.  

---

## Status do Projeto

Em fase de documentação técnica e planejamento de desenvolvimento.  
Próximas entregas: protótipo no Figma e implementação inicial no GitHub.
