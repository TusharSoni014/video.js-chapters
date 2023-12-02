# video.js-chapters
videojs chapters with hover seekbar chapter names

# Whats New?
I added A YouTube like seekbar chapters, when you hover over it, the current playing chapter title will appear above your cursor and it will highlight in the timeline from which timing it will start or end.

# What do you need to show chapters?
Only a array of chapters along with timestamps are needed like this.
```
      var chapters = [
        {
          timeStamp: 30,
          title: "chater 1",
        },
        {
          timeStamp: 60,
          title: "chapter 2",
        },
        {
          timeStamp: 120,
          title: "chapter 3",
        },
        {
          timeStamp: 190,
          title: "chapter 4",
        },
        {
          timeStamp: 220,
          title: "chapter 5",
        },
      ];
```
### The timestamps are in seconds, so it will be divied accordingly in the video.

# Keyboard Shortcuts?
I have also added keyboard shortcuts to make the player functionality similar to YouTube,
- Play/Pause: `Spacebar`
- Seek Forward/Backward: `Right Arrow(→) / Left Arrow(←)`
- Toggle FullScreen: `F`
