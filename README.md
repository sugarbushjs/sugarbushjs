# Sugarbush
![logo.png](logo-sm.png)

Official source code for [Sugarbush](https://github.com/sugarbushjs/sugarbush).


**Sugarbush** is a performance enhancer for your react-redux application by replacing the redux
<u>combinedReducers</u> with `switchback`. Switchback will only run the corresponding reducer that matches
the dispatched action type. Sugarbush also has accompanied components such as
`confingureAdaptiveStrore`, `adaptiveDispatch`, `adaptiveSagaDispatch` and `spPut` (saga effect)
