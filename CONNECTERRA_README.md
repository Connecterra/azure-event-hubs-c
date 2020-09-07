# Infos about the eventhub library used.

Eventhub communication is based on: [original project](https://github.com/Azure/azure-event-hubs-c)
it creates a static library linked to our project.

this project was forked and stored in connecterra github to guarantee that we have access to source code and compile the library.

the library azure-event-hubs-c also depends on other libraries, they are needed to compile it.
to get those libraries, in the root directory of azure-event-hubs-c, we have to execute the command:

git submodule update --init --recursive

# Other libraries/projects that work with eventhub

[example using proton](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-c-getstarted-send)
[apache proton library](https://qpid.apache.org/proton/)

# History
- Initial version tagged with: connecterra_eventhub_1.0.0
