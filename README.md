# PersistX Standards
Code standards for PersistX

## Usage
Add a _Run Script_ phase to each of your Xcode targets:

```
if [ -x "${SRCROOT}/Carthage/Checkouts/Standards" ]
then
  "${SRCROOT}/Carthage/Checkouts/Standards/build" "${SRCROOT}/Tests"
fi
```

The first first path should point to the location of the `build` script. Pass the paths to all of
the sourcee files in that target.

