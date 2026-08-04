

<p align="center">
  <a href="https://chromewebstore.google.com/detail/kjbodcmljdmjmcjdhoghcclejpmgfeoj?utm_source=item-share-cb" target="_blank" rel="noopener">
    <img src="https://raw.githubusercontent.com/Alarisco/WPlace-AutoBOT/refs/heads/main/src/addons/Auto-bot-extension/icons/icon128.png" alt="WPlace AutoBOT" width="160" height="160"/>
  </a>
</p>

<h1 align="center">WPLACE-AUTOBOT</h1>

<!-- Botón Buy Me a Coffee -->
<p align="center">
  <a href="https://buymeacoffee.com/alariscoi" target="_blank" rel="noopener">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Cómprame un café" height="50" />
  </a>
</p>


<!-- Badges de Chrome y Firefox -->
<p align="center">
  <a href="https://chromewebstore.google.com/detail/kjbodcmljdmjmcjdhoghcclejpmgfeoj?utm_source=item-share-cb" target="_blank" rel="noopener noreferrer">
    <img
      src="https://developer.chrome.com/static/docs/webstore/branding/image/mPGKYBIR2uCP0ApchDXE.png"
      alt="Disponible en Chrome Web Store"
      height="70"
    />
  </a>
  &nbsp;&nbsp;
  <a href="https://addons.mozilla.org/es-ES/firefox/addon/wplace-autobot-launcher/" target="_blank" rel="noopener noreferrer">
    <img
      src="https://logos-world.net/wp-content/uploads/2021/08/Firefox-Logo.png"
      alt="Complemento para Firefox"
      height="70"
    />
  </a>
</p>


<!-- Novedad: enlace al repositorio WPlace Master Server -->
<p align="center">
  🚀 Nueva herramienta relacionada: <br>
  <a href="https://github.com/Alarisco/Wplace-AutoBotnet-Server" target="_blank" rel="noopener">
    WPlace Master Server
  </a> – servidor central para coordinar bots con interfaz web.
</p>


<!-- Texto en otro párrafo centrado -->
<p align="center">
  <em>La mejor experiencia: instala la extensión del navegador.</em>
</p>

---

## 🚀 Inicio Rápido (Recomendado: Extensión)

Instala la extensión oficial de Chrome e inicia el bot con un solo clic:

1. Abre la publicación en Chrome Web Store:
   https://chromewebstore.google.com/detail/kjbodcmljdmjmcjdhoghcclejpmgfeoj?utm_source=item-share-cb
2. Haz clic en "Agregar a Chrome"
3. Fija la extensión (opcional) y abre WPlace
4. Haz clic en el icono → elige el modo (Lanzador, Guardia, Imagen, Granja)

> La extensión siempre proporciona la última versión del bot automáticamente.

---

## 📦 Alternativa: Inyección mediante marcador
Si prefieres no instalar la extensión, puedes usar un marcador en su lugar.
Crea un nuevo marcador y pega uno de los fragmentos de código a continuación como la URL.

### Lanzador (elige cualquier modo después de cargar)
```javascript
javascript:(async()=>{const U="https://raw.githubusercontent.com/Alarisco/WPlace-AutoBOT/refs/heads/main/Auto-Launcher.js";try{const r=await fetch(U,{cache:"no-cache"});if(!r.ok)throw new Error(r.status+" "+r.statusText);const code=await r.text();const blob=new Blob([code+"\n//# sourceURL="+U],{type:"text/javascript"});const blobUrl=URL.createObjectURL(blob);try{await new Promise((ok,err)=>{const s=document.createElement("script");s.src=blobUrl;s.onload=ok;s.onerror=err;document.documentElement.appendChild(s);});}catch(e){await import(blobUrl);}}catch(e){alert("[Auto-Launcher] Could not load/inject: "+e.message+"\nTry another page or use Option C (module).");}})();
```

### Guardia (proteger y reparar automáticamente)
```javascript
javascript:(async()=>{const U="https://raw.githubusercontent.com/Alarisco/WPlace-AutoBOT/refs/heads/main/Auto-Guard.js";try{const r=await fetch(U,{cache:"no-cache"});if(!r.ok)throw new Error(r.status+" "+r.statusText);const code=await r.text();const blob=new Blob([code+"\n//# sourceURL="+U],{type:"text/javascript"});const blobUrl=URL.createObjectURL(blob);try{await new Promise((ok,err)=>{const s=document.createElement("script");s.src=blobUrl;s.onload=ok;s.onerror=err;document.documentElement.appendChild(s);});}catch(e){await import(blobUrl);}}catch(e){alert("[Auto-Guard] Could not load/inject: "+e.message+"\nTry another page or use Option C (module).");}})();
```

### Imagen (pintar arte pixelado automáticamente)
```javascript
javascript:(async(()=>{const U="https://raw.githubusercontent.com/Alarisco/WPlace-AutoBOT/refs/heads/main/Auto-Image.js";try{const r=await fetch(U,{cache:"no-cache"});if(!r.ok)throw new Error(r.status+" "+r.statusText);const code=await r.text();const blob=new Blob([code+"\n//# sourceURL="+U],{type:"text/javascript"});const blobUrl=URL.createObjectURL(blob);try{await new Promise((ok,err)=>{const s=document.createElement("script");s.src=blobUrl;s.onload=ok;s.onerror=err;document.documentElement.appendChild(s);});}catch(e){await import(blobUrl);}}catch(e){alert("[Auto-Image] Could not load/inject: "+e.message+"\nTry another page or use Option C (module).");}})();
```

### Granja (recolección de XP)
```javascript
javascript:(async()=>{const U="https://raw.githubusercontent.com/Alarisco/WPlace-AutoBOT/refs/heads/main/Auto-Farm.js";try{const r=await fetch(U,{cache:"no-cache"});if(!r.ok)throw new Error(r.status+" "+r.statusText);const code=await r.text();const blob=new Blob([code+"\n//# sourceURL="+U],{type:"text/javascript"});const blobUrl=URL.createObjectURL(blob);try{await new Promise((ok,err)=>{const s=document.createElement("script");s.src=blobUrl;s.onload=ok;s.onerror=err;document.documentElement.appendChild(s);});}catch(e){await import(blobUrl);}}catch(e){alert("[Auto-Farm] Could not load/inject: "+e.message+"\nTry another page or use Option C (module).");}})();
```

---

## 🔄 Actualizaciones
Tanto la extensión como los marcadores siempre obtienen la versión más reciente. Solo tienes que volver a ejecutarlos.

---

## 🤝 Contribuciones
Los pull requests son bienvenidos. Consulta CONTRIBUTING.md para conocer la arquitectura, el flujo de trabajo y los estándares.

---

<p align="center"><strong>Hecho con ❤️ para la comunidad de WPlace – úsalo con responsabilidad.</strong></p>
