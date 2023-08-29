
1. Clone the project with the code below.
    ```sh

    # Make sure you have the above prerequisites installed already!
    git clone https://github.com/aopoku255/andtecx.git
    cd andtecx
    yarn install # Installs all the dependencies.
    ```
2. Create an Infuria project, copy and paste your key in the spaces below.

    ```sh
    REACT_APP_INFURIA_PID=<INFURIA_API_KEY_HERE>
    REACT_APP_INFURIA_API=<INFURIA_API_KEY_SECRET_HERE>
    ```
3. Create a CometChat project, copy and paste your key in the spaces below.
4. Install truffle and ganache.
    ```sh
    npm install -g truffle
    npm install ganache --global
    ```
5. Run the app using the following commands.
    ```sh
    yarn install
    ganache -d
    truffle migrate --reset
    yarn start
    ```
6. Add some ganache accounts, connect your wallet and interact with the app.
<br/>

