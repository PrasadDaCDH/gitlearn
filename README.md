# gitlearn

Everything that we learn about the git will be here including commands and the theory part we can seprate the theory and command diffrently


Problems:

1> Sharing the code :
    sharing the code that is dev are working on is complicated from bigger and smaller project
2> Versioning:
    before version control systems there was no versioning available

Solution:
  The solution to both above problems is a version control system like GIT

Q)what is difrence between centralize system and distributed system like (CSV and Git)

The difference between a centralized system and a distributed system can be illustrated by comparing centralized version control systems (like SVN) and distributed version control systems (like Git). Here’s how they differ:

### Centralized System (e.g., SVN)
- **Single Central Repository**: In a centralized system, there is a single central server that holds the complete version history of the project. Developers interact with this central repository directly.
- **Server Dependency**: All operations (like commit, update, and merge) require communication with the central server. If the server is down, most operations cannot be performed.
- **Checkout vs. Commit**: Developers check out the latest version of the project, work on it locally, and then commit changes back to the central repository. This means that the central repository always has the most up-to-date version of the project.
- **Collaboration**: Collaboration in a centralized system requires constant access to the central server, and all changes are tracked centrally.

### Distributed System (e.g., Git)
- **Multiple Repositories**: In a distributed system, every developer has their own complete copy of the entire project history. This means that each clone of the repository is a fully functional repository.
- **Local Operations**: Many operations (like commit, branch, and merge) can be performed locally without needing to communicate with a central server. This makes the system more resilient and allows for offline work.
- **Push and Pull**: Developers commit changes to their local repository and can later push these changes to a remote repository (often used for collaboration). Other developers can pull changes from the remote repository into their own local repositories.
- **Branching and Merging**: Git makes branching and merging easier and more flexible, allowing developers to experiment and collaborate without interfering with the main project.

### Key Differences
- **Reliability**: Centralized systems depend on the availability of the central server, while distributed systems are more resilient as they don't rely on a single point of failure.
- **Performance**: Distributed systems like Git allow for faster operations since many actions are done locally.
- **Flexibility**: Git’s branching and merging capabilities provide more flexibility for development workflows compared to centralized systems.

These differences make distributed systems like Git more suited for modern collaborative and flexible development environments, while centralized systems are simpler but more rigid.



Q)Diffrence between git and github give answer in short

Git: A distributed version control system that manages and tracks changes in your code locally. It allows you to commit, branch, merge, and roll back changes without needing an internet connection.

GitHub: A web-based platform that hosts Git repositories online, providing collaboration features like pull requests, issue tracking, and project management tools. It’s essentially a social network for coders where you can share your Git repositories with others.
