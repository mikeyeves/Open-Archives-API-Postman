# Open Archives (openarchieven.nl) API — Postman Collection

A Postman (v2.1) collection for the **[Open Archives API](https://www.openarchieven.nl/api/docs/)** (27 requests), generated from the official OpenAPI spec. Open Archives indexes **hundreds of millions of genealogical records** from Dutch, Belgian, German, French and other archives: civil registration, church books, population registers, notarial records, military and emigration records. It also has page transcriptions, statistics, Dutch census data and historical weather.

**Import link** (Postman → Import → Link):
```
https://raw.githubusercontent.com/mikeyeves/Open-Archives-API-Postman/main/Open_Archives_API.postman_collection.json
```
No key and no environment file are needed. Settings are in the collection's **Variables** tab.

## Folders
| Folder | Requests |
|---|---|
| ★ Research searches | 6 |
| Records | 7 |
| Transcriptions | 3 |
| Stats | 9 |
| Related | 2 |

Record searches show results in a **Visualizer** table with person, role, event, date, place, source and archive.

## Notes
- **Rate limit:** 4 requests per second per IP. A descriptive User-Agent is sent automatically.
- **Search syntax:** `name` accepts two names and a year or period (e.g. `Coret 1800-1850`). See the [Records/Search docs](https://www.openarchieven.nl/api/docs/records/search.php).
- **Single record:** use `archive` + `identifier` from a search result with **Show a single genealogical record**.
- **Tested at build time:** `Bukovszky` returned 2 records (a French INSEE death index and the Reclaim The Records US index). `Krupl` and `Borbala Barna` returned 0.

## Related collections
[WikiTree](https://github.com/mikeyeves/WikiTree-API-Postman) · [Library of Congress](https://github.com/mikeyeves/Library-of-Congress-API-Postman) · [FamilySearch](https://github.com/mikeyeves/FamilySearch-API-Postman) · [European Archives](https://github.com/mikeyeves/European-Archives-APIs-Postman) · [UK & Ireland Archives](https://github.com/mikeyeves/UK-Ireland-Archives-APIs-Postman)

*Unofficial. Not affiliated with Open Archives. Built from the public OpenAPI spec.*
