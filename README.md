# workflows
Arraial Github reusable workflows bundle for Python applications

## Runtime prerequisites
Only requirement is to define a Makefile similar to the ([example](./Makefile.example)), where the required commands are:
- test_setup
- set_version
- lint
- format
- test_secrets_file
- test

For additional guidance, a docker-bake example is also [available](./example.docker-bake.hcl).
