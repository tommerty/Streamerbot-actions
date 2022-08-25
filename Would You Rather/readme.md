# Would You Rather - Twitch Channel Reward game by TommoIRL (IRLCreate)
> You can follow these instructions, or watch the video [here](https://youtu.be/I2Sk7rzUAAA)

# Part 1: Installation Instructions

### Prerequisites
- [Fira Sans Font](https://fonts.google.com/download?family=Fira%20Sans) (this is a Google font that's completely safe to download from fonts.google.com) 
> You technically could use whatever font you'd like, however I've built this with Fira(black) so things may need to be re-aligned if you choose another font.
- OBS Source Copy Plugin - [download here](https://obsproject.com/forum/resources/source-copy.1261/)
- [StreamerBot](https://streamer.bot), of course!
- A Twitch channel (affiliated as it's channel points)

### Step 1 - Downloading:
1. Download all the files from [here](https://ko-fi.com/s/f77c9f39eb)
> Please note: I stopped uploading these to Github and started using the Gezel Ko-Fi instead.
2. Download and install the [OBS Source Copy Plugin](https://obsproject.com/forum/resources/source-copy.1261/) if you haven't already.
### Step 2 - Getting OBS + Streamerbot ready:
1. Launch OBS and navigate to tools > Source Copy > Load Scene
  - Select the `wouldyourather.json` file
  - You should now see a new scene in your OBS called `Would You Rather`. Feel free to add this scene into your alert scene so it's nested and visible from other places.
2. Launch Streamerbot
  - Navigate to import and drag/drop the `wouldyourather.streamerbot` file in.

### Step 3 - Configuring the channel rewards:
1. Inside Streamerbot, go to Platforms > Twitch > Channel Point Rewards and create the following rewards with these settings:

- `Start Would You Rather` - Enabled: `yes` - User Input Required: `no` - Action: `Would You Rather`
- `WYR - First Option` - Enabled: `no` - User Input Required: `yes` - Action: `WYR - First Option`
- `WYR - Second Option` - Enabled: `no` - User Input Required: `yes` - Action: `WYR - Second Option`
> Any other options such as cost/etc can be modified how you like. If you change any of the names of these rewards or files in general, be sure to update it in the actions also. I would just recommend leaving them as is to not cause any problems.

That should be it, and you should be ready to go!
Any problems or questions feel free to comment on the video or jump into the [Gezel Discord](https://gezel.io/discord) and drop a message somewhere and I'll be happy to take a look!

# Part 2: Commands
- `wyr1`: Left wins
- `wyr2`: Right wins
- `!wyr cancel`: Kills the game and restarts

Don't forget to subscribe if you haven't already!
And you should also check out [Mystl.ink](https://mystl.ink) too if you haven't already! ❤️
