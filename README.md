# interest
REST API from CSV/markdown/txt/SQLite

Drop a ... to a folder, and it will be served as REST endpoints, where ... might be:

- CSV: File names will be endpoints, first line will be field names, rows will be records.
- SQLite: Table names will be endpoints, columns will be fields, rows will be records.
- Markdown: File names will be endpoints, only tables are parsed, anything else is ignored.
- JSON: File names will be endpoints, objects in a list will be records, object keys will be fields.
- YAML: same as JSON (YAML is a superset of JSON)
