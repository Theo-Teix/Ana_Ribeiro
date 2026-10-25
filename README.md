# Nutricionista Ana Carolina Ribeiro

Site de página única da nutricionista Ana Carolina Ribeiro (CRN-3 78052), Salto, SP.
HTML, CSS e JavaScript puros, sem build. Todos os botões de agendamento abrem o WhatsApp (11) 97604-3761.

## Estrutura

```
index.html               página completa (estilos e scripts dentro do arquivo)
img/logo.png             logo original
img/ana-carolina-ribeiro.jpg
img/frutas.jpg
img/favicon.png          ícone da aba (monograma AR)
img/apple-touch-icon.png ícone ao salvar na tela do celular
vercel.json              cache das imagens e URLs limpas
```

## Publicar

1. Crie um repositório no GitHub e envie todos os arquivos desta pasta para a raiz dele.
2. Na Vercel, clique em **Add New → Project**, importe o repositório e mantenha:
   - Framework Preset: **Other**
   - Build Command: vazio
   - Output Directory: vazio (raiz)
3. Clique em **Deploy**. Cada novo commit no GitHub publica a atualização sozinho.

## Depois do primeiro deploy

Troque o endereço da imagem de prévia (linha `og:image` no `index.html`) pelo endereço completo do site,
por exemplo `https://nutri-anaribeiro.vercel.app/img/ana-carolina-ribeiro.jpg`,
para a foto aparecer quando o link for compartilhado no WhatsApp.

## Editar conteúdo

- Número do WhatsApp: variável `numero` no fim do `index.html` e os links `wa.me`.
- Mensagens automáticas: atributo `data-wa` de cada botão.
- Cores: variáveis no início do `<style>` (`--floresta`, `--salvia`, `--blush`).
