# PracticeRepo

This repo exists so that you can make sure that you can 
clone a repo, make changes, and push those changes back
to Github.  

Make sure that you have configured your `.gitconfig` file
as described on Canvas and that you have your Authentication
Token.


## Steps


* Clone the repo

  ```
  git clone https://github.com/cs334s26/PracticeRepo.git
  ```

* Make sure you are in the folder

  ```
  cd PracticeRepo
  ```

* Create a file `<lastname>.txt` and add a few lines of text.

  ```
  nano <lastname>.txt
  ```
  
* Add and Commit your file (on the `main` branch)

  ```
  git add <lastname>.txt
  git commit -m "add information about me"
  ```

* Push your commit back to the repo

  ```
  git push origin main
  ```

  If you see the following:

  ```
  ! [rejected]        main -> main (fetch first)
  error: failed to push some refs to 'https://github.com/cs334s26/PracticeRepo.git'
  hint: Updates were rejected because the remote contains work that you do not
  hint: have locally. This is usually caused by another repository pushing to
  hint: the same ref. If you want to integrate the remote changes, use
  hint: 'git pull' before pushing again.
  hint: See the 'Note about fast-forwards' in 'git push --help' for details.
  ```

  it means that someone else pushed to the repo while you were working.  In
  this case you need to pull their work down first:

  ```
  git pull origin main
  ```

  This will open `nano` with the message:

  ```
  Merge branch 'main' of https://github.com/cs334s26/PracticeRepo
  ```

  You can leave this message as-is and exit `nano`.  This will merge the 
  work on Github with your copy of the repo on your laptop.

  Now you can push:

  ```
  git push origin main
  ```

* Verify that your file is in the [repo](https://github.com/cs334s26/PracticeRepo).



