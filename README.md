# Flet ToDo App • [Tutorial](http://todomvc.com)
> Flet is a framework that allows building interactive multi-user web, desktop and mobile applications in your favorite language without prior experience in frontend development.
>
> You build a UI for your program with Flet controls which are based on Flutter by Google. Flet does not just "wrap" Flutter widgets, but adds its own "opinion" by combining smaller widgets, hiding complexities, implementing UI best-practices, applying reasonable defaults - all to ensure your apps look cool and professional without extra efforts.

## More about

This app is based on the example app tutorial from [Flet documentation](https://flet.dev/docs/tutorials) and received some other features and ideas from this [ToDo app](https://github.com/ReynaldoCC/todoDjangoHtmx)
##### Item

###### A todo item has three possible interactions:

 - mark as complete using the checkbox
 - edit the todo name using the button for edit
 - delete the todo using the button for that action in the To-do element

##### Counter
Displays the number of active todos from the total

##### Clear completed button
Remove completed todos when clicked. It Should be hidden when there are no completed todos.

## Implementation

### For development

##### Get the code

Clone this repository or download it from [GitHub](https://github.com/ReynaldoCC/flet-todo/archive/refs/heads/main.zip)

    git clone https://github.com/ReynaldoCC/flet-todo.git


##### Install requirements

To run this project, need to install [python](https://realpython.com/installing-python/) and after having python 
installed, need to run the following commands to install more dependencies

    pip install --upgrade pip
    pip install poetry
    poetry install

#### Run the app

    poetry run python main.py


## Credit

Created by [Reynaldo Cuenca Campos](http://reynaldocc.github.io)