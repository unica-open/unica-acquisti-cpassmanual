# CPASS USER MANUAL
User manual for CPass.

## Development
The manual MUST be created in both aggregate form and module-specific form.\
In case a new module-specific manual is created, it MUST be referenced in the `pom.xml` file and a corresponding `/src/main/assembly/distribution-<module>.xml` file MUST be generated to allow its handling.

## Configuration
In case a new profile is to be added, it MUST be referenced in the `<profiles>` section of the `pom.xml`. As of now, no particular specialization is given for any single profile, but they are defined by symmetry with other projects.
