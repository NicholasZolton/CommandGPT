# Setting Up Your Key
Create a system environment variable named `OPENAI_APIKEY` and give it your secret key.

# Installing
Add the python file to your path to run it, or, if you are on Windows, compile it using pyinstaller and then add the executable output to your path.

# Usage
Simply type `helpme [prompt]` to get help doing something on the command line. For exmaple, `helpme list all the python files in my current directory` will return a command which will list all the python files in your current directory.

# Future Features
- [ ] Go through the list of all commands that are valid on the current system, and add their descriptions to a vector database. Then, when prompting the model, provide the most relevant commands based on the prompt.
- [ ] Add a flag to the command to allow the user to specify the number of commands to return.
- [ ] Add a flag to the command that will remove the explanation from the command, and only return the command itself.
