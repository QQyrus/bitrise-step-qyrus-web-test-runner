# bitrise-step-qyrus-web-test-runner

This steps help to run tests on web automation service Qyrus platform.

## Limitations

You can run only the test suites but not the test scripts, Also user will not be able to choose
the browser versions.

## How to use this Step

Add the *qyrus-web-test-runner* step into your worflow.

Initialize inputs variables from the bitrise form.

* Qyrus gateway URL `$GATEWAY_URL` **required**
* Qyrus Username `$QYRUS_USERNAME` **required**
* Qyrus Team Name `$QYRUS_TEAM_NAME` **required**
* Qyrus Project Name `$QYRUS_PROJECT_NAME` **required**

**Note:** 
* Please set the $QYRUS_PASSWORD under secrets.
* Please set the $DEBUG_MODE to yes (Prints additional debug information in logs if this option is enabled).

## Support
Please write us at support@qyrus.com