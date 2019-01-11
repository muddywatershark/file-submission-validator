fsvl
---
### File submissions validator

Signs (MD5) and checks for duplicates in submitted files writing information into a log, returns UI messages and exit codes.

#### UI Messages

In order to use different user interface messages please edit (before build) `ui-msg.yaml` and run `./yaml2shell ./ui-msg.yaml` this will re-generate `us-msg.sh`.

#### Building complete script

Run `./build-fsvl`

#### Installing script

Run `./install-fsvl`

#### Testing installation

Run `fsvl --version` or `fsvl -v`
