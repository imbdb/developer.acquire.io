# One Click Button

{% hint style="info" %}
Start video, audio and chat support with one click of button.
{% endhint %}

Copy the code on the right inside the body tag to customize a quick connection to support.

## Methods

|  Method |  Parameters |  Type |  Description |
| :--- | :--- | :--- | :--- |
|  max\(\) |  video |  _`String`_ |  Starts a video call with widget maximized |
|  | audio | _`String`_ |  Starts a audio call with widget maximized |
|  | text | _`String`_ |  Starts a text chat with widget maximized |

### Sample Code to embedd \( for video call \)

```javascript
<a href="javascript:acquireIO.max('video')"> Start Video Call Now </a>
```

### Sample Code to embedd \( for audio call \)

```javascript
<a href="javascript:acquireIO.max('audio')"> Start Audio Call Now </a>
```

### Sample Code to embedd \( for text chat \)

```javascript
<a href="javascript:acquireIO.max('text')"> Start Text Chat Now </a>
```

## Quick Chat Link for Specific Agent

 To make a custom link to initiate chat with specific agent, use the following code to generate link.

### Embedd Code For Text Chat

```javascript
<a href="javascript:acquireIO.max('text',AGENT_ID)">Start the Chat</a>
```

####  **Get AGENT\_ID**

 First login [Acquire dashboard](https://app.acquire.io/)  and open **Agents** and copy specific **`agent ID`**.

![Get Agent\_ID](../../.gitbook/assets/get-agent-id-1.png)

#### Example:

```javascript
<a href="javascript:acquireIO.max('text',12823)">Start the Chat With Som</a>
```

### Embedd Code For Video Call

```javascript
<a href="javascript:acquireIO.max('video',AGENT_ID)"> Start Video Call Now </a>
```

#### Example:

```javascript
<a href="javascript:acquireIO.max('video',12823)"> Start Video Call Now </a>
```

### Embedd Code For Audio Call

```javascript
<a href="javascript:acquireIO.max('audio',AGENT_ID)"> Start Audio Call Now </a>
```

#### Example:

```javascript
<a href="javascript:acquireIO.max('audio',12823)"> Start Audio Call Now </a>
```

