# capability-graph-kotoba

Atomic authority package for `graph/kotoba`.

- imports: `#{:kgraph-assert! :kgraph-retract! :kgraph-query :kgraph-get-objects}`
- effects: `#{:storage-read :storage-write}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
