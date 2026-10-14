# Bozzetto Studio: public alpha

Bozzetto Studio is the desktop version of [Bozzetto](https://bozzetto.vidarrapp.se):
a native sculpting and painting application for Windows, macOS and Linux,
built in Rust for large meshes. This repository holds its downloads and its
issue tracker. There is no source code here; Studio is closed source.

## What the alpha is

- **Free until 1.0.** Every 0.x build is free of charge. From 1.0 Studio is
  sold at a fixed price per major version, with paid major upgrades and free
  point releases. No subscription.
- **As it is.** An alpha is unfinished software. It can crash, lose work,
  and change between builds. Keep copies of what matters to you.
- **Your files carry forward.** A file saved by an alpha build opens in
  1.0. That promise starts with the first build that writes Studio's own
  file format and holds from then on.
- **Local.** Studio makes no network requests unless you point it at a
  Bozzetto server. It sends no usage data and no crash reports; what you
  report is what you choose to paste.

## Downloads

Each release on the [Releases page](https://github.com/vidarrapp/bozzetto-studio-releases/releases)
carries an installer for each platform, a `SHA256SUMS` file, and a build
provenance attestation. There are no alpha builds yet; the first one
follows the engine's first milestone.

Alpha builds are **unsigned**, so macOS and Windows warn before opening
them. On macOS, right-click the app and choose Open the first time. On
Windows, choose More info, then Run anyway. Check a download against
`SHA256SUMS`, or verify its attestation with
`gh attestation verify <file> -R vidarrapp/bozzetto-studio-releases`.
Signed builds come with 1.0.

## Reporting

Open an [issue](https://github.com/vidarrapp/bozzetto-studio-releases/issues)
for a crash, a wrong result or a request, or write to
bozzetto@vidarrapp.se. A useful report names the build (the About panel
and the stats overlay say it), the operating system and GPU, what you did,
and what happened instead. For a security problem, write to the email
address rather than opening an issue.

## Relationship to Bozzetto on the web

Bozzetto on the web stays free and open source under MIT at
[vidarrapp/bozzetto](https://github.com/vidarrapp/bozzetto). Its viewer and
gallery play the timelapses Studio exports.
