---
id: zdnf834cgp0a0l7cj1bgdwt
title: Day55log
desc: 'Programming day 55 Log'
updated: 1647610723921
created: 1647598458606
---

**Thunk***
a pattern of writing async logic in redux apps

they interact with redux store dispatch() and getState() methods.

primarly used for fetching data.

lets recap on the Redux Flow

UI --> Actions --> Reducers --> Store

the store has to know which action happened...we will use Thunk to dispatch that action.
the second paramter is getState where we can retrive the state.

![](/assets/images/2022-03-18-15-38-24.png)
