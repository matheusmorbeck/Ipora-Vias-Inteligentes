Criar um checkbox interativo no Figma usando componentes e variantes é uma das melhores formas de praticar design system.O segredo aqui é usar o recurso de Interactive Components (Componentes Interativos) para que ele funcione sozinho no protótipo.

Aqui está o passo a passo direto para criar o seu:
Passo 1: Criar a estrutura visual (Base)
Pressione F ou R e desenhe um quadrado de 20x20 px. Adicione um border radius (arredondamento) de 4 px para dar um acabamento padrão.Adicione uma borda (Stroke) cinza e um preenchimento (Fill) branco.Esse será o seu estado Desmarcado.Escreva um texto ao lado (ex: "Opção") e selecione o quadrado + o texto.Pressione Shift + A para aplicar o Auto Layout.Isso garante que o alinhamento fique perfeito.

Passo 2: Criar as Variantes
Selecione o frame do Auto Layout que você acabou de criar.Vá até a barra superior do Figma e clique no ícone de Componente (os quatro losangos) ou use o atalho Ctrl + Alt + K (Windows) / Cmd + Option + K (Mac).Com o componente selecionado, olhe para a barra lateral direita e clique no botão "+" ao lado de Variants (ou clique em "Add Variant" na barra superior). Isso vai criar um segundo estado dentro de um painel roxo.

Passo 3: Estilizar os Estados
Agora você tem duas variantes. Vamos nomeá-las e estilizá-las:Selecione a primeira variante (a de cima). Na barra lateral direita, mude o nome da propriedade para Checked e o valor para False.Selecione a segunda variante (a de dentro do box roxo). Na barra lateral direita, mude o valor de Checked para True.Altere o visual dessa segunda variante (True): mude a cor do quadrado para o tom principal da sua marca (ex: azul) e desenhe ou cole um ícone de "check" ($\checkmark$) branco dentro dele.

Passo 4: Adicionar a Interatividade (Prototipagem)
Para fazer o checkbox mudar de estado ao ser clicado:No painel superior direito, mude da aba Design para a aba Prototype.Clique na primeira variante (Checked=False). Um pequeno círculo azul vai aparecer na borda dela.Clique e arraste esse círculo azul até a segunda variante (Checked=True).No painel de configuração que aparecer, configure o gatilho:Trigger: On clickAction: Change toAnimation: Smart Animate (coloque Ease out com 150ms para uma transição suave).Agora, faça o caminho inverso: clique na segunda variante (Checked=True) e arraste o círculo azul de volta para a primeira (Checked=False), usando as mesmas configurações.

Como testar:Vá até a aba Assets (Ativos) no painel esquerdo, arraste o seu novo componente de Checkbox para dentro de uma tela de design (Frame).Clique no botão de Play (Preview) no canto superior direito para rodar o protótipo.Ao clicar no checkbox, ele vai alternar entre marcado e desmarcado automaticamente.
