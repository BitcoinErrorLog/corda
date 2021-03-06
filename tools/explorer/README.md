# Node Explorer

The node explorer provide views of the node's vault and transaction data using Corda's RPC framework.
The user can execute cash transaction commands to issue and move cash to other parties on the network or exit cash using the user interface.

## Running the UI

**Windows:**

    gradlew.bat tools:explorer:run

**Other:**

    ./gradlew tools:explorer:run
    

## Running Demo Nodes

**Windows:**

    gradlew.bat tools:explorer:runDemoNodes

**Other:**

    ./gradlew tools:explorer:runDemoNodes

**These Corda nodes will be created on the following port on localhost.**

    Notary -> 20002
    Alice -> 20004
    Bob -> 20006
    Bank of Corda -> 20008
  

## TODOs:
- Shows more useful information in the dashboard.
- Improve Network View, display other nodes in the world map and show transactions between them.
- Add a new view showing node's state machines.
- Link transaction input to its originated transaction to make it easier to trace back.
- Shows Node information (Configuration, properties etc.) in Settings view. 
- Support other contract types.


More information can be found in the [Project website](https://corda.net) and [Documentation](https://docs.corda.net).