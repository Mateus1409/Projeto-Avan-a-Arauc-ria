# Avança Araucária - Site Moderno

Site moderno e responsivo com animações para o Avança Araucária.

## ⚡ Início Rápido

**Comando mais rápido para iniciar o servidor:**

```powershell
cd C:\Users\Big\Desktop\avancaaraucaria\frontend
python -m http.server 8000
```

Depois abra no navegador: **http://localhost:8000**

---

## 🚀 Características

- **Design Moderno**: Interface limpa e profissional
- **Animações Suaves**: Efeitos de scroll, hover e transições
- **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Performance Otimizada**: Código leve e rápido
- **Navegação Intuitiva**: Menu fixo e navegação suave entre seções

## 📁 Estrutura de Arquivos

```
frontend/
├── index.html      # Página principal
├── styles.css      # Estilos e animações
├── script.js       # JavaScript para interatividade
├── Avancaaraucaria_logo.jpg  # Imagem de fundo do hero
└── README.md       # Este arquivo
```

## 🎨 Seções do Site

1. **Hero**: Seção inicial com imagem de fundo e call-to-action
2. **Sobre**: Informações sobre o Avança Araucária
3. **Projetos**: Cards com os principais projetos
4. **Câmaras Técnicas**: Lista de câmaras técnicas
5. **Notícias**: Últimas notícias e atualizações
6. **Contato**: Formulário de contato e informações

## 💻 Como Usar

### 🚀 Iniciar o Servidor Local

#### Opção 1: Python (Recomendado - Mais Simples)

**Windows (PowerShell ou CMD):**
```powershell
cd C:\Users\Big\Desktop\avancaaraucaria\frontend
python -m http.server 8000
```

**Ou se estiver na raiz do projeto:**
```powershell
cd frontend
python -m http.server 8000
```

**Acesse no navegador:**
```
http://localhost:8000
```

**Para parar o servidor:** Pressione `Ctrl + C` no terminal

---

#### Opção 2: Node.js (http-server)

**Instalar o http-server (se ainda não tiver):**
```bash
npm install -g http-server
```

**Iniciar o servidor:**
```powershell
cd C:\Users\Big\Desktop\avancaaraucaria\frontend
http-server -p 8000
```

**Acesse no navegador:**
```
http://localhost:8000
```

---

#### Opção 3: PHP

**Windows (se tiver PHP instalado):**
```powershell
cd C:\Users\Big\Desktop\avancaaraucaria\frontend
php -S localhost:8000
```

**Acesse no navegador:**
```
http://localhost:8000
```

---

#### Opção 4: VS Code Live Server

Se você usa Visual Studio Code:
1. Instale a extensão "Live Server"
2. Clique com botão direito no arquivo `index.html`
3. Selecione "Open with Live Server"

---

#### Opção 5: Abrir diretamente no navegador

**Nota:** Algumas funcionalidades podem não funcionar corretamente sem um servidor.

1. Navegue até a pasta `frontend`
2. Clique duas vezes no arquivo `index.html`
3. O site abrirá no seu navegador padrão

## 🎯 Recursos Implementados

### Animações
- ✨ Fade in ao fazer scroll
- 🎭 Efeitos de hover nos cards
- 📊 Contadores animados nas estatísticas
- 🌊 Efeito parallax na imagem do hero
- 🎨 Barra de progresso de scroll
- 💫 Efeito ripple nos botões

### Interatividade
- 📱 Menu mobile responsivo
- 🔗 Navegação suave entre seções
- ✍️ Formulário de contato funcional
- 🎯 Destaque de seção ativa no menu
- 📜 Navbar que muda ao fazer scroll

### Design
- 🎨 Paleta de cores moderna
- 📐 Layout responsivo (mobile-first)
- 🖼️ Imagem de fundo integrada
- 💎 Sombras e efeitos visuais
- 🎭 Transições suaves

## 🔧 Personalização

### Cores
As cores podem ser alteradas no arquivo `styles.css` através das variáveis CSS:

```css
:root {
    --primary-color: #2c5f8d;
    --secondary-color: #4a90a4;
    --accent-color: #f39c12;
    /* ... */
}
```

### Conteúdo
Todo o conteúdo pode ser editado diretamente no arquivo `index.html`.

### Animações
As animações podem ser ajustadas no arquivo `styles.css` e `script.js`.

## 📱 Compatibilidade

- ✅ Chrome (últimas versões)
- ✅ Firefox (últimas versões)
- ✅ Safari (últimas versões)
- ✅ Edge (últimas versões)
- ✅ Navegadores mobile

## 📝 Notas

- A imagem `Avancaaraucaria_logo.jpg` é usada como fundo na seção hero
- O formulário de contato mostra uma mensagem de sucesso, mas não envia emails automaticamente (precisa de backend)
- Todas as animações são otimizadas para performance

## 🚀 Próximos Passos

Para produção, considere:
- Adicionar backend para o formulário de contato
- Implementar um CMS para gerenciar notícias
- Adicionar mais imagens e conteúdo
- Otimizar imagens para web
- Configurar SEO

## 📄 Licença

Este projeto foi criado para o Avança Araucária.

