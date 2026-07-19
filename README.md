# Data Bravo — Landing Page

Landing page institucional da **Data Bravo**, software house especializada em desenvolvimento de sistemas, plataformas, automações e produtos SaaS sob medida.

## Sobre o arquivo

O site inteiro é **um único arquivo**: `index.html`.

Tudo está embutido dentro dele:

- Fontes (Clash Display, Satoshi, Poppins) em base64
- Logo oficial da marca em base64
- Ícones das linguagens e frameworks em SVG
- Todo o CSS e JavaScript inline

Ou seja: **não depende de CDN, pasta de imagens ou qualquer recurso externo**. Basta abrir o arquivo, ou servi-lo de qualquer lugar, que ele funciona.

## Publicar com GitHub Pages

1. Suba este repositório para o GitHub
2. No repositório, vá em **Settings → Pages**
3. Em **Source**, escolha a branch `main` e a pasta `/ (root)`
4. Salve

Em cerca de um minuto o site estará no ar em:

```
https://<seu-usuario>.github.io/<nome-do-repositorio>/
```

### Domínio próprio (databravo.com.br)

Ainda em **Settings → Pages**, preencha o campo **Custom domain** com `databravo.com.br` e configure no seu provedor de DNS:

| Tipo  | Nome | Valor                        |
|-------|------|------------------------------|
| CNAME | www  | `<seu-usuario>.github.io`    |
| A     | @    | `185.199.108.153`            |
| A     | @    | `185.199.109.153`            |
| A     | @    | `185.199.110.153`            |
| A     | @    | `185.199.111.153`            |

Depois marque **Enforce HTTPS**.

## Editar o site

Como é um arquivo único, qualquer alteração é feita direto no `index.html`. As seções estão comentadas no CSS para facilitar a navegação (hero, MVP, serviços, cases, diferenciais, processo, stack, FAQ, CTA).
