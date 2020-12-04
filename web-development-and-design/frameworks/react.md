# React

[Anatomy of a React application: optimistic updates](https://medium.com/guidesmiths-dev/anatomy-of-a-react-application-optimistic-updates-e4a3318665c7) \#article - "Web applications often require interaction with APIs in order to retrieve and update data. Server-side rendering can greatly reduce the time required to fetch data on the initial page load. Once the application is loaded on the browser though, additional API calls will involve further network calls which could potentially be slow and flaky, making your application sluggish. This is especially true when on mobile connections."

[Expo](https://expo.io/) - "With Expo tools, services, and React, you can build, deploy, and quickly iterate on native Android, iOS, and web apps from the same JavaScript codebase."

[Next.js](https://nextjs.org/) - "The React Framework"

[oayres/react-ssr](https://github.com/oayres/react-ssr) - "Seamless server-side rendering of React apps"

[Preact](https://preactjs.com/) - "Fast 3kB alternative to React with the same modern API."

[React Async](https://docs.react-async.com/) - "React Async is a utility belt for declarative promise resolution and data fetching. It makes it easy to handle asynchronous UI states, without assumptions about the shape of your data or the type of request. React Async consists of a React component and several hooks. You can use it with `fetch`, Axios or other data fetching libraries, even GraphQL."

[React Next](https://react-next.com/) \#conference

[Understanding the React useReducer Hook](https://alligator.io/react/usereducer/#:~:text=%20Understanding%20the%20React%20useReducer%20Hook%20%201,Context%20API%20or%20whatever%20means%20you...%20More%20) \#article - "If you are at all [familiar with reducers](https://alligator.io/redux/redux-intro/#whats-a-reducer), you should have a good understanding of what React’s _useReducer_ hook does. Plain and simple, it allows functional components in React access to reducer functions from your state management. If you are not familiar with reducers, read this [Reducers Introduction](https://redux.js.org/basics/reducers) first."

## Global State

[Context](https://reactjs.org/docs/context.html) \#article - "Context provides a way to pass data through the component tree without having to pass props down manually at every level."

[React Context vs Redux - Who wins?](https://www.youtube.com/watch?v=OvM4hIxrqAw) \#video - "Is the React Conext API a good replacement for Redux? And how would you switch? Here's an example project and some reasons on why \(not to\) switch!"

## Hooks

[A Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/) \#article - "When I just started using Hooks, I was confused by all of those questions too. Even when writing the initial docs, I didn’t have a firm grasp on some of the subtleties. I’ve since had a few “aha” moments that I want to share with you. **This deep dive will make the answers to these questions look obvious to you."**

[Deep dive: How do React hooks really work?](https://www.netlify.com/blog/2019/03/11/deep-dive-how-do-react-hooks-really-work/) \#article - "[Hooks](https://reactjs.org/hooks) are a fundamentally simpler way to encapsulate stateful behavior and side effects in user interfaces. They were [first introduced in React](https://www.youtube.com/watch?v=dpw9EHDh2bM) and have been broadly embraced by other frameworks like [Vue](https://css-tricks.com/what-hooks-mean-for-vue/), [Svelte](https://twitter.com/Rich_Harris/status/1093260097558581250), and even adapted for [general functional JS](https://github.com/getify/TNG-Hooks). However, their functional design requires a good understanding of closures in JavaScript."

[Getting Closure on Hooks \(JSConf Edition\)](https://www.swyx.io/speaking/react-hooks/) \#video - "The design of React Hooks requires a good understanding of closures in JavaScript. In this talk, we’ll reintroduce closures by building a tiny clone of React! This will serve two purposes – to demonstrate the effective use of closures, and to show how you can build a Hooks clone in just 29 lines of readable JS. Finally, we arrive at how you get Custom Hooks and the Rules of Hooks out of this incredible mental model!"

[How to fetch data with React Hooks?](https://www.robinwieruch.de/react-hooks-fetch-data) \#article - "In this tutorial, I want to show you **how to fetch data in React with Hooks** by using the [state](https://reactjs.org/docs/hooks-state.html) and [effect](https://reactjs.org/docs/hooks-effect.html) hooks. We will use the widely known [Hacker News API](https://hn.algolia.com/api) to fetch popular articles from the tech world. You will also implement your custom hook for the data fetching that can be reused anywhere in your application or published on npm as standalone node package."

[Introducing Hooks](https://reactjs.org/docs/hooks-intro.html) \#article - "_Hooks_ are a new addition in React 16.8. They let you use state and other React features without writing a class."

[react-hooks-testing-library](https://react-hooks-testing-library.com/) - "Simple and complete React hooks testing utilities that encourage good testing practices."

[Run useEffect Only Once](https://css-tricks.com/run-useeffect-only-once/) \#article - "The trick is that `useEffect` takes a second parameter."

## React Query

[All About React Query \(with Tanner Linsley\) — Learn With Jason](https://www.youtube.com/watch?v=DocXo3gqGdI) \#video - "There‘s a lot of buzz about React Query and how much it can simplify your development workflow. In this episode, we’ll learn all about it from the [\#TanStack](https://www.youtube.com/results?search_query=%23TanStack) creator himself!"

[React Query](https://react-query.tanstack.com/) - "Performant and powerful data synchronization for React. Fetch, cache and update data in your React and React Native applications all without touching any "global state"."

[React Query - Essentials](https://learn.tanstack.com/) \#course - $150. "The official and exclusive guide to mastering server-state in your applications, straight from the original creator and maintainer of the library."

[React Query: Guides & Concepts: Optimistic Updates](https://react-query.tanstack.com/docs/guides/optimistic-updates) \#article - "When you optimistically update your state before performing a mutation, there is a non-zero chance that the mutation will fail. In most cases, you can just trigger a refetch for your optimistic queries to revert them to their true server state. In some circumstances though, refetching may not work correctly and the mutation error could represent some type of server issue that won't make it possible to refetch. In this event, you can instead choose to rollback your update."

## SWR

[Mutate the data without key at first \#403](https://github.com/vercel/swr/issues/403) - "Hey, I have hard time figuring out how to deal with usage of SWR and revalidation when key for request is not there from the beginning."

[SWR](https://swr.vercel.app/) - "React Hooks library for data fetching"

## Testing Library

[Cheatsheet](https://testing-library.com/docs/react-testing-library/cheatsheet) \#article - "A short guide to all the exported functions in `React Testing Library`"

[Common mistakes with React Testing Library](https://kentcdodds.com/blog/common-mistakes-with-react-testing-library) \#article - "Some mistakes I frequently see people making with React Testing Library."

[eslint-plugin-jest-dom](https://github.com/testing-library/eslint-plugin-jest-dom) - "ESLint plugin to follow best practices and anticipate common mistakes when writing tests with jest-dom."

[eslint-plugin-testing-library](https://github.com/testing-library/eslint-plugin-testing-library) - "ESLint plugin to follow best practices and anticipate common mistakes when writing tests with Testing Library"

[How To Do the Basics in React Testing Library](https://medium.com/better-programming/how-to-do-the-basics-in-react-testing-library-c52cdb3a7726) \#article - "A few months ago I was hired to be the tester of a [React](https://reactjs.org/) website. The problem? I had little experience with React, and to follow the test documentation from React, from [Enzyme](https://airbnb.io/enzyme/) and React Testing Library was quite complicated. So after I understood all of this, I decided to make this tutorial."

[React Testing Library](https://testing-library.com/docs/react-testing-library/intro) - "[`React Testing Library`](https://github.com/testing-library/react-testing-library) builds on top of `DOM Testing Library` by adding APIs for working with React components."

[Which query should I use?](https://testing-library.com/docs/guide-which-query) \#article - "Based on [the Guiding Principles](https://testing-library.com/docs/guiding-principles), your test should resemble how users interact with your code \(component, page, etc.\) as much as possible."

