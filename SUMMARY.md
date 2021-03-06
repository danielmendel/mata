# Table of Contents

* [Introduction](/README.md)
  * [Example](/README.md#quick-example)
  * [Motivation](/README.md#motivation)
* [Guide](/docs/Guide.md)
  * [Definition](/docs/Guide.md#definition)
    * [Global Routes](/docs/Guide.md#global-routes)
    * [Route Priority](/docs/Guide.md#route-priority)
  * [Execution](/docs/Guide.md#execution)
  * [Devtool](/docs/Guide.md#devtool)
* [API Reference](/docs/api/README.md)
  * [Schematic](/docs/api/Schematic.md)
    * [TypeScript](/docs/api/Schematic.md#typescript)
    * [createAutomaton(initialState)](/docs/api/Schematic.md#createAutomaton)
    * [states](/docs/api/Schematic.md#states)
    * [rules](/docs/api/Schematic.md#rules)
  * [Automaton](/docs/api/Automaton.md)
    * [next(input)](/docs/api/Automaton.md#next)
    * [force(state)](/docs/api/Automaton.md#force)
    * [subscribe(listener)](/docs/api/Automaton.md#subscribe)
    * [state](/docs/api/Automaton.md#state)
    * [states](/docs/api/Automaton.md#states)
    * [schematic](/docs/api/Automaton.md#schematic)
  * [Route](/docs/api/Route.md)
    * [FromAnyState](/docs/api/Route.md#FromAnyState)
    * [Continue](/docs/api/Route.md#Continue)
    * [Never](/docs/api/Route.md#Never)
  * [Types](/docs/api/Types.md)
    * [State](/docs/api/Types.md#State)
    * [ValidStates](/docs/api/Types.md#ValidStates)
    * [Condition<T>](/docs/api/Types.md#Condition)
    * [RuleSet<T>](/docs/api/Types.md#RuleSet)
    * [Listener<T>](/docs/api/Types.md#Listener)
    * [Unsubscribe](/docs/api/Types.md#Unsubscribe)
    * [TransitionEvent<T>](/docs/api/Types.md#TransitionEvent)
  * [Devtool](/docs/api/Devtool.md)