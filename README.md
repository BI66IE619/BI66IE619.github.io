# [BI6PROXY](https://github.com/BI66IE619/BI6PROXY-WEB-PROXY/)
### A node.js web proxy for use in combating web filters

# Updates
```
(Updated 4/13/22): DO NOT RELY ON THIS TO "HIDE YOUR ACTIVITY". Due to lack of updates, most companies can now detect BI6PROXY. I may work on it over a period of time.
```
# Security
### VirusTotal:

### SSL/TLS:
BI6PROXY is encrypted with the latest TLS 1.3

Since Heroku does not support SSL Certificates for free dynos, the next best alternative is using CloudFare Flexible.

### Email Address Obfuscation
CloudFare will attempt to obfuscate email addresses on BI6PROXY to prevent harvesting by bots and spammers

# Speed
There a lot of speed improvements since BI6PROXY/Test, mainly including:

- Brotli Compression
- Rocket Loader
- Auto Minify
- Cloudfare Caching
- Arc.io Caching
- Browser Cache

##### BI6PROXY has a higher PageSpeed rating of 99/100 compared to BI6PROXY'S 94/100

## Running locally

```sh
git clone https://github.com/titaniumnetwork-dev/alloyproxy.git
cd alloyproxy
node server.js
```

## Options in config.json
```json
{
    "port": "8080",
    "ssl": false,
    "prefix": "/web/",
    "localAddresses": [],
    "blockedHostnames": []
}
```

`"port": "8080"` = Sets HTTP server port of web proxy.

`"ssl": "false"` = Sets HTTP server SSL.

`"prefix": "/web/"` = Sets the overall prefix of the web proxy.

`"localAddresses": [ "0.0.0.0" ]` = Allows you to choose which IP to make the request from. If there are multiple IP's then the IP chosen will be randomized.

`"blockedHostnames": [ "example.org", "example.com" ]` = If the hostname of the proxy URL matches any of the URL hostnames listed in the array, the request to the server will be cancelled.

# Credits
- [Titanium Network](https://github.com/titaniumnetwork-dev)
- [QuiteAFancyEmerald](https://github.com/QuiteAFancyEmerald)
- [Jason](https://github.com/caracal-js)
- [B3ATDROP3R](https://github.com/B3ATDROP3R)
- [shirt](https://github.com/shirt-dev)
- [Xproassassinn](https://github.com/Xproassassinn)

# License 
![GitHub](https://img.shields.io/github/license/BI66IE619/BI6PROXY-WEB-PROXY?style=for-the-badge)
```
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
### Copyright (c) 2024-2025 BI6PROXY
