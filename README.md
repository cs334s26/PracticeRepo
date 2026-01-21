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

* Verify that your file is in the [repo](https://github.com/cs334s26/PracticeRepo).



