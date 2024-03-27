# Zurf Test Flight
Find out more about Zurf.social, download the app on testflight

![frame2](https://github.com/robertcedwards/Zurf-XMTP-OpenFrame/assets/139775/3184f776-c88f-4bc5-86f0-9668066dcd7b)

Live URL: https://robertcedwards.github.io/Zurf-XMTP-OpenFrame/



This is the simplest form that a frame can have to validate on XMTP, Farcaster, Twitter, & FB.

Most of the magic happens in the meta tags. These are the required for XMTP/Farcaster. The rest below in the example are for FB/Twitter
You need a minimum of 1 button, 3 max for FC, and it looks like 4 for XMTP.
You also need the <meta name="of:accepts:xmtp" content="2024-02-01" /> for XMTP

This can even be served on Github Pages, just like this one!

```
<meta name="description"/>
<meta name="fc:frame" content="vNext" />
<meta name="fc:frame:image"
<meta name="fc:frame:button:1"/>
<meta name="fc:frame:button:1:action" content="link" />
<meta name="fc:frame:button:1:target" content="LINK URL GOES HERE" />
<meta name="of:accepts:xmtp" content="2024-02-01" />
```
_______________________________________________________________________
```
 <head>
    <meta charSet="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="preload" as="image" href="https://0xprimordia.github.io/framevertisment/1.gif?height=672&width=1344" />
    <title>Zurf 🏄‍♂️</title>
    <link rel="icon" href="/favicon.ico" type="image/x-icon" sizes="54x57"/>
    <meta name="description" content="🤍 Building the funniest web3 social app." />
    <meta name="fc:frame" content="vNext" />
    <meta name="fc:frame:image" content="https://0xprimordia.github.io/framevertisment/1.gif?height=672&width=1344" />
    <meta name="fc:frame:button:1" content="🏄‍♂️ Download Zurf" />
    <meta name="fc:frame:button:1:action" content="link" />
    <meta name="fc:frame:button:1:target" content="https://testflight.apple.com/join/9vAjdPl7" />
    <meta name="fc:frame:button:2" content="👨‍💻 Website" />
    <meta name="fc:frame:button:2:action" content="link" />
    <meta name="fc:frame:button:2:target" content="https://zurf.social/" />
    <meta name="fc:frame:button:3" content="🌊 Wav3s" />
    <meta name="fc:frame:button:3:action" content="link" />
    <meta name="fc:frame:button:3:target" content="https://www.wav3s.app/" />
    <meta name="of:accepts:xmtp" content="2024-02-01" />
    <meta property="og:title" content="Zurf 🏄‍♂️" />
    <meta property="og:description" content="🤍 Building the funniest web3 social app." />
    <meta property="og:image" content="https://0xprimordia.github.io/framevertisment/1.gif?height=672&width=1344" />
    <meta name="twitter:card" content="summary_large_image" />
</head>
```
    <meta name="twitter:title" content="Zurf 🏄‍♂️" />
    <meta name="twitter:description" content="🤍 Building the funniest web3 social app." />
    <meta name="twitter:image" content="https://0xprimordia.github.io/framevertisment/1.gif?height=672&width=1344" />
  </head>
