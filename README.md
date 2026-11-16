# Homebrew tap for Twayblade

[Twayblade](https://github.com/zerw0/twayblade) is a native Matrix client with
end-to-end encrypted messages, spaces, threads and MatrixRTC calls.

```sh
brew install --cask zerw0/twayblade/twayblade
```

**Status:** 0.1.0-rc.3, a test pre-release.

## First launch

Twayblade is ad hoc signed, not notarised, so macOS refuses to open it the
first time. Choose **Done**, then open **System Settings › Privacy & Security**
and click **Open Anyway** next to Twayblade. This cask does not remove the
quarantine attribute for you.

The cask is generated from the main repository
(`packaging/homebrew/twayblade.rb`, filled by `scripts/homebrew-cask.py` from
the release's `SHA256SUMS`).
