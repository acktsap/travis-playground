# Travis Template

[![Build Status](https://travis-ci.com/acktsap/travis-playground.svg?token=C2YSnCVsgmivMDuqZgK9&branch=master)](https://travis-ci.com/acktsap/travis-playground)

ci, phase, job, build, stage, matrix

- [getting-started](https://docs.travis-ci.com/user/for-beginners/)
- [jobs-builds-matrices-stages](https://docs.travis-ci.com/user/job-lifecycle)
- [languages](https://docs.travis-ci.com/user/languages/)
- [validating](https://support.travis-ci.com/hc/en-us/articles/115002904174-Validating-travis-yml-files)

## Opinion

Use install, script (with custom script) along with matrices

Use stage to speed up test (run in parallelly)

Validate before commit it using `travis-lint`

Make sure script permission (must be executable)
