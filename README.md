[![Quarto Publish](https://github.com/vanHeemstraSystems/flow-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/flow-management/actions/workflows/publish.yml)

flow-management
# Flow Management

Can be read as "Flow Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Flow Management" at https://vanheemstrasystems.github.io/flow-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "Sequential Workflow Designer" at https://github.com/nocode-js/sequential-workflow-designer

<img width="1262" height="710" alt="Image" src="https://github.com/user-attachments/assets/1e9b0c85-922b-4949-b23e-e733bef2c521" />

<table>
<th colspan="5">Summarize with:</th><tr/> 
<td><a href="https://chat.openai.com/?q=please+read+and+summarize+the+content+from+this+url+https://github.com/vanHeemstraSystems/flow-management/">ChatGPT</a></td>
<td><a href="https://x.com/i/grok?text=please+read+and+summarize+the+content+from+this+url+https://github.com/vanHeemstraSystems/flow-management/">Grok</a></td>
<td><a href="https://www.google.com/search?udm=50&aep=11&q=please+read+and+summarize+the+content+from+this+url+https://github.com/vanHeemstraSystems/flow-management/">Google AI Mode</a></td>
<td><a href="https://www.perplexity.ai/search/new?q=please+read+and+summarize+the+content+from+this+url+https://github.com/vanHeemstraSystems/flow-management/">Perplexity</a></td>
<td><a href="https://claude.ai/new?q=please+read+and+summarize+the+content+from+this+url+https://github.com/vanHeemstraSystems/flow-management/">Claude.ai</a></td>  
</table>

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name flow-management-dev up --build -d
```
