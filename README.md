# Rejane Real

Páginas do Studio Rejane Real (Nobres-MT), publicadas na Vercel.

| Caminho | Página |
|---|---|
| `/lash-lifting-shine` | Landing page do curso Lash Lifting Shine (lançamento R$ 97) |
| `/` | Redireciona para `/lash-lifting-shine` por enquanto |

## Configurar antes de rodar anúncios

No fim de `lash-lifting-shine/index.html`, bloco `CONFIG`:

- `pixelId`: ID do Pixel da Meta
- `checkoutUrl`: link do checkout da Kiwify
- `offerEnds`: data real de fim do preço de lançamento (vazio = sem contador)

O evento de compra (Purchase) é disparado pela Kiwify: configure o mesmo pixel nas configurações do produto.

## Publicação

Site estático, sem build. Cada push na `main` publica na Vercel.
