# Mastodon, mais encore?

Les sources *markdown* se trouvent dans le fichier `deck.mdx`. En fait, il s'agit de *MDX* et non de *markdown* à proprement parler, mais ça se ressemble beaucoup, sauf qu'on peut aussi insérer du React dans un *MDX*.

Pour générer le *slideshow*, il faut d'abord installer les outils (qui dépendent de NodeJS et NPM):

```sh
git clone https://github.com/millette/masto-2020-06-02.git
cd masto-2020-06-02
npm install
npm start # votre fureteur devrait s'ouvrir automatiquement sur http://localhost:8040/
# ctrl-c pour fermer la version de développment
npm run build # pour générer la version de productiond dans public/
```

## Framework

* <https://github.com/jxnblk/mdx-deck>
* <https://www.gatsbyjs.org/>
* <https://github.com/mdx-js/mdx>
* <https://github.com/system-ui/theme-ui>
* <https://reactjs.org/>


## Keyboard Shortcuts

| Key      | Description                                    |
| -------- | ---------------------------------------------- |
| Left Arrow, Page Up, Shift + Space | Go to previous slide |
| Right Arrow, Page Down, Space | Go to next slide          |
| ALT + P  | Toggle Presenter Mode                          |
| ALT + O  | Toggle Overview Mode                           |
| ALT + G  | Toggle Grid Mode                               |
