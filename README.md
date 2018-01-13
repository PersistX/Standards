# PersistX Standards
Code standards for PersistX

## Usage
Add a _Run Script_ phase to each of your Xcode targets:

```
"${SRCROOT}/Carthage/Checkouts/Standards/build" "${SRCROOT}/Source"
```

The first first path should point to the location of the `build` script. Pass the paths to all of
the sourcee files in that target.

