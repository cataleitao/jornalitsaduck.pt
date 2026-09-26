# jornalitsaduck.pt

Site estático do *Jornal, if it walks like a duck and it talks like a duck, it's a duck*
(ESAD.CR / LIDA). Sem dependências: HTML, CSS e imagens.

## Estrutura

    index.html            Apresentação
    numeros.html          Arquivo de todos os números
    como-submeter.html    Normas, calendário e submissão
    inscricao.html        Formulário de inscrição nas chamadas
    css/jornal.css        Folha de estilos única
    img/mastro.png        Cabeçalho
    img/capas/            Fotografias de cada número (jornal-N.jpg)
    img/logos/            ESAD.CR, LIDA, FCT
    pdf/                  Números em PDF (jornal-N.pdf)
    CNAME                 Domínio próprio (GitHub Pages)
    2022/, 2025/          Redirecionamentos dos endereços antigos do WordPress

## Acrescentar um número novo

1. `pdf/jornal-12.pdf` — o PDF para descarregar.
2. `img/capas/jornal-12.jpg` — fotografia do exemplar, 1400 px de largura, JPEG a 82%.
3. Em `numeros.html`, copiar o bloco comentado que está no topo da lista,
   colá-lo logo a seguir e trocar o número, o tema e o peso do ficheiro.
4. Em `como-submeter.html`, actualizar o calendário da chamada seguinte.
