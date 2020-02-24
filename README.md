# WebSockets Library for V

The websockets library itself is ready and working (passes all tests of AutoBahn). What's left:

1. It needs to be updated and made to run with latest V.
2. No Windows Support (SSL issues)
3. No proper AutoBahn test client (a prototype is in the main.v but nothing clean and neat).

## What's needed for Windows support:

1. SSL (either make the VSChannel work or OpenSSL)

General code cleanup etc. is also needed (but the codebase is generally clean).

## Contributors

Anyone and everyone is welcome to contribute. I don't have time for working on this completely but I will review and merge Pull Requests ASAP. So if anyone is interested, know that I am interested too.

If anyone has any questions regarding design etc. please open an Issue or contact me on Discord.

## Future Planning:

This is supposed to be merged into V stdlib but it's not ready for that yet. As soon as it is, I will open a PR and merge it.