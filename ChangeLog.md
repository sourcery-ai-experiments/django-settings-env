# ChangeLog

### Release 4.7.1

- Add support for Env(timeout) parameter (vault connection timeout)

### Release 4.7.0

- Use django core redis cache if using django >= 4.0

### Release 4.6.1

- upgrade envex to 2.2.0 for improved Vault support

### Release 4.6

- upgraded envex to 2.1.0, inherited hashicorp vault support
- cleaned up env() call behavior
- increase test coverage on core functinality
- add build & publish github action

### Release 4.5.0
  - documentation cleanup
  - code quality improvements

### Release 4.3.0
  - fixed an issue evaluating DeferredSettings instance where __getattr__ would get skipped
  - deferred values are now cached
