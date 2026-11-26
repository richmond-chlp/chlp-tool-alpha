**FOR INTERNAL PURPOSES ONLY**

# How to push the Health per Credit tool's unlisted page

Richmond Chua | November 26, 2026, 10:57 AM Central | Carbon markets chat. Internal.

**What it is.** The tool's build of November 26, 10:52 AM, as `health-per-credit/index.html`. Pushed to the main tool's public repository, it opens at https://richmond-chlp.github.io/chlp-tool-alpha/health-per-credit/. It asks search engines not to index it, and nothing in the repository links to it, so it is unlisted (ruling 433; testing group plan, decision 3).

**On GitHub's website:**

1. Open https://github.com/richmond-chlp/chlp-tool-alpha, signed in as `richmond-chlp` (ruling 231).
2. Choose Add file, then Upload files.
3. Drag the folder `health-per-credit` from this folder onto the page. GitHub keeps the folder name, so the file lands at `health-per-credit/index.html`.
4. Commit message: "Health per Credit tool: unlisted beta page, build of November 26, 2026, 10:52 AM". Commit directly to `main`.

**From a terminal, instead:**

```
git clone https://github.com/richmond-chlp/chlp-tool-alpha
cd chlp-tool-alpha
mkdir -p health-per-credit
cp "PATH TO THIS FOLDER/health-per-credit/index.html" health-per-credit/index.html
git add health-per-credit/index.html
git commit -m "Health per Credit tool: unlisted beta page, build of November 26, 2026, 10:52 AM"
git push
```

**Then check.** After about a minute, open the address above. The footer should read "Build November 26, 2026, 10:52 AM Central". The main tool at https://richmond-chlp.github.io/chlp-tool-alpha/ is unchanged.

**Leave alone.** The README and the main tool's `index.html`. Linking the page from either would list it.

**After the push.** Send the Slack message to Joseph, version 0.5, which carries the address.

**The new address.** Under ruling 507 the tools move to tool.climatehealthledger.org; the main chat's note of 10:19 AM gives the setup. Pushing this folder first is fine: once the domain is set, the page also opens at https://tool.climatehealthledger.org/health-per-credit/. The Slack message to Joseph waits for the main chat's test (ruling 508).
