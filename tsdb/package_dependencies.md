# Dependency Table For: github.com/prometheus/prometheus/tsdb/**

| | c o n f i g - S | d i s c o v e r y - S | [d i s c o v e r y / t a r g e t g r o u p - S](../discovery/package_dependencies.md)  | p k g / e x e m p l a r - S | p k g / g a t e - S | p k g / l a b e l s - S | p k g / l o g g i n g - S | p k g / p o o l - S | p k g / r e l a b e l - S | p k g / t e x t p a r s e - S | p k g / t i m e s t a m p - S | p k g / v a l u e - S | p r o m p b - S | s c r a p e - S | s t o r a g e - S | s t o r a g e / r e m o t e - S | t s d b - S | t s d b / c h u n k e n c - S | t s d b / c h u n k s - S | t s d b / e n c o d i n g - S | t s d b / e r r o r s - S | t s d b / f i l e u t i l - S | t s d b / g o v e r s i o n - S | t s d b / i n d e x - S | t s d b / r e c o r d - S | t s d b / t o m b s t o n e s - S | t s d b / t s d b u t i l - S | t s d b / w a l - S | u t i l / o s u t i l - S |
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
| config | | S | | | | S | | | S | | | | | | | | | | | | | | | | | | | | |
| pkg/exemplar | | | | | | S | | | | | | | | | | | | | | | | | | | | | | | |
| pkg/relabel | | | | | | S | | | | | | | | | | | | | | | | | | | | | | | |
| pkg/textparse | | | | S | | S | | | | | | S | | | | | | | | | | | | | | | | | |
| scrape | S | | S | S | | S | | S | S | S | S | S | | | S | | | | | | | | | | | | | | S |
| storage | | | | S | | S | | | | | | | | | | | | S | S | | S | | | | | | S | | |
| storage/remote | S | | | S | S | S | S | | S | S | | | S | S | S | | | S | S | | | | | | S | | | S | |
| tsdb | S | | | S | | S | | | | | S | | | | S | | | S | S | S | S | S | S | S | S | S | S | S | |
| tsdb/agent | | | | S | | S | | | | | S | | | | S | S | S | | S | | | | | | S | | | S | |
| tsdb/chunks | | | | | | | | | | | | | | | | | | S | | | S | S | | | | | | | |
| tsdb/index | | | | | | S | | | | | | | | | S | | | | S | S | S | S | | | | | | | |
| tsdb/record | | | | | | S | | | | | | | | | S | | | | S | S | | | | | | S | | | |
| tsdb/tombstones | | | | | | | | | | | | | | | S | | | | | S | S | S | | | | | | | |
| tsdb/tsdbutil | | | | | | | | | | | | | | | | | | S | S | | | | | | | | | | |
| tsdb/wal | | | | | | | | | | | S | | | | | | | | S | | S | S | | | S | S | | | |

### Legend

* Rows - Importing packages
* columns - Imported packages


#### Meaning Of Row And Row Header Formatting

* **Bold** - God package (can use all packages)
* `Code` - Database package (can only use tool and other database packages)
* _Italic_ - Tool package (foundational, no dependencies)
* no formatting - Standard package (can only use tool and database packages)


#### Meaning Of Letters In Table Columns

* G - God package (can use all packages)
* D - Database package (can only use tool and other database packages)
* T - Tool package (foundational, no dependencies)
* S - Standard package (can only use tool and database packages)
