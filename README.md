# avalanche-HyperSDK-Project-Create-a-Custom-Subnet_M4.2
// Project: Step By Step

!. Inside your project folder," run go mod tidy " to normalize all the dependencies
Configure your project constants

2. Go to consts/consts.go and add the missing parts.
Register the Create_Asset and Mint_Assest actions in registry/registry.go
Run your VM locally

3. Make sure Go is on your path, defined on your terminal, if not you can do so by running "export PATH=$PATH:$(go env GOPATH)/bin"
If this path doesn’t work, you can also try" export PATH=$PATH:/usr/local/go/bin"
Run "MODE="run-single" ./scripts/run.sh"

4. Run" ./scripts/build.sh"

5. If you get a permissions denied error, try running these scripts with the bash command (i.e.bash ./scripts/run.sh)
Load the demo private key included on the project "./build/token-cli key import demo.pk" and "./build/token-cli chain import-anr"
Interact with your own HyperChain!

6. Use the demos included in the README file or located at the repo in step
     * create the asset "./build/token-cli action create-order".
     * mint the asset "./build/token-cli action mint-asset".

8. To close your Local Avalanche Network "run killall avalanche-network-runner" .

Author 
Sweta singh 


