# Nutricionista Ana Carolina Ribeiro

Site de página única da nutricionista Ana Carolina Ribeiro (CRN-3 78052), Salto, SP.
HTML, CSS e JavaScript puros, sem build. Todos os botões de agendamento abrem o WhatsApp (11) 97604-3761.

Versão 2 (09/11/2026): abertura escura em verde-floresta com a foto em arco e os anéis do logo, frase que acende na rolagem, serviços em painéis que se expandem, "O que inclui" em grade colorida, planos com mostradores, avaliações em destaque, horários com "aberto agora" e mapa do consultório.

## Estrutura

```
index.html                 página completa (estilos e scripts dentro do arquivo)
img/logo.png               logo original (topo depois de rolar)
img/logo-claro.png         logo com o nome em creme (topo sobre o verde e rodapé)
img/monograma.png          monograma "AR" com o ramo (marcas d'água)
img/monograma-claro.png    monograma em versão clara (fundos escuros)
img/ana-carolina-ribeiro.jpg
img/frutas.jpg
img/favicon.png            ícone da aba
img/apple-touch-icon.png   ícone ao salvar na tela do celular
vercel.json                configuração da Vercel (URLs limpas)
```

## Publicar

1. No repositório do GitHub (Ana_Ribeiro), envie todos os arquivos desta pasta para a raiz.
   Importante: **arraste a pasta `img` inteira** para a área de upload. O botão "choose your files" não envia pastas.
2. Na Vercel, o projeto `nutri-anaribeiro` publica sozinho a cada commit (Framework Preset: **Other**, sem Build Command).
3. Confira em https://nutri-anaribeiro.vercel.app/.

## Imagens

Ao trocar uma imagem mantendo o mesmo nome, aumente o número `?v=` nos links do `index.html` (por exemplo `?v=3`) para os navegadores baixarem a versão nova.

## Editar conteúdo

- Número do WhatsApp: variável `numero` no fim do `index.html`.
- Mensagens automáticas: atributo `data-wa` de cada botão.
- Horários: tabela `.horarios` (o selo "Aberto agora" usa os horários definidos em `fecha` no script).
- Cores: variáveis no início do `<style>` (`--floresta`, `--salvia`, `--blush`).
