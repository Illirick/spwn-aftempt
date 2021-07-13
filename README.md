# spwn aftempt
Library witten in spwn that is made to store data between attempts or do something in later attmept.

It uses technic discovered by blanketaddict
## Usage
You need to put folder aftempt in the same folder of your project and then import it
```spwn
aft = import aftempt
```

After that you need to run the function `aft.init([functions])` and it will return groups of death triggers. So, for example if you activate second death trigger in that array then the second function in your array that you passed as argument will be executed every attempt after the current one. You can also pass the group that you use for invisible objects as your second argugent so script won't create extra one

You can also build the example script to see this library in action
