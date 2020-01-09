# Auerswald D-Series Config Templates

This repository contains some useful Configuration Examples, that I use personally in D-Series Desktop Phones made by Auerswald and FONtevo.

<p>
  <a href="https://github.com/richardklose/auerswald-d-series-config-templates/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://twitter.com/richard_klose">
    <img alt="Twitter: richard_klose" src="https://img.shields.io/twitter/follow/richard_klose.svg?style=social" target="_blank" />
  </a>
</p>

PLEASE NOTE THAT THIS FILES ARE MADE BY ME AND ARE NEITHER GUARANTEED TO WORK IN EVERY PHONE AND FIRMWARE VERSION, NOR VERIFIED BY AUERSWALD IN ANY WAY.

Although the D-Series Phones already offer great functionality and flexibility out of the box, some use cases are not covered by the factory default configuration. Thankfully, new functions can be added easily by customers with provisioning.

## Table of contents
### README
* [Usage](#Usage)
* [Further information](#Further-information)
* [Author](#Author)
* [Contributing](#Contributing)
* [Show your support](#Show-your-support)
* [License](#License)

### Repository
* templates
  * [Speed dial without subscription](templates/speeddial_without_subscription.xml)

## Usage
### Import XML files manually
Confgiuration files can be imported as a backup via the Web UI, even if it is not a full phone configuration. Imported files are merged into the existing configuration in the phone.
1. Login to the Web UI of your phone
2. Go to "Backup"
3. Import the XML file
   
### Add the relevant parts to the templates in your Provisiong Server (e.g. your PBX)
If you want to use the XML Files in your Provisiong Server, you can add the relevant parts of the XML file to your exisiting template. This depends on what you already have in your templates, but in most cases this means "take everything inside the `<configuration></configuration>` block and copy it to your existing template".
For updating provisioning templates in Auerswald PBX systems, please refer to the [official manuals](https://www.auerswald.de/en/service/service-products-en/pbx-systems-en.html).

## Further information
Additional information and documentation about XML configuration files can be found in the official [developer documentation](http://wiki.auerswald.de/doku.php?id=en:products:comfortel-d-series).

## Author

👤 **Richard Klose &lt;richard@klose.dev&gt;**

* Twitter: [@richard_klose](https://twitter.com/richard_klose)
* Github: [@richardklose](https://github.com/richardklose)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/richardklose/auerswald-d-series-config-templates/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2019 [Richard Klose &lt;richard@klose.dev&gt;](https://github.com/richardklose).<br />
This project is [MIT](https://github.com/richardklose/auerswald-d-series-config-templates/blob/master/LICENSE) licensed.