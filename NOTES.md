# Notes
* Use ```cargo watch -x check -x test -x run``` when developing to speed things up.
* cargo-tarpaulin is a code coverage tool. Run with ```cargo tarpaulin --ignore-tests``` to run while ignoring test coverage.
* Lint with ```cargo clippy``` to lint
* Format code with ```cargo fmt``` (newlines, extra whitespace, etc.)
* Use ```cargo audit``` to scan the dependency tree for anything that has an open CVE

# Current User Stories

### Newsletter
1) As a blog visitor,
   I want to subscribe to the newsletter
   So that I can receive email updates when new content is published on the blog.
2) As a blog author,
   I want to send an email to all of my subscribers
   So that I can notify them when new content is published.

### Implementation Strategy
* Installed actix-web and tokio for web app framework setup