# NGRX
Redux modified with extra features for angular. Uses RxJs, typescript and deeply integrates with angular. Alternative to Services and Subjects and maintaining state for bigger applications to streamline the process.

## Store
Store is the main source of truth. It holds the state of the application. Services and components receive the state from the store.

## Reducer functions
Functions which add new state changes(synchronously) in store depending on the action dispatched. State changes are made immutably i.e. a new copy of the state is made and changes are made to it and a new state is returned and saved to the store.

## Action classes
Classes that define the different actions that can be executed, have a type and optional payload.

## Effects
Similar to angular services, perform the async operations which are not supposed to be done in reducer functions. Effects may or may not return an action upon completion.