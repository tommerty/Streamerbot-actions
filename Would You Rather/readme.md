# Would You Rather - Twitch Channel Reward game by TommoIRL (IRLCreate)

## You can follow these instructions, or watch the video [here]()

### Prerequisites
- [Fira Sans Font](https://fonts.google.com/download?family=Fira%20Sans) (this is a Google font that's completely safe to download from fonts.google.com) 
> You technically could use whatever font you'd like, however I've built this with Fira(black) so things may need to be re-aligned if you choose another font.
- OBS Source Copy Plugin - [download here](https://obsproject.com/forum/resources/source-copy.1261/)
- [StreamerBot](https://streamer.bot), of course!
- A Twitch channel (affiliated as it's channel points)

### Step 1 - Downloading:
1. Download all the files from [here]()
> Please note: I stopped uploading these to Github and started using the Gezel Ko-Fi instead.
2. Download and install the [OBS Source Copy Plugin](https://obsproject.com/forum/resources/source-copy.1261/) if you haven't already.
### Step 2 - Getting OBS + Streamerbot ready:
1. Launch OBS and navigate to tools > Source Copy > Load Scene
  - Select the `wouldyourather.json` file
  - You should now see a new scene in your OBS called `Would You Rather`. Feel free to add this scene into your alert scene so it's nested and visible from other places.
2. Launch Streamerbot
  - Navigate to import and drag/drop the `wouldyourather.streamerbot` file in.
> If you're having any problems with this, you can paste the following code instead:
```
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
```
### Step 3 - Configuring the channel rewards:
1. Inside Streamerbot, go to Platforms > Twitch > Channel Point Rewards and create the following rewards with these settings:

- `Start Would You Rather` - Enabled: `yes` - User Input Required: `no` - Action: `Would You Rather`
- `WYR - First Option` - Enabled: `no` - User Input Required: `yes` - Action: `WYR - First Option`
- `WYR - Second Option` - Enabled: `no` - User Input Required: `yes` - Action: `WYR - Second Option`
> Any other options such as cost/etc can be modified how you like. If you change any of the names of these rewards or files in general, be sure to update it in the actions also. I would just recommend leaving them as is to not cause any problems.

That should be it, and you should be ready to go!
Any problems or questions feel free to comment on the video or jump into the [Gezel Discord}(https://gezel.io/discord) and drop a message somewhere and I'll be happy to take a look!

Don't forget to subscribe if you haven't already!
And you should also check out [Mystl.ink](https://mystl.ink) too if you haven't already! ❤️
