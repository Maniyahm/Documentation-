### Main screen ###

**home.dart**
Widgets
- SearchBar -> sends input to chat screen
- GridView
- Card

1. SearchBar gives an output from an input and sends the output to a new second screen (Chat_screen.dart).
2. GridView builds grids of different cards.
3. Card takes input from card_data.dart (json file) to build different cards.


### Second Screen ###

**chat_screen.dart**
Widgets:
- SearchBar
- Messages

1. ChatScreen takes text input from the SearchBar of first.dart to display initial output.
2. SearchBar of chat_screen.dart takes input and shows output on the same screen.
3. Message takes the response of the input query from SearchBar as input and sets the design of messages.
4. Messages are displayed in chat_screen.dart using ListView.


### Form Screen ###

**form.dart**
1. TextFields take input from the user or take default input.
2. Default input form data (json file).
3. When the form is submitted, one prompt is generated.
4. The prompt goes to apiService.dart.
5. This response is sent to the Answer Screen for user output.














