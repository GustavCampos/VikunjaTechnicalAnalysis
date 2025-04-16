# 🛤️ Roadmap do Projeto: Avaliação e Perícia do Software Livre Vikunja

## 1. Planejamento e Preparação

### **Definir objetivos do projeto**  
  


#### ✅ Objetivo 1 – Avaliar a segurança do Vikunja enquanto software livre
- [ ] Identificar mecanismos de autenticação utilizados (ex: JWT, senhas criptografadas)  
- [ ] Analisar controle de acesso e permissões de usuários  
- [ ] Verificar proteção contra ataques comuns (XSS, CSRF, injeção de código)  
- [ ] Testar possíveis endpoints sensíveis expostos publicamente  
- [ ] Verificar como os dados dos usuários são armazenados e trafegam  

#### ✅ Objetivo 2 – Investigar boas práticas de segurança adotadas no código-fonte
- [ ] Avaliar uso de variáveis de ambiente para dados sensíveis  
- [ ] Analisar se senhas e tokens são criptografados adequadamente  
- [ ] Conferir se há testes automatizados cobrindo fluxos críticos  
- [ ] Verificar dependências utilizadas e se estão atualizadas  
- [ ] Observar práticas de versionamento e CI/CD no repositório  

#### ✅ Objetivo 3 – Analisar a transparência e maturidade do projeto como software open source
- [ ] Observar a frequência de commits e releases  
- [ ] Verificar tempo médio de resposta para issues e pull requests  
- [ ] Identificar existência de políticas de segurança e governança  
- [ ] Avaliar documentação para usuários e colaboradores  
- [ ] Analisar nível de participação da comunidade no GitHub  

#### ✅ Objetivo 4 – Analisar a arquitetura e as tecnologias utilizadas no projeto Vikunja
- [ ] Mapear os principais componentes do sistema (frontend, backend, banco de dados)  
- [ ] Identificar as linguagens, frameworks e bibliotecas utilizadas (ex: Go, Vue.js)  
- [ ] Verificar se o sistema utiliza contêineres (ex: Docker, docker-compose)  
- [ ] Analisar a modularidade do projeto e sua escalabilidade  
- [ ] Avaliar como ocorre a comunicação entre os módulos (ex: REST, APIs internas)  

---

### **Revisar conceitos de avaliação e perícia de software**  
  → Ex: O que é perícia técnica em software? Que normas ou guias utilizar (ex: ISO/IEC 25010)?

---

### **Coletar informações sobre o Vikunja**  
  → Origem, licença, comunidade, tecnologias utilizadas (Go, Vue.js), arquitetura, etc.

---

## 2. Instalação e Familiarização

### **Instalar o Vikunja (backend + frontend)**  
  → Documentar o processo, possíveis dificuldades.

### **Explorar funcionalidades**  
  → Criação de tarefas, projetos, times, etiquetas, integrações, etc.

---

## 3. Análise Técnica

### **Inspeção do código-fonte**  
  → Analisar organização, padronização, presença de testes, documentação.

### **Análise de segurança**  
  → Uso de dependências, práticas seguras de autenticação/autorização, possíveis vulnerabilidades.

### **Avaliação de qualidade de software**  
  → Usar ISO/IEC 25010 para verificar atributos como usabilidade, manutenibilidade, portabilidade, etc.

### **Execução de testes**  
  → Testes funcionais e não funcionais (desempenho, segurança básica).

---

## 4. Perícia Técnica

### **Identificação de riscos e falhas**  
  → Potenciais problemas críticos: falhas lógicas, riscos de segurança, inconsistências.

### **Emissão de laudo técnico/pericial**  
  → Relatório que descreve os achados, metodologia, evidências coletadas, conclusões e recomendações.

---

## 5. Conclusão e Apresentação

#### **Redigir conclusão crítica sobre o Vikunja**  
  → Pontos fortes, limitações, possíveis melhorias.

#### **Organizar materiais para entrega/apresentação**  
  → Slides, documento final, resumo expandido, anexos (prints, logs, código analisado).
