## 🧩 Régua de Relacionamento – Petlove (Cross-Sell: Ração + Brinquedos)

Esta régua de relacionamento foi criada para uma campanha de **cross-sell** que oferece brinquedos para clientes que compraram ração. O foco está na **personalização por comportamento e espécie**, utilizando uma **estratégia multicanal** ao longo de 5 dias.

---

### 📡 Estratégia Multicanal

| Dia     | Canal     | Ação                                                                 |
|---------|-----------|----------------------------------------------------------------------|
| D0      | Email     | Sugestão de brinquedos + cupom exclusivo com nome do pet             |
| D+2     | Push      | Enviado só se o cliente **não abriu o email**                        |
| D+4     | SMS       | Último contato, CTA com urgência (“Último dia!”)                     |
| D+5     | Email     | Agradecimento + cupom se o cliente comprou                           |
| Bounce  | Push/SMS  | Redirecionamento para canal alternativo em caso de falha             |

---

### 🎯 Personalizações aplicadas
- Nome do pet no assunto
- Recomendações por espécie (gato ou cachorro)
- Porte (pequeno, médio, grande)
- Ticket médio do cliente

---

### 🔄 Respostas automatizadas por comportamento

- **Abriu o e-mail**: espera até D+2
- **Clicou no CTA**: espera até D+5 ou envia agradecimento
- **Comprou**: sai da régua e recebe cupom futuro
- **Bounce**: redireciona para canal alternativo
- **Não respondeu**: segue fluxo até D+5

---

### ✅ Boas práticas consideradas

- Intervalo mínimo de 48h entre disparos
- Personalização avançada por perfil de compra
- Sem sobrecarga de comunicação

> Exercício desenvolvido no curso de CRM Marketing da EBAC com base em um case fictício da Petlove.
