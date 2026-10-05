# ddm-app-privacy-payloads
A content repository for storing and sharing payloads for Apple's new App Privacy declaration

## Repository structure

To help make it easy to find an application you're looking for, the applications are grouped by type. E.g. Browsers, Video Conferencign Applications, VDI Clients, et cetera.

If you can't find an app you're looking for, please feel free to submit an [Application Request](https://github.com/philipross/ddm-app-privacy-payloads/issues/new/choose) with relevant details.<br>
Even better - if you weren't able to find it here but then subsequently find it/build it yourself, please consider [contributing](https://github.com/philipross/ddm-app-privacy-payloads/blob/main/README.md#-contributing).

## Using a template from the repo

When you find a template you wish to use, you can copy the relevant details into your DMS of choice.<br>
You'll need to ensure you update the following:
* If you need to specify it, make sure you update the identifier as per the format your org uses. Typically identifiers are:<br>
    * A randomly generated UUID (uuidgen in Terminal.app will generate one for you)
    * A unique string, relevant to the control and application it's referencing. E.g. `com.apple.configuration.app.settings.chrome-privacy`

* The organisation/organization justification:
    * The string in the templates is just to provide an example. Make sure you update it to something relevant to your users.<br>*(Or don't, if you're feeling brave)*

* Modify the permissions you wish to set as default.
    * Templates contain all of the values applicable to each key. If you don't modify this, the payload won't be valid.
    * Organisations may wish to set different default values for their own requirements, so make sure to mould the template to your needs.

****

## 💬 Giving Feedback
🐛 If you find a bug, please create an [issue](https://github.com/philipross/ddm-app-privacy-payloads/issues/new/choose) so it can be tracked. 

## 💡 Contributing

🤝 If you'd like to contribute individual files, please read the [CONTRIBUTING.md](placeholder) for more details.

🧑‍🔧 If you're interested on becoming a maintainer on the repo, shoot me a message on the <img src="https://a.slack-edge.com/9cc0056/marketing/img/nav/logo.svg" width=12> [MacAdmins Slack](https://macadmins.org/community/slack/)!


## 🗃️ Documentation

 Apple's Developer docs for this feature can be found [here.](https://developer.apple.com/documentation/devicemanagement/appsettings)

<body>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="Assets/GitHub_Invertocat_White.png" width=15>
  <img src="Assets/GitHub_Invertocat_Black.png" width=15>
Apple's GitHub YAML for this feature can be found <a href="https://github.com/apple/device-management/blob/release/declarative/declarations/configurations/app.settings.yaml#L180"> here.</a>
</picture>
</body>


<!--
Author: Philip Ross
Keywords: AppPrivacy declaration App Privacy DDM Apple macos
-->
