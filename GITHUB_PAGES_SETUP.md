# Como Ativar GitHub Pages

Siga estes passos:

1. **Faça commit de todos os arquivos:**
   ```powershell
   git add .
   git commit -m "Add Doom game and GitHub Pages config"
   git push origin main
   ```

2. **Ative o GitHub Pages:**
   - Vá em: https://github.com/Natteens/Natteens/settings/pages
   - Em **Source**, selecione: `Deploy from a branch`
   - Em **Branch**, selecione: `main` e pasta `/ (root)`
   - Clique em **Save**

3. **Aguarde 1-2 minutos** e seu Doom estará em:
   - 🎮 **https://natteens.github.io/Natteens/**
   - 🎮 **https://natteens.github.io/Natteens/doom.html**

## O que você terá:

✅ **README com animação** - SVG da cobra comendo contribuições (tema Doom)
✅ **Doom jogável** - Acesse via GitHub Pages
✅ **doom.html** - Doom completo rodando via js-dos
✅ **index.html** - Redireciona automaticamente pro Doom

## Nota Importante:

**GitHub README não executa JavaScript por segurança** - isso é uma limitação do próprio GitHub, não tem como contornar. Mas o workflow gera um SVG animado legal (cobra com cores do Doom comendo suas contribuições).

O Doom JOGÁVEL ficará disponível via GitHub Pages! 🔥

