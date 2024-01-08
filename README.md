# WebRTC-High-Resolution-Photo

A demo of taking a high resolution photo with WebRTC's getUserMedia.

[Online demo](https://tony-xlh.github.io/WebRTC-High-Resolution-Photo)

There are several ways to take a photo with the camera.

1. Use WebRTC's [getUserMedia](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia) to start camera preview in a video element and then use a 2D canvas context to drawImage from that video. The canvas can return a data URL for an image to use.
2. Use the HTML [Media Capture API](https://w3c.github.io/html-media-capture/), i.e.  `<input type="file" name="image" accept="image/*" capture>`


This demo uses WebRTC's approach. It can set the resolution to a high value to take a high resolution photo. In addition, it can also use the [Image Capture API](https://w3c.github.io/mediacapture-image/) if supported.

