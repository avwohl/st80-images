# st80-images

Public asset mirror for [avwohl/st80-2026](https://github.com/avwohl/st80-2026).
Hosts the Xerox 1983 Smalltalk-80 v2 virtual image and companion
files so the st80-2026 app can fetch them at runtime without
requiring GitHub authentication.

## Provenance

The files under the `xerox-v2` release are unmodified copies of
Mario Wolczko's long-standing distribution:

    http://www.wolczko.com/st80/image.tar.gz

Originally published by Xerox PARC in 1983 as the Smalltalk-80
"distribution image," updated by Wolczko with the corrections
documented in his porting guide.

## Files in the `xerox-v2` release

    VirtualImage            596128 bytes   the VM snapshot
    Smalltalk-80.sources   1411072 bytes   source code strings
    trace2                   20644 bytes   Xerox reference bytecode trace
    trace3                   23679 bytes   Xerox reference send/return trace

## Licensing

The Smalltalk-80 image is Xerox PARC's 1983 research distribution.
It has been publicly available via Wolczko's site since the early
1990s with no restrictions enforced on academic / hobbyist use.
This mirror exists solely to provide a predictable HTTPS-backed
download URL for the st80-2026 client.

If you are a copyright holder and would like this mirror removed,
open an issue on [st80-2026](https://github.com/avwohl/st80-2026)
and it will be taken down.
