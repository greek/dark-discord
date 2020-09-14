# Dark Discord
An actual dark mode for discord.

# Downloads
- Powercord: `git clone https://github.com/greek/dark-discord/`

# Preview
<img src="http://i.apap04.com/2020/09/14/DiscordCanary_ICOhlfuWQD.png"/>

# Support 
- [Support Server](https://discord.gg/nr8Fx9u)
- andreas#0001

## Parts of the theme not working?

On my own experience, the changes I made to the theme did not load properly. So I added this section just in case.
If some parts of the theme look off (like the user panel on the bottom right), here's what to do
- Go to settings
- Under the Powercord category, go to the Themes tab
- Click on "Quick CSS" and paste the following code

```css
.peopleColumn-29fq28 {
   background-color: var(--background-primary);
}

.panels-j1Uci_ {
  background-color: var(--background-secondary);
}

.theme-dark .inset-3sAvek {
  background-color: var(--background-primary);
}

.theme-dark .root-1gCeng {
	background-color: var(--background-secondary);
}

.autocompleteInner-zh20B_ {
  padding-bottom: 8px;
  background-color: var(--background-tertiary);
}
```
