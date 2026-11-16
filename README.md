# Marcelo Lucas Silva

Atuo na fronteira entre a LGPD e o código.

Venho do Direito — perícia judicial, direito tributário, licitações. Hoje escrevo ferramentas que auditam sistemas procurando exposição de dado pessoal e traduzem cada achado para o dispositivo legal correspondente.

A lacuna que tento ocupar é concreta: o parecer jurídico que o time técnico não sabe aplicar não protege ninguém, e a correção técnica que ignora o artigo não sustenta uma defesa.

---

### 🔎 [lgpd-scan](https://github.com/Marcelo-Lucas-Silva/lgpd-scan)

Análise estática de exposição de dados pessoais, com os achados mapeados aos artigos da Lei 13.709/2018.

Scanners de segredo apontam que há uma chave de API no seu código. Nenhum diz que aquilo é o Art. 46, que a providência é corrigir e documentar, e que a documentação da correção pesa na dosimetria da sanção pelo Art. 52, § 1º, IX.

- 9 regras de detecção, 4 com validador próprio
- CPF e CNPJ validados por módulo 11; cartão por Luhn; telefone por DDD e faixa de assinante
- Relatório mascara o que encontra, para não virar uma segunda cópia do vazamento
- 83 testes, incluindo regressões nascidas de falsos positivos reais

`Python` · `análise estática` · `LGPD`

---

### Estudando agora

- Fundamentos de segurança da informação (ISC2 CC)
- Python aplicado a automação de auditoria
- Resposta a incidente e dever de comunicação do Art. 48

### Interesses

Governança, risco e conformidade. Perícia digital. O ponto em que a obrigação legal vira requisito técnico — e o inverso.

---

*Aberto a conversas sobre adequação à LGPD, auditoria de código e perícia em informática.*
