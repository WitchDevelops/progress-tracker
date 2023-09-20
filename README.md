# About
It's a personal project to track progress in many courses I'm taking. Build for fun. The idea was born out of necessity (and way too many opened browser tabs).

# What it does
At the moment it does nothing.
But it will let you input the progress (in %) and save it, to have an overview of all the courses. No idea how to achieve it.
It's like Goodreads (books) or GG (games), but for learning (courses, tutorials, textbooks).

# Live
https://witchdevelops.github.io/progress-tracker/

# What needs to be done
Basically everything, lol.
## urgent
Add the core functionality (how? `<form>` and `<input type="progress"`? Then what, connect it to a database of sorts to save it? Or store it in browser cache? No idea, I'll figure it out somehow.)
## later
Refactor the code to allow adding new courses from the UI. For this I guess I'll need a database... and probably user account so that the others won't mess with your stuff

# Sofware requirements
Software requirements document can be found [here](https://www.craft.me/s/JRZluxKSODazXO)
1. Web app
2. Login
3. Manually adding a resource: input fields for the title, type (course/tutorial/book/article/other), link (optional)
4. Manually updating progress in %
5. Manually adding learning topics: this is defined as, e.g. "Learn Vue" or "Learn PHP". Defined manually in a form of input type="text". Then to each topic one can add unlimited number of resources.
6. Some sorting based on resource status: not started/in progress/finished. Default view will show everything with status "in progress". I imagine this sorting can be done with a button next to the learning topic.
7. Tech stack: to be decided. Preferably something JS-based, maybe Python.

# Where to start
* [google search for "build goodreads clone"](https://www.google.com/search?q=build+goodreads+clone&oq=build+goodreads+clone&aqs=chrome.0.69i59.11292j0j7&sourceid=chrome&ie=UTF-8)
* [hashnode article, build Goodreads clone with React/Redux](https://saravanakumarjn.hashnode.dev/goodreads-clone-reactjs) - for general idea and architecture
* [dev.to article, build YT clone](https://dev.to/reedbarger/how-to-build-a-youtube-clone-with-react-1m27) - for database and authentication
