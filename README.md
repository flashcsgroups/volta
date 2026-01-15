<p align="center">
  <a href="https://www.volta.sh/">
    <img alt="Volta" src="./volta.png?raw=true" width="360">
  </a>
</p>

<p align="center">
  The Hassle-Free JavaScript Tool Manager
</p>

<p align="center">
  <img alt="Production Build Status" src="https://github.com/volta-cli/volta/workflows/Production/badge.svg" />
  <a href="https://github.com/volta-cli/volta/actions?query=workflow%3ATest">
    <img alt="Test Status" src="https://github.com/volta-cli/volta/workflows/Test/badge.svg" />
  </a>
</p>

---

> [!IMPORTANT]
> **Volta is unmaintained.** Everything that works today should continue to do so for the foreseeable future, so if it is working for you, there is no particular *urgency* to migrate to another tool, but we will not be able to address breakages from new OS releases or other changes in the ecosystem, so you should put it on your maintenance roadmap at some point. We recommend migrating to [`mise`](https://mise.jdx.dev/). See [issue #2080](https://github.com/volta-cli/volta/issues/2080).

---


**Fast:** Install and run any JS tool quickly and seamlessly! Volta is built in Rust and ships as a snappy static binary.

**Reliable:** Ensure everyone in your project has the same tools—without interfering with their workflow.

**Universal:** No matter the package manager, Node runtime, or OS, one command is all you need: `volta install`.

## Features

- Speed 🚀
- Seamless, per-project version switching
- Cross-platform support, including Windows and all Unix shells
- Support for multiple package managers
- Stable tool installation—no reinstalling on every Node upgrade!
- Extensibility hooks for site-specific customization

## Installing Volta

$ uname -a
Linux raspberrypi 4.19.97-v7+ #1294 SMP Thu Jan 30 13:15:58 GMT 2020 armv7l GNU/Linux

$ ./dev/unix/volta-install.sh --release

$ volta install node
success: installed and set node@12.16.2 (with npm@6.14.4) as default

$ node --version
v12.16.2

$ node  -e "console.log(process.platform, process.arch)"
linux arm

$ volta install yarn
success: installed and set yarn@1.22.4 as default

$ yarn --version
1.22.4

$ volta install cowsay
success: installed cowsay@1.4.0 with executables: cowthink, cowsay

$ cowsay ⚡️⚡️⚡️
 ________
< ⚡️⚡️⚡️ >
 --------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

Read the [Getting Started Guide](https://docs.volta.sh/guide/getting-started) on our website for detailed instructions on how to install Volta.

## Using Volta

Read the [Understanding Volta Guide](https://docs.volta.sh/guide/understanding) on our website for detailed instructions on how to use Volta.

## Contributing to Volta

Contributions are always welcome, no matter how large or small. Substantial feature ideas should be proposed as an [RFC](https://github.com/volta-cli/rfcs). Before contributing, please read the [code of conduct](CODE_OF_CONDUCT.md).

See the [Contributing Guide](https://docs.volta.sh/contributing/) on our website for detailed instructions on how to contribute to Volta.

## Who is using Volta?

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/microsoft/TypeScript" target="_blank">
          <img src="https://raw.githubusercontent.com/microsoft/TypeScript-Website/v2/packages/typescriptlang-org/static/branding/ts-logo-512.svg" alt="TypeScript" width="100" height="100">
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/getsentry/sentry-javascript" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/1396951?s=100" alt="Sentry" width="100" height="100">
        </a>
      </td>
    </tr>
  </tbody>
</table>

See [here](https://sourcegraph.com/search?q=context:global+%22volta%22+file:package.json&patternType=literal
https://github.com/volta-cli/volta https://github.com/volta-cli/volta/pull/710) for more Volta users.
