# Just a collection of Hooks I often reuse

> Credit where credit is due. A single line comment will be  at the top of each file with the associated license and author.

Feel free to copy and paste from here.

## The Hooks:

### [useConstructor](./hooks/useConstructor.ts)
A hook that functions like a class constructor

Note:
- It is **SYNCHRONOUS** despite having a callback (*if it wasn't it wouldn't be a constructor*)
- It does not have any of the issues that `useEffect(() => {}, [])` has.
- It does not cause an additional re-render.
- It is a drop-in for both typescript and javascript (*without changing anything*).
