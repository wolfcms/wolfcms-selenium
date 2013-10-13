# WOLF CMS SELENIUM TESTS

## Introduction

These are basic tests that can be used for sanity checking Wolf CMS. The were created
using the Firefox Selenium IDE addon, in HTML format.

## Usage

- Install the Firefox Selenium IDE addon.
- Clone the wolfcms-selenium repository.
- Start the Selenium IDE console. (Tools -> Selenium IDE)
- Open the .../dev/wolfcms-dev-suite.html file in Selenium. (File -> Open Test Suite)
- If you have a faster machine, you may want to dial down the speed to two thirds.
- Click "Play entire test suite".

## Requirements

The tests currently make a number of assumptions:

- The Wolf CMS install is a vanilla install (without any changes after install).
- Wolf CMS is installed under http://localhost/wolfcms/
- Clean URLs are *not* used.
- The administrative user is: admin
- The administrative user's password is: pswpsw

(please note that the admin password is the only change compared to vanilla installs)
