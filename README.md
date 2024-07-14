# Import Obsidian vault to Typesense search engine

In this project, I'm testing [Typesense](https://typesense.org/) on the contents of an [Obsidian](https://obsidian.md/) vault.

```sh
$ mise install
$ pnpm install
$ docker compose up -d --wait
```

```sh
$ ./import.js
```

```sh
$ pnpm run http-server
```

Go to http://localhost:8080/instant-search/
