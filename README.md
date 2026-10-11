# migration-plan-reviewer

Review a migration plan for sequencing and rollback gaps.

## Run

Requires Go 1.22+.

```sh
go run .
```

The tool reads its development gateway settings from `config/development.json`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.
