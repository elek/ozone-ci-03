# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.ozShell.TestOzoneShellHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA-output.txt))
 * [org.apache.hadoop.ozone.om.TestKeyManagerImpl](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestKeyManagerImpl.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestKeyManagerImpl-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.TestSecureOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis-output.txt))
 * [org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerConfiguration](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerConfiguration.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerConfiguration-output.txt))
 * [org.apache.hadoop.ozone.om.TestOMRatisSnapshots](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOMRatisSnapshots.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOMRatisSnapshots-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2408-nxmhk/acceptance/summary.html)



# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/unit)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/checkstyle)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-nxmhk/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2408-nxmhk/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-nxmhk/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
