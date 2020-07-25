<!--info-header-start-->
# Pick<T, K> <img src="https://img.shields.io/badge/-easy-green" alt="easy"/>
> by Anthony Fu

<a href="https://type-challenges.netlify.app/case/4/play/en" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-blue?logo=typescript" alt="Take the Challenge"/></a> <!--info-header-end-->

Implement the built-in `Pick<T, K>` generic without using it.

Constructs a type by picking the set of properties `T` from `K`

For example

```ts
interface Todo {
  title: string
  description: string
  completed: boolean
}

type TodoPreview = MyPick<Todo, 'title' | 'completed'>

const todo: TodoPreview = {
    title: 'Clean room',
    completed: false,
}
```

<!--info-footer-start-->
<a href="https://type-challenges.netlify.app/case/4/play/en" target="_blank"><img src="https://img.shields.io/badge/-Check%20out%20Answers-F59BAF?logo=awesome-lists&logoColor=white" alt="Check out Answers"/></a> <a href="../../README.md" target="_blank"><img src="https://img.shields.io/badge/-Back-grey" alt="Back"/></a> 
<!--info-footer-end-->