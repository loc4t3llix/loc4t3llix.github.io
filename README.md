# loc4t3llix.github.io

Portfolio personale di loc4t3llix - Studente e Sviluppatore

🌐 **URL**: https://loc4t3llix.github.io

## 📋 Caratteristiche

- ✨ Design moderno con tema scuro e gradiente viola
- 📱 Completamente responsive (desktop, tablet, mobile)
- 🎨 Sezioni: Home, Chi Sono, Progetti, Contatti
- ⚡ Animazioni smooth e effetti interattivi
- 🚀 Ottimizzato per GitHub Pages

## 🛠️ Struttura

```
├── index.html    # Struttura HTML principale
├── style.css     # Stili CSS (tema scuro, layout responsive)
└── script.js     # JavaScript (navigazione smooth, animazioni)
```

## 🎨 Personalizzazione

### Modificare le Informazioni di Contatto

1. **Email**: Modifica la riga 170 in `index.html`
   ```html
   <a href="mailto:tua.email@esempio.com" class="contact-card">
   ```

2. **LinkedIn**: Modifica la riga 176 in `index.html`
   ```html
   <a href="https://linkedin.com/in/tuo-profilo" class="contact-card">
   ```

### Aggiungere Progetti

Modifica le card dei progetti nella sezione "I Miei Progetti" (linee 80-159 in `index.html`):

```html
<div class="project-card">
    <div class="project-header">
        <h3 class="project-title">Nome Progetto</h3>
        <span class="project-tag">Categoria</span>
    </div>
    <p class="project-description">
        Descrizione del progetto...
    </p>
    <div class="project-tech">
        <span class="tech-badge">Tecnologia 1</span>
        <span class="tech-badge">Tecnologia 2</span>
    </div>
    <div class="project-links">
        <a href="link-demo" class="project-link">
            <span class="link-icon">🔗</span> Demo
        </a>
        <a href="link-github" class="project-link">
            <span class="link-icon">📁</span> GitHub
        </a>
    </div>
</div>
```

### Modificare le Competenze

Aggiorna la sezione skills (linee 55-75 in `index.html`):

```html
<div class="skill-item">
    <span class="skill-icon">🎯</span>
    <span class="skill-name">Nome Competenza</span>
</div>
```

### Cambiare i Colori

Modifica le variabili CSS in `style.css` (linee 6-13):

```css
:root {
    --primary-color: #6366f1;      /* Colore primario */
    --secondary-color: #8b5cf6;    /* Colore secondario */
    --dark-bg: #0f172a;            /* Sfondo principale */
    --darker-bg: #020617;          /* Sfondo più scuro */
}
```

## 🚀 Deployment

Il sito è già configurato per GitHub Pages. Dopo aver fatto il merge di questo PR:

1. Vai su Settings → Pages nel repository
2. Seleziona branch `main` come source
3. Il sito sarà disponibile su https://loc4t3llix.github.io

## 📝 Licenza

© 2024 loc4t3llix. Tutti i diritti riservati.