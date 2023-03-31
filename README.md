# Required Parameters
## Type 
```bash
Success (default), Warning, Error, Info & Other
Other is styled like Info but is displayed without an Icon unless you specify a custom icon to use.
```
## Message 
```bash
The message to display in the toast.
To include a clickable link in the message, place the characters {url} in your message and provide values for the URL Link and URL Label parameters.
```
# Optional
## Title
```bash
Text to appear above the message in a slightly larger font
```
## Icon
```bash
The name of the Utility icon to display when choosing a Type of Other
```
See Utility [Icons](https://www.lightningdesignsystem.com/icons/) Icons section

## Mode 
```bash
Dismissible : will display the toast message until the close button is clicked or the duration time has elapsed.
Pester : will display until the duration time has elapsed. No close button will be available.
Sticky: will remain displayed until the close button is pressed
```
## Duration
```bash
The default is 10 seconds and the minimum is 5 seconds.
The duration attribute only applies to Dismissible and Pester modes.
```
## Url Label
```bash
This is the Label for the link in your message
To include a clickable link in the message, place the characters {url} in your message. At run-time the message will be updated to replace {url} with the value of your URL Label parameter and it will link to the address you specified in the URL Link parameter.
```
## Url Link
```bash
This is the URL for the link in your message
```
