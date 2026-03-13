# ✦ Mapa Sagrado - Plataforma de Cura Holística

Plataforma web completa para jornada de cura de feridas de vínculo, com terapias sonoras, práticas somáticas, rituais e meditações guiadas.

## 🌟 Funcionalidades

- **Mapa Personalizado**: Diagnóstico baseado em 5 sinais de ferida de vínculo
- **30 Dias de Protocolo**: Jornada estruturada em 4 fases de transformação
- **Terapias Sonoras**: Frequências de cura (432Hz, 528Hz, 741Hz, 852Hz, Delta)
- **Terapias Somáticas**: Tapping EFT, Coerência Cardíaca, Grounding
- **Rituais e Meditações**: Práticas guiadas para cada fase
- **Diário Sagrado**: Registro de emoções e insights da jornada
- **Árvore de Crescimento**: Visualização do progresso transformacional
- **Sistema de Energia**: Gamificação com pontos e níveis
- **Sincronização Lunar**: Práticas alinhadas com as fases da lua

## 🚀 Deploy na Vercel

### Pré-requisitos
- Conta no [Vercel](https://vercel.com)
- Repositório no GitHub

### Passos para Deploy

1. **Clone o repositório** (se ainda não tiver):
```bash
git clone https://github.com/Leonardotrentini/tarotent.git
cd tarotent
```

2. **Adicione os arquivos do projeto**:
```bash
# Copie todos os arquivos do projeto para esta pasta
# Certifique-se de incluir:
# - index.html
# - mapa-sagrado-app-ptbr.html
# - pasta audio/ (se houver arquivos de áudio)
```

3. **Commit e push**:
```bash
git add .
git commit -m "Mapa Sagrado - versão inicial"
git push origin main
```

4. **Deploy na Vercel**:
   - Acesse [vercel.com](https://vercel.com)
   - Clique em **"New Project"**
   - Importe o repositório `tarotent`
   - A Vercel detectará automaticamente como **Static Site**
   - Clique em **Deploy**

5. **Pronto!** Seu site estará disponível em `https://tarotent.vercel.app`

## 📁 Estrutura do Projeto

```
tarotent/
├── index.html                    # Ponto de entrada (redirect)
├── mapa-sagrado-app-ptbr.html    # Aplicação principal
├── audio/                        # Arquivos de áudio (se houver)
│   └── README.md
├── .gitignore
└── README.md
```

## 🎨 Tecnologias

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- JavaScript (Vanilla)
- Web Audio API (para frequências)
- LocalStorage (para persistência)

## 📝 Notas

- O projeto é 100% estático, sem necessidade de build
- Todos os dados são salvos localmente no navegador (LocalStorage)
- As frequências sonoras são geradas em tempo real via Web Audio API
- Compatível com todos os navegadores modernos

## 🔗 Links

- Repositório: [GitHub](https://github.com/Leonardotrentini/tarotent)
- Deploy: Será gerado automaticamente pela Vercel

---

Desenvolvido com ✦ para jornadas de cura e transformação pessoal.
