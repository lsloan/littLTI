# Overview

littLTI is a JavaScript tool for launching LTI 1.1 tools.  It's helpful while developing LTI tool providers.  Note that this tool may only include parameters for LTI 1.0 and doesn't include all of the optional parameters for that version of the standard.

Whenever a launch is triggered, the configuration parameters are applied, new nonce and timestamp values are obtained, and a new OAuth signature is calculated.  The "Refresh" button does the same, without triggering a launch.

Feedback on this tool is welcome, including better labels for UI elements. 

  -- lsloan at umich dot edu

# Requirements

Requires the following JavaScript libraries deployed to the same directory:

* jQuery v2.1.3 (jquery-2.1.3.js)

  http://jquery.com

* CryptoJS v3.1.2 (hmac-sha1.js & enc-base64.js)

  http://code.google.com/p/crypto-js

