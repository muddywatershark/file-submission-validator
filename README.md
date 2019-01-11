fsvl
---
### File submissions validator

Signs (MD5) and checks for duplicates in submitted files writing information into a log, returns UI messages and exit codes.

#### UI Messages

In order to use different user interface messages please edit (before build) `ui-msg.yaml` and run `./yaml2bash.sh ./ui-msg.yaml` this will re-generate `us-msg.sh` (used later for `build` process).

#### How to build a complete script

Run `./build-fsvl.sh`

#### How to install the script

Run `./install-fsvl.sh`

#### Testing installation

Run `fsvl --version` or `fsvl -v`
