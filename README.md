# beam-go

Following are the steps to run the program on your system.

1. Firstly, visit this [Link](https://beam.apache.org/get-started/quickstart-go/#run-wordcount) and install ```go1.18.windows-amd64.msi``` on to your system.
2. Upon successfull download, install the setup file.
3. After that, create project directory with the name 'beam-go' on your system. 
4. Type this command in the directory using Powershell with admin privileges or VS Code
> ```go mod init github.com/<yourgithubusername>/beam-go```
5. Below are the set of instructions to run the project.
> ```go version``` - To check the version
  
> ```go get -u github.com/apache/beam/sdks/v2/go/pkg/beam``` - To get the Apache Beam Go SDK
  
> ```go install github.com/apache/beam/sdks/v2/go/examples/wordcount``` - To install the wordcount program
  
> ```wordcount --input <PATH_TO_INPUT_FILE> --output counts``` - To run the program
  
6. The output file will be generated
  
