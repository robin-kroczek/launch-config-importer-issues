# Launch Config Importer: Issue Tracker

Bug reports and feature requests for **Launch Config Importer**, the IntelliJ IDEA plugin that
converts Eclipse `.launch` files into IntelliJ run configurations.

Launch Config Importer is a commercial plugin. This repository contains no source code and is
used for issue tracking only.

## Report a bug

**From the IDE (preferred).** If the plugin fails with an unexpected error, IntelliJ shows a red
icon in the bottom-right corner of the status bar. Click it, select the error and choose
**Report to Launch Config Importer**. Your browser opens a pre-filled bug report on this page.
Check it, edit it if needed, and submit it.

**Manually.** Open a [new issue](https://github.com/robin-kroczek/launch-config-importer-issues/issues/new/choose)
and choose **Bug report**.

Helpful information:

- what you did and what you expected
- the messages from the import report (tool window **Launch Import**)
- plugin version, IDE version and operating system
- the `.launch` file, if you can share it (see below)

## Request a feature

Missing a launch type, an Eclipse attribute or an Eclipse variable such as `${project_loc}`?
Open a [new issue](https://github.com/robin-kroczek/launch-config-importer-issues/issues/new/choose)
and choose **Feature request**.

## Privacy

Issues in this repository are **public**. Before you submit, remove anything you do not want to
publish, for example:

- file paths, user names, company or customer names
- environment variables, VM arguments or program arguments that contain passwords, tokens or
  internal host names

`.launch` files often contain such values. Shorten them to the part that matters, or replace
values with placeholders.

## Security issues

Do not report security issues publicly. Use
[private vulnerability reporting](https://github.com/robin-kroczek/launch-config-importer-issues/security/advisories/new)
instead, see [SECURITY.md](SECURITY.md).

## Confidential reports

If you cannot share the details publicly, send the report by email to
**kontakt@rkroczek.de**. Please include the same information as in a public bug report.
