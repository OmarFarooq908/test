# Notes

1. ```git
   git init
   ```

2. ```git
   git add .
   ```

3. ```git
   git commit -m "First commit"
   ```

4. ```git
   git remote add origin https://github.com/OmarFarooq908/test.git
   ```

5. ```git
   git push -u origin master
   ```

6.  If you get the following message:

   ​	

   ```git
    ! [rejected]        master -> master (fetch first)
   error: failed to push some refs to 'https://github.com/OmarFarooq908/test.git'
   hint: Updates were rejected because the remote contains work that you do
   hint: not have locally. This is usually caused by another repository pushing
   hint: to the same ref. You may want to first integrate the remote changes
   hint: (e.g., 'git pull ...') before pushing again.
   hint: See the 'Note about fast-forwards' in 'git push --help' for details.
   ```

   Then run the following command:

   ```git
   git push -u origin master --force
   ```

   