# WOLF CMS SELENIUM TESTS

## Introduction

These are basic tests that can be used for sanity checking Wolf CMS. The were created
using the Firefox Selenium IDE addon, in HTML format.

## Usage

- Install the Firefox Selenium IDE addon.
- Save all of the html test files in the same directory.
- Start the Selenium IDE console. (Tools -> Selenium IDE)
- Open the appropriate wolfcms-???-suite.html file in Selenium. (File -> Open Test Suite)
- Click "Play entire test suite".

## Requirements

The tests currently make a number of assumptions:

- Wolf CMS 0.7.2 is installed without any changes.
- Wolf CMS is installed under http://localhost/wolfcms/
- Clean URLs are *not* used.
- The administrative user is: admin
- The administrative user's password is: pswpsw
