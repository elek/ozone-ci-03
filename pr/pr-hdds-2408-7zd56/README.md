# Tests with failure status

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/checkstyle/summary.txt)

hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/OzoneManager.java
 57: Unused import - org.apache.hadoop.io.retry.RetryPolicy.
 135: Unused import - org.apache.hadoop.hdds.utils.RetriableTask.
 171: Unused import - org.apache.hadoop.io.retry.RetryPolicies.retryUpToMaximumCountWithFixedSleep.
hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/ozone/TestSecureOzoneCluster.java
 67: Unused import - org.apache.hadoop.security.KerberosAuthException.

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.TestSecureOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster-output.txt))
 * [org.apache.hadoop.ozone.ozShell.TestOzoneShellHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA-output.txt))
 * [org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider-output.txt))
 * [org.apache.hadoop.ozone.om.TestOMRatisSnapshots](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOMRatisSnapshots.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOMRatisSnapshots-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2408-7zd56/acceptance/summary.html)



# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2408-7zd56/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/checkout)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/build)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/rat)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2408-7zd56/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2408-7zd56/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
