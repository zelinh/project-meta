This is a component issue for release 1.3.0.<br/>
Coming from [opensearch-build#889](https://github.com/opensearch-project/opensearch-build/issues/889), release version 1.3. Please follow the following checklist.

### Preparation

- [ ] Assign this issue to a release owner.
- [ ] Finalize scope and feature set and update [the Public Roadmap](https://github.com/orgs/opensearch-project/projects/1).
- [ ] Create, update, triage and label all features and issues targeted for this release with `v1.3.0`.

### CI/CD

- [ ] Increment version on main to `1.3.0.0`.
- [ ] Ensure working and passing CI.
- [ ] Re(add) this repo to the (if not exist) [manifest](https://github.com/opensearch-project/opensearch-build/blob/main/manifests/1.3.0/).

### Pre-Release

- [ ] Branch and build from a `1.3` branch.
- [ ] Update your branch in the [manifest](https://github.com/opensearch-project/opensearch-build/blob/main/manifests/1.3.0).
- [ ] Feature complete, pencils down.
- [ ] Fix bugs that target this release.

### Release

- [ ] Complete [documentation](https://github.com/opensearch-project/documentation-website).
- [ ] Gather, review and publish release notes.
- [ ] Verify all issued labeled for this release are closed or labelled for the next release.

### Post Release

- [ ] Create [a release tag](https://github.com/opensearch-project/.github/blob/main/RELEASING.md#tagging).
- [ ] Suggest improvements to [this template](https://github.com/opensearch-project/opensearch-build/blob/main/.github/ISSUE_TEMPLATE/release_template.md).
- [ ] Conduct a postmortem, and publish its results.
