# solidity-partial-evaluator
An experiment in building a partial function evaluator (e.g. if i have a function f(x,y) that returns z, what are some conditions I can put on z if I call f with x = 2?) for Solidity smart contracts.

This is still a rough work-in-progress. See StaticAnalysis/PartialEvaluator.hs for the current implementation, where more or less the semantics of every Solidity operator has been modelled approximately with Haskell. The next step is programming the partial execution of the code.
