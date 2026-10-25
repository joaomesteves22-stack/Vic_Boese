# Site da Victoria Boese

Site estático de uma página. Não tem build, não tem dependência, não tem framework.

## Estrutura
- `index.html` — a página inteira (HTML, CSS e JS num arquivo só)
- `img/` — fotos e certificados já otimizados para web
- `curriculo-victoria-boese.pdf` — currículo que o botão entrega
- `vercel.json` — cache das imagens

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. vercel.com → Add New → Project → importe o repositório.
3. Framework Preset: **Other**. Build Command e Output Directory: deixe vazios.
4. Deploy.

A partir daí, cada push na branch principal republica o site.

## Trocar uma foto
Substitua o arquivo em `img/` mantendo o mesmo nome, ou edite o `src` na
seção `<section id="campo">`. Largura recomendada: 1100 px, qualidade 78.

## Editar texto
Tudo está em `index.html`, em português, nas seções `#sobre`,
`#trajetoria`, `#formacao` e `#contato`.

## Atenção
O certificado do SENAR em `img/cert-senar.jpg` está com o CPF removido.
Não substitua por uma cópia do PDF original: ele contém o CPF completo.

## Tema
O site é escuro por decisão de projeto e não acompanha o tema do sistema.
A paleta inteira está no bloco `:root` no topo do `<style>` em `index.html`.
