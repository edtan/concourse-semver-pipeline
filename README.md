# concourse-semver-pipeline

An example of a Concourse pipeline to illustrate how to utilize idempotence.  If you'd like to run these examples, launch the [Concourse quick start](https://concourse-ci.org/#quickstart).  Modify the examples to point to your own GitHub accounts, and populate secrets.yml (use secrets.yml.example as a template) with your GitHub credentials.  Then run:

```
fly -t local sp -p initial -c initial-pipeline.yml -l secrets.yml
fly -t local sp -p final -c final-pipeline.yml -l secrets.yml
```
