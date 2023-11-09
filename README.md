# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).


Esercizio di oggi: Vite Hello World
nome repo: vite-hello-world
Descrizione:
Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente `AppTitle`, il quale contiene un titolo che recita "La mia prima app con Vite!"
Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron.
(per l'inserimento delle immagini non create immagini dinamiche, ma piuttosto create una cartella images in public e mettete le immagini lì. Per richiamarle il path sarà semplicemente  /images/nome_immagine)

# scaffolding progetto
1. aprire repo si github (nome: vue-test),vai su vs,chiudi folder
2. clona repo
3. apro cartella nella cartella padre
4. apri terminale
5. scrivere nel terminale
    ```sh
         npm create vite@latest
     ```
     oppure meglio:
     ```sh
     npm create vue@latest
     ```
    una volta fatto [enter] uscirà
    ```sh
    project name:.
    ```
     (va a creare una cartella dentro quella attuale)quindi scrivi "."
     Poi apparirà
     ```sh
    packagename: nomerepo
    ```
    e quindi scrivi packagename: nomerepo[enter]/
    
    e poi seleziona tutto no

    altra versione:
    ```sh
    ? Project name: .[enter]
    seleziona confreccette Vue
    seleziona confreccette JavaScript
    ```
    

6. appaiono cartelle
7. compila comandi indicati --> 
    ```sh
    npm install[enter]
    ```
    (solo la prima volta per compilare progetto)
8. lancia serverino di sviluppo(come se fosse go live)--->
```sh
  npm run dev[enter]
  ```
9. apri il link-->Local: (indirizzo link) click+ctrl
10. per arrestare terminale ctrl+C

opzionale -- per pulire terminale
```sh
    clear
```

# pulizia scaffolding

- apro `App.vue` e cancello tutto e riscrivo codice con i mio codice modalità 'options'
- apro cartella componets e la svuoto (cancello tutti i file)
- apro assets e cancello tutto e creo cartella `styles` e una `img`, e sposto `main.css` in styles (creazione cartelle opzionale)
''meglio mettere img in public e quella di gestione sfondi in assets''
- cambio percorso in `main.js` per il file css
- cancello tutto il contenuto di `main.css`
