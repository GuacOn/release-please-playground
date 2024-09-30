### What is this?
Playground repo for implementing [Release Please](https://github.com/googleapis/release-please) in my Monitor Review Finder project.

Release Please automates CHANGELOG generation, the creation of GitHub releases, and version bumps for your projects.

### Rationale
When choosing between Release Please and Semantic Release, I decided that maintaining a release PR fit this project better. We can't do real Continuous Delivery with Firefox addons due to the lengthy review process, so Release Please automates away the boring bits, while allowing us to hold deployment at the final stage until it makes sense.

