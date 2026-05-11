# CUE Controller Rewire Privacy Policy

Effective date: May 11, 2026

CUE Controller Rewire is a Chrome extension that connects Google Sheets workflows
to the CUE Controller desktop application running locally on the user's computer.

## Single Purpose

The extension has one purpose: to connect Google Sheets with the local CUE
Controller desktop app. It allows users to open CUE timecode links from Google
Sheets and allows the local app to receive the active spreadsheet row/cell
context for Sheet Stamp workflows.

## Data Handled

The extension may read limited metadata from Google Sheets pages when the user is
using the workflow:

- Spreadsheet ID from the current Google Sheets URL.
- Sheet gid from the current Google Sheets URL.
- Active cell reference from the Google Sheets name box.
- Active row and column metadata derived from the active cell reference.
- CUE Controller timecode links clicked by the user.

The extension does not intentionally read, collect, or transmit full spreadsheet
contents.

## How Data Is Used

The data is used only to send workflow commands and row/cell context to the CUE
Controller desktop app running locally on the user's computer.

The extension communicates with the local app at:

```text
http://127.0.0.1:43142/
```

This loopback address refers to the user's own computer.

## Data Sharing

CUE Controller Rewire does not sell, rent, share, or transfer user data to third
parties.

The extension does not send user data to the developer, to analytics services, to
advertising services, or to any remote server.

## Remote Code

The extension does not load or execute remotely hosted code. All extension logic
is included in the packaged extension files.

## Storage

The extension does not store spreadsheet contents on external servers.

The CUE Controller desktop app may separately use Google Sheets APIs when the
user configures Sheet Stamp features in the desktop app. That app-side access is
used only to write user-requested CUE workflow data, such as timecode links or
session log rows, into the user's selected Google Sheet.

## Limited Use

The use of information received from Chrome extension permissions complies with
the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Contact

For privacy questions, contact:

```text
emu@muziument.com
```
