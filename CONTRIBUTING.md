# Contributing to Golint

## Before filing an issue:

### Are you having trouble building golint?

To run this fork, run `go get -u github.com/morgasaurus/lint` and then from the `./golint` folder run `go build` or `go install`

The text below is included from the original Go repository CONTRIBUDING.md file:

Check you have the latest version of its dependencies. Run
```
go get -u golang.org/x/lint/golint
```
If you still have problems, consider searching for existing issues before filing a new issue.

## Before sending a pull request:

Have you understood the purpose of golint? Make sure to carefully read `README`.

## Morgasaurus fork

I forked this repository so I could customize the enforced rules; if you'd like to use that version instead then run `go get -u github.com/morgasaurus/lint`
