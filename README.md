# spwn aftempt
Library witten in spwn that is made to store data between attempts or do something in later attmept.
## Usage
You need to put folder aftempt in the same folder of your project and then import it
```spwn
aft = import aftempt
```

After that you need to run the function in that you need to run the function `aft.init([functions])`

Parameter     | Description
:------------:|:------------------------------------------------------------------------------------------------------:
functions     | Array of functions that will be executed once player dies
invisigroup   | Group for invisible objects. In case you have your own
initially_off | Wheather the death triggers should be always active or they need to be triggered in your program

It returns the list of death triggers groups


You can also build the example script to see it in action
