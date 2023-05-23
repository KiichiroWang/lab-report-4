# Baseline Steps for Lab Report 4

Setup Delete any existing forks of the repository you have on your account
Setup Fork the repository
The real deal Start the timer!
Log into ieng6
Clone your fork of the repository from your Github account
Run the tests, demonstrating that they fail
Edit the code file to fix the failing test
Run the tests, demonstrating that they now succeed
Commit and push the resulting change to your Github account (you can pick any commit message!)

1. Completed Setup Steps

2. Login to ieng6
  [Login]("Step1")
  <ssh cs15lsp23qr@ieng6.ucsd.edu><enter><entered password><enter>
  Used the ssh command and my username and password credentials to login to the remote computer.
  
3. Clone Fork
    [Login]("Step1")
  <git clone><paste link><enter>
  Pasted and cloned the forked repository into the directory.
    
4. Ran the tests
    image
<javac><paste junit library><*.java><enter>
Compiled all the .java files.
  
 <java><paste junit library><ListExamplesTests><enter>
   Ran the test files to see that they did not work.
   
   5. Edit the Code
   image
   <vim ListExamples.java><enter><up><up><up><up><up><up><up><up><up><up><i><right><right><right><right><right><right><backspace><2><escape><:><w><q><enter>
     
     
     6. Run the tests
     <javac><paste junit library><*.java><enter>
Compiled all the .java files.
  
 <java><paste junit library><ListExamplesTests><enter>
   Ran the test files to see that they did not work.
   
   
   7.  Git Commit/Push
   git add .
   git commit -m "Wooo"
   git push origin main
   <username>
     <password>
