# Simple C# Web Server

## Startup Steps
- Open a terminal and change to the folder containing the project. Specifically, where the `.sln` file is

## Build the app
- `dotnet build`

## Starting the server
- `dotnet run --project basic-web-app`

## Testing
- Run the tests
  - `dotnet test`

## Deployed Link
[link](http://deploycsharpappenv-env.wmp3upeg2i.us-west-2.elasticbeanstalk.com/)

## Code Build
+ Add Code Build -> 'Create new Build Stage'
    + Choose windows environment
    + Choose Use your Own (make sure yml file is at root of your Git repo)
    ![](./assets/source.png)
    ![](./assets/build.png)

    ### Blockers
    + Do not revise YAML file in intellij
    + **SPACES ARE VERY SPECIFIC AND SENSITIVE!!!** -> 2 spaces for an indent
        + YAML LINT will verify if spacing is correct
        ![](./assets/error.png)