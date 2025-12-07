# react-resource
I created this repo to keep all important React resources and questions in one place for easy learning and revision.

## React Interview Questions

### BASIC REACT QUESTIONS

📌 Section 1 — React Fundamentals (1–20)

1. What is React and why is it used?
2. What is a library vs a framework in context of React?
3. What is the Virtual DOM?
4. How is React different from vanilla JavaScript?
5. What is a React component?
6. What are the types of components in React?
7. What is JSX?
8. Why do we use JSX in React?
9. Is JSX mandatory in React?
10. How does React convert JSX into JavaScript?
11. What is the role of React.createElement()?
12. What is rendering in React?
13. What is a root element in React?
14. What is the significance of the index.js file in React?
15. What is the difference between React and ReactDOM?
16. What does "React is declarative" mean?
17. What is a single-page application (SPA)?
18. How does React achieve fast updates?
19. What are "elements" in React?
20. What are "components" in React?

📌 Section 2 — Components & Props (21–40)

21. What are props in React?
22. How do you pass props from parent to child?
23. Are props read-only or can they be changed?
24. What happens if you modify props directly?
25. What is defaultProps?
26. How do you validate props using PropTypes?
27. What is the difference between props and state?
28. What is component composition?
29. What are pure components?
30. What is the purpose of keys in lists?
31. Why must list items have unique keys?
32. Can we use index as a key?
33. What is children prop in React?
34. How do you send JSX as props?
35. What is conditional rendering?
36. What is a controlled component?
37. What is an uncontrolled component?
38. What is the significance of React.Fragment?
39. When would you use fragments instead of divs?
40. How do you re-render a component?

📌 Section 3 — State & Lifecycle Basics (41–60)

41. What is state in React?
42. How do you initialize state in a component?
43. What does "state is immutable" mean?
44. Why should you not update state directly?
45. How does updating state trigger a re-render?
46. What is the difference between state and variables?
47. How do you update state based on previous state?
48. What is the purpose of setState()?
49. Why is state update asynchronous?
50. What is a functional component?
51. What is a class component?
52. Why are class components less used today?
53. What is the lifecycle of a React component?
54. Which lifecycle methods run on component mount?
55. What method is used to fetch data in a class component?
56. What is unmounting in React?
57. What is componentDidUpdate?
58. What is componentWillUnmount used for?
59. What are side effects?
60. Why was hooks introduced?

📌 Section 4 — Hooks Basics (61–80)

61. What are React hooks?
62. Why can't we use hooks inside class components?
63. What is the useState hook?
64. How do you update a state array using useState?
65. How do you update a state object using useState?
66. What is useEffect?
67. When does useEffect run by default?
68. What is the dependency array in useEffect?
69. What happens if we leave the dependency array empty?
70. What happens if we omit the dependency array completely?
71. How do you stop an infinite loop in useEffect?
72. What is cleanup function in useEffect?
73. Why do we use cleanup in effects?
74. What is useRef used for?
75. How do you access DOM elements using useRef?
76. What is the difference between useRef and useState?
77. Does changing useRef cause re-render?
78. What is useContext used for?
79. What is the Context API?
80. How do you create and use a context in React?

## Medium Level React Interview Questions

📌 Section 1 — Deep Dive into Hooks (1–25)

1. What are the rules of hooks?
2. Why must hooks be called at the top level of a component?
3. What is the difference between useEffect and useLayoutEffect?
4. When would you use useLayoutEffect over useEffect?
5. What is useReducer and when should you use it?
6. How does useReducer differ from useState?
7. What are lazy initializers in useState and useReducer?
8. What is useMemo used for?
9. How does useMemo help avoid unnecessary re-renders?
10. What is useCallback used for?
11. Difference between useCallback and useMemo?
12. What is useImperativeHandle?
13. What is the purpose of forwardRef?
14. How do custom hooks work?
15. When should you build a custom hook?
16. What are potential pitfalls of useEffect dependencies?
17. What causes stale closures in hooks?
18. Why does React warn about missing dependencies in useEffect?
19. How do you debounce or throttle in React using hooks?
20. How to store previous state using hooks?
21. What is batching in React state updates?
22. Does React batch state updates inside promises?
23. When does useEffect cleanup run?
24. What is the difference between a mount effect and an update effect?
25. Can you make useEffect async? Why or why not?

📌 Section 2 — Working with Context & State Management (26–40)

26. What problem does the Context API solve?
27. What is prop drilling and how does context prevent it?
28. What is the downside of using context?
29. Why can context cause unnecessary re-renders?
30. How do you optimize context value updates?
31. Difference between context and Redux?
32. What is Redux Toolkit?
33. What is a reducer in Redux?
34. What are actions and action creators?
35. What is middleware in Redux?
36. What is thunk middleware used for?
37. Difference between Redux Thunk and Redux Saga?
38. What is a selector in Redux?
39. Why is immutability important in Redux?
40. How do you integrate Redux with React?

📌 Section 3 — React Rendering & Performance (41–55)

41. What is reconciliation in React?
42. How does the diffing algorithm work?
43. Why does React use keys during reconciliation?
44. What triggers a re-render in React?
45. How do you prevent unnecessary re-renders in React?
46. What is React.memo and when should you use it?
47. What is memoization in React?
48. What is the difference between controlled and uncontrolled re-renders?
49. What is useTransition in React?
50. What are concurrent features in React?
51. What is a slow render and how do you detect it?
52. What is React.StrictMode?
53. Why does React run effects twice in development mode?
54. What is windowing or virtualization in React?
55. How does React handle asynchronous rendering?

📌 Section 4 — Forms, Events & Controlled Inputs (56–65)

56. What is a controlled input in React?
57. Why should input values be stored in state?
58. What is two-way binding in React?
59. How do you handle complex form state?
60. What is Formik and why is it used?
61. What is React Hook Form and why is it preferred?
62. How do you validate forms in React?
63. What is synthetic event in React?
64. How does event delegation work in React?
65. Why doesn't React use the browser's native event system?

📌 Section 5 — APIs, Routing & Practical Scenarios (66–80)

66. How do you fetch data in React using useEffect?
67. Why can fetching inside useEffect cause memory leaks?
68. What is Axios and how is it used with React?
69. What is SWR or React Query?
70. How does caching work in React Query?
71. What is optimistic update?
72. How do you handle global loading states?
73. How do you cancel API requests in React?
74. What is React Router?
75. Difference between <Link> and <a>?
76. What is nested routing?
77. What is protected routing?
78. How do you redirect in React Router v6?
79. What is lazy loading in React?
80. How do you implement code-splitting in React?


## Advanced React Interview Questions

📌 Section 1 — React Internals & Fiber Architecture (1–20)

1. What is the React Fiber architecture and why was it introduced?
2. How does Fiber improve React's rendering performance?
3. What is the difference between synchronous and asynchronous rendering in React?
4. What are "units of work" in the Fiber architecture?
5. What is the reconciliation phase vs the commit phase?
6. Explain how React breaks rendering into small chunks.
7. What is the priority scheduling feature in React Fiber?
8. What is cooperative scheduling in React?
9. How does React handle interruptions during long renders?
10. What is the purpose of lanes in modern React?
11. How does React determine which update to process first?
12. What is double buffering in React reconciliation?
13. What is the difference between the render tree and the effect list?
14. What is the significance of the effect tag in React Fiber?
15. How does React keep track of DOM mutations before committing?
16. What is the difference between legacy mode and concurrent mode?
17. Why does concurrent mode make React "interruptible"?
18. How does React batch updates by default in concurrent mode?
19. What does "time slicing" mean in React?
20. What are Suspense boundaries and how do they work internally?

📌 Section 2 — Advanced Hooks, States, & Patterns (21–40)

21. Why is useEffect not guaranteed to run immediately after DOM updates?
22. How does React prevent race conditions with effects?
23. What is a tear-off update?
24. Why can stale closures occur even with dependency arrays?
25. What is the difference between useMemo caching and component memoization?
26. What are the limitations of useCallback?
27. Why should heavy logic not be placed directly inside components?
28. How to create a global event bus using hooks?
29. How do you implement a custom pub/sub pattern in React?
30. What is the difference between lifting state and global state?
31. What is a controlled re-render strategy?
32. What is a selector pattern and how do you implement one?
33. How does React detect state changes with objects?
34. How do you optimize React for large nested states?
35. How does useSyncExternalStore work internally?
36. Why was useSyncExternalStore added to React 18?
37. What is an atom-based state management pattern?
38. How do libraries like Recoil and Jotai differ from Redux?
39. What is the difference between optimistic UI and pessimistic UI?
40. How do you detect and fix a memory leak caused by hooks?

📌 Section 3 — Advanced Performance & Optimization (41–55)

41. How do you identify a React performance bottleneck?
42. What is why-did-you-render and how does it help profiling?
43. How do you optimize re-renders in deeply nested components?
44. What is render-as-you-fetch strategy?
45. What is the difference between fetch-on-render and fetch-then-render?
46. How does React handle large lists efficiently?
47. What is react-window and how does it work internally?
48. How do you implement infinite scrolling in React?
49. How does debouncing vs throttling impact performance?
50. What is priority-based rendering?
51. How do you measure FPS or performance drops in React apps?
52. How do you optimize React for low-end devices?
53. What is the difference between hydration and rendering?
54. How to optimize React hydration on slower networks?
55. Analyze why unnecessary props cause re-renders in React.

📌 Section 4 — Architecture, Patterns & Large-Scale Apps (56–70)

56. What is container-presentational pattern?
57. What is a render prop and when should you use it?
58. Why are Higher-Order Components still relevant?
59. What is the difference between HOCs and custom hooks?
60. How do you structure a large-scale React application?
61. What folder structure works best for scalable React projects?
62. What are micro-frontends and how do they integrate with React?
63. What is Module Federation in Webpack?
64. How do you share components across micro-frontends?
65. What is an event-driven architecture in React apps?
66. What is an error boundary and how does it work internally?
67. Why can't error boundaries catch errors inside event handlers?
68. How do you implement feature flags in React?
69. What is code-splitting vs component-level splitting?
70. What is dead code elimination and how does React benefit from it?

📌 Section 5 — Routing, SSR, Next.js & Advanced Ecosystem (71–80)

71. How does React Router differ from Next.js routing?
72. What is SSR (Server-Side Rendering) in React?
73. What is SSG (Static Site Generation) and when should you use it?
74. What is ISR (Incremental Static Regeneration) in Next.js?
75. What is the difference between SSR hydration and client rendering?
76. Explain how Next.js handles API caching.
77. How does Next.js streaming and server components work?
78. What are React Server Components (RSC)?
79. What is the difference between client components and server components?
80. How does Next.js improve React performance internally?

