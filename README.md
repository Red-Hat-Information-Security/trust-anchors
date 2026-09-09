# trust-anchors

Repository for managing PKI references and trust anchors.

## Directory Structure

Each top-level folder in this repository represents a different group or team.
The internal directory structure within those group folders is based on the
needs of the respective team.

### Person-Specific Directories

Folders may exist under `/people/<uid>` for individuals to add their own
public keys. The existence of a person-specific folder is not indicative of
their status as an active Red Hatter. Please refer to IAM provided services
to determine if they are active.

If you are contributing a key, please note its location. In the event that a
private key is compromised, please submit a pull request to remove or rotate
it.

Expired keys may remain in the repo for historical purposes. It is the client's
responsibility to confirm that a key is not expired.

## Contributing

- All commits MUST be signed by an author with a `@redhat.com` email address.
- All updates MUST be submitted via pull requests.
- All pull requests must be approved by the appropriate CODEOWNERS

### Scope

Currently this repo is not accepting contributions from Red Hatters in general.
We will work with specific teams based on their needs and use cases.
