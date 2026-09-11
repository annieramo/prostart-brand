# ProStart — marca, logo e fotos da Annie

Repositório de assets da ProStart Academy e da Annie Ramos.

Existe para que qualquer máquina — o PC da Annie, o do Marco, ou o Claude
rodando em qualquer lugar — consiga puxar a logo, a paleta, as fontes e as
fotos da Annie sem depender do disco de ninguém.

Tudo aqui é público e pode ser baixado direto, sem conta no GitHub.

---

## Como baixar

**Tudo de uma vez:** botão verde `Code` → `Download ZIP`.

**Um arquivo só, por URL direta:** troque o caminho no fim da URL abaixo.

```
https://raw.githubusercontent.com/annieramo/prostart-brand/main/<caminho>
```

Exemplo — a logo positiva colorida em PNG:

```
https://raw.githubusercontent.com/annieramo/prostart-brand/main/logo/png/positivo-colorido.png
```

**Clonando pelo terminal:**

```bash
git clone https://github.com/annieramo/prostart-brand.git
```

---

## O que tem aqui

### `logo/`

| Arquivo | Quando usar |
|---|---|
| `png/positivo.png` · `svg/positivo.svg` | Logo sobre fundo claro, monocromática |
| `png/positivo-colorido.png` · `svg/positivo-colorido.svg` | Logo sobre fundo claro, colorida |
| `png/negativo.png` · `svg/negativo.svg` | Logo sobre fundo escuro, monocromática |
| `png/negativo-colorido.png` · `svg/negativo-colorido.svg` | Logo sobre fundo escuro, colorida |
| `svg/logotipo-prostart.svg` | Logotipo principal, vetor |
| `svg/logo-vertical.svg` | Versão vertical (empilhada) |
| `svg/asset-3.svg` a `asset-6.svg` | Variações do símbolo, vetor |
| `png/prostart-logo.png` | Logo em uso hoje no app-prostart.com |
| `png/prostart-icon.png` | Ícone quadrado, sem texto |
| `png/favicon.png` | Favicon de site |

SVG escala sem perder qualidade — prefira SVG sempre que o destino aceitar.
PNG só quando o lugar não aceitar vetor.

### `identidade/`

**Paleta** (`paleta-de-cores.txt`):

| Cor | Hex | Papel |
|---|---|---|
| Fundo | `#04090E` | Preto azulado, base de tudo |
| Roxo | `#AA00FF` | Cor de destaque principal |
| Turquesa | `#00DCD5` | Gradiente linear, ponta 1 |
| Azul | `#01ADFD` | Gradiente linear, ponta 2 |

**Fontes** (`fontes/`): dois sistemas convivem hoje, e é proposital anotar os dois.

- `fontes/satoshi/` — corpo de texto. Funciona bem em bold no título também.
- `fontes/apple-garamond/` — títulos e palavras em destaque. Usar com moderação.
- Os **materiais institucionais em HTML** (`~/PROSTART.SITE/materiais/`) não usam
  essas duas: usam Bebas Neue, Outfit e DM Sans, carregadas do Google Fonts. Se o
  trabalho for um material HTML da ProStart, siga o padrão dos arquivos de lá.
  Essas fontes locais são para peças gráficas.

### `fotos-annie/`

| Pasta | O que é |
|---|---|
| `ensaio-julho-2026/paineis/` | Os seis painéis de contato do ensaio — visão geral de cada linha |
| `ensaio-julho-2026/conceitos/` | Cinco conceitos: tech/IA, editorial claro, palco de autoridade, gradiente da marca, acolhedora |
| `ensaio-julho-2026/poses-hd/` | Cinco poses em alta resolução: braços cruzados, mãos no quadril, andando, recostada, braços abertos |
| `ensaio-julho-2026/nano-banana/` | Três looks: blazer bege, parka, verde com calça wide |
| `ensaio-julho-2026/street-elegante/` | Quatro cenas de rua: esquina, prédio, calçada, praça |
| `ensaio-dez-2024/` | Ensaio fotográfico real de dezembro de 2024 |
| `uso-no-app/` | A foto da Annie que já está em uso no app-prostart.com |

O ensaio de julho de 2026 é o que foi para o Instagram. As imagens de
`ensaio-dez-2024/` são fotografia; as de julho passaram por geração de imagem
a partir do rosto real.

---

## O que não está aqui, e por quê

A pasta `MARCA` original no disco tem 1,4 GB. O GitHub recusa qualquer arquivo
acima de 100 MB, então ficaram de fora:

- `VÍDEO -20251125T183157Z-1-001.zip` (424 MB)
- `FOTOS-20251125T183157Z-1-001.zip` (344 MB)
- Dois vídeos de 101 MB em `VIDEOS ANNIE` e `VIDEOS ANNIE MKT`

Também ficaram de fora as pastas que estão vazias no disco porque são do iCloud
e não foram baixadas: `fotos outubro`, `ENSAIO-MARCH2026`, `FOTOS FOZ`,
`FOTOS EQUIPE`, `CRIATIVOS SEM COPY`.

Se precisar de vídeo, o caminho é outro — Drive ou WeTransfer, não GitHub.
