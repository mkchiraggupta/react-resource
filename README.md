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

