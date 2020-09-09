---
display: "disableReferencedProjectLoad"
oneline: "Reduz o número de projetos carregados automaticamente pelo TypeScript"
---

Em programas TypeScript de vários projetos, o TypeScript carregará todos os projetos disponíveis na memória a fim de fornecer resultados precisos para as respostas do editor que requerem um gráfico de conhecimento completo como 'Localizar todas as referências'.

Se o seu projeto for grande, você pode usar o sinalizador `disableReferencedProjectLoad` para desativar o carregamento automático de todos os projetos. Em vez disso, os projetos são carregados dinamicamente à medida que você abre arquivos por meio de seu editor.
