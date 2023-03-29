# DotNet Setup (dotnet6)

1. Download script - 
    ```
    wget https://dot.net/v1/dotnet-install.sh -O dotnet-install.sh
1. Giving permissions to execute
    ```
    sudo chmod +x ./dotnet-install.sh
1. Running shell script
    ```
    ./dotnet-install.sh --version latest
1. Adding to environment variables
    ``` 
    sudo nano ~/.bashrc
    export DOTNET_ROOT=$HOME/.dotnet
    export PATH=$PATH:$HOME/.dotnet:$HOME/.dotnet/tools
1. Checking version
    ```
    dotnet --version


# Clone the code
1. ```
    git clone https://github.com/anandshende/.net-samplecode.git
    mv .net-samplecode dotnet-samplecode
    cd dotnet-samplecode
    git checkout master


# Building
1. Build using dotnet
    ```
    cd DynamoStudentManager
    dotnet build

# Running
1. Run using dotnet
    ```
    dotnet run
