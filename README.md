# Imagens do site Sosucesso

Repositório público que serve as imagens do site **sosucessomedicamentos.com.br**.

A ideia é simples: **trocar a imagem aqui troca a imagem no site**, sem mexer em
código e sem precisar de painel. O site lê estes arquivos direto por URL pública.

## Como usar

1. Escolha a pasta pelo tipo de imagem.
2. Suba o arquivo com um **nome fixo** (sobrescrevendo o anterior) — se mudar o
   nome, o site não encontra.
3. Espere de 1 a 5 minutos. O site passa a mostrar a imagem nova.

Não é preciso avisar ninguém nem publicar o site de novo.

## Estrutura

```
site/     imagens da estrutura do site
  logo.png            logo do cabeçalho (quadrado, fundo transparente)
  mapa-loja.png       mapa da localização com o pino na loja

ofertas/  fotos dos produtos das ofertas
  salonpas.png
  strepsils.png
  decongex.png
  sibionics.jpg

social/   imagem de prévia ao compartilhar o link
  og-sosucesso.png    1200 x 630 (proporção usada por WhatsApp, Instagram,
                      Facebook, LinkedIn e Telegram)
```

## Regras de tamanho

| Pasta | Formato | Tamanho |
|---|---|---|
| `site/logo.png` | PNG, fundo transparente | 256 × 256 ou maior, **quadrada** |
| `site/mapa-loja.png` | PNG ou JPG | 732 × 694 |
| `ofertas/` | JPG ou PNG | proporção **4:5** (ex.: 600 × 750) |
| `social/og-sosucesso.png` | PNG | **1200 × 630** |

Foto fora de proporção é cortada nas laterais pelo card do site. O card é
vertical (4:5), então foto deitada perde a embalagem nas bordas.

## Recomendações para foto de oferta

- Produto **de frente**, embalagem inteira no quadro.
- Fundo branco ou transparente.
- Sem preço escrito na imagem: preço vai no texto do card. **Medicamento com
  tarja vermelha não pode exibir preço** (RDC 96/2008) — nesse caso a imagem
  entra só com o produto e o card mostra o aviso.

## Atenção

Repositório **público**: qualquer pessoa com o link vê as imagens. Não coloque
aqui documento, foto de cliente, CPF, nota fiscal ou material interno.
