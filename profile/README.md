# Bongo

Bongo is a mail and calendar server. It runs as one Go binary and serves IMAP, SMTP,
POP3, CalDAV, CardDAV and a web interface. Storage is embedded, so no separate
database is needed. Several nodes can form a cluster using Raft.

Bongo is a reimplementation in Go of the original Bongo project, a mail and calendar
server from the Hula and Novell days.

## Status

Bongo is pre-1.0. A single-node deployment runs in production. Multi-node clustering
is implemented but less tested. Only the latest release receives fixes.

## Repositories

- [bongo](https://github.com/bongo-project/bongo): the server and the `bongo-import`
  mail import tool
- [bongo-project](https://github.com/bongo-project/bongo-project): the website at
  [bongo-project.org](https://bongo-project.org)

The other repositories are archived. They hold the original C and Python code base
and its related projects.

## Documentation

- [Install](https://bongo-project.org/docs/install/)
- [Development quick start](https://bongo-project.org/docs/dev-quickstart/)
- [Walkthrough](https://bongo-project.org/docs/walkthrough/)
- [All documentation](https://bongo-project.org/docs/)

## Licence

The Bongo server is licensed under the GNU Affero General Public License v3.0.
The archived original code base (bongo-orig) is licensed under the GNU General
Public License v2.0.
Security reports follow the policy in
[SECURITY.md](https://github.com/bongo-project/bongo/blob/main/SECURITY.md).
