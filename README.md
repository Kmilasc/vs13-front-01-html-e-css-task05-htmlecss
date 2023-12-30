Análise crítica e planejamento de possíveis problemas:
1. Acessibilidade Visual
Problema: Usuários com deficiência visual podem ter dificuldade em navegar pelo site se as informações visuais não forem acessíveis.
Soluções:
Garantir que todas as imagens tenham descrições alt text apropriadas.
Usar um bom contraste de cores entre o texto e o fundo.
Permitir que o texto seja redimensionado sem perder a funcionalidade do site.
Evitar conteúdo exclusivamente visual, como CAPTCHAs baseados em imagem.
2. Acessibilidade Auditiva
Problema: Usuários com deficiência auditiva não poderão acessar informações transmitidas apenas por áudio.
Soluções:
Fornecer legendas ou transcrições para todos os vídeos e conteúdos de áudio.
Assegurar que toda a comunicação possa ser realizada via texto (por exemplo, formulários de contato e chat online).
3. Acessibilidade Motora
Problema: Usuários com limitações motoras podem ter dificuldade em interagir com elementos de interface que requerem precisão ou são muito pequenos.
Soluções:
Tornar todos os elementos clicáveis (como links e botões) grandes o suficiente para serem facilmente acionados.
Assegurar que o site possa ser navegado apenas com o teclado.
Implementar tempo de resposta flexível para ações que requerem interações rápidas.
4. Acessibilidade Cognitiva
Problema: Usuários com dificuldades cognitivas podem achar o site confuso se a informação for muito complexa ou a navegação for complicada.
Soluções:
Manter um design claro e consistente em todo o site.
Fornecer instruções claras e simples.
Evitar o uso excessivo de jargões ou linguagem complexa.
Utilizar breadcrumbs ou outros elementos de navegação para ajudar os usuários a entender onde eles estão no site.

Alterações Realizadas:
1. ARIA Roles em Elementos de Navegação
Adicionado role="navigation" na tag <nav> para indicar explicitamente a seção de navegação do site.
Incluído role="menu" na lista <ul> e role="menuitem" em cada <li> dentro da navegação para descrever melhor a estrutura do menu.
![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/791f6e20-2857-4273-b1d3-14e299f8716c)

3. ARIA Role e Label em Imagens
Implementado role="img" e aria-label em imagens importantes (como na imagem da home) para fornecer contexto adicional aos usuários de leitores de tela.
![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/2220571f-1b25-4c47-93c2-8d57df6d9bab)

5. ARIA Roles em Cabeçalhos
Aplicado role="heading" e aria-level nos elementos <h1>, <h2>, etc., para indicar a hierarquia dos cabeçalhos de forma mais clara.
![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/6b7084b4-bb15-4dc0-8039-fc2d3cb68757)

7. ARIA em Formulários
Utilizado aria-labelledby nos campos de entrada do formulário de contato para associar as etiquetas de texto aos respectivos campos.
![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/3631f7e9-46b4-422e-ba55-7b8c84db9d37)

9. ARIA em Tabelas
Adicionado role="table" na tag <table> e scope nas tags <th> para indicar cabeçalhos de colunas, melhorando a interpretação das tabelas.
![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/fa08532f-f357-4c81-831c-35d071cd38bb)

11. ARIA Role em Rodapé
Marcado o rodapé com role="contentinfo" para informar que contém informações sobre o conteúdo do site.
![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/3b682384-5dc5-498f-976b-97594022a5ee)

Sobre boa utilização de formatos e dimensionamento de imagens:

 1. As imagens foram comprimidas para reduzir o tempo de carregamento da página, mas mantendo uma qualidade visual aceitável.
 2. Foi ajustado o tamanho da imagem "Carta" para manter sua qualidade, pois antes estava visivelmente esticada e deformada.
    ![image](https://github.com/Kmilasc/vs13-front-01-html-e-css-task03-htmlecss/assets/110876983/d176f142-d48d-40bc-a3c3-3ca4327291e5)
 4. As imagens possuem textos que as descrevem

Impacto das Alterações:
Essas alterações visam aumentar a acessibilidade do site, permitindo uma melhor navegação e compreensão do conteúdo por parte dos usuários com deficiências visuais que utilizam leitores de tela. Com a implementação dessas tags ARIA, o site se torna mais inclusivo e acessível a um público mais amplo.
