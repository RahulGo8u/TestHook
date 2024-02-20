# TestHook

#!/bin/bash

cd "$(dirname "$0")"                         
ln -s commit_msg ../.git/hooks/commit-msg
