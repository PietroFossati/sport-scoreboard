# 🏓 Padel Scoreboard

Un contapunti **moderno, intuitivo e responsive** per partite di padel. Interfaccia professionale ottimizzata per dispositivi mobile, perfetta per tenere il punteggio durante le tue partite.

[![Deploy Status](https://img.shields.io/badge/deploy-live-brightgreen)](https://tuousername.github.io/padel-scoreboard)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Mobile Friendly](https://img.shields.io/badge/mobile-friendly-orange)](#-caratteristiche)

## 🚀 Demo Live

🌐 **[Prova l'App Online](https://pietrofossati.github.io/sport-scoreboard)**

---

## ✨ Caratteristiche

### 🎯 **Funzionalità Complete**
- ✅ **Sistema di punteggio tradizionale** (0, 15, 30, 40, Deuce, Advantage)
- ✅ **Best of 3 o Best of 5** set configurabili
- ✅ **Nomi squadre personalizzabili**
- ✅ **Gestione situazioni speciali** (Deuce/Advantage)
- ✅ **Controllo punti precedenti** (undo last point)
- ✅ **Reset completo del match**
- ✅ **Statistiche in tempo reale**

### 📱 **Design & UX**
- 🎨 **Interfaccia moderna** con gradientinti e glassmorphism
- 📱 **100% Responsive** - ottimizzato per smartphone
- ⚡ **Animazioni fluide** e micro-interazioni
- 🌟 **Banner di vittoria** animato
- 🎪 **Feedback visivo** su ogni azione
- 🔥 **Touch-friendly** - bottoni grandi e accessibili

### 🛠️ **Tecnologie**
- ⚛️ **React 18** con Hooks
- 🎨 **Tailwind CSS** per styling moderno
- 📦 **Single HTML File** - zero configurazione
- 🌐 **CDN-based** - caricamento veloce
- 📱 **Progressive Web App** ready

---

## 🎮 Come Usare

### **Avvio Rapido**
1. **Apri** il link dell'app sul tuo smartphone
2. **Configura** nomi squadre e tipo di match (Best of 3/5)
3. **Tap** sui pulsanti "Punto" per aggiungere punti
4. **Segui** il punteggio in tempo reale

### **Controlli Principali**
| Azione | Descrizione |
|--------|-------------|
| **➕ Punto** | Aggiunge un punto alla squadra |
| **➖ Undo** | Rimuove l'ultimo punto assegnato |
| **⚙️ Impostazioni** | Configura match e nomi squadre |
| **🔄 Reset** | Ricomincia il match da 0-0 |

### **Sistema Punteggio**
```
Punti Game: 0 → 15 → 30 → 40 → Game
Situazioni Speciali: 40-40 = Deuce
                     Advantage quando +1 dopo Deuce
Set: 6 game (con differenza di 2) o 7-6
Match: Best of 3 (2 set) o Best of 5 (3 set)
```

---

## 🚀 Installazione & Deploy

### **GitHub Pages (Consigliato)**
```bash
# 1. Clona il repository
git clone https://github.com/tuousername/padel-scoreboard.git

# 2. Vai su GitHub → Settings → Pages
# 3. Source: Deploy from a branch
# 4. Branch: main, Folder: / (root)
# 5. Il sito sarà disponibile su: https://tuousername.github.io/padel-scoreboard
```

### **Deploy Locale**
```bash
# Semplicemente apri index.html nel browser
open index.html
# oppure
python -m http.server 8000  # http://localhost:8000
```

### **Altri Provider**
- **Netlify**: Trascina `index.html` su netlify.com
- **Vercel**: Upload del file su vercel.com
- **Surge**: `surge index.html`

---

## 📱 Compatibilità

### **Dispositivi Testati**
- ✅ iPhone (iOS 14+)
- ✅ Android (Chrome 90+)
- ✅ iPad / Tablet
- ✅ Desktop (tutti i browser moderni)

### **Browser Supportati**
- ✅ Safari Mobile
- ✅ Chrome Mobile
- ✅ Firefox Mobile
- ✅ Samsung Internet
- ✅ Edge Mobile

---

## 🎨 Screenshots

### Mobile Interface
```
┌─────────────────┐
│  🏆 Padel Board │
│                 │
│ Team A    Team B│
│   Set: 1    0   │
│  Game: 4    3   │
│ Point:30   40   │
│                 │
│ [+Punto] [+Punto]│
│    [-]      [-] │
└─────────────────┘
```

### Desktop View
```
┌─────────────────────────────────────┐
│           🏆 Padel Scoreboard       │
│                                     │
│  Team Alpha        |    Team Beta   │
│     Set: 2         |      Set: 1    │
│    Game: 3         |     Game: 5    │
│   Point: 15        |    Point: 30   │
│                    |                │
│  [➕ Punto] [➖]   |   [➕ Punto] [➖]│
└─────────────────────────────────────┘
```

---

## 🤝 Contribuire

Contributi benvenuti! Ecco come puoi aiutare:

### **Segnalare Bug**
- 🐛 Apri una [Issue](../../issues) con dettagli del problema
- 📱 Includi dispositivo/browser utilizzato
- 📋 Passi per riprodurre il bug

### **Proporre Funzionalità**
- 💡 Apri una [Issue](../../issues) con tag `enhancement`
- 📝 Descrivi la funzionalità richiesta
- 🎯 Spiega il caso d'uso

### **Sviluppo**
```bash
# 1. Fork del repository
# 2. Crea un branch per la tua feature
git checkout -b feature/nuova-funzionalita

# 3. Modifica index.html
# 4. Testa le modifiche
# 5. Commit e push
git commit -m "Aggiunge nuova funzionalità"
git push origin feature/nuova-funzionalita

# 6. Apri una Pull Request
```

---

## 📋 Roadmap

### **v1.1** (Prossima Release)
- [ ] 🔊 Suoni per punti e vittorie
- [ ] 📊 Cronologia partite salvata
- [ ] ⏱️ Timer per set/game
- [ ] 🌙 Modalità scura

### **v1.2** (Futuro)
- [ ] 📈 Statistiche avanzate
- [ ] 🏆 Sistema tornei
- [ ] 📤 Condivisione risultati
- [ ] 🔄 Sync multi-dispositivo

### **v2.0** (Long Term)
- [ ] 👥 Modalità multiplayer online
- [ ] 📱 App nativa (PWA)
- [ ] 🤖 AI coaching suggestions
- [ ] 📺 Modalità spettatore

---

## 📄 Licenza

Questo progetto è sotto licenza **MIT** - vedi il file [LICENSE](LICENSE) per dettagli.

### **In Breve:**
- ✅ Uso commerciale
- ✅ Modifica
- ✅ Distribuzione
- ✅ Uso privato

---

## 👨‍💻 Autore

**[Il Tuo Nome]** - *Sviluppatore Full Stack*

- 🌐 Website: [tuosito.com](https://tuosito.com)
- 📧 Email: tua.email@example.com
- 🐦 Twitter: [@tuousername](https://twitter.com/tuousername)
- 💼 LinkedIn: [tuoprofilo](https://linkedin.com/in/tuoprofilo)

---

## 🙏 Ringraziamenti

- 🏓 **Comunità Padel** per feedback e testing
- ⚛️ **React Team** per il fantastico framework  
- 🎨 **Tailwind CSS** per il sistema di design
- 🚀 **GitHub** per l'hosting gratuito

---

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/tuousername/padel-scoreboard?style=social)
![GitHub forks](https://img.shields.io/github/forks/tuousername/padel-scoreboard?style=social)
![GitHub issues](https://img.shields.io/github/issues/tuousername/padel-scoreboard)
![GitHub last commit](https://img.shields.io/github/last-commit/tuousername/padel-scoreboard)

---

<div align="center">

**⭐ Se questo progetto ti è utile, lascia una stella! ⭐**

**🏓 Buone partite di Padel! 🏓**

</div>
