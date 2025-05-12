# Testing issue 8541

A simple repro to test out multi tenancy on the auth emulator

## Steps to run

1. Run `firebase emulators:start --project demo-project`
2. Open "http://127.0.0.1:5000/" in a web browser and follow the steps listed

## Expected behavior

SSO users should be created in the tenant that is specified.

## Actual behavior

SSO users are always created in the default tenant.

