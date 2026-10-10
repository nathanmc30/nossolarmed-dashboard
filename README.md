# Funil comercial · NossoLarMed

Dashboard do funil do lead à venda: leads do Kommo cruzados pelo telefone com a agenda e os orçamentos do Clinicorp.

- `index.html`: a página, sem dependências (abre direto do disco).
- `dados.js`: **só números agregados**, sem nome, telefone ou id de paciente. Gerado por `scripts/analise-funil.mjs` do projeto local `C:\Dev\nossolarmed`, a partir das extrações em `dados/` (que nunca saem da máquina).
- `fontes/`: Inter (OFL), a mesma do Aspekto Business.

Atualizar:

```
node C:\Dev\nossolarmed\scripts\analise-funil.mjs C:\Dev\nossolarmed-dashboard
```

Documentação: vault `Clientes/NossoLarMed/05-DASHBOARDS.md`.
