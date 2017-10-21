# devops-milestone2
Devops 2 Milestone Testing

## Itrust fork

https://github.ncsu.edu/akshetty/iTrust-v23

branch : fuzzer


## Fuzzer progress

fuzzer.js has main method that takes a directory path and randomly selects a sample list, and modifies them.

runFuzzerJob.js will clone the itrust module, call fuzzer.js and commit the changes.

### Things to add

1) add mvn compile step to verify if the changes are proper.
2) If the changes are proper, commit them else revert the changes.
3) After commiting changes, trigger a jenkins build and moonitor it.