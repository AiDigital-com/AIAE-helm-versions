# AIAE Helm Versions

Feedlot-style immutable image versions for AIAE services. Operational Hub is
the first deployed service.

Branch ownership:

- `main` contains one values directory per deployable service.

GitHub Actions commits new application and Liquibase image tags to `main`, then
pins that commit in the target `AIAE-helm` environment branch.
