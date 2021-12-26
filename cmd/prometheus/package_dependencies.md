# Dependency Table For: github.com/prometheus/prometheus/cmd/prometheus

| | c o n f i g - S | [d i s c o v e r y - S](../../discovery/package_dependencies.md)  | [d i s c o v e r y / i n s t a l l - S](../../discovery/package_dependencies.md)  | [d i s c o v e r y / l e g a c y m a n a g e r - S](../../discovery/package_dependencies.md)  | [d i s c o v e r y / t a r g e t g r o u p - S](../../discovery/package_dependencies.md)  | n o t i f i e r - S | p k g / e x e m p l a r - S | p k g / g a t e - S | p k g / l a b e l s - S | p k g / l o g g i n g - S | p k g / p o o l - S | p k g / r e l a b e l - S | p k g / r u l e f m t - S | p k g / r u n t i m e - S | p k g / t e x t p a r s e - S | p k g / t i m e s t a m p - S | p k g / v a l u e - S | p r o m p b - S | p r o m q l - S | p r o m q l / p a r s e r - S | r u l e s - S | s c r a p e - S | s t o r a g e - S | s t o r a g e / r e m o t e - S | t e m p l a t e - S | [t s d b - S](../../tsdb/package_dependencies.md)  | [t s d b / a g e n t - S](../../tsdb/package_dependencies.md)  | [t s d b / c h u n k e n c - S](../../tsdb/package_dependencies.md)  | [t s d b / c h u n k s - S](../../tsdb/package_dependencies.md)  | [t s d b / e r r o r s - S](../../tsdb/package_dependencies.md)  | [t s d b / i n d e x - S](../../tsdb/package_dependencies.md)  | [t s d b / r e c o r d - S](../../tsdb/package_dependencies.md)  | [t s d b / t s d b u t i l - S](../../tsdb/package_dependencies.md)  | [t s d b / w a l - S](../../tsdb/package_dependencies.md)  | u t i l / h t t p u t i l - S | u t i l / o s u t i l - S | u t i l / s t a t s - S | u t i l / s t r u t i l - S | u t i l / t e s t s t o r a g e - S | u t i l / t e s t u t i l - S | w e b - S | w e b / a p i / v 1 - S | w e b / u i - S |
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
| **cmd/prometheus** | **S** | **S** | **S** | **S** | **S** | **S** | **S** | | **S** | **S** | | **S** | | **S** | | | | | **S** | | **S** | **S** | **S** | **S** | | **S** | **S** | | | | | | | | | | | **S** | | | **S** | | |
| config | | S | | | | | | | S | | | S | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| notifier | S | | | | S | | | | S | | | S | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| pkg/exemplar | | | | | | | | | S | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| pkg/relabel | | | | | | | | | S | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
| pkg/rulefmt | | | | | | | | | | | | | | | | S | | | | S | | | | | S | | | | | | | | | | | | | | | | | | |
| pkg/textparse | | | | | | | S | | S | | | | | | | | S | | | | | | | | | | | | | | | | | | | | | | | | | | |
| promql | | | | | | | S | | S | | | | | | | S | S | | | S | | | S | | | S | | S | | | | | | | | | S | | S | S | | | |
| promql/parser | | | | | | | | | S | | | | | | | S | S | | | | | | S | | | | | | | | | | | | | | | S | | | | | |
| rules | | | | | | | | | S | | | | S | | | S | S | | S | S | | | S | | S | | | | | | | | | | | | | S | | | | | |
| scrape | S | | | | S | | S | | S | | S | S | | | S | S | S | | | | | | S | | | | | | | | | | | | | S | | | | | | | |
| storage | | | | | | | S | | S | | | | | | | | | | | | | | | | | | | S | S | S | | | S | | | | | | | | | | |
| storage/remote | S | | | | | | S | S | S | S | | S | | | S | | | S | | | | S | S | | | | | S | S | | | S | | S | | | | | | | | | |
| template | | | | | | | | | | | | | | | | | | | S | | | | | | | | | | | | | | | | | | | S | | | | | |
| util/httputil | | | | | | | | | | | | | | | | | | | S | | | | | | | | | | | | | | | | | | | | | | | | |
| util/teststorage | | | | | | | S | | S | | | | | | | | | | | | | | S | | | S | | | | | | | | | | | | | | S | | | |
| web | S | | | | | S | | | S | | | | | | | S | S | | S | S | S | S | S | | S | S | | | | | S | | | | S | | | | | | | S | S |
| web/api/v1 | S | | | | | | S | | S | | | | | | S | S | | | S | S | S | S | S | S | | S | | | | | S | | | | S | | S | | | | | | |

### Legend

* Rows - Importing packages
* Columns - Imported packages


#### Meaning Of Row And Row Header Formatting

* **Bold** - God package (can use all packages)
* `Code` - Database package (can only use tool and other database packages)
* _Italic_ - Tool package (foundational, no dependencies)
* No formatting - Standard package (can only use tool and database packages)


#### Meaning Of Letters In Table Columns

* G - God package (can use all packages)
* D - Database package (can only use tool and other database packages)
* T - Tool package (foundational, no dependencies)
* S - Standard package (can only use tool and database packages)
