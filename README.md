# NimChat
Chat App using Nim

To compile run:

```
nim c src/client
nim c src/server
```
If you encounter the error like Error: Threadpool requires --threads:on option, you can run client with this command. ``` nim c --threads:on src/client ```

You can then run the ``server`` in one terminal by executing ``./src/server``.

After doing so you can execute multiple clients in different terminals and have
them communicate via the server.

To execute a client, make sure to specify the server address and user name
on the command line:

```bash
./src/client localhost Sedat
```

You should then be able to start typing in messages and sending them
by pressing the Enter key.
