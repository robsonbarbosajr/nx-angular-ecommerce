# Ecommerce

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **Este workspace foi gerado por Robson Júnior** ✨

## Para iniciar a aplicação

Execute `npm start` para iniciar o servidor de desenvolvimento.

## Para gerar build em produção

Execute `npm build` para construir a aplicação. Os artefatos serão armazenados no diretório de saída (e.g. `dist/` ou `build/`), pronto para seu deploy.

## Executando tasks

Para executar tasks com Nx use a seguinte sintaxe:

```
npx nx <target> <project> <...options>
```

Você também pode executar para multiplos destinos:

```
npx nx run-many -t <target1> <target2>
```

..ou adicione `-p` para filtrar projetos especificos

```
npx nx run-many -t <target1> <target2> -p <proj1> <proj2>
```

Destinos podem ser definidos no `package.json` ou `projects.json`. Leia mais [na documentação](https://nx.dev/features/run-tasks).

## Set up CI!

Nx comes with local caching already built-in (check your `nx.json`). On CI you might want to go a step further.

- [Set up remote caching](https://nx.dev/features/share-your-cache)
- [Set up task distribution across multiple machines](https://nx.dev/nx-cloud/features/distribute-task-execution)
- [Learn more how to setup CI](https://nx.dev/recipes/ci)

## Explore the project graph

Run `npx nx graph` to show the graph of the workspace.
It will show tasks that you can run with Nx.

- [Learn more about Exploring the Project Graph](https://nx.dev/core-features/explore-graph)

## Connect with us!

- [Join the community](https://nx.dev/community)
- [Subscribe to the Nx Youtube Channel](https://www.youtube.com/@nxdevtools)
- [Follow us on Twitter](https://twitter.com/nxdevtools)
