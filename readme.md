# Just a collection of Hooks I often reuse

> If I take a hook from somewhere there will be a credit comment at the top of the file.

## The Hooks:

### [useConstructor](./hooks/useConstructor.ts)
A hook that functions like a class constructor

Note:
- It does not have any of the issues that `useEffect(() => {}, [])` has.
- It does not cause an additional re-render.
- It is a drop-in for both typescript and javascript (*without changing anything*).
