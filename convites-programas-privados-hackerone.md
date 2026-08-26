# Convites para programas privados no HackerOne

Direto ao ponto: convite para programa privado no HackerOne é resultado de **Signal e Impact**, não de volume de relatórios. E isso muda completamente a estratégia.

## Como o convite funciona na prática

O algoritmo de convite olha basicamente:

- **Signal** — média de reputação por relatório (escala de -10 a 7). Cada N/A, spam ou duplicata derruba isso. Um hunter com 5 relatórios válidos e zero inválidos tem Signal melhor que um com 20 válidos e 30 inválidos.
- **Impact** — severidade média dos achados válidos. Cinco XSS refletidos valem menos que um IDOR bem demonstrado.
- **Atividade recente** — conta se você aceita convite e some. Recusar é melhor que aceitar e ignorar; hunter não responsivo entra numa espécie de lista fria.
- **Skills declaradas no perfil** — programas conseguem buscar hunters por expertise específica. Perfil vazio não aparece nessa busca.

A disciplina de PoC antes de reportar é exatamente o que protege o Signal. A maioria dos hunters que empaca em programa público empaca porque queima Signal atirando para todo lado.

## Alavancas mais rápidas

**Hacker101 CTF.** É o caminho mais direto e menos falado. As flags do CTF disparam convites automáticos para programas privados — é literalmente um funil de recrutamento da HackerOne. Para quem já é pentester sênior, é fim de semana de trabalho.

**VDPs (Vulnerability Disclosure Programs).** Sem bounty, mas constroem reputação rápido e têm muito menos concorrência porque a maioria dos hunters ignora programa que não paga. É investimento em Signal.

**Verificação de identidade.** Existe uma camada de programas que só aceita hunter com ID verificado. Vale fazer.

**Perfil 100% preenchido** com as skills em que você tem profundidade real, que você manda bem.
