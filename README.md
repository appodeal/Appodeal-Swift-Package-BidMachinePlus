# Appodeal-Swift-Package-BidMachinePlus

Swift Package for the Appodeal BidMachine Plus adapter. `Package.swift` is published
and versioned automatically by the AppodealSDK-iOS release pipeline
(`adapter_spm` lane): release PRs land on `release/<version>` branches, get
auto-approved, auto-merged and tagged.

Publishers get this package as a dependency of
[Appodeal-Swift-Package-BidMachine](https://github.com/appodeal/Appodeal-Swift-Package-BidMachine)
and don't need to add it themselves.

Tags use the encoded adapter version (e.g. adapter 0.2.0.0 tags as
`0020000.0.0`, which SwiftPM reads as version 20000.0.0).
