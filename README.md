# command-line-helpers - for cmd and bash


##### uninstall all node dependencies from project dir
windows: ```for /f %f in ('dir node_modules /b') do echo npm uninstall %f && npm uninstall %f```

bash: ```for package in `ls node_modules`; do npm uninstall $package; done;```
