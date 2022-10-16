# react-native-custom-video-player

A `<Video>` component for react-native



https://user-images.githubusercontent.com/51233027/196026981-c0c7b6e9-a67b-4602-b701-4971056add58.mp4




## Installation

Using npm:

```shell
npm install --save react-native-custom-video-player
```

or using yarn:

```shell
yarn add react-native-custom-video-player
```

## Usage

```javascript
// Load the module

import CustomVideoPlayer from "react-native-custom-video-player";

// Within your render function

<CustomVideoPlayer
        style={{
          width: Dimensions.get("window").width,
          height: 250,
          marginTop: Platform.OS == "ios" ? 50 : 0,
        }}
        source={{
          uri: "https://test-streams.mux.dev/x36xhzz/x36xhzz.m3u8",
        }}
        poster="https://pbs.twimg.com/media/FDX7UCbVcAUcNXj.jpg"
        title="GYAN-VIDEO-PLAYER"
        autoPlay={false}
        playInBackground={false}
        showSeeking10SecondsButton={true}
        showHeader={true}
        showFullScreenButton={true}
        showSettingButton={true}
        showMuteButton={true}
      />

```

---
