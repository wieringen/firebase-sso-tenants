# Testing issue 5623

A simple repro to test out multi tenancy on the auth emulator

## Steps to run

1. Run `firebase emulators:start --project demo-project`
2. Open "http://127.0.0.1:5000/" in a web browser and follow the steps listed

## Expected behavior

When using sign in with pop-up an a Google Auth provider. show the correct tenant

## Actual behavior

Only users on the "default" tenant is being shown
