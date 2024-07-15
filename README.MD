# The De1-LoC Smart Lock

The De1-LoC is a smart lock with a multitude of customizable unlock options, including pinpad entry and FaceID. The lock also support notification of anomalous unlocks. The project was comrpised of 3 main parts: [the backend](backend/BACKEND.md), [the user app built in React Native](UserApp/README.MD), and [the embedded system](embedded_system/README.md). Following these three links provides you with the documentation for running these aspects of the project.

Management of unlock methods is initiated through the user app, with most information being stored in the backend. The hardware was integrated to make API requests to the backend when prompted by a user triggered interrupt. Full documentation of the systems are provided at the link above, including instructions on how to set up the system for yourself.

A [short video](https://youtu.be/hqYXZ-t4QIY?si=MfLnU6hYM16AfSYI) on how the lock and the app work.
