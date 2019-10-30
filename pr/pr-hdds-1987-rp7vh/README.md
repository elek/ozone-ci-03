# Tests with failure status

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/checkstyle/summary.txt)

hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/KeyManagerImpl.java
 2052: Line is longer than 80 characters (found 86).

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-1987-rp7vh/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractRename](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractRename.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractRename-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFileSystem](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFileSystem.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFileSystem-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDistCp](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDistCp.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDistCp-output.txt))
 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/rat)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-1987-rp7vh/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-1987-rp7vh/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-1987-rp7vh/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
