## 0.1.1 (November 24, 2026)

- Install script uses `$os_name`, `$arch_name`, and `$CLI_VERSION` with no braces. The task driver treats `${...}` as Nomad interpolation and failed the prestart task with "Unknown variable".
- Add `node_pool` variable

## 0.1.0 (November 23, 2026)

- Initial pack. Prestart install of the Cursor CLI, worker task, Nomad Variable API key, and an HTTP check on `/healthz`.
