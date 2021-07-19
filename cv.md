## Sergei Gorobtsev
My GitHub <https://github.com/Schoolboyl337>
**Telegram: *@Schoolboy_1337***
Skills:
* HTML
* CSS
* JS
* Vue
* Git

Code:
```
function addTask() {
    if(inputTask.value) {
      let listItem = createNewElement(inputTask.value,false);
      unfinishedTask.appendChild(listItem);
      bindTaskEvents(listItem,finishTask)
      inputTask.value = ''; 
    }
    save();
}
addButton.onclick = addTask;
```
