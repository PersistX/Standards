# PersistX Standards
Code standards for PersistX

## Usage
You can run standards against the files in the current project easily:

```
$ ./Carthage/Checkouts/Standards/run
```

That will check _all_ files in the current repository.

If you want, you can pass specific files to check:

```
$ ./Carthage/Checkouts/Standards/run file1 file2
```

## Pre-Commit Hook
Standards also includes a pre-commit hook that can be used with `git`. After installing it, `git commit` will automatically format and will prevent the commit if there are any linting failures.

You can easily install the pre-commit for a repository by running the included `install-hooks` script. Note: This will change the hooks directory for the current repo.

## CI
You can run the `test` script on CI to verify that standards have been run.
