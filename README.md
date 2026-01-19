# cqlTextMate

An open source grammar compatible with textmate for CQL (Cassandra Query Language).

> [!TIP]
> CQL is now supported by GitHub | [github-linguist v9.4.0](https://github.com/github-linguist/linguist/releases/tag/v9.4.0)
> Example using `cql` instad of `sql`
> ```cql
> ALTER MATERIALIZED VIEW cycling.cyclist_by_age
> ALTER MATERIALIZED VIEW cycling.cyclist_by_age
> WITH comment = 'A most excellent and useful view'
> AND bloom_filter_fp_chance = 0.02;
> 
> ALTER MATERIALIZED VIEW cycling.cyclist_by_age
> WITH compression = {
>    'sstable_compression' : 'DeflateCompressor',
>   'chunk_length_kb' : 64
> }
> AND compaction = {
>    'class' : 'SizeTieredCompactionStrategy',
>    'max_threshold' : 64
> };
>
> ALTER MATERIALIZED VIEW cycling.cyclist_by_age
> WITH caching = {
>    'keys' : 'NONE',
>    'rows_per_partition' : '15'
> };
> ```

> [!NOTE]
> If you experiencing any issues with the grammar, feel free to open an issue on github

# Other Open Source Grammar and Tooling for CQL

- [Nvim Plugin](https://github.com/Akzestia/nvim-cql-v2)
- [Zed Extension](https://github.com/Akzestia/zed-cql)
- [Language Server](https://github.com/Akzestia/cqlls)
- [Tree-Sitter](https://github.com/Akzestia/tree-sitter-cql)

# VS Code integration | Highlights

You can use cqlTextMate with the following VS Code [Extension](https://marketplace.visualstudio.com/items?itemName=pedro-w.tmlanguage).

# Language Server Support in VsCode

I don't currently have plans to create or integrate a VS Code extension for language server support.
My main focus is on Neovim and Zed (primarily Neovim, since Zed has become bloated with AI features).
