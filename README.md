# test
This repository is supposed to be for testing anything related to GitHub and Webappky Phabricator (phabricator.vps.urbanec.cz). If you are connected to Webappky and wish have access, write to Urbanecm. 

## What is this repo for

For playing with Phabricator, in connection to GitHub. We have this as a permanent testing space as we don't want to have thousands of test-only repos/projects etc. All testing activities can be in one place. 

## What is this repo not for

For publishing content which will be used somehow, no matter if in production or test environment. 

## What is working

* Audits - you can request audits from your test account
* Autoclose - if you say something like Fixes T1241, Phabricator will close that task instead of you. 
* Browsing all our code in Phabricator
* Commenting changes on Phabricator
* Editing from GitHub web/with git@github.com (actually, you can't use anything else)

## What is working not

* Editing from Phabricator - Phabricator uses anonymous access so it can't push (yeah, it is possible to monitor private repositories, then a read-only private key is used)
* Phabricator code-review - Phabricator can't modify repository itself and successful code-review is a way to say yeah, you can merge this change at any time, as Phabricator does not control this repository, it can't take this role)
