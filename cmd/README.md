# cmd, terminal, etc.


#### start/stop services UI
```
services.msc
```

#### git delete remote
```
git push origin --delete features/TICKET-000-name
```

#### - git useful
git reset ORIG_HEAD
git branch -m <new_name>
git push -u origin <branch_to_push_and_start_tracking> 
git branch --set-upstream-to <remote-branch>


#### delete recursive e.g: .DT_Store
```
del /s /q /f /a .DS_STORE
```

#### port already used - kill
```
netstat -o -n -a | findstr 1099
taskkill /F /PID 3724
```

#### kill all desc by name
```
taskkill /f /im postgres.exe
```

#### postgres
```
# login
psql -U db_user -d db_name
# db_pswd

# postgres import 
# db_name=>
\i 'C:\\Users\\jmelezinek\\Downloads\\db_name.dmp'
```
