# Client-Side

O que se segue é um registro, um conjunto de notas pessoais a respeito de minhas descobertas na exploração de vulnerabilidades Client-Side em **ambientes controlados**. Essas vulnerabilidades consistem em falhas que residem inteiramente no código executado no navegador do usuário (cliente), não no backend da aplicação (servidor). Como todo elemento client-side está sob controle do atacante, atributos desabilitados, validações em JS, campos ocultos e regras de exibição via CSS podem ser inspecionados e manipulados livremente via DevTools, proxies ou requisições forjadas manualmente. Das categorias mais comuns, XSS, DOM manipulation, bypass nas restrições de formulário e lógicas sensíveis, expostas no código-fonte.

### 🔗 Referências e/ou links úteis

[DOM based XSS Prevention Cheat Sheet (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/DOM_based_XSS_Prevention_Cheat_Sheet.html)
[DOM-based vulnerabilities (PortSwigger Web Security Academy)](https://portswigger.net/web-security/dom-based)
[Cross Site Scripting (XSS) – Saiba o que é e que tipos existem (Pplware, PT)](https://pplware.sapo.pt/tutoriais/networking/cross-site-scripting-xss-saiba-o-que-e-e-que-tipos-existem/)
[OWASP Testing Guide — Client-Side Testing (OTG-CLIENT)](https://wiki.owasp.org/index.php/Testing_for_Client_Side_URL_Redirect_(OTG-CLIENT-004))

---

## Out. de 2026 // 🦂🏴‍☠️
│ >  Tive de fazer uma requisição num formulário que estava desabilitado. Uma rápida análise no código fonte foi suficiente para descobrir um erro de design, uma falha client-side que permitia, através de uma alteração simples num atributo JS, ativar o formulário, fazer uma requisição e obter a flag final.

│ >  XYZ

│ >  XYZ

│ >  XYZ

│ >  XYZ

## Set. de 2026

│ >  Tive de obter as credenciais de acesso de uma interface de controle de dados (admin panel, p os íntimos, rs). Fui à análise do código fonte, e não teria encontrado nada, não fosse pela existência de um login.js, o código que possuia a function de login e, com ela, as credenciais necessárias e em texto claro, para logar na plataforma e obter a flag final. O mesmo repetia-se sempre que tentava acessar outros paineis da plataforma, com um detalhe a mais (ou a menos?): dessa vez, a senha não estava em um arquivo .js, mas no próprio código fonte.
 
│ >  XYZ

│ >  XYZ

│ >  XYZ

│ >  XYZ

## XXX. de XXXX // ☠️☠️

│ >  ???
