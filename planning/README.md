# My ToDo List

## General info

> This is a simple application helps us create ToDo list for day

## Technologies

- Node 18.16.0
- VSC code
- JavaScript
- Separating of concerns

## Code Examples

```js
// update data
const itemId = Number(editedItem.id);
const findedTask = data.tasks.find((task) => task.id === itemId);
findedTask.text = value;
```
