# Using KinD

The following is what is needed to use KinD to run the e2e tests. Base path is assumed to be the top level project.

Startup a cluster:

```shell
./test/kind/bootstrap.sh
```

Install the Discovery Controllers:

```shell
./test/kind/install.sh
```

Run the end to end tests:

```shell
./test/kind/e2e-tests.sh
```

Cleanup:

```shell
./test/kind/bootstrap.sh --shutdown
```