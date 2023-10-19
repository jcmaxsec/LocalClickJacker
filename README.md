# LocalClickJacker
A clickjack testing page that allows you to test both internet and internal (local network, VPN, etc.) websites.

# Instalation
1. [Download the tester page here](https://github.com/jcmaxsec/LocalClickJacker/blob/main/ClickjackingTester.html) or clone this repository and cd to "LocalClickJacker" folder.
2. Double-click "ClickjackingTester.html" page to open it in your browser

# Usage
1. Enter the full url to test e.g. "http://www.my-website.com/". Notice the tester pagescan also work with internal hostnames or IPs like:
   * http://myserver.local
   * https://mylinuxserver
   * http://192.168.1.5/
4. Press ENTER key or click on "Load in Frame" button
5. If the page is loaded then clickjacking is possible, if you see a connection error then clickjacking is not possible. **IMPORTANT: Make sure the error is a "connection error" and not some "not found" or similar error in that case you might have mispelled the website.**

## Alternative Usage
Open the "ClickjackingTester.html" page and then add "?url=https://website-to-test.com/" after the page name. For example, ```ClickjackingTester.html?url=https://website-to-test.com/``` and the test will happen automatically.

# Author
Juan C Calderon
