# Organização no Pentest

Repositório com guias, processos e melhores práticas para estruturar e implantar programas de segurança ofensiva em empresas.

> Foco: De zero a um programa de pentest **que realmente funciona**.

---

## 📋 Conteúdo

### 1. **[Guia: Primeiro Pentester na Empresa](./primeiro-pentester-guia.md)**

Guia completo para quem é o **primeiro pentester** entrando em uma organização e precisa criar um programa de segurança ofensiva do zero.

**O que cobre:**
- Pergunta fundamental: "Para quem vão as vulnerabilidades?"
- Fase de diagnóstico (entender maturidade da org)
- Estruturação do programa (SLA, tracking, processo)
- Como começar controlado (não sobrecarregar)
- Escalabilidade (expansão gradual)
- Riscos comuns e como evitar
- Checklist de implementação

**Ideal para:**
- Pentester entrando em startup/empresa
- Security Manager estruturando primeiro programa
- CTO/CISO pensando em criar equipe ofensiva

---

## 🚀 Como Usar Este Repositório

1. **Você é novo em pentesting ofensivo?**
   → Leia o guia do começo ao fim

2. **Você vai montar um programa?**
   → Use o checklist de implementação

3. **Seu programa já existe mas tem problemas?**
   → Consulte a seção "Riscos Comuns"

---

## 📁 Estrutura Planejada

```
/organizacao-pentest
├── README.md (você está aqui)
├── primeiro-pentester-guia.md
├── /templates          (templates prontos)
│   ├── finding-template.md
│   ├── sla-agreement.md
│   └── weekly-sync-agenda.md
├── /processos          (processos documentados)
│   ├── triagem-findings.md
│   ├── escalacao.md
│   └── metricas.md
└── /exemplos           (exemplos práticos)
    ├── empresa-pequena.md
    ├── empresa-media.md
    └── empresa-grande.md
```

*(Será expandido com o tempo)*

---

## ⚡ TL;DR - 3 Princípios Fundamentais

Se você não tiver tempo pra ler tudo, lembre-se desses 3:

### 1. **Estrutura Antes de Testar**
Não comece pentesting sem saber quem vai remediar, quem vai priorizar, e qual é o SLA.

### 2. **Comece Pequeno**
1-2 aplicações com processo perfeito > 10 apps com caos

### 3. **Seja Parceiro, Não Polícia**
Dev team não é inimigo. Você está junto pra ajudar a remediar.

---

## 🎯 Objetivo

Este repositório existe pra que quando você entrar em uma empresa como primeiro pentester, você não cometa os erros clássicos:

❌ Testar, encontrar 50 vulns, ninguém remediar
❌ Criar frustração entre Dev e Security
❌ Program virar inútil em 3 meses

✅ Estruturar um processo que funciona
✅ Ganhar credibilidade rapidamente
✅ Criar programa sustentável

---

## 📚 Referências Úteis

- [OWASP Secure SDLC](https://cheatsheetseries.owasp.org/)
- [Responsible Disclosure](https://www.eff.org/issues/responsible-disclosure)
- [Metrics for Security Programs](https://www.cisa.gov/)

---

## 🤝 Contribuições

Tem um processo, template, ou dica que funcionou bem pra você?

**Contribuições são bem-vindas!** Abra uma issue ou faça um PR com melhorias.

---

## 📝 Licença

Conteúdo livre para uso educacional e comercial. Cite a fonte quando usar.

---

**Última atualização**: Janeiro 2025

**Mantido por**: [Iran Macedo](https://github.com/ifmacedo) - Agility Networks Tecnologia | AulasHack
