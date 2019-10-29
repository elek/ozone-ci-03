# Tests with failure status

## findbugs check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2363-bbk75/findbugs/summary.html)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/findbugs/summary.txt)

M D RCN: Redundant nullcheck of StringBuilder.toString(), which is known to be non-null in new org.apache.hadoop.hdds.utils.RocksDBStore(File, Options)  Redundant null check at RocksDBStore.java:[line 82]
M D RCN: Redundant nullcheck of StringBuilder.toString(), which is known to be non-null in new org.apache.hadoop.hdds.utils.db.RDBStore(File, DBOptions, WriteOptions, Set, CodecRegistry)  Redundant null check at RDBStore.java:[line 137]

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))
 * [org.apache.hadoop.ozone.container.common.impl.TestContainerPersistence](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.impl.TestContainerPersistence.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.impl.TestContainerPersistence-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/unit)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.container.common.impl.TestHddsDispatcher](hadoop-hdds/container-service/org.apache.hadoop.ozone.container.common.impl.TestHddsDispatcher.txt) ([output](hadoop-hdds/container-service/org.apache.hadoop.ozone.container.common.impl.TestHddsDispatcher-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/rat)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/checkstyle)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/build)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2363-bbk75/acceptance/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2363-bbk75/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/author)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2363-bbk75/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
