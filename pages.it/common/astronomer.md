# astronomer

> Strumento per individuare star illegittime da account bot su progetti GitHub.
> Maggiori informazioni: <https://github.com/Ullaakut/astronomer>.

- Scannerizza una repository:

`astronomer {{khulnasoft-lab/cheatlist-node-client}}`

- Scannerizza le star di una repository fino ad un massimo di 50:

`astronomer {{khulnasoft-lab/cheatlist-node-client}} --stars {{50}}`

- Scannerizza una repository includendo report comparativi:

`astronomer {{khulnasoft-lab/cheatlist-node-client}} --verbose`
