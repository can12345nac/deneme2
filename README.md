//META{"name":"BasicBackground","description":"Allows you to use a background image in Discord without greatly altering the basic look of Discord.","author":"DevilBro","version":"1.0.5","authorId":"278543574059057154","invite":"Jx3TjNS","donate":"https://www.paypal.me/MircoWittrien","patreon":"https://www.patreon.com/MircoWittrien","website":"https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/BasicBackground","source":"https://raw.githubusercontent.com/mwittrien/BetterDiscordAddons/master/Themes/BasicBackground/BasicBackground.theme.css"}*//{}

@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/BasicBackground/BasicBackground.css);

:root {
	--transparencycolor:			0,0,0;						/* default:	0,0,0																								*/
	--transparencyalpha:			0.15;						/* default: 0.15				(general darkness of the app)													*/
	--messagetransparency:			0.5;						/* default: 0.5					(additional shadows behind messages, set to 0 to remove boxes)					*/
	--guildchanneltransparency:		0.15;						/* default: 0.15				(additional darkness for guild/channel list)									*/
	--memberlisttransparency:		0.0;						/* default: 0.0					(additional darkness for member list)											*/
	--accentcolor:					190,78,180;					/* default: 190,78,180			(blurple: 114,137,218 bd-blue: 58,113,193)										*/
	
	--font:							Whitney, Helvetica Neue, Helvetica, Arial, sans-serif;		/* font used in most places														*/
	--textshadow:					transparent;				/* default: transparent			(textshadow for text ontop of accentcolor nodes, ONLY accepts a color, no px)	*/
	
	--background:					url(https://cdn.discordapp.com/attachments/600030123953225754/707969010121179306/blade-15-stock-wallpaper-with-razer-logo-removed-1080p-for-razer-png-purple-1920_1080.png);	/* general background image						*/
	--backgroundsize:				cover;						/* default: cover				(sizefit of general background - values: [cover/contain/auto])					*/
	--backgroundblur:				0px;						/* default: 0px					(only works when --background is set to an image)								*/
	
	--popout:						var(--background);			/* default: var(--background)	(change to use another background/color for modals/popouts)						*/
	--popoutsize:					var(--backgroundsize);		/* default: cover				(sizefit of popout background - values: [cover/contain/auto])					*/
	--popoutblur:					0px;						/* default: 0px					(only works when --popout is set to an image)									*/
	
	--backdrop:						rgba(0,0,0,0.85);			/* default: rgba(0,0,0,0.85)	(change to use another background/color for backdrops)							*/
	--backdropsize:					var(--backgroundsize);		/* default: cover				(sizefit of backdrop background - values: [cover/contain/auto])					*/
	--backdropblur:					0px;						/* default: 0px					(only works when --backdrop is set to an image)									*/
	
	--version1_0_5:					none;						/* DO NOT CHANGE, USED TO HIDE UPDATE NOTICE																	*/
}
