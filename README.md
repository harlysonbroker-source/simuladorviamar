# Simulador Viamar · Stanza

Simulador do plano de pagamento do Viamar (Stanza), feito pela Cavalcante Conexões Imobiliárias (CRECI 8699J).

- Tabela de preços: Viamar, setembro/2026 (V0). São 96 unidades disponíveis na Torre B (Orla).
- Regra: a Stanza parcela até 25% do valor do imóvel. O que passar disso vira sinal, pago no ato.
- O simulador inteiro está em um arquivo só (`index.html`), sem servidor e sem instalação.

## Publicar no GitHub Pages
1. Suba o `index.html` para a raiz do repositório.
2. Abra **Settings → Pages → Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
3. Em 1 a 2 minutos o site fica no ar em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

## Atualizar a tabela
Os preços ficam dentro do `index.html`, na lista `RAW`. Quando a Stanza lançar uma tabela nova, gere um novo `index.html` e substitua o arquivo no repositório.

Simulação sem valor de proposta. A tabela está sujeita a alteração.
