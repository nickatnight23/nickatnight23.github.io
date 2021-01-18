---
layout: post
title:      "Redux Thunk"
date:       2021-01-18 19:31:43 +0000
permalink:  redux_thunk
---


This by far was the most challenging project. I think because you have so many moving parts and the goal is to figure out how each moving part works. Even though this was a challenging project I enjoyed the process. 

One of the challenging concepts I had during my journey with react was redux more specifically how everything connects through the middleware Thunk.

Thunk is a middleware like I mentioned above that allows you to call action creators that will return a function instead of an object.  There are some key terms to keep in mind. The key terms are action creators, dispatch, store and reducers. Action creators are the functions that are dispatched to create a change. Dispatch is away to trigger state change. Store is what holds your state. Reducers  are functions that take the current state and action and returns the new state.

Redux action creators do not fetch data so this is where Redux Thunk comes into play. Thunk allows you to write action creators that return a function. Now the inner function can work with store method such as dispatch. That is essentially what Redux Thunk is used for, which is that in between stage. 

There is still a lot for me to learn with React and Redux, but I am glad that I was able to understand how this process works. Hopefully this was helpful. Happy coding!
