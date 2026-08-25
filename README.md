# AIAE Helm Versions

Environment-specific values and image tags for AIAE services. Operational Hub
is the first deployed service.

Branches:

- dev - development values
- prod - production values

GitHub Actions updates operational-hub-api/images.yaml on the target environment branch after backend verification, image push, and Maven Liquibase migration succeed.
