# Labeler Guide

```
documentation:
  - changed-files:
      - any-glob-to-any-file: "docs/*"

source:
  - all:
      - changed-files:
          - any-glob-to-any-file: "**"
          - any-glob-to-all-files:
              - "!docs/*"
              - "!.github/*"

```

# References

> https://github.com/actions/labeler
