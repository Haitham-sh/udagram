#Pipeline process
After the developer pushes the repository on Github the circleci code do :
1. The pipeline uses orbs to install:
   * Node js,
   * the AWS cli
   * the EB cli.
2. checks out the code from the repo
3. Front-End install.
4. Back-End install
5. Front-End build.
6. Back-End build
7. deploy Front-End.
8. deploy Back-End.


 

 