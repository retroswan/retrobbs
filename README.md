# RetroBBS

RetroBBS will/should be a modern forum software which seeks to give communities back the self-ownership that they used to have.

## Features

### Accounts

#### Authentication

Pretty self-explanatory. Username/email address + password.

Optional Mastodon SSO would be cool though!

#### Permissions

Probably do group-based permissions. This doesn't need to be very robuts for Version One Point Oh.

### Posts

A message from a user, posted inside a specific forum. Posts are viewable by anyone who can view a given forum.

Post formatting could be handled by BBCode, Markdown, or maybe both + more?

### Threads

Probably also self-explanatory. A thread consists of a first post by the thread starter, followed by a series of linear replies.

## Technical

### Stack

- Node.js
- TypeScript
- MySQL

### Design

I would say make it mostly API-based, except that I'm not a big fan of JavaScript-heavy frontends. I love the idea of having a zero-JS frontend.
