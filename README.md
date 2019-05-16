# DLTS Load Tests

Note that the JMeter test plans will work as-is if this repo has been cloned to `/tmp/dlts-load-tests`.
If you wish to place the repo somewhere else, change the ROOT user defined variable in *Test Plan Configuration*
from (using ACO as an example) `/tmp/dlts-load-tests/aco/jmeter-test-plan` to
`[Absolute path to root of dlts-load-tests repo]/aco/jmeter-test-plan`.

`${ROOT}` is used to specify the paths to the data files and reports output by the test run.  If the directories
in these paths do not already exist, JMeter will create them when it first writes out to the files, so make
sure `${ROOT}` is pointing to exactly where you want it.  It has been set to default to
`/tmp/dlts-load-tests` for safety.

These test plans were developed in JMeter version 2.13, which can be downloaded from https://archive.apache.org/dist/jmeter/binaries/.