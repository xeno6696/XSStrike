<h1 align="center">
  <br>
  <a href="https://github.com/s0md3v/XSStrike"><img src="https://image.ibb.co/cpuYoA/xsstrike-logo.png" alt="XSStrike"></a>
  <br>
  XSStrike
  <br>
</h1>

<h4 align="center">Advanced XSS Detection Suite</h4>

<p align="center">
  <a href="https://github.com/s0md3v/XSStrike/releases">
    <img src="https://img.shields.io/github/release/s0md3v/XSStrike.svg">
  </a>
  <a href="https://travis-ci.com/s0md3v/XSStrike">
    <img src="https://img.shields.io/travis/com/s0md3v/XSStrike.svg">
  </a>
  <a href="https://github.com/s0md3v/XSStrike/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues-closed-raw/s0md3v/XSStrike.svg">
  </a>
</p>

![multi xss](https://image.ibb.co/gR1ToA/Screenshot-2018-10-27-11-18-43.png)

<p align="center">
  <a href="https://github.com/s0md3v/XSStrike/wiki">XSStrike Wiki</a> •
  <a href="https://github.com/s0md3v/XSStrike/wiki/Usage">Usage</a> •
  <a href="https://github.com/s0md3v/XSStrike/wiki/Compatibility-&-Dependencies">Compatibility</a> •
  <a href="https://github.com/s0md3v/XSStrike#gallery">Gallery</a>
</p>

### Why XSStrike?
Every XSS scanner out there has a list of payloads, they inject the payloads and if the payload is reflected into the webpage, it is declared vulnerable but that's just stupid. XSStrike on the other hand analyses the response with multiple parsers and then crafts payloads that are guaranteed to work.
Here are some examples of the payloads generated by XSStrike:
```
}]};(confirm)()//\
<A%0aONMouseOvER%0d=%0d[8].find(confirm)>z
</tiTlE/><a%0donpOintErentER%0d=%0d(prompt)``>z
</SCRiPT/><DETAILs/+/onpoINTERenTEr%0a=%0aa=prompt,a()//
```
Apart from that, XSStrike has crawling, fuzzing, WAF detection capabilities as well. It also scans for DOM XSS vulnerabilities.

### Main Features
- Reflected and DOM XSS Scanning
- Multithreaded crawling
- Context analysis
- Configurable Core
- Highly Researched Workflow
- WAF detection & evasion
- Handmade HTML & JavaScript parser
- Powerful fuzzing engine
- Intelligent payload generator
- Complete HTTP Support
- Powered by [Photon](https://github.com/s0md3v/Photon), [Zetanize](https://github.com/s0md3v/zetanize) and [Arjun](https://github.com/s0md3v/Arjun)

### Gallery
#### DOM XSS
![dom xss](https://image.ibb.co/d1rpvq/Screenshot-2018-10-27-10-59-43.png)
#### Reflected XSS
![multi xss](https://image.ibb.co/gR1ToA/Screenshot-2018-10-27-11-18-43.png)
#### Crawling
![crawling](https://image.ibb.co/iAWNFq/Screenshot-2018-10-27-16-20-36.png)
#### Hidden Parameter Discovery
![arjun](https://image.ibb.co/bOAD5q/Screenshot-2018-10-27-18-16-37.png)
#### Interactive HTTP Headers Prompt
![headers](https://image.ibb.co/jw5NgV/Screenshot-2018-10-27-18-45-32.png)


### Contribution & License
XSStrike v.30 is in beta phase and has been released for public testing.<br>
Useful issues and pull requests are appreciated.

I haven't decided a license yet.
