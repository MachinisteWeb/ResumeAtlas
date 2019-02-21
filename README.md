# ResumeAtlas #

Version : 0.12.0 (Beta)

NodeAtlas Version minimale : 2.0.x

**For an international version of this README.md, [see below](#international-version).**



## Avant-propos ##

ResumeAtlas est un exemple de site web multilingue sans back-end maintenable avec [NodeAtlas](http://node-atlas.js.org/). Il fait également office d'exemple de maquette HTML exportable.

Il peut vous servir d'inspiration pour créer vos propres sites !



## Modifier le site en local ##

Pour modifier le site avec un rendu en temps réel, il vous faudra installer [NodeAtlas](http://node-atlas.js.org/) sur votre poste de développement et vous rendre dans le dossier :

```
\> cd </path/to/resume>sources/
```

et utilisez la commande :

```
\> node </path/to/>node-atlas/ --browse
```

ou lancez `server.na` en double cliquant dessus :
- en expliquant à votre OS que les fichiers `.na` sont lancé par défaut par `node`,
- en ayant installé `node-atlas` via `npm install -g node-atlas`
- en étant sur que votre variable d'environnement `NODE_PATH` pointe bien sur le dossier des `node_modules` globaux.

Les deux pages seront à :

- *http://localhost:7777/*
- *http://localhost:7777/en/*



## Générer le site ##

Une fois que votre site vous plait, générez sa version exportable en utilisant :

```
\> cd </path/to/resume>sources/
```

puis en utilisant la commande :

```
\> node </path/to/>node-atlas/ --generate
```

Il ne vous reste plus qu'à envoyer le dossier `</path/to/resume>website/` 
- à votre client pour une review des assets HTML ou
- à votre équipe Back-end pour une intégration dans un CMS, ou un site PHP, .NET, Node.js ou
- sur votre serveur de production quelque soit l'environnement (Apache, IIS, Node.js, etc.).



## Même fichier, configuration différente ##

Vous pouvez transformer votre projet initialement paramètré pour créer des maquettes en un site sans Back-end avec NodeAtlas.

Il suffit pour cela de monter le site sur un serveur et d'utiliser un webconfig différent :


```
\> cd </path/to/resume>sources/
```

puis en utilisant la commande :

```
\> node </path/to/>node-atlas/ --webconfig webconfig.prod.json
```


## Exemple en ligne ##

Vous pouvez voir fonctionner ce repository à l'adresse : [http://bruno.lesieur.name/](http://bruno.lesieur.name/).


-----


## International Version ##

### Overview ###

ResumeAtlas is an example of a multilingual website maintainable without back-end with [NodeAtlas](http://node-atlas.js.org/). It also used as an example of HTML exportable model.

It used as inspiration to create your own website!



### Edit the website in local server ###

To change the website with a real-time rendering, you need to install [NodeAtlas](http://node-atlas.js.org/) on your development computer and go to the folder:

```
\> cd </path/to/resume>sources/
```

and use the command:

```
\> node </path/to/>node-atlas/ --browse
```

or run `server.na` by double clicking and:
- explaining your OS that `.na` files are run by default with `node`,
- Having installed `node-atlas` via `npm install -g node-atlas`
- Being on your environment variable `NODE_PATH` is pointing to the global `node_modules` folder.

The two pages will be to:

- *http://localhost:7777/*
- *http://localhost:7777/en/*



### Generate site ###

Once your site vous plait, generate its exportable version using:

```
\> cd </path/to/resume>sources/
```

then using the command:

```
\> node </path/to/>node-atlas/ --generate
```

It'll just send the file `</path/to/resume>website/` 
- to your client for review of HTML assets
- à votre équipe Back-end pour une intégration dans un CMS, ou un site PHP, .NET, Node.js ou
- to your Back-end team for integration into a CMS, or a PHP site, .NET, Node.js or
- on your production server in any environment (Apache, IIS, Node.js, etc.).



### Same file, different configuration ###

Vous pouvez transformer votre projet initialement paramètré pour créer des maquettes en un site sans Back-end avec NodeAtlas.
You can turn your generating asset project into a website without Back-end with NodeAtlas.

Simply mount the site on a server and use a different webconfig:


```
\> cd </path/to/resume>sources/
```

then using the command:

```
\> node </path/to/>node-atlas/ --webconfig webconfig.prod.json
```


### Online Example ###

You can see this repository running at: [http://bruno.lesieur.name/](http://bruno.lesieur.name/) (Fr).