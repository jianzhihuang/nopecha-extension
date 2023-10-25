# NopeCHA Chrome Extension & Firefox Add-on

[![Latest Version](https://img.shields.io/github/v/release/NopeCHALLC/nopecha-extension?style=flat-square)](https://github.com/NopeCHALLC/nopecha-extension/releases)
[![License](https://img.shields.io/github/license/NopeCHALLC/nopecha-extension?style=flat-square)](LICENSE)

### Introduction

NopeCHA is a **free-to-use** automated CAPTCHA solver, compatible with multiple CAPTCHA types, and powered by advanced deep learning models via the [NopeCHA API](https://developers.nopecha.com).

### Why NopeCHA?

Staying up-to-date with frequently changing CAPTCHA challenges can be tedious.
That's why we've developed browser extensions for both Chrome and Firefox.
These extensions receive regular updates to support the latest CAPTCHA challenges, ensuring uninterrupted service for your automation scripts.
Once installed, NopeCHA autonomously handles CAPTCHAs, allowing you to focus on more important tasks.

### Getting Started

For developers interested in integrating NopeCHA into their projects, please consult our [API documentation](http://localhost:34129/guides/extension_advanced/).

To test the extension:
- [Chrome Extension](https://www.nopecha.com/chrome)
- [Firefox Add-on](https://www.nopecha.com/firefox)

### Supported CAPTCHA Types

Here's a sample of CAPTCHA types supported by NopeCHA, with ongoing development for more:

<div style="display: flex; flex-flow: row wrap;">
    <div style="margin: auto; padding: 16px; display: flex; flex-flow: column nowrap; min-width: 300px; width: 45%; flex-grow: 1;">
        <div style="text-align: center; padding-bottom: 8px; margin-bottom: 8px; border-bottom: 1px solid #aaa;">All versions of reCAPTCHA</div>
        <img src="assets/recaptcha.gif?raw=true" style="object-fit: contain;" alt="reCAPTCHA" title="reCAPTCHA" />
    </div>
    <div style="margin: auto; padding: 16px; display: flex; flex-flow: column nowrap; min-width: 300px; width: 45%; flex-grow: 1;">
        <div style="text-align: center; padding-bottom: 8px; margin-bottom: 8px; border-bottom: 1px solid #aaa;">Most versions of FunCAPTCHA</div>
        <img src="assets/funcaptcha.gif?raw=true" style="object-fit: contain;" alt="FunCAPTCHA" title="FunCAPTCHA" />
    </div>
    <div style="margin: auto; padding: 16px; display: flex; flex-flow: column nowrap; min-width: 300px; width: 45%; flex-grow: 1;">
        <div style="text-align: center; padding-bottom: 8px; margin-bottom: 8px; border-bottom: 1px solid #aaa;">All versions of hCaptcha</div>
        <img src="assets/hcaptcha.gif?raw=true" style="object-fit: contain;" alt="hCaptcha" title="hCaptcha" />
    </div>
    <div style="margin: auto; padding: 16px; display: flex; flex-flow: column nowrap; min-width: 300px; width: 45%; flex-grow: 1;">
        <div style="text-align: center; padding-bottom: 8px; margin-bottom: 8px; border-bottom: 1px solid #aaa;">AWS WAF CAPTCHA</div>
        <img src="assets/awscaptcha.gif?raw=true" style="object-fit: contain;" alt="AWS WAF CAPTCHA" title="AWS WAF CAPTCHA" />
    </div>
    <div style="margin: auto; padding: 16px; display: flex; flex-flow: column nowrap; min-width: 300px; width: 45%; flex-grow: 1;">
        <div style="text-align: center; padding-bottom: 8px; margin-bottom: 8px; border-bottom: 1px solid #aaa;">300+ Types of Text-based CAPTCHA</div>
        <img src="assets/textcaptcha.gif?raw=true" style="object-fit: contain;" alt="Text-based CAPTCHA" title="Text-based CAPTCHA" />
    </div>
    <div style="margin: auto; padding: 16px; display: flex; flex-flow: column nowrap; min-width: 300px; width: 45%; flex-grow: 1;">
        <div style="text-align: center; padding-bottom: 8px; margin-bottom: 8px; border-bottom: 1px solid #aaa;">Cloudflare Turnstile</div>
        <img src="assets/turnstile.gif?raw=true" style="object-fit: contain;" alt="Cloudflare Turnstile" title="Cloudflare Turnstile" />
    </div>
</div>

<br>

# Important Update: Transition to Closed-Source in 2023

### What's New?

Starting 2023, NopeCHA has transitioned to a closed-source model.
Despite this, we will continue to publish the latest builds under [Releases](../../releases).

### Why the Transition?

Earlier this year, hCaptcha and FunCAPTCHA added a hardcoded check to detect NopeCHA v0.3.x and open-source softwares developed by NopeCHA, LLC.
This attention validates our impact.
To maintain our edge without offering CAPTCHA providers a counter-strategy, we have chosen to restrict source code access.

<br>

<div style="text-align: center;">
    <img src="assets/hcaptcha_butterfly.gif?raw=true" alt="NopeCHA Cartoon" title="NopeCHA Cartoon" style="max-width: 240px" />
    <img src="assets/nopecha_banner_1.webp?raw=true" alt="NopeCHA Cartoon" title="NopeCHA Cartoon" style="max-width: 300px" />
</div>

<br>

### Technical Advancements

Behind the scenes, NopeCHA is undergoing intense training and refinement.
Our neural network architecture continuously adapts to new challenges.
Whether it's decoding obscure characters or solving complex image-to-image tasks, NopeCHA is built for it.

### The Road Ahead

We're committed to refining our algorithms and expanding our library of solved CAPTCHAs.
While our advanced machine learning models give us a definitive edge, the story isn't over.
We will continue to push the boundaries of what's possible in CAPTCHA-solving technology.

Thanks for your support, and remember—in a world full of CAPTCHAs, be a NopeCHA. 😎✌️

<br>

<div style="text-align: center;">
    <img src="assets/nopecha_banner_0.webp?raw=true" alt="NopeCHA Digital Gym" title="NopeCHA Digital Gym" style="max-height: 400px" />
</div>

<br>
<br>
<br>

# The following section is deprecated and kept for archival purposes only

## Usage Examples

> :warning: **[Outdated examples due to Colab updates]**:
While it's possible to use NopeCHA in Colab, we're not actively supporting it.
If you're interested in using NopeCHA in Colab, you will need to change the code to get it working again.

NopeCHA Extension in Selenium

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1h9Q37yQqrLNhkqBCCWtHMPc09iOlLEQ5?usp=sharing)

NopeCHA Extension in Undetected Chromedriver

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IAIwMWxpK7j1zzWJ1RmajD0TjaW_ANz4?usp=sharing)


## Development
### Prerequisites

Having [Python 3.8](https://python.org) or above installed.

### Building

To build debug copy for both Chrome and Firefox, simply run the following command:

`python build.py`

This will create a `dist` directory in the project root directory, in which you will find `firefox` and `chrome` directories for debugging purposes. If you use the `-p` argument, each debugging directory will have an additional xpi/crc archive for production usage.

### Actively listening for changes
For development convenience, `build.py` also supports listening to changes so files are quickly updated.

For that, you need to install python's `watchdog` in your machine:

`python -m pip install watchdog`

Then you can run `build.py` command with the `-w` option so your changes immediately apply:

`python build.py -w`
or
`./build.py -w`


## Building for production
### Prerequisites

`npm install uglify-js -g`

### Build

`python build.py -p`

Note: The watchdog option `-w` is also supported here: (`python build.py -pw`)

Minified code for production can be found in the `.zip` files in the corresponding browser directory. The zip files can be used for final testing/debugging before sending them to the webstores.
