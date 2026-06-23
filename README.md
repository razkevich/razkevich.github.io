# razkevich.github.io

Serves the **ValkeyCluster Operator** documentation at <https://razkevich.github.io/>.

This repo intentionally contains no docs. The canonical source is
[`razkevich/valkeycluster-operator`](https://github.com/razkevich/valkeycluster-operator)
(`docs/` + `mkdocs.yml`); the workflow here checks that repo out, builds the MkDocs site, and
deploys it to GitHub Pages. It rebuilds on a schedule and can be refreshed on demand via
**Actions → deploy → Run workflow**.
