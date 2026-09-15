# How to Install SWIFT ?

Search "swift"

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Click  [swift.org](https://swift.org)

Click Install

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Click on Windows

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Open Terminal and Run these Commands

{% code overflow="wrap" %}
```powershell
winget install --id Microsoft.VisualStudio.2022.Community --exact --force --custom "--add Microsoft.VisualStudio.Component.Windows11SDK.22621 --add Microsoft.VisualStudio.Component.VC.Tools.x86.x64 --add Microsoft.VisualStudio.Component.VC.Tools.ARM64" --source winget
```
{% endcode %}

{% code overflow="wrap" %}
```powershell
winget install --id Swift.Toolchain -e --source winget
```
{% endcode %}



To CHECK WHETHER IT INSTALLED OR NOT

{% code overflow="wrap" %}
```
swift --version
```
{% endcode %}



### HOW TO SETUP A PROJECT

Create a folder "SWIFT" on desktop

|

Open that folder in vs code

|

Open terminal and run:

{% code overflow="wrap" %}
```powershell
swift package init --name MyCLI --type executable
```
{% endcode %}

|

Run it

{% code overflow="wrap" %}
```swift
swift run
```
{% endcode %}









### SOURCES:

[https://www.swift.org/install/windows/](https://www.swift.org/install/windows/)
