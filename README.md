# Drion issue tracker

Public bug reports and app compatibility reports for the Drion alpha on the
Linux desktop (Flatpak) and Ubuntu Touch.

Drion runs Android apps on Linux. Getting started, requirements and the
privacy notes are at [actinis.io/drion](https://actinis.io/drion).

## Before you report

- Read the [known issues](https://github.com/Actinis-Drion/issue-tracker/issues?q=is%3Aissue+is%3Apinned)
  and search the [open reports](https://github.com/Actinis-Drion/issue-tracker/issues).
  Add to an existing report rather than opening a second one.
- Make sure you run the latest alpha. The launcher reminds you when a newer
  build is out; Settings → About shows the version you have.

## How to report

The easiest way is **Report a problem** in the Drion launcher. It opens a form
here with your Drion version and system details already filled in.

You can also open a form yourself:

- [Bug report](https://github.com/Actinis-Drion/issue-tracker/issues/new?template=bug_report.yml):
  Drion crashed, did not install or update, or did something wrong.
- [App compatibility report](https://github.com/Actinis-Drion/issue-tracker/issues/new?template=app_compatibility.yml):
  an Android app does not install, does not start, or does not work fully.

A good report names one problem, the steps that lead to it, and the Drion
version and build from Settings → About.

## This tracker is public

Everything you write or attach here can be read by anyone.

- Do not post passwords, account names, phone numbers or other personal data.
- Never post diagnostic archives or logs in this tracker or in Telegram.
  Email small files to contact@actinis.io and mention the issue number. For
  larger files, upload them to Google Drive or a similar service, restrict
  access to contact@actinis.io, and email the link with the issue number.

## Crash reports

In this alpha, Drion sends a crash report automatically when Drion itself
crashes. It collects nothing else. You do not need to file a crash that
happened once, but a report with the steps that led to it helps us fix it.

## What happens to your report

We read new reports every working day. If we need more details, we label the
report `need-info` and ask. When we confirm a defect, we track the fix in our
development tracker, label the report `tracked`, and post here when a build
with the fix is out.

## Chat

Drion has a Telegram group for each platform, for questions and discussion: [Linux desktop](https://t.me/drion_desktop) and [Ubuntu Touch](https://t.me/drion_ubuntu_touch). Please file bugs here, and never post diagnostic archives in the chat.
