# Privacy Policy — Buhalteris Automation

**Effective date:** 2026-06-30

Buhalteris Automation ("the add-on") is a Google Workspace add-on for Google
Docs used by an accounting team to format weekly meeting protocol documents,
archive tasks, and send protocol and reminder emails. This policy explains what
data the add-on accesses and how it is handled.

## Who runs the add-on

Developer: Areza Digital — nikita@shipmint.dev

The add-on runs entirely inside Google Apps Script under the account of the
user who installs it. The developer does not operate any external server and
does not receive your data.

## Data the add-on accesses

The add-on uses the following Google authorisation scopes, only to provide its
features:

- **Google Docs (documents)** — read and edit the protocol and archive
  documents you use it with (formatting, numbering, archiving tasks).
- **Google Drive (drive)** — find protocol and archive documents in the folder
  you configure, and create new protocol/archive documents on your request.
- **Gmail send / modify** — send protocol notifications, reminders, per-person
  and deadline emails from your own account, and reply within the protocol
  email thread. The add-on does not read your unrelated email; the Gmail access
  is used to send messages and to locate the protocol thread it created.
- **Run as a trigger (script.scriptapp)** — install the optional weekly/daily
  automatic schedule you enable.

## Data the add-on stores

The add-on stores its configuration in Apps Script properties inside your own
Google account:

- the Drive folder ID and the selected protocol/archive document IDs,
- the team list (names and email addresses) you enter,
- your email templates and schedule on/off settings.

This information stays within your Google account. It is not transmitted to the
developer or to any third party. The names, email addresses and task details
processed from your documents are your data and remain under your control.

## How data is used and shared

- Data is used only to perform the actions you trigger (formatting, archiving,
  sending emails) or the schedule you enable.
- The add-on does not sell, share, or transfer your data to third parties.
- The add-on does not use Google Workspace data for advertising or to train any
  AI/ML model.
- Emails are delivered through Google's Gmail service to the recipients you
  configure.

## Data retention and deletion

Settings persist until you change them or uninstall the add-on. To remove all
stored settings, clear the script properties or uninstall the add-on and revoke
its access at https://myaccount.google.com/permissions. Documents and emails
created by the add-on remain in your Google Drive and Gmail under your control.

## Changes

This policy may be updated; the current version applies to continued use.

## Contact

Questions: Areza Digital — nikita@shipmint.dev
