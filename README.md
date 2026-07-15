# Guia-de-Diagrama-o-com-o-NotebookLM

## 🎯 Contexto e Objetivos
Diagramação de livros se tornou um hobbie bem presente em minha vida, por isso, escolhi este como inspiração para esse guia utilizando da ferramenta NotebookLM

## 📚 Curadoria de Fontes
Os materiais utilizados e integrados ao NotebookLM abordam a estética da capa, diagramação de miolo e fechamento técnico de arquivos:
1. **Fundamentos da Estrutura Editorial** - Guias sobre a anatomia do Grid (margens, colunas, módulos e calhas).
2. **Especificações Técnicas de Pré-impressão** - Documentos técnicos sobre sangria, padrões de cores CMYK e exportação em PDF/X-1a.
3. **Engenharia de Layout em Softwares e Processadores** - Análise comparativa entre ferramentas líderes de mercado (Adobe InDesign, Affinity Publisher) e alternativas (Microsoft Word, Scribus, Reedsy).

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
* **Prompt Estratégico Utilizado:** *"Como aplicar técnicas profissionais de design editorial, como margens e sangrias, dentro do ambiente do Microsoft Word?"*
* **Comportamento da IA:** A IA inicialmente tendeu a sugerir apenas softwares dedicados (InDesign). Foi necessário refiná-la para entender as limitações de ferramentas que não possuem suporte nativo de sangria.
* **Refinamento/Troubleshooting (Cicatrizes):** Ajustei o prompt exigindo soluções alternativas de contorno. A IA retornou com sucesso a técnica avançada do *"Arquivo Maior"* (configurar a página com 1 cm a mais e compensar as margens internas e externas em 0,5 cm), demonstrando como simular o comportamento de ferramentas tradicionais de paginação.

## 📖 Miniguia de Estudo (Entrega Final)

### Resumos Estruturados
* **O Grid Editorial:** É o esqueleto invisível (malha gráfica) composto por margens, colunas, módulos e calhas. Em textos corridos, prioriza-se uma coluna; em materiais complexos, usa-se grids multicolunas ou técnicas de composição dinâmica (como as regras do "L" ou do "I").
* **Tipografia Editorial:** O entrelinhamento (*leading*) profissional para leitura fluida deve ficar estritamente entre 120% e 145% do tamanho da fonte. O ajuste macro do bloco é o *Tracking*, enquanto a correção micro entre caracteres específicos é o *Kerning*.
* **Preparação para Impressão:** Para evitar cortes de texto na dobra da encadernação, livros extensos (mais de 500 páginas) exigem margem interna superior a 2,5 cm. A sangria (*bleed*) de 5 mm é obrigatória em fundos coloridos e imagens para evitar filetes brancos pós-corte.
* **Ecossistema de Softwares:** O *Adobe InDesign* continua sendo o padrão da indústria. O *Scribus* lidera como a melhor ferramenta profissional de código aberto. Para publicação automatizada de e-books e colaboração online, destaca-se o *Reedsy Book Editor*.

### 🔤 Glossário
* **Projeto Invisível:** Conceito editorial onde as decisões técnicas de diagramação são tão equilibradas que o leitor flui pelo texto sem notar o design por trás da obra.
* **PDF/X-1a:** Padrão de exportação profissional exigido por gráficas que garante o encapsulamento correto de fontes e cores.
* **Preflight (Revisão Técnica):** Checklist rigoroso pré-impressão feito para verificar se todas as imagens possuem resolução mínima de 300 DPI, fontes incorporadas e cores convertidas para CMYK ou Pantone.
* **Fontes Serifadas:** Famílias tipográficas com pequenos traços ornamentais nas extremidades (ex: Garamond, Minion), altamente recomendadas para textos longos impressos devido à tradição e conforto visual.

### 🔄 Prompts Reutilizáveis para Revisão
* *"Com base nos conceitos de Jan Tschichold, explique por que a tipografia perfeita deve ser governada por leis de clareza e organização, e não por gosto pessoal."*
* *"Quais as principais diferenças de saída de arquivo e finalidade de mercado entre o Reedsy Book Editor e o Blurb BookWright?"*

### 🔗 Link do Notebook:
* https://notebooklm.google.com/notebook/94f496ab-de42-45ee-8381-9945ded72983 
