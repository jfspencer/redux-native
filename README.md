# redux-native
Native Powered, Cross Platform, State Management, Redux Inspired 

Tools and Libs powering this project in implementation and or concept (Thank You!)
- https://redux.js.org
- https://redux-saga.js.org
- https://github.com/ReSwift/ReSwift
- https://github.com/ReKotlin/ReKotlin
- https://www.couchbase.com/products/lite
- https://github.com/ReactiveX/RxKotlin
- https://ionicframework.com
- https://facebook.github.io/react-native/

## General Idea
- Lots of UIs are built using Javascript (Web, Mobile and Desktop). Javascript is single threaded. JS apps need to treat the JS thread as the UI thread on native platforms, don't do non-UI rendering tasks on it. period. Web workers help to some extent, but they are hard to deal with at scale. 
- Keep the JS/UI thread clean by running business logic, network traffic and other processing tasks in their own thread (or multiple)
- Use Kotlin/Native as the universal business logic language.
- Use the redux pattern to facilitate clean state management at scale
- Actions are the universal building blocks of business logic development
- selectors are streams 
- reducers use IO Monad to sync with persistence
- use couchbase lite for free pear to pear state sync
