# mercurius-command-policy

**English** | [Русский](README.ru.md)

Command danger classification and an execution policy: read-only only when proven, a never-allowed list, a role × server group matrix, one-time grants, quotas and an audit log of decisions. One policy for a local sandbox and for SSH.

Part of [Mercurius](https://github.com/opencck/mercurius) — an autonomous personal agent. The package does not depend on the Mercurius application and can be used on its own.

**Status:** the code still lives in the main repository, in [`src/CommandPolicy/`](https://github.com/opencck/mercurius/tree/master/src/CommandPolicy) (classifiers of shell and SSH commands, the never-allowed list); no date to move it yet.

**Stack:** PHP 8.2+.

## License

[MIT](LICENSE)
