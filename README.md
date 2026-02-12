================================================
📘 TEMA 03 - ATIVIDADE MÃO NA MASSA
================================================
Agência de Jornalismo Web
Template Básico com Páginas de Notícias

📁 ESTRUTURA DE PASTAS (OBRIGATÓRIA!):
----------------------------------------
📂 agencia-noticias/
   │
   ├── 📄 index.html              (página principal - EDITAR)
   │
   ├── 📁 imagens/                (imagens das notícias)
   │   ├── formatura.jpg
   │   ├── feira-ciencias.jpg
   │   └── futebol.jpg
   │
   ├── 📁 noticias/               (páginas individuais - NÃO PRECISA EDITAR)
   │   ├── formatura.html
   │   ├── feira-ciencias.html
   │   └── futebol.html
   │
   └── 📄 LEIA-ME.txt            (este arquivo)

================================================
🎯 OBJETIVO DA ATIVIDADE
================================================

Personalizar a página PRINCIPAL (index.html) para criar 
a identidade visual da SUA agência de notícias!

⏰ TEMPO: 30-40 minutos
👥 GRUPOS: 3-4 pessoas
📦 ENTREGA: Site completo publicado no GitHub Pages

================================================
🔧 PASSO A PASSO (FAÇA NA ORDEM!)
================================================

PASSO 1 - BAIXAR AS IMAGENS (3 minutos)
----------------------------------------
1. Crie a pasta 📁 "imagens" dentro da pasta do projeto
2. Clique nos links abaixo e salve as imagens na pasta:

   🎓 formatura.jpg     → https://images.unsplash.com/photo-1523050854058-8df90110c9f1?w=800&h=400&fit=crop
   🔬 feira-ciencias.jpg → https://images.unsplash.com/photo-1532094349884-543bc11b234d?w=800&h=400&fit=crop
   ⚽ futebol.jpg        → https://images.unsplash.com/photo-1575361204480-aadea25e6e68?w=800&h=400&fit=crop

PASSO 2 - EDITAR O ARQUIVO index.html (20 minutos)
--------------------------------------------------
1. Abra o arquivo index.html no VSCode
2. Procure por "🔴 ATENÇÃO" (ctrl + f) - TODAS as edições são aqui!

   🔴 LOCAL 1: CORES (linha ~70)
        Altere os valores das 3 cores:
        --cor-principal:   #2c3e50;   → SUA COR PRINCIPAL
        --cor-secundaria:  #3498db;   → SUA COR SECUNDÁRIA
        --cor-destaque:    #e74c3c;   → SUA COR DE DESTAQUE

   🔴 LOCAL 2: FONTES (linha ~90)
        Altere as 2 fontes:
        body { font-family: 'Segoe UI', Arial, sans-serif; }  → FONTE DO CORPO
        h1, h2, h3 { font-family: 'Segoe UI', Arial, ...; }  → FONTE DOS TÍTULOS

   🔴 LOCAL 3: CABEÇALHO (linha ~205)
        Altere:
        <h1>AGÊNCIA ESCOLAR</h1>              → Nome da sua agência
        <p>Notícias fresquinhas...</p>        → Slogan da sua agência

   🔴 LOCAL 4: NOTÍCIA 1 (linha ~235)
        - Categoria (tag)
        - Título
        - Texto resumo
        - Imagem (src="imagens/formatura.jpg")

   🔴 LOCAL 5: NOTÍCIA 2 (linha ~265)
        - Categoria (tag)
        - Título
        - Texto resumo
        - Imagem (src="imagens/feira-ciencias.jpg")

   🔴 LOCAL 6: NOTÍCIA 3 (linha ~295)
        - Categoria (tag)
        - Título
        - Texto resumo
        - Imagem (src="imagens/futebol.jpg")

   🔴 LOCAL 7: EQUIPE (linha ~325)
        - Nomes reais do seu grupo
        - Funções (Editor, Webmaster, Repórter, Fotógrafo)
        - Iniciais para os avatares

   🔴 LOCAL 8: RODAPÉ (linha ~375)
        - Nome da agência
        - Data de publicação

PASSO 3 - VISUALIZAR (2 minutos)
--------------------------------
1. Salve o arquivo (ctrl + s)
2. Abra o index.html no navegador
3. Clique nos botões "Ler notícia completa" para ver as páginas prontas!
4. Volte para a página principal

PASSO 4 - PUBLICAR NO GITHUB PAGES (10 minutos)
-----------------------------------------------
1. Crie um repositório público no GitHub chamado: agencia-noticias
2. Faça upload de TODA a pasta (mantenha a estrutura!)
3. Ative o GitHub Pages (Settings → Pages → main branch → /root → Save)
4. Aguarde 2 minutos e acesse: https://SEUUSUARIO.github.io/agencia-noticias/
5. Compartilhe o link no chat da turma!

================================================
✅ CHECKLIST FINAL (NÃO ESQUEÇA!)
================================================

☐ Criei a pasta 📁 imagens e coloquei as 3 fotos
☐ Altere as 3 cores (principal, secundária, destaque)
☐ Alterei as 2 fontes (títulos e corpo)
☐ Altereio nome da agência e slogan
☐ Editei as 3 notícias (categoria, título, texto)
☐ As imagens aparecem corretamente no site
☐ Coloquei os nomes reais da minha equipe
☐ O site abre no navegador
☐ Publiquei no GitHub Pages
☐ Compartilhei o link

================================================
🎨 SUGESTÕES DE CORES (copie e cole)
================================================

🔵 Azul Marinho: #1a2639 (sério, profissional)
🔵 Azul Claro:   #3498db (tecnologia, confiança)
🟢 Verde:        #2ecc71 (natureza, saúde)
🔴 Vermelho:     #e74c3c (urgência, esportes)
🟡 Amarelo:      #f1c40f (criatividade, alegria)
🟣 Roxo:         #9b59b6 (inovação, mistério)
🟠 Laranja:      #f39c12 (entusiasmo, juventude)
⚫ Cinza:        #34495e (elegância, seriedade)

================================================
📝 SUGESTÕES DE FONTES (copie e cole)
================================================

PARA TÍTULOS (personalidade):
----------------------------
'Poppins', sans-serif
'Montserrat', sans-serif
'Oswald', sans-serif
'Playfair Display', serif
'Times New Roman', serif

PARA CORPO (legibilidade):
-------------------------
'Open Sans', sans-serif
'Roboto', sans-serif
'Verdana', sans-serif
'Arial', sans-serif
'Georgia', serif

================================================
🎯 ENTENDENDO OS LINKS
================================================

Os botões "Ler notícia completa" já estão configurados!

📌 index.html                       → Página principal
📌 noticias/formatura.html          → Página completa da notícia 1
📌 noticias/feira-ciencias.html     → Página completa da notícia 2
📌 noticias/futebol.html            → Página completa da notícia 3

Isso mostra como um site de notícias REAL funciona:
- Página inicial = resumo das notícias (cards)
- Páginas internas = conteúdo completo
