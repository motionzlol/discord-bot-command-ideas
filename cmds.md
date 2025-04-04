#Bot Command Ideas

Here is a list of potential command ideas for your Discord bot:

## Utility Commands
1.  `/ping` - Check bot latency and status.
2.  `/help` - Display available commands and usage.
3.  `/userinfo [user]` - Show details about a user (ID, join date, roles, etc.).
4.  `/serverinfo` - Show details about the current server (ID, owner, members, channels, creation date).
5.  `/avatar [user]` - Display a user's avatar (profile picture).
6.  `/roleinfo [role]` - Show details about a specific role (ID, members, permissions).
7.  `/channelinfo [channel]` - Show details about a specific channel (ID, topic, type).
8.  `/permissions [user] [channel]` - Check a user's permissions in a specific channel or server-wide.
9.  `/invite` - Generate an invite link for the bot.
10. `/uptime` - Show how long the bot has been online.
11. `/stats` - Display bot statistics (servers, users, memory usage).
12. `/poll <question> | <option1> | <option2> ...` - Create a simple poll with reactions.
13. `/remindme <time> <message>` - Set a reminder for yourself.
14. `/snipe` - Show the last deleted message in the channel (optional, privacy concerns).
15. `/editsnipe` - Show the original content of the last edited message (optional, privacy concerns).
16. `/jumbo <emoji>` - Enlarge a custom emoji.
17. `/afk [reason]` - Set an AFK status.
18. `/prefix` - View the current command prefix (if using prefix commands).
19. `/source` - Link to the bot's source code (if public).
20. `/feedback <message>` - Send feedback directly to the bot owner(s).
21. `/servericon` - Display the server's icon.
22. `/serverbanner` - Display the server's banner (if boosted).
23. `/rolecolor [role]` - Show the hex color of a role.
24. `/emojilist` - List all custom emojis available in the server.
25. `/stickerlist` - List all custom stickers available in the server.
26. `/membercount` - Show the total number of members (optionally broken down by status or humans/bots).
27. `/channelcount` - Show the total number of channels (optionally broken down by type).
28. `/rolecount` - Show the total number of roles.
29. `/booststatus` - Show the server's boost level and count.
30. `/inrole [role]` - List members who have a specific role.
31. `/notinrole [role]` - List members who *do not* have a specific role.
32. `/haspermission [permission] [user]` - Check if a user has a specific server permission.
33. `/time [timezone]` - Show the current time in a specified timezone.
34. `/convert <amount> <unit_from> <unit_to>` - Convert between units (e.g., temperature, length, currency).
35. `/calculate <expression>` - Evaluate a mathematical expression.
36. `/qrcode <text_or_url>` - Generate a QR code for given text or URL.
37. `/shortenurl <url>` - Shorten a long URL using a service.
38. `/expandurl <short_url>` - Expand a shortened URL to see the original.
39. `/passwordgen [length] [options]` - Generate a secure random password.
40. `/uuidgen` - Generate a random UUID.
41. `/base64encode <text>` - Encode text to Base64.
42. `/base64decode <base64_string>` - Decode Base64 text.
43. `/md5 <text>` - Calculate the MD5 hash of text.
44. `/sha256 <text>` - Calculate the SHA256 hash of text.
45. `/whois [domain_or_ip]` - Perform a WHOIS lookup on a domain or IP address.
46. `/dnslookup [domain]` - Perform a DNS lookup for a domain.
47. `/pingip <ip_address>` - Check network connectivity to an IP address (bot server perspective).
48. `/color <hex_or_rgb>` - Display a color swatch and its values (hex, rgb, hsl).
49. `/randomcolor` - Generate and display a random color.
50. `/timestamp [datetime_string]` - Convert a human-readable date/time to a Discord timestamp format.
51. `/fromtimestamp <unix_timestamp>` - Convert a Unix timestamp to human-readable date/time.
52. `/firstmessage [channel]` - Find and link the first message sent in a channel.
53. `/lastmessage [user] [channel]` - Find the last message sent by a user in a channel.
54. `/messagecount [user] [channel]` - Count messages sent by a user in a channel (can be slow/API intensive).
55. `/activity [user]` - Show a user's current activity/status message (requires presence intent).
56. `/listreminders` - Show your pending reminders set with `/remindme`.
57. `/deletereminder [id]` - Delete a specific reminder.
58. `/serverroles` - List all roles on the server.
59. `/userroles [user]` - List all roles a specific user has.
60. `/getid [user|role|channel|emoji]` - Get the Discord ID of an entity.
61. `/getuser [user_id]` - Find a user by their ID.
62. `/charinfo <character>` - Show information about a Unicode character (name, code point).
63. `/invites` - List active server invites (requires permissions).
64. `/inviteinfo [invite_code]` - Show information about a specific invite code.
65. `/auditlog [limit] [action_type]` - View recent server audit log entries (requires permissions).
66. `/tempchannel [name] [duration]` - Create a temporary text or voice channel.
67. `/voicekick [user] [reason]` - Disconnect a user from a voice channel (requires permissions).
68. `/voicemove [user] [channel]` - Move a user to another voice channel (requires permissions).
69. `/setnickname [user] [nickname]` - Change a user's nickname (requires permissions).
70. `/resetnickname [user]` - Reset a user's nickname (requires permissions).
71. `/purge [amount] [options]` - Advanced message deletion (bots, humans, embeds, links, text contains).
72. `/slowmodeoff [channel]` - Disable slowmode in a channel.
73. `/channeltopic [channel] [new_topic]` - Set the topic for a text channel.
74. `/channelname [channel] [new_name]` - Rename a channel.
75. `/roleadd [user] [role]` - Add a role to a user.
76. `/roleremove [user] [role]` - Remove a role from a user.
77. `/createrole [name] [color] [permissions]` - Create a new role.
78. `/deleterole [role]` - Delete a role.
79. `/rolepermissions [role]` - View permissions for a specific role.
80. `/setrolecolor [role] [color]` - Change the color of a role.
81. `/setrolehoist [role] [true|false]` - Toggle whether a role is displayed separately.
82. `/setrolementionable [role] [true|false]` - Toggle whether a role can be mentioned.
83. `/backupcreate` - Create a backup of server settings/roles (complex feature).
84. `/backupload [backup_id]` - Load a server backup (complex, dangerous).
85. `/massrole [add|remove] [role] [target_role]` - Add/remove a role from everyone who has another role.
86. `/cleanreacts [message_id]` - Remove all reactions from a message.
87. `/embedsource [message_id]` - Show the raw data/source of an embed message.
88. `/webhooksend <url> <message>` - Send a message via a webhook URL.
89. `/pastebin <text>` - Upload text to a pastebin service and return the link.
90. `/hastebin <text>` - Alias for `/pastebin`.
91. `/githubgist <filename> <content>` - Create a GitHub Gist.
92. `/binaryencode <text>` - Convert text to binary.
93. `/binarydecode <binary_string>` - Convert binary to text.
94. `/hexencode <text>` - Convert text to hexadecimal.
95. `/hexdecode <hex_string>` - Convert hexadecimal to text.
96. `/morseencode <text>` - Convert text to Morse code.
97. `/morsedecode <morse_string>` - Convert Morse code to text.
98. `/serverlocale` - Show the server's preferred locale/language setting.
99. `/mutualservers [user]` - List servers you share with another user (limited by bot scope).
100. `/shardinfo` - Show information about the bot's current shard (if sharded).
101. `/listbots` - List all bot users currently in the server.
102. `/listadmins` - List all users with Administrator permissions.
103. `/listmods [moderator_role]` - List all users with a specific moderator role.
104. `/fetchmessage [message_id] [channel_id]` - Fetch and display a specific message by ID.
105. `/fetchchannel [channel_id]` - Get channel object by ID.
106. `/fetchrole [role_id]` - Get role object by ID.
107. `/nowplaying [user]` - Show what song a user is listening to on Spotify (requires presence).
108. `/membergraph [days]` - Show a graph of member joins/leaves over time.
109. `/messagegraph [days]` - Show a graph of message activity over time.
110. `/reactionpoll <message_id> <emoji1> <emoji2> ...` - Turn reactions on an existing message into poll results.
111. `/stickermeta [sticker_name_or_id]` - Show metadata about a server sticker.
112. `/emojimeta [emoji_name_or_id]` - Show metadata about a custom emoji.
113. `/stealemoji <emoji> [name]` - Add a custom emoji from another server to this one (requires permissions).
114. `/stealsticker <sticker> [name]` - Add a custom sticker from another server to this one (requires permissions).
115. `/finduser <query>` - Search for users matching a name/discriminator query.
116. `/findchannel <query>` - Search for channels matching a name query.
117. `/findrole <query>` - Search for roles matching a name query.
118. `/threadcreate <message_id_or_channel> <name> [duration]` - Create a thread.
119. `/threadarchive [thread_id]` - Archive a thread.
120. `/threadlock [thread_id]` - Lock a thread.

## Fun Commands
121. `/coinflip` - Flip a virtual coin.
122. `/dice [number]` - Roll a dice (or multiple dice).
123. `/8ball <question>` - Ask the magic 8-ball a question.
124. `/meme` - Fetch a random meme from a source like Reddit.
125. `/joke` - Tell a random joke.
126. `/cat` - Show a random cat picture/gif.
127. `/dog` - Show a random dog picture/gif.
128. `/quote` - Display a random inspirational or funny quote.
129. `/rps [rock|paper|scissors]` - Play Rock Paper Scissors against the bot.
130. `/say <message>` - Make the bot repeat a message.
131. `/embed <title> | <description>` - Create a simple embed message.
132. `/ascii <text>` - Convert text to ASCII art.
133. `/wyr` - Ask a "Would You Rather" question.
134. `/truth` - Get a "Truth" question.
135. `/dare` - Get a "Dare" prompt.
136. `/ship [user1] [user2]` - Calculate a "love compatibility" percentage (just for fun).
137. `/rate <thing>` - Rate something out of 10.
138. `/topic` - Suggest a random conversation topic.
139. `/fact` - Tell a random interesting fact.
140. `/lenny` - Display the ( ͡° ͜ʖ ͡°) face.

## Moderation Commands
141. `/kick [user] [reason]` - Remove a user from the server.
142. `/ban [user] [reason] [days_to_delete_messages]` - Ban a user from the server.
143. `/unban [user_id]` - Unban a user using their ID.
144. `/mute [user] [duration] [reason]` - Mute a user (requires role setup).
145. `/unmute [user] [reason]` - Unmute a user.
146. `/clear [amount] [user]` - Delete a specified number of messages (optionally from a specific user).
147. `/warn [user] [reason]` - Give a user a warning.
148. `/warnings [user]` - List warnings for a user.
149. `/clearwarnings [user]` - Clear all warnings for a user.
150. `/slowmode [seconds] [channel]` - Set slowmode for a channel.
151. `/lock [channel] [reason]` - Prevent non-moderators from sending messages in a channel.
152. `/unlock [channel]` - Remove the message lock from a channel.
153. `/nuke [channel]` - Clone and replace a channel to clear all history (use with extreme caution).
154. `/reason [case_id] [new_reason]` - Update the reason for a moderation action.
155. `/softban [user] [reason]` - Kick a user and immediately unban them to delete their recent messages.

## Information Commands
156. `/weather [location]` - Get the current weather for a location.
157. `/define [word]` - Get the dictionary definition of a word.
158. `/urban [term]` - Look up a term on Urban Dictionary.
159. `/wikipedia [query]` - Search Wikipedia for an article summary.
160. `/google [query]` - Perform a Google search.
161. `/youtube [query]` - Search YouTube for a video.
162. `/github [repository]` - Show information about a GitHub repository.
163. `/steam [game]` - Search for a game on Steam.
164. `/crypto [symbol]` - Get the current price of a cryptocurrency.
165. `/stock [symbol]` - Get the current price of a stock.
166. `/movie [title]` - Search for information about a movie.
167. `/tvshow [title]` - Search for information about a TV show.
168. `/anime [title]` - Search for information about an anime.
169. `/manga [title]` - Search for information about a manga.
170. `/translate <language> <text>` - Translate text to another language.

## Image Manipulation Commands
171. `/greyscale [user_or_image]` - Apply a greyscale filter.
172. `/invert [user_or_image]` - Invert the colors of an image.
173. `/sepia [user_or_image]` - Apply a sepia filter.
174. `/blur [user_or_image]` - Apply a blur filter.
175. `/pixelate [user_or_image]` - Pixelate an image.
176. `/wanted [user]` - Put a user's avatar on a "Wanted" poster.
177. `/triggered [user]` - Create a "Triggered" gif with a user's avatar.
178. `/wasted [user]` - Apply a GTA "Wasted" overlay to a user's avatar.
179. `/jail [user]` - Put a user's avatar behind jail bars.
180. `/brightness [level] [user_or_image]` - Adjust image brightness.

## Configuration Commands (for Admins)
181. `/setprefix [new_prefix]` - Change the bot's command prefix (if applicable).
182. `/setmodlog [channel]` - Set the channel for moderation logs.
183. `/setwelcomemsg [message]` - Configure the welcome message for new members.
184. `/setleavemsg [message]` - Configure the leave message for departing members.
185. `/autorole [add|remove|view] [role]` - Configure roles to be automatically assigned to new members.
186. `/ignoredchannels [add|remove|view] [channel]` - Make the bot ignore commands in certain channels.
187. `/ignoredroles [add|remove|view] [role]` - Make the bot ignore commands from users with certain roles.
188. `/enable [command|category]` - Enable a specific command or category.
189. `/disable [command|category]` - Disable a specific command or category.
190. `/permissionsrole [level] [role]` - Assign permission levels to roles for bot commands.

## Miscellaneous Commands
191. `/suggest [suggestion]` - Submit a suggestion for the server or bot.
192. `/bugreport [report]` - Report a bug found in the bot.
193. `/changelog` - Show recent changes or updates to the bot.
194. `/giveaway [duration] [winners] [prize]` - Start a giveaway (requires managing entries).
195. `/tag [create|edit|delete|view] [name] [content]` - Create reusable text snippets (tags).
196. `/timer [duration]` - Start a simple countdown timer.
197. `/level (user)` - Check your or someone else's level (requires leveling system).
198. `/rank (user)` - Alias for `/level`.
199. `/leaderboard` - Show the server's experience/level leaderboard.
200. `/vote` - Provide links to vote for the bot on bot lists (if applicable).
201. `/serverstats` - Display graphs of server activity (messages, joins, etc.).
202. `/userhistory [user]` - Show a summary of a user's activity/moderation history (requires logging).
203. `/modstats [moderator]` - Show moderation action statistics for a specific moderator.
204. `/slowpoll <question> | <option1>...` - A poll where results are hidden until it ends.
205. `/anonymouspoll <question> | <option1>...` - A poll where votes are anonymous.
206. `/advancedpoll` - Create polls with multiple choices, time limits, role restrictions.
207. `/tempban [user] [duration] [reason]` - Temporarily ban a user.
208. `/tempmute [user] [duration] [reason]` - Temporarily mute a user.
209. `/note [user] <message>` - Add a private moderation note about a user.
210. `/notes [user]` - View moderation notes for a user.
211. `/delnote [note_id]` - Delete a specific moderation note.
212. `/case [case_id]` - View details of a specific moderation case.
213. `/cases [user]` - List all moderation cases involving a user.
214. `/voicemute [user] [reason]` - Server mute a user in voice channels.
215. `/voiceunmute [user]` - Unmute a user in voice channels.
216. `/voicedeafen [user] [reason]` - Server deafen a user in voice channels.
217. `/voiceundeafen [user]` - Undeafen a user in voice channels.
218. `/reactionrole [add|remove|list] [message_id] [emoji] [role]` - Set up reaction roles.
219. `/buttonrole [add|remove|list] [message_id] [button_label] [role]` - Set up roles assigned via buttons.
220. `/selfrole [add|remove|list] [role_name]` - Allow users to assign specific roles to themselves.
221. `/timezone [set|view] [timezone_name]` - Set or view your personal timezone for bot features.
222. `/worldclock` - Display the time in several configured timezones.
223. `/currencyconvert <amount> <from_currency> <to_currency>` - Convert between world currencies using live rates.
224. `/weatherforecast [location] [days]` - Get a multi-day weather forecast.
225. `/airquality [location]` - Get the Air Quality Index (AQI) for a location.
226. `/cryptograph [symbol] [range]` - Show a price graph for a cryptocurrency.
227. `/stockgraph [symbol] [range]` - Show a price graph for a stock.
228. `/news [category]` - Fetch recent news headlines (optionally by category).
229. `/reddit [subreddit] [sort_by]` - Browse posts from a specific subreddit.
230. `/stackoverflow [query]` - Search Stack Overflow for programming questions.
231. `/imdb [query]` - Search IMDb for movies, shows, actors.
232. `/steamprofile [user_id_or_name]` - Show a Steam user's profile summary.
233. `/steamgame [game_name]` - Show details about a game on Steam (price, reviews, etc.).
234. `/twitch [streamer_name]` - Check if a Twitch streamer is live and show stream info.
235. `/spotify [user]` - Show what a user is listening to on Spotify (requires connection & presence).
236. `/lyrics [song_name]` - Fetch lyrics for a song.
237. `/githubuser [username]` - Show information about a GitHub user.
238. `/githubrepo [owner/repo]` - Show information about a GitHub repository.
239. `/pypi [package_name]` - Show information about a Python package from PyPI.
240. `/npm [package_name]` - Show information about an NPM package.
241. `/urbandefine [term]` - Alias for `/urban`.
242. `/xkcd [number]` - Fetch a specific or random XKCD comic.
243. `/advice` - Get a random piece of advice slip.
244. `/fortune` - Get a fortune cookie message.
245. `/numberfact [number]` - Get a trivia fact about a specific number.
246. `/yearfact [year]` - Get a trivia fact about a specific year.
247. `/catfact` - Get a random fact about cats.
248. `/dogfact` - Get a random fact about dogs.
249. `/pandafact` - Get a random fact about pandas.
250. `/birdfact` - Get a random fact about birds.
251. `/image search [query]` - Search for images online (e.g., Google Images, DuckDuckGo).
252. `/gif search [query]` - Search for GIFs online (e.g., Tenor, Giphy).
253. `/avatarhistory [user]` - Show previous avatars of a user (if logged).
254. `/namehistory [user]` - Show previous usernames of a user (if logged).
255. `/status [set|clear] <message>` - Set a custom status message for the bot (temporary).
256. `/birthday [set|view|list] [user] [date]` - Store and view user birthdays.
257. `/nextbirthday` - Show whose birthday is coming up next.
258. `/todayinhiistory` - Show significant events that happened on this date.
259. `/onthisday` - Alias for `/todayinhistory`.
260. `/distance <place1> <place2>` - Calculate the distance between two locations.
261. `/maps [location]` - Show a map of a location.
262. `/isslocation` - Show the current location of the International Space Station.
263. `/astronauts` - List the astronauts currently in space.
264. `/apod` - Fetch NASA's Astronomy Picture of the Day.
265. `/epic` - Fetch recent images from NASA's EPIC camera.
266. `/launchschedule` - Show upcoming space launch schedules.
267. `/tictactoe [user]` - Start a game of Tic-Tac-Toe.
268. `/connect4 [user]` - Start a game of Connect Four.
269. `/hangman` - Start a game of Hangman.
270. `/chess [user]` - Start a game of Chess (complex).
271. `/trivia [category] [difficulty]` - Start a trivia game.
272. `/leaderboard trivia` - Show the trivia high scores.
273. `/minesweeper [size] [bombs]` - Generate a Minesweeper board.
274. `/sudoku` - Generate a Sudoku puzzle.
275. `/akinator` - Play a game of Akinator (requires API/library).
276. `/wyr interactive` - Start an interactive Would You Rather session.
277. `/wordle` - Play a Wordle-like game.
278. `/scramble` - Unscramble a given word.
279. `/fasttype` - Test your typing speed.
280. `/memorygame` - Play a simple card matching memory game.
281. `/fish` - Go fishing (part of an economy system?).
282. `/hunt` - Go hunting (part of an economy system?).
283. `/work` - Earn currency (part of an economy system).
284. `/balance [user]` - Check your or someone's virtual currency balance.
285. `/pay [user] <amount>` - Transfer virtual currency to another user.
286. `/leaderboard economy` - Show the richest users.
287. `/shop [list|buy|sell] [item]` - Interact with an item shop (economy).
288. `/inventory` - View your purchased items (economy).
289. `/daily` - Claim a daily currency reward.
290. `/weekly` - Claim a weekly currency reward.
291. `/gamble <amount>` - Gamble virtual currency (e.g., coinflip, slots).
292. `/slots <bet>` - Play a slot machine game.
293. `/roulette <bet> <on_what>` - Play roulette.
294. `/blackjack <bet>` - Play Blackjack against the bot.
295. `/profile [user]` - Show a user's customizable profile (level, balance, badges, etc.).
296. `/setbio <text>` - Set your description on your profile.
297. `/setcolor <hex_color>` - Set the embed color for your profile.
298. `/setbackground <image_url>` - Set a background image for your profile.
299. `/badges [list|equip] [badge_name]` - View or equip profile badges.
300. `/rep [user]` - Give a reputation point to a user.
301. `/reputation [user]` - Check a user's reputation score.
302. `/leaderboard reputation` - Show users with the highest reputation.
303. `/marry [user]` - Propose marriage to another user (fun command).
304. `/divorce` - Divorce your married partner.
305. `/family` - View your married partner/family.
306. `/adopt [user]` - Adopt another user (fun command).
307. `/abandon [user]` - Abandon an adopted user.
308. `/hug [user]` - Send a hug GIF/message.
309. `/pat [user]` - Send a pat GIF/message.
310. `/slap [user]` - Send a slap GIF/message.
311. `/kiss [user]` - Send a kiss GIF/message.
312. `/cuddle [user]` - Send a cuddle GIF/message.
313. `/poke [user]` - Send a poke GIF/message.
314. `/highfive [user]` - Send a high-five GIF/message.
315. `/wave [user]` - Send a wave GIF/message.
316. `/boop [user]` - Send a boop GIF/message.
317. `/meme template [name] <text1> | <text2>...` - Generate a meme using a known template.
318. `/imagememe [image_url] <top_text> | <bottom_text>` - Add text to an image URL.
319. `/deepfry [image_or_user]` - Apply a deep-fry effect to an image.
320. `/swirl [image_or_user]` - Apply a swirl effect.
321. `/magik [image_or_user]` - Apply a content-aware scaling (magik) effect.
322. `/edge detect [image_or_user]` - Apply edge detection filter.
323. `/charcoal [image_or_user]` - Apply a charcoal sketch filter.
324. `/oilpaint [image_or_user]` - Apply an oil painting filter.
325. `/blurple [image_or_user]` - Apply a Discord blurple color filter.
326. `/yt comment [user] <comment_text>` - Generate a fake YouTube comment image.
327. `/tweet [user] <tweet_text>` - Generate a fake Tweet image.
328. `/achievement get <text>` - Generate a Minecraft achievement image.
329. `/challenger [user]` - Generate a "A New Challenger Approaches" image.
330. `/changemymind <text>` - Generate a "Change My Mind" meme.
331. `/drake <text1> | <text2>` - Generate the Drake meme.
332. `/lisapresentation <text>` - Generate the Lisa Simpson presentation meme.
333. `/phub comment [user] <comment>` - Generate a fake PornHub comment.
334. `/captcha [user]` - Generate a fake Google Captcha image.
335. `/circle [image_or_user]` - Crop an image into a circle.
336. `/speechbubble [image_or_user]` - Add a speech bubble overlay.
337. `/rainbow [image_or_user]` - Apply a rainbow overlay.
338. `/approved [image_or_user]` - Apply an "Approved" stamp overlay.
339. `/rejected [image_or_user]` - Apply a "Rejected" stamp overlay.
340. `/rotate [degrees] [image_or_user]` - Rotate an image.
341. `/flip horizontal [image_or_user]` - Flip an image horizontally.
342. `/flip vertical [image_or_user]` - Flip an image vertically.
343. `/resize <width> <height> [image_or_user]` - Resize an image.
344. `/spotify card [user]` - Generate a card showing Spotify activity.
345. `/level card [user]` - Generate a rank/level card image.
346. `/welcome card [user]` - Generate a welcome banner image for a user.
347. `/leave card [user]` - Generate a goodbye banner image for a user.
348. `/role sync [role_from] [role_to]` - Give role B to everyone who has role A.
349. `/channel clone [channel] [new_name]` - Clone a channel's permissions and settings.
350. `/permissions view [role_or_user] [channel]` - Show a detailed breakdown of permissions.
351. `/permission check [user] <permission_name>` - Check if a user has a specific Discord permission.
352. `/setlevel [user] <level>` - Manually set a user's level (admin command).
353. `/setxp [user] <xp>` - Manually set a user's experience points (admin command).
354. `/addxp [user] <amount>` - Give XP to a user (admin command).
355. `/removexp [user] <amount>` - Remove XP from a user (admin command).
356. `/setbalance [user] <amount>` - Set a user's currency balance (admin command).
357. `/addbalance [user] <amount>` - Give currency to a user (admin command).
358. `/removebalance [user] <amount>` - Remove currency from a user (admin command).
359. `/resetlevel [user]` - Reset a user's level and XP.
360. `/reseteconomy [user]` - Reset a user's balance and inventory.
361. `/settings [view|set] <module> <setting> [value]` - Configure bot module settings.
362. `/logchannel [type] [channel]` - Set specific channels for different log types (joins, leaves, edits, moderation).
363. `/welcomeconfig [channel|message|embed|image]` - Configure welcome messages.
364. `/leaveconfig [channel|message|embed|image]` - Configure leave messages.
365. `/levelconfig [channel|message|roles|ignored_channels]` - Configure the leveling system.
366. `/economyconfig [currency_symbol|daily_amount|work_range]` - Configure the economy system.
367. `/modconfig [mute_role|mod_roles|admin_roles]` - Configure moderation settings.
368. `/automod [enable|disable|config] <feature>` - Configure built-in automod features (spam, links, invites, bad words).
369. `/badwords [add|remove|list] <word>` - Manage the list of filtered words for automod.
370. `/allowedlinks [add|remove|list] <domain>` - Manage domains allowed by automod.
371. `/messageembed <channel> <json_or_builder>` - Send a custom embed message using JSON or a builder interface.
372. `/editmessage <message_id> <new_content>` - Edit a message sent by the bot.
373. `/deletemessage <message_id>` - Delete a message sent by the bot.
374. `/webhook create [channel] [name] [avatar_url]` - Create a webhook in a channel.
375. `/webhook edit [webhook_id_or_url] [name|avatar]` - Edit a webhook's name or avatar.
376. `/webhook delete [webhook_id_or_url]` - Delete a webhook.
377. `/webhook list [channel]` - List webhooks in a channel.
378. `/webhook sendraw [url] <json_payload>` - Send a raw JSON payload via webhook.
379. `/schedule message <cron_or_time> <channel> <message>` - Schedule a message to be sent.
380. `/schedule list` - List scheduled tasks.
381. `/schedule delete [task_id]` - Delete a scheduled task.
382. `/rss feed [add|remove|list] <url> [channel]` - Add RSS feeds to post updates in a channel.
383. `/twitter feed [add|remove|list] <username> [channel]` - Add Twitter feeds.
384. `/youtube feed [add|remove|list] <channel_id> [channel]` - Add YouTube channel upload feeds.
385. `/twitch feed [add|remove|list] <username> [channel]` - Add Twitch live notifications.
386. `/stream feed [add|remove|list] <service> <id> [channel]` - General purpose streaming notifications.
387. `/autopublish [channel] [enable|disable]` - Automatically publish messages in announcement channels.
388. `/autoresponse [add|remove|list] <trigger> <response>` - Set up automatic responses to certain words/phrases.
389. `/role persist [user] [role]` - Reapply a role if a user rejoins (requires database).
390. `/sticky message [channel] [set|clear] <message>` - Keep a message pinned to the bottom of a channel.
391. `/clearchannel [channel]` - Delete all messages in a channel (alternative to nuke).
392. `/clonepermissions [from_channel] [to_channel]` - Copy permission overwrites from one channel to another.
393. `/rolerequest [role] [reason]` - Allow users to request a role that requires approval.
394. `/approverole [request_id_or_user]` - Approve a role request.
395. `/denyrole [request_id_or_user] [reason]` - Deny a role request.
396. `/listrole requests` - List pending role requests.
397. `/vanityurl` - Show the server's custom vanity invite URL (if any).
398. `/setvanityurl <code S>` - Set the server's vanity URL (requires boost level 3).
399. `/community enable` - Enable community server features.
400. `/community disable` - Disable community server features.
401. `/server template [create|view]` - Create or view the server template code.
402. `/apply template <code>` - Apply a server template (highly destructive).
403. `/widget [enable|disable|view]` - Configure the server widget.
404. `/discovery [enable|disable]` - Enable/disable server discovery listing (if eligible).
405. `/partnership application [view|submit]` - Manage partnership applications (if bot supports).
406. `/ticket create [reason]` - Create a support ticket (opens a private channel).
407. `/ticket close [reason]` - Close the current support ticket channel.
408. `/ticket adduser [user]` - Add a user to the current ticket channel.
409. `/ticket removeuser [user]` - Remove a user from the current ticket channel.
410. `/ticket transcript` - Save a transcript of the ticket channel.
411. `/ticket claim` - Allow staff to claim a ticket.
412. `/ticket unclaim` - Unclaim a ticket.
413. `/ticket setup [category] [support_role] [log_channel]` - Configure the ticket system.
414. `/starboard setup [channel] [threshold]` - Configure a starboard channel.
415. `/starboard config [emoji|ignore_channels|blacklist]` - Configure starboard settings.
416. `/starboard info [message_id]` - Show starboard info for a message.
417. `/starboard top [count]` - Show top starred messages.
418. `/archive channel [channel]` - Archive messages from a channel to a file.
419. `/import archive [file]` - Import messages from an archive file (difficult/risky).
420. `/massban [user_ids...] [reason]` - Ban multiple users by ID.
421. `/masskick [users...] [reason]` - Kick multiple users.
422. `/findduplicates [role|permission]` - Find users with duplicate roles or permissions.
423. `/voicelog [enable|disable|channel]` - Log voice channel join/leave events.
424. `/messagelog [enable|disable|channel]` - Log edited/deleted messages.
425. `/memberlog [enable|disable|channel]` - Log member join/leave/update events.
426. `/serverlog [enable|disable|channel]` - Log server setting changes.
427. `/rolelog [enable|disable|channel]` - Log role creation/deletion/update events.
428. `/channellog [enable|disable|channel]` - Log channel creation/deletion/update events.
429. `/threadlog [enable|disable|channel]` - Log thread creation/deletion/update events.
430. `/snipe reactions [message_id]` - Show recently removed reactions (optional).
431. `/snipe pins [channel]` - Show recently unpinned messages (optional).
432. `/afk list` - Show users who are currently marked as AFK.
433. `/afk clear [user]` - Manually remove a user's AFK status.
434. `/away` - Alias for `/afk`.
435. `/timezone list` - List available timezones for `/timezone set`.
436. `/unit list` - List available units for `/convert`.
437. `/currency list` - List available currencies for `/currencyconvert`.
438. `/github status` - Check the status of GitHub services.
439. `/discord status` - Check the status of Discord services.
440. `/twitter status` - Check the status of Twitter services.
441. `/reddit status` - Check the status of Reddit services.
442. `/cloudflare status` - Check the status of Cloudflare services.
443. `/http status <code>` - Get information about an HTTP status code.
444. `/minecraft server [ip_address]` - Check the status of a Minecraft server.
445. `/minecraft user [username]` - Get information about a Minecraft user (UUID, skin).
446. `/roblox user [username]` - Get information about a Roblox user.
447. `/roblox game [game_id]` - Get information about a Roblox game.
448. `/leagueoflegends player [summoner_name] [region]` - Get League of Legends player stats.
449. `/valorant player [riot_id] [tagline]` - Get Valorant player stats.
450. `/overwatch player [battletag]` - Get Overwatch player stats.
451. `/fortnite player [epic_username]` - Get Fortnite player stats.
452. `/csgo player [steam_id]` - Get CS:GO player stats.
453. `/apexlegends player [username] [platform]` - Get Apex Legends player stats.
454. `/genshinimpact uid [uid]` - Get Genshin Impact player stats via UID.
455. `/ipinfo [ip_address]` - Get geolocation and ISP information for an IP address.
456. `/domaininfo [domain]` - Get registration and DNS info for a domain.
457. `/portscan [ip_address] [ports]` - Scan common ports on an IP address (use responsibly).
458. `/reverseip [ip_address]` - Find domains hosted on a shared IP address.
459. `/subdomainfinder [domain]` - Find subdomains for a given domain.
460. `/urlscan [url]` - Scan a URL for malware/phishing (using external service).
461. `/phonenumberinfo [number]` - Look up information about a phone number (carrier, location - privacy risk).
462. `/emailvalidator [email]` - Check if an email address format is valid (doesn't guarantee existence).
463. `/passwordstrength <password>` - Check the estimated strength of a password.
464. `/haveibeenpwned [email_or_username]` - Check if an email/username has been in known data breaches.
465. `/safetycheck` - Run a series of security/privacy checks on server settings.
466. `/namemc [username]` - Search NameMC for Minecraft username availability/history.
467. `/hypixel player [username]` - Get Hypixel player stats.
468. `/covid [country_or_global]` - Get COVID-19 statistics.
469. `/poll end [message_id]` - Manually end an active poll.
470. `/poll results [message_id]` - Show the results of a ended poll.
471. `/giveaway reroll [message_id]` - Reroll winners for a giveaway.
472. `/giveaway end [message_id]` - Manually end a giveaway.
473. `/giveaway list` - List active giveaways in the server.
474. `/giveaway winners [message_id]` - List the winners of a giveaway.
475. `/tag view [name]` - View the content of a tag.
476. `/tag edit [name] <new_content>` - Edit an existing tag.
477. `/tag delete [name]` - Delete a tag.
478. `/tag list` - List all available tags.
479. `/tag owner [name]` - Show who created a tag.
480. `/tag info [name]` - Show usage stats for a tag.
481. `/tag search <query>` - Search for tags by name or content.
482. `/tag raw [name]` - View the raw markdown content of a tag.
483. `/tag transfer [name] [new_owner]` - Transfer ownership of a tag.
484. `/timer list` - List your active timers.
485. `/timer delete [id]` - Delete an active timer.
486. `/stopwatch start` - Start a stopwatch.
487. `/stopwatch stop` - Stop the stopwatch and show elapsed time.
488. `/stopwatch lap` - Record a lap time on the stopwatch.
489. `/pomodoro start [work_minutes] [break_minutes]` - Start a Pomodoro timer.
490. `/pomodoro stop` - Stop the current Pomodoro session.
491. `/serverbackup auto [enable|disable] [frequency]` - Set up automatic server backups.
492. `/serverbackup list` - List available server backups.
493. `/serverbackup restore [id]` - Restore a specific server backup (very dangerous!).
494. `/serverdiff [backup_id_1] [backup_id_2]` - Show differences between two backups.
495. `/channelpermissions [channel]` - Show all role/user permission overwrites for a channel.
496. `/rolepermissions [role]` - Show all permissions granted by a specific role.
497. `/userpermissions [user]` - Show all calculated permissions for a user in the server.
498. `/debug command <command_name>` - Get debug info for a slash command.
499. `/debug permissions [user]` - Get detailed permission calculation breakdown for a user.
500. `/debug latency` - Show detailed latency breakdown (websocket, API, processing).
501. `/echo <channel> <message>` - Make the bot send a message to a specific channel.
502. `/react <message_id> <emoji>` - Make the bot react to a message.
503. `/unreact <message_id> <emoji>` - Make the bot remove a reaction.
504. `/dm [user] <message>` - Send a direct message to a user via the bot.
505. `/sudo [user] <command>` - Make the bot run a command as if initiated by another user (highly dangerous admin command).
506. `/eval <code>` - Evaluate Python code (extremely dangerous admin command).
507. `/exec <shell_command>` - Execute a shell command (extremely dangerous admin command).
508. `/sql <query>` - Execute a SQL query on the bot's database (dangerous admin command).
509. `/restart` - Restart the bot process (admin command).
510. `/shutdown` - Shut down the bot process (admin command).
511. `/update` - Pull the latest code from git and restart (admin command).
512. `/reload cog <cog_name>` - Reload a specific cog.
513. `/unload cog <cog_name>` - Unload a specific cog.
514. `/load cog <cog_name>` - Load a specific cog.
515. `/cogs list` - List all loaded cogs.
516. `/invitegen [uses] [duration] [temporary]` - Generate a custom server invite.
517. `/cleaninvites` - Prune expired or unused server invites.
518. `/roleinfo detailed [role]` - Show every single permission for a role.
519. `/serverinfo detailed` - Show extremely detailed server info (all features, limits, etc.).
520. `/userinfo detailed [user]` - Show very detailed user info (flags, mutual servers/friends if possible).
521. `/stealstickerpack [message_link]` - Add all stickers from a message to the server.
522. `/emojipack [create|add|remove|view] <pack_name>` - Manage packs of emojis.
523. `/stickerpack [create|add|remove|view] <pack_name>` - Manage packs of stickers.
524. `/create privatechannel [name] [users...]` - Create a private channel with specific users.
525. `/create category [name]` - Create a new channel category.
526. `/move channel [channel] [category]` - Move a channel to a different category.
527. `/syncpermissions [category]` - Sync all channels in a category to its permissions.
528. `/lockdown server [reason]` - Lock most channels in the server during an emergency.
529. `/unlockdown server` - Lift a server lockdown.
530. `/raidmode [enable|disable|auto]` - Automatically lock down or take action during suspected raids.
531. `/antispam config [threshold] [action]` - Configure anti-spam measures.
532. `/antilink config [allow_roles] [action]` - Configure anti-link measures.
533. `/antiinvite config [action]` - Configure anti-invite link measures.
534. `/massnick <text>` - Change the nickname of all (or selected) members.
535. `/massroleremove [role]` - Remove a specific role from all members who have it.
536. `/archive user [user]` - Archive all messages from a specific user.
537. `/report [user] [reason] [message_link]` - Report a user to server moderators.
538. `/modmail [message]` - Send a message to the server moderators anonymously or directly.
539. `/anonmessage [channel] <message>` - Send a message anonymously through the bot (risky).
540. `/confess <message>` - Submit an anonymous confession (if configured).
541. `/ask [question]` - Ask a question anonymously (if configured).
542. `/dashboard` - Link to the bot's web dashboard (if available).
543. `/premium info` - Show information about bot premium features (if any).
544. `/premium activate <code>` - Activate a premium code.
545. `/premium status` - Check your server's or user's premium status.
546. `/support` - Link to the bot's support server or contact info.
547. `/docs` - Link to the bot's documentation.
548. `/privacy` - Link to the bot's privacy policy.
549. `/terms` - Link to the bot's terms of service.
550. `/ping graph` - Show a graph of recent websocket ping times.
551. `/shards` - List all bot shards and their status/latency.
552. `/memory usage` - Show detailed memory usage (RSS, VMS, Heap).
553. `/cpu usage` - Show detailed CPU usage per core/process.
554. `/disk usage` - Show detailed disk usage per partition.
555. `/network stats` - Show network usage statistics.
556. `/guild list` - List all servers the bot is in (owner only).
557. `/guild leave <guild_id>` - Make the bot leave a server (owner only).
558. `/guild info <guild_id>` - Get info about a server the bot is in (owner only).
559. `/broadcast <message>` - Send a message to a configured channel in all servers (owner only).
560. `/maintenance [enable|disable] [message]` - Put the bot into maintenance mode (owner only).
561. `/blacklist add [user_id] [reason]` - Prevent a user from using the bot (owner only).
562. `/blacklist remove [user_id]` - Remove a user from the blacklist (owner only).
563. `/blacklist list` - List blacklisted users (owner only).
564. `/serverblacklist add [guild_id] [reason]` - Prevent the bot from being used in a server (owner only).
565. `/serverblacklist remove [guild_id]` - Remove a server from the blacklist (owner only).
566. `/serverblacklist list` - List blacklisted servers (owner only).
567. `/command stats [command_name]` - Show usage statistics for a specific command.
568. `/command list [sort_by_usage]` - List all commands, optionally sorted by usage.
569. `/error log [count]` - Show recent errors logged by the bot (owner/admin).
570. `/clear errorlog` - Clear the bot's error log.
571. `/usersearch <query>` - Search for users across all servers the bot is in (owner only).
572. `/global messagecount [user]` - Show a user's total message count across mutual servers (privacy concern).
573. `/api latency [endpoint]` - Measure latency to specific Discord API endpoints.
574. `/api status` - Check Discord API status directly.
575. `/voice region` - Show the current voice server region for your channel.
576. `/voice regions list` - List available voice regions.
577. `/voice bitrate [channel]` - Show the current bitrate of a voice channel.
578. `/voice userlimit [channel]` - Show the user limit for a voice channel.
579. `/set voicebitrate [channel] <bitrate>` - Set the bitrate for a voice channel.
580. `/set userlimit [channel] <limit>` - Set the user limit for a voice channel.
581. `/create stage [name] [topic]` - Create a Stage channel.
582. `/stage start [message]` - Start the event in the current Stage channel.
583. `/stage end` - End the event in the current Stage channel.
584. `/stage speakers [add|remove] [user]` - Manage speakers in a Stage channel.
585. `/stage audience [move] [user]` - Move a user from audience to speaker (or vice versa).
586. `/event create <name> <description> <channel> <start_time> [end_time]` - Create a scheduled server event.
587. `/event list` - List upcoming scheduled server events.
588. `/event info <event_id>` - Show details about a scheduled event.
589. `/event start <event_id>` - Manually start a scheduled event.
590. `/event cancel <event_id>` - Cancel a scheduled event.
591. `/event subscribers <event_id>` - List users interested in an event.
592. `/welcometest` - Simulate a member joining to test welcome messages.
593. `/leavetest` - Simulate a member leaving to test leave messages.
594. `/boosttest` - Simulate a server boost to test boost messages.
595. `/commandtest <command_string>` - Test running a command via the bot's parser.
596. `/permissiontest [user] [channel] <permission>` - Test if a user has a specific permission in context.
597. `/font <font_name> <text>` - Generate text using a specific font (requires font files).
598. `/texttomorse <text>` - Convert text to morse code audio/dots and dashes.
599. `/texttospeech <text> [language]` - Generate speech audio from text.
600. `/speachtotext [audio_file]` - Transcribe speech from an audio file.
601. `/music play <query_or_url>` - Play music in a voice channel.
602. `/music queue [view|add] <query_or_url>` - View or add to the music queue.
603. `/music skip` - Skip the current song.
604. `/music stop` - Stop playing music and clear the queue.
605. `/music leave` - Disconnect the bot from the voice channel.
606. `/music join` - Make the bot join your voice channel.
607. `/music volume <level>` - Set the music playback volume.
608. `/music nowplaying` - Show the currently playing song.
609. `/music lyrics [song_name]` - Get lyrics for the current or specified song.
610. `/music shuffle` - Shuffle the music queue.
611. `/music loop [off|song|queue]` - Set the loop mode.
612. `/music remove <index_or_title>` - Remove a song from the queue.
613. `/music clearqueue` - Clear the entire music queue.
614. `/music seek <timestamp>` - Seek to a specific time in the current song.
615. `/music pause` - Pause music playback.
616. `/music resume` - Resume music playback.
617. `/music skipto <index>` - Skip to a specific song in the queue.
618. `/music jump <index>` - Alias for `/music skipto`.
619. `/music move <from_index> <to_index>` - Move a song within the queue.
620. `/music playlist [create|delete|add|remove|load|list] <name> [song]` - Manage saved playlists.
621. `/music search <query>` - Search YouTube/SoundCloud for music.
622. `/music soundcloud <query>` - Specifically search SoundCloud.
623. `/music spotify <playlist_or_song_url>` - Load a Spotify playlist or song.
624. `/music effects [bassboost|nightcore|vaporwave|...]` - Apply audio effects.
625. `/music radio [station_name]` - Play an internet radio station.
626. `/music request <song>` - Request a song to be added (if DJ system is enabled).
627. `/music dj [add|remove] [role_or_user]` - Manage DJ roles for music commands.
628. `/music settings [autoplay|announce_songs|vote_skip]` - Configure music module settings.
629. `/music forceskip` - Force skip the current song (DJ/Admin only).
630. `/music repeat` - Alias for `/music loop`.
631. `/antiraid config [threshold_joins] [threshold_accounts] [action]` - Configure anti-raid parameters.
632. `/lockdown addchannel [channel]` - Add a channel to be affected by `/lockdown server`.
633. `/lockdown removechannel [channel]` - Remove a channel from the lockdown list.
634. `/lockdown listchannels` - List channels affected by lockdown.
635. `/wordcloud [channel] [user] [limit]` - Generate a word cloud from recent messages.
636. `/sentiment [channel] [user] [limit]` - Analyze the sentiment of recent messages.
637. `/translate message <message_id> [language]` - Translate a specific message.
638. `/autotranslate [channel] [language] [enable|disable]` - Automatically translate messages in a channel.
639. `/ocr [image_url_or_upload]` - Extract text from an image using OCR.
640. `/summarize [text_or_url]` - Summarize a long piece of text or a webpage.
641. `/pdf tools [merge|split|compress] [files]` - Perform actions on PDF files.
642. `/image tools [convert|resize|watermark] [image] [options]` - Perform actions on image files.
643. `/video tools [convert|trim|gif] [video] [options]` - Perform actions on video files.
644. `/audio tools [convert|trim|volume] [audio] [options]` - Perform actions on audio files.
645. `/archive web <url>` - Create a web archive (e.g., archive.org) of a URL.
646. `/screenshot <url>` - Take a screenshot of a webpage.
647. `/remind list [all|channel|user]` - List reminders with filters.
648. `/remind delete all` - Delete all your pending reminders.
649. `/remind snooze [id] <duration>` - Snooze a reminder.
650. `/remind edit [id] <new_time> <new_message>` - Edit an existing reminder.
651. `/poll create advanced` - Start an interactive poll creation wizard.
652. `/giveaway create advanced` - Start an interactive giveaway creation wizard.
653. `/reactionrole create advanced` - Start an interactive reaction role setup wizard.
654. `/embed create advanced` - Use an interactive embed builder.
655. `/customcommand create <name> <action_script>` - Create custom commands via script (dangerous).
656. `/customcommand delete <name>` - Delete a custom command.
657. `/customcommand list` - List custom commands.
658. `/customcommand run <name> [args...]` - Run a custom command.
659. `/permission group [create|delete|add|remove|list] <group_name> [role|user]` - Manage permission groups for bot commands.
660. `/permission set <command_name> <group_or_role_or_user> [allow|deny]` - Set permissions for specific bot commands.
661. `/permission view <command_name>` - View who can run a specific bot command.
662. `/userreport list [status]` - List user reports submitted via `/report`.
663. `/userreport view <report_id>` - View details of a specific user report.
664. `/userreport action [report_id] <action_taken>` - Mark a report as actioned.
665. `/userreport reject [report_id] [reason]` - Reject/close a user report.
666. `/suggest list [status]` - List suggestions.
667. `/suggest view <suggestion_id>` - View a suggestion.
668. `/suggest approve <suggestion_id>` - Mark a suggestion as approved.
669. `/suggest implement <suggestion_id>` - Mark a suggestion as implemented.
670. `/suggest reject <suggestion_id> [reason]` - Reject a suggestion.
671. `/suggest comment <suggestion_id> <comment>` - Add a comment to a suggestion.
672. `/bugreport list [status]` - List bug reports.
673. `/bugreport view <bug_id>` - View a bug report.
674. `/bugreport assign <bug_id> [user]` - Assign a bug report to someone.
675. `/bugreport resolve <bug_id>` - Mark a bug report as resolved.
676. `/bugreport close <bug_id> [reason]` - Close a bug report (e.g., duplicate, won't fix).
677. `/apply staff [position]` - Start a staff application process.
678. `/application list [position] [status]` - List staff applications.
679. `/application view <app_id>` - View a staff application.
680. `/application accept <app_id>` - Accept a staff application.
681. `/application reject <app_id> [reason]` - Reject a staff application.
682. `/leavemessage test` - Test the leave message configuration.
683. `/boostmessage test` - Test the server boost message configuration.
684. `/autorole test` - Test the autorole configuration.
685. `/automod test <message_content>` - Test the automod filter with sample text.
686. `/purge user [user] [channel] [limit]` - Purge messages from a specific user.
687. `/purge bots [channel] [limit]` - Purge messages sent by bots.
688. `/purge links [channel] [limit]` - Purge messages containing links.
689. `/purge invites [channel] [limit]` - Purge messages containing Discord invites.
690. `/purge embeds [channel] [limit]` - Purge messages containing embeds.
691. `/purge attachments [channel] [limit]` - Purge messages containing attachments.
692. `/purge reactions [channel] [limit]` - Purge all reactions in a channel.
693. `/purge text <text_to_match> [channel] [limit]` - Purge messages containing specific text.
694. `/purge before <message_id> [channel]` - Purge messages before a specific message.
695. `/purge after <message_id> [channel]` - Purge messages after a specific message.
696. `/purge between <start_message_id> <end_message_id> [channel]` - Purge messages between two messages.
697. `/prune members [days] [role]` - Prune inactive members (dangerous!).
698. `/prune check [days] [role]` - Check how many members would be pruned.
699. `/slowmode view [channel]` - View the current slowmode setting for a channel.
700. `/role members [role]` - Paginated list of members with a role.
701. `/role mentionable [role] [toggle]` - Toggle mentionable state for a role.
702. `/role hoist [role] [toggle]` - Toggle hoisted state for a role.
703. `/role color [role] <hex_color>` - Set the color for a role.
704. `/role name [role] <new_name>` - Rename a role.
705. `/role icon [role] <emoji_or_image>` - Set a custom icon for a role (boosted servers).
706. `/role createadvanced` - Interactive role creation wizard.
707. `/channel create text [name] [category] [topic]` - Create a text channel.
708. `/channel create voice [name] [category] [bitrate] [user_limit]` - Create a voice channel.
709. `/channel delete [channel]` - Delete a channel.
710. `/channel move [channel] <position>` - Change the position of a channel in the list.
711. `/channel topic [channel] <new_topic>` - Set the topic for a text channel.
712. `/channel bitrate [channel] <bitrate>` - Set the bitrate for a voice channel.
713. `/channel userlimit [channel] <limit>` - Set the user limit for a voice channel.
714. `/channel nsfw [channel] [toggle]` - Toggle NSFW status for a channel.
715. `/channel overwrites [channel] [role_or_user] [allow|deny|reset] [permissions...]` - Manage permission overwrites.
716. `/category create [name]` - Create a channel category.
717. `/category delete [category]` - Delete a category (and potentially its channels).
718. `/category move [category] <position>` - Change the position of a category.
719. `/category name [category] <new_name>` - Rename a category.
720. `/category permissions [category] [role_or_user] [allow|deny|reset] [permissions...]` - Manage category permissions.
721. `/emoji create <name> <image_url_or_upload>` - Create a custom server emoji.
722. `/emoji delete <emoji>` - Delete a custom emoji.
723. `/emoji rename <emoji> <new_name>` - Rename a custom emoji.
724. `/emoji list [animated|static]` - List server emojis.
725. `/emoji info <emoji>` - Show info about a custom emoji (creator, ID, URL).
726. `/sticker create <name> <description> <emoji> <image_upload>` - Create a custom server sticker.
727. `/sticker delete <sticker>` - Delete a custom sticker.
728. `/sticker rename <sticker> <new_name>` - Rename a custom sticker.
729. `/sticker description <sticker> <new_description>` - Change a sticker's description.
730. `/sticker emoji <sticker> <new_emoji>` - Change a sticker's related emoji.
731. `/sticker list` - List server stickers.
732. `/sticker info <sticker>` - Show info about a custom sticker.
733. `/thread create public <message_or_channel> <name> [duration]` - Create a public thread.
734. `/thread create private <channel> <name> [duration] [invite_users...]` - Create a private thread.
735. `/thread join <thread>` - Join a thread.
736. `/thread leave <thread>` - Leave a thread.
737. `/thread adduser <thread> <user>` - Add a user to a thread.
738. `/thread removeuser <thread> <user>` - Remove a user from a thread.
739. `/thread name <thread> <new_name>` - Rename a thread.
740. `/thread archive <thread>` - Archive a thread.
741. `/thread unarchive <thread>` - Unarchive a thread.
742. `/thread lock <thread>` - Lock a thread (prevent non-mods from messaging).
743. `/thread unlock <thread>` - Unlock a thread.
744. `/thread slowmode <thread> <seconds>` - Set slowmode for a thread.
745. `/thread list [active|archived]` - List threads in the current channel or server.
746. `/forum create <name> [topic] [tags...]` - Create a forum channel.
747. `/forum post <forum_channel> <title> <message> [tags...]` - Create a new post in a forum channel.
748. `/forum tags [forum_channel] [add|remove|list] <tag>` - Manage tags for a forum channel.
749. `/forum guidelines [forum_channel] [set|view]` - Set or view guidelines for a forum channel.
750. `/forum defaultreaction [forum_channel] [set|clear] <emoji>` - Set a default reaction for new posts.
751. `/auditlog search <query>` - Search the audit log for specific actions or users.
752. `/webhook message [url] <message_id>` - Get info about a message sent by a webhook.
753. `/invite uses [invite_code]` - Show how many times an invite has been used.
754. `/invite creator [invite_code]` - Show who created an invite.
755. `/mutualfriends [user]` - List friends you share with another user (requires user auth scope).
756. `/connections [user]` - List a user's connected accounts (Spotify, Steam, etc.) (requires user auth).
757. `/appinfo` - Show information about the Discord application the bot is running as.
758. `/oauth2 url [scopes...] [permissions]` - Generate an OAuth2 URL for the bot.
759. `/gateway info` - Show information about the bot's gateway connection.
760. `/ratelimits` - Show current known Discord API rate limit statuses.
761. `/backup messages [channel] [limit]` - Backup messages from a channel to a file.
762. `/restore messages [channel] [file]` - Restore messages from a file (very slow, risky).
763. `/server name <new_name>` - Rename the server.
764. `/server icon <image_url_or_upload>` - Change the server icon.
765. `/server banner <image_url_or_upload>` - Change the server banner.
766. `/server region <region_name>` - Change the server's preferred voice region.
767. `/server verificationlevel <level>` - Change the server's verification level.
768. `/server notificationlevel <level>` - Change the default notification level.
769. `/server afkchannel [channel]` - Set the AFK voice channel.
770. `/server afktimeout <minutes>` - Set the AFK timeout.
771. `/server systemchannel [channel]` - Set the channel for system messages (welcome, boost).
772. `/server systemflags [toggle] [flags...]` - Toggle specific system messages.
773. `/server ruleschannel [channel]` - Set the server's rules channel (for community servers).
774. `/server updateschannel [channel]` - Set the moderator updates channel (for community servers).
775. `/server preferredlocale <locale>` - Set the server's primary language.
776. `/image reverse search [image_url_or_upload]` - Perform a reverse image search (Google, TinEye).
777. `/image caption [image_url_or_upload]` - Attempt to automatically caption an image.
778. `/image identify [image_url_or_upload]` - Attempt to identify objects/landmarks in an image.
779. `/image readtext [image_url_or_upload]` - Alias for `/ocr`.
780. `/image colorpalette [image_url_or_upload]` - Extract the dominant color palette from an image.
781. `/image exif [image_url_or_upload]` - Show EXIF metadata from an image (if present).
782. `/image removebg [image_url_or_upload]` - Attempt to remove the background from an image.
783. `/image compare [image1] [image2]` - Show differences between two images.
784. `/ai draw <prompt>` - Generate an image using AI (Stable Diffusion, DALL-E API).
785. `/ai chat <prompt>` - Chat with an AI language model (GPT, Claude API).
786. `/ai summarize <text_or_url>` - Summarize text using AI.
787. `/ai translate <language> <text>` - Translate text using AI.
788. `/ai correct <text>` - Correct grammar and spelling using AI.
789. `/ai rewrite <text> [style]` - Rewrite text in a different style using AI.
790. `/ai code <language> <prompt>` - Generate code using AI.
791. `/ai explain code <code>` - Explain a piece of code using AI.
792. `/ai story <prompt>` - Generate a short story using AI.
793. `/ai poem <prompt>` - Generate a poem using AI.
794. `/ai lyrics <prompt>` - Generate song lyrics using AI.
795. `/soundboard play <sound_name>` - Play a sound effect in voice channel.
796. `/soundboard list` - List available soundboard sounds.
797. `/soundboard add <name> <audio_file>` - Add a sound to the soundboard.
798. `/soundboard remove <name>` - Remove a sound from the soundboard.
799. `/voicemod play <effect> [user]` - Apply a temporary voice modification effect (requires client mod?).
800. `/remind interval <interval> <message>` - Set a recurring reminder.
801. `/birthday list [month]` - List birthdays in a specific month.
802. `/timeuntil <datetime_string>` - Show the time remaining until a specific date/time.
803. `/timesince <datetime_string>` - Show the time elapsed since a specific date/time.
804. `/countdown <datetime_string> [message]` - Create a message that counts down live.
805. `/movie quotes` - Fetch a random movie quote.
806. `/tv quotes` - Fetch a random TV show quote.
807. `/book quotes` - Fetch a random quote from a book.
808. `/game quotes` - Fetch a random quote from a video game.
809. `/wikipedia random` - Fetch a random Wikipedia article summary.
810. `/reddit random [subreddit]` - Fetch a random post from Reddit (or a specific subreddit).
811. `/steam random game` - Suggest a random game from the Steam store.
812. `/dictionary random` - Fetch a random word and its definition.
813. `/urban random` - Fetch a random Urban Dictionary definition.
814. `/color random name` - Generate a random color with its name.
815. `/advice random` - Alias for `/advice`.
816. `/fact random` - Alias for `/fact`, `/numberfact`, `/catfact`, etc. combined.
817. `/meme random` - Alias for `/meme`.
818. `/joke random` - Alias for `/joke`.
819. `/recipe search <query>` - Search for cooking recipes.
820. `/recipe random` - Suggest a random recipe.
821. `/cocktail search <query>` - Search for cocktail recipes.
822. `/cocktail random` - Suggest a random cocktail.
823. `/deal find <query>` - Search for deals/discounts online.
824. `/deal alert [set|remove] <query>` - Set alerts for specific product deals.
825. `/amazon search <query>` - Search for products on Amazon.
826. `/ebay search <query>` - Search for products on eBay.
827. `/etsy search <query>` - Search for products on Etsy.
828. `/flight tracker [flight_number]` - Track a flight's status.
829. `/flight deals [from_city] [to_city]` - Search for flight deals.
830. `/hotel deals [location] [dates]` - Search for hotel deals.
831. `/job search [query] [location]` - Search for job postings.
832. `/stock portfolio [view|add|remove] [symbol] [amount]` - Track your stock portfolio.
833. `/crypto portfolio [view|add|remove] [symbol] [amount]` - Track your crypto portfolio.
834. `/crypto alert [set|remove] [symbol] [price_target]` - Set price alerts for cryptocurrencies.
835. `/stock alert [set|remove] [symbol] [price_target]` - Set price alerts for stocks.
836. `/webhook proxy <url>` - Create a proxy webhook URL to hide the original.
837. `/server template gallery` - Browse a gallery of server templates.
838. `/emoji gallery` - Browse a gallery of emojis to add.
839. `/sticker gallery` - Browse a gallery of stickers to add.
840. `/bot list invite <bot_name>` - Generate an invite link for another known bot.
841. `/user lookup <username_or_id>` - Perform a lookup across bot databases (if shared).
842. `/server lookup <invite_code_or_id>` - Look up public info about a server.
843. `/twitch schedule [streamer]` - Show a streamer's broadcast schedule.
844. `/youtube schedule [channel]` - Show a YouTube channel's upcoming streams/premieres.
845. `/tv schedule [show_name]` - Find the broadcast schedule for a TV show.
846. `/movie showtimes [movie_title] [location]` - Find movie showtimes near you.
847. `/concerts [artist_name] [location]` - Find upcoming concerts.
848. `/sports scores [league]` - Get live scores for a sports league.
849. `/sports schedule [league] [team]` - Get the schedule for a sports league or team.
850. `/sports standings [league]` - Get the current standings for a sports league.
851. `/fantasy sports [league] [manage|scores]` - Manage your fantasy team (requires specific API).
852. `/antivirus scan [file_upload]` - Scan a file using VirusTotal API.
853. `/shortenurl custom <url> [alias]` - Create a custom short URL (if service supports).
854. `/qrcode scan [image_upload]` - Read data from a QR code image.
855. `/barcode scan [image_upload]` - Read data from a barcode image.
856. `/barcode generate <type> <data>` - Generate various types of barcodes.
857. `/music history` - Show recently played songs.
858. `/music export queue` - Export the current queue to a file/link.
859. `/music import queue [file_or_link]` - Import a queue from a file/link.
860. `/music equalizer [set|view]` - Set custom equalizer levels.
861. `/server iconhistory` - View previous server icons (if logged).
862. `/server bannerhistory` - View previous server banners (if logged).
863. `/server namehistory` - View previous server names (if logged).
864. `/poll edit [message_id] <new_question> | <new_options>` - Edit an ongoing poll.
865. `/giveaway edit [message_id] [new_duration|new_winners|new_prize]` - Edit an ongoing giveaway.
866. `/tempchannel extend [duration]` - Extend the duration of your temporary channel.
867. `/tempchannel owner [transfer] [user]` - Transfer ownership of a temp channel.
868. `/tempchannel lock` - Lock your temp channel.
869. `/tempchannel unlock` - Unlock your temp channel.
870. `/tempchannel kick [user]` - Kick a user from your temp channel.
871. `/tempchannel ban [user]` - Ban a user from your temp channel.
872. `/tempchannel unban [user]` - Unban a user from your temp channel.
873. `/tempchannel limit [number]` - Set the user limit for your temp voice channel.
874. `/tempchannel name <new_name>` - Rename your temp channel.
875. `/tempchannel claim` - Claim an orphaned temporary channel if possible.
876. `/connect spotify` - Initiate linking your Spotify account to the bot.
877. `/connect steam` - Initiate linking your Steam account.
878. `/connect twitch` - Initiate linking your Twitch account.
879. `/connect youtube` - Initiate linking your YouTube account.
880. `/connect reddit` - Initiate linking your Reddit account.
881. `/connections view` - View your linked accounts.
882. `/disconnect [service]` - Disconnect a linked account.
883. `/datarequest` - Request an export of your data stored by the bot.
884. `/datadelete` - Request deletion of your data stored by the bot.
885. `/block bot` - Prevent the bot from DMing you.
886. `/unblock bot` - Allow the bot to DM you again.
887. `/notifications [enable|disable] [type]` - Manage notifications from the bot (reminders, levels, etc.).
888. `/language set <language_code>` - Set your preferred language for bot responses.
889. `/language view` - View your current language setting.
890. `/help command <command_name>` - Get detailed help for a specific command.
891. `/help category <category_name>` - List commands in a specific category.
892. `/help search <query>` - Search for commands matching a query.
893. `/help interactive` - Start an interactive help session.
894. `/aliase create <alias_name> <command_string>` - Create a personal alias for a command.
895. `/aliase delete <alias_name>` - Delete a personal alias.
896. `/aliase list` - List your personal aliases.
897. `/run alias <alias_name> [args...]` - Run one of your aliases.
898. `/math solve <equation>` - Solve complex math equations (algebra, calculus).
899. `/math graph <function>` - Graph a mathematical function.
900. `/wolframalpha <query>` - Send a query to WolframAlpha.
901. `/set game <game_name>` - Set the bot's "Playing" status.
902. `/set stream <url> <title>` - Set the bot's "Streaming" status.
903. `/set listen <song_name>` - Set the bot's "Listening to" status.
904. `/set watch <show_name>` - Set the bot's "Watching" status.
905. `/clear status` - Clear the bot's custom activity status.
906. `/embed frommessage <message_id>` - Create an embed based on an existing message's content.
907. `/embed edit <message_id> <json_or_builder>` - Edit an embed in a message sent by the bot.
908. `/react addmulti <message_id> <emojis...>` - Add multiple reactions quickly.
909. `/react removemulti <message_id> <emojis...>` - Remove multiple reactions quickly.
910. `/react removeall <message_id>` - Remove all reactions from a message (alias).
911. `/react copy <from_message_id> <to_message_id>` - Copy reactions from one message to another.
912. `/webhook simulate <url> <username> <avatar> <message>` - Simulate a webhook message.
913. `/moderation history [user]` - View a user's moderation history (warnings, mutes, kicks, bans).
914. `/moderation clearhistory [user]` - Clear a user's moderation history (admin).
915. `/moderation stats [server|moderator]` - View overall moderation statistics.
916. `/activity leaderboard [voice|text]` - Show leaderboards based on voice or text activity.
917. `/voicetime [user]` - Show how much time a user has spent in voice channels.
918. `/messagestats [user|channel]` - Show detailed message statistics.
919. `/emojistats [emoji]` - Show usage statistics for a specific emoji.
920. `/commanderrors [command_name]` - Show recent errors specifically for one command.
921. `/snipe attachments [channel]` - Show recently deleted message attachments (optional).
922. `/editsnipe history [message_id]` - Show the edit history of a message (optional, requires logging).
923. `/role restore [user]` - Restore roles a user had when they rejoined (requires logging).
924. `/nickname restore [user]` - Restore a user's previous nickname on rejoin (requires logging).
925. `/server lockreason [set|clear] <reason>` - Set a reason for server lockdown.
926. `/raidmode status` - View the current raid mode status and settings.
927. `/antispam whitelist [user|role]` - Whitelist users/roles from anti-spam.
928. `/antilink whitelist [user|role|channel]` - Whitelist users/roles/channels from anti-link.
929. `/antiinvite whitelist [user|role]` - Whitelist users/roles from anti-invite.
930. `/automod status` - View the status of all automod features.
931. `/backup view [id]` - View the contents summary of a backup file.
932. `/channel stats [channel]` - Show activity statistics for a specific channel.
933. `/role stats [role]` - Show statistics about a role (member count over time, etc.).
934. `/server growth` - Show a graph of server member growth over time.
935. `/auditlog webhook [enable|disable] [url]` - Send audit log events to a webhook.
936. `/modlog webhook [enable|disable] [url]` - Send bot moderation logs to a webhook.
937. `/github webhook [add|remove|list] [repo] [channel]` - Set up GitHub webhooks (commits, issues) to post in Discord.
938. `/trello webhook [add|remove|list] [board] [channel]` - Set up Trello webhooks.
939. `/dynamic vc create [name_template]` - Create dynamic voice channels that clone when full.
940. `/dynamic vc config [template|limit]` - Configure dynamic voice channels.
941. `/purge keep [message_ids...] [channel] [limit]` - Purge messages *except* for specific ones.
942. `/purge images [channel] [limit]` - Purge messages containing images.
943. `/purge files [channel] [limit]` - Purge messages containing files/attachments.
944. `/purge embeds only [channel] [limit]` - Purge messages that are *only* embeds.
945. `/purge mentions [user|role] [channel] [limit]` - Purge messages containing specific mentions.
946. `/purge duplicates [channel] [limit]` - Purge duplicate messages.
947. `/channel slowmode exempt [role|user]` - Exempt users/roles from channel slowmode.
948. `/role exclusive [group_name] [add|remove|list] [role]` - Create mutually exclusive roles (user can only have one from the group).
949. `/role hierarchy view` - Visualize the role hierarchy.
950. `/role assignall [role]` - Assign a role to all members (dangerous!).
951. `/role removeall [role]` - Remove a role from all members (dangerous!).
952. `/server invites list [active|expired]` - List server invites.
953. `/server invites prune [min_uses] [max_age]` - Prune old or unused invites.
954. `/server invites pause [toggle]` - Pause all server invites temporarily.
955. `/thread digest [thread]` - Get a summary of recent activity in a thread.
956. `/forum digest [forum]` - Get a summary of recent posts in a forum.
957. `/activity watchtogether [youtube_url]` - Start a Watch Together activity in voice channel.
958. `/activity poker` - Start a Poker Night activity.
959. `/activity chess` - Start a Chess in the Park activity.
960. `/activity checkers` - Start a Checkers in the Park activity.
961. `/activity betrayal` - Start a Betrayal.io activity.
962. `/activity fishington` - Start a Fishington.io activity.
963. `/activity wordsnacks` - Start a Word Snacks activity.
964. `/activity doodlecrew` - Start a Doodle Crew activity.
965. `/activity spellcast` - Start a SpellCast activity.
966. `/activity lettertile` - Start a Letter Tile activity.
967. `/activity puttparty` - Start a Putt Party activity.
968. `/activity awkward` - Start an Awkward Arena activity.
969. `/activity list` - List available voice channel activities.
970. `/remind onmessage <user> <keyword> <message>` - Remind you when a user sends a message containing a keyword.
971. `/tag random` - Get a random tag.
972. `/image enhance [image_url_or_upload]` - Attempt to enhance image resolution/quality.
973. `/image colorize [image_url_or_upload]` - Attempt to colorize a black and white image.
974. `/image caption gif [gif_url]` - Add caption text to a GIF.
975. `/image text [image_url] <text> [position] [font] [color]` - Add overlay text to an image.
976. `/music bass level <level>` - Set the bass boost level specifically.
977. `/music pitch <level>` - Change the pitch of the music.
978. `/music speed <level>` - Change the playback speed of the music.
979. `/music filter [add|remove|list] <filter_name>` - Manage complex audio filters.
980. `/music grab` - Send details of the currently playing song to your DMs.
981. `/music autoplay [toggle]` - Toggle automatically playing related songs when the queue ends.
982. `/music voteskip [toggle|status]` - Enable/disable or view status of vote skipping.
983. `/confession view [id]` - View a specific confession (admin).
984. `/confession list` - List recent confessions (admin).
985. `/confession approve [id]` - Approve a confession to be posted publicly (if system requires).
986. `/confession reject [id]` - Reject/delete a confession.
987. `/ask answer <question_id> <answer>` - Anonymously answer a question from `/ask` (admin).
988. `/ask list` - List unanswered questions from `/ask` (admin).
989. `/profile background [list|set] <name_or_url>` - Set profile background from pre-approved list or URL.
990. `/profile badge [grant|revoke] [user] <badge_name>` - Manually grant/revoke profile badges (admin).
991. `/profile reset [user]` - Reset a user's profile settings (admin).
992. `/marry list` - Show all married couples in the server.
993. `/leaderboard messages [channel] [timeframe]` - Show message leaderboards with filters.
994. `/leaderboard voice [timeframe]` - Show voice activity leaderboards.
995. `/leaderboard invites [timeframe]` - Show who has invited the most members.
996. `/leaderboard boosts` - Show who has boosted the server the most/longest.
997. `/leaderboard reactions_given` - Show who gives the most reactions.
998. `/leaderboard reactions_received` - Show who receives the most reactions.
999. `/soundboard favorites [add|remove|list] <sound_name>` - Manage your favorite sounds.
1000. `/gpt query <prompt>` - General purpose query to a GPT model API.
1001. `/system load` - Show system load averages.
1002. `/system processes [sort_by_cpu|sort_by_mem]` - List running processes on the bot's host.
1003. `/system uptime` - Show host system uptime.
1004. `/userflags [user]` - Show the raw user flags (badges) for a user.
1005. `/guildflags [server]` - Show the raw guild feature flags.
1006. `/snowflake decode <id>` - Decode a Discord ID (snowflake) into timestamp and internal IDs.
1007. `/webhook info [url]` - Get information about a webhook from its URL.
1008. `/message source <message_id>` - Show the raw message content (markdown).
1009. `/role mention [role]` - Get a mentionable role mention without pinging.
1010. `/user mention [user]` - Get a user mention string.
1011. `/channel mention [channel]` - Get a channel mention string.
1012. `/permission calculator [permissions...]` - Calculate the integer value for a set of permissions.
1013. `/intent calculator [intents...]` - Calculate the integer value for a set of intents.
1014. `/color picker` - Show an interactive color picker.
1015. `/unicode search <query>` - Search for Unicode characters by name.
1016. `/unicode emoji [skin_tone]` - List emojis, optionally filtered by skin tone.
1017. `/timezone convert <time> <from_tz> <to_tz>` - Convert a time between timezones.
1018. `/server splash` - Show the server's invite splash image.
1019. `/server discovery_splash` - Show the server's discovery splash image.
1020. `/member statuscount` - Show counts of members by status (online, idle, dnd, offline).
1021. `/member platformcount` - Show counts of members by platform (desktop, web, mobile).
1022. `/member activitycount` - Show counts of members by current activity type (playing, listening, etc.).
1023. `/purge pins [channel]` - Purge pinned messages in a channel.
1024. `/purge webhooks [channel] [limit]` - Purge messages sent by webhooks.
1025. `/purge system [channel] [limit]` - Purge system messages (joins, boosts, pins).
1026. `/invite track [enable|disable]` - Start tracking who invites whom.
1027. `/inviter [user]` - Show who invited a specific user (if tracked).
1028. `/invites leaderbord` - Show users who have the most successful invites.
1029. `/level rewards [list|add|remove] <level> <role>` - Configure roles awarded at certain levels.
1030. `/level multiplier [set|view] [role|channel] <multiplier>` - Set XP multipliers for roles/channels.
1031. `/level announce [toggle|channel|message]` - Configure level up announcements.
1032. `/economy items [add|remove|edit] <item_name> [price] [description]` - Manage shop items.
1033. `/economy roleshop [add|remove|list] <role> <price>` - Allow users to buy roles with currency.
1034. `/economy lottery [status|buy|draw]` - Run a server lottery.
1035. `/economy stocks [buy|sell] <symbol> <amount>` - Simulate stock market trading.
1036. `/economy heist [user] <amount>` - Attempt to steal currency from another user (minigame).
1037. `/image face swap [image1] [image2]` - Swap faces between two images.
1038. `/image perspective [image] [coords]` - Apply perspective transform to an image.
1039. `/image caption advanced [image] [text] [font] [size] [color] [position]` - Add text with advanced options.
1040. `/image watermark [image] [watermark_image_or_text] [opacity] [position]` - Add a watermark.
1041. `/image border [image] [color] [width]` - Add a border to an image.
1042. `/image vignette [image]` - Apply a vignette effect.
1043. `/image posterize [image] [levels]` - Apply a posterize effect.
1044. `/image solarize [image] [threshold]` - Apply a solarize effect.
1045. `/image ascii art [image]` - Convert an image to ASCII art.
1046. `/image pixel sort [image]` - Apply a pixel sorting glitch effect.
1047. `/image glitch [image]` - Apply various glitch effects.
1048. `/image bobross [image_or_user]` - Put an image on Bob Ross's canvas.
1049. `/image billboard [image_or_user]` - Put an image on a billboard.
1050. `/image tattoo [image_or_user]` - Overlay an image as a tattoo.
1051. `/image tv [image_or_user]` - Put an image on a TV screen.
1052. `/image rip [user]` - Generate a tombstone image for a user.
1053. `/image trash [user]` - Put a user's avatar in the trash.
1054. `/image slap [user1] [user2]` - Generate a slapping meme image.
1055. `/image spank [user1] [user2]` - Generate a spanking meme image.
1056. `/image distractedbf <text1> | <text2> | <text3>` - Generate the Distracted Boyfriend meme.
1057. `/image buttons <text1> | <text2>` - Generate the Two Buttons meme.
1058. `/image expandingbrain <text1> | ... | <text4>` - Generate the Expanding Brain meme.
1059. `/music lyrics card [song]` - Generate an image card with lyrics.
1060. `/music queue image` - Generate an image representing the current queue.
1061. `/server boost graph` - Show graph of server boost count over time.
1062. `/channel activity [channel]` - Show graph of message activity in a channel.
1063. `/role distribution` - Show a pie chart of role distribution.
1064. `/joinage [user]` - Show how long a user has been in the server.
1065. `/accountage [user]` - Show how old a user's Discord account is.
1066. `/firstseen [user]` - Show when the bot first saw a user in the server (if logged).
1067. `/lastseen [user]` - Show when a user was last active/seen by the bot (if logged).
1068. `/spotify top tracks [user]` - Show a user's top Spotify tracks (requires scope).
1069. `/spotify top artists [user]` - Show a user's top Spotify artists (requires scope).
1070. `/spotify recently played [user]` - Show a user's recently played tracks.
1071. `/steam hours [user] [game]` - Show a user's hours played in a Steam game.
1072. `/steam recent games [user]` - Show a user's recently played Steam games.
1073. `/steam wishlist [user]` - Show a user's Steam wishlist.
1074. `/github contributions [user]` - Show a user's GitHub contribution graph/stats.
1075. `/poll timer <message_id> <duration>` - Add a timer to an existing poll.
1076. `/embed timestamp <message_id> [toggle]` - Add/remove timestamp from bot embed.
1077. `/embed color <message_id> <hex_color>` - Change the color of a bot embed.
1078. `/embed author <message_id> <text> [icon_url]` - Change the author of a bot embed.
1079. `/embed footer <message_id> <text> [icon_url]` - Change the footer of a bot embed.
1080. `/embed field <message_id> [add|edit|remove] <index_or_name> [value] [inline]` - Modify fields in a bot embed.
1081. `/snipe clear` - Clear the snipe cache for the channel.
1082. `/auditlog filter [user] [action_type] [before_id] [after_id] [limit]` - Filter audit logs with more precision.
1083. `/permission history [role_or_user]` - Show the history of permission changes for a role or user (requires logging).
1084. `/role clone [role] <new_name>` - Clone an existing role's permissions and settings.
1085. `/channel permissions copy [source_channel] [target_channel]` - Copy all permission overwrites.
1086. `/message crosspost <message_id>` - Manually crosspost (publish) a message from an announcement channel.
1087. `/server discovery requirements` - Check if the server meets requirements for Discovery listing.
1088. `/server template sync` - Update the server's template code.
1089. `/server integrations` - List active server integrations (webhooks, bots, apps).
1090. `/integration info [integration_id]` - Show details about a specific integration.
1091. `/webhook permissions [webhook_url]` - Check permissions needed to send to a webhook URL.
1092. `/automod rules` - List the currently configured Discord AutoMod rules.
1093. `/automod rule create [name] [trigger] [action] [exempt_roles/channels]` - Create a new Discord AutoMod rule.
1094. `/automod rule delete [rule_id]` - Delete a Discord AutoMod rule.
1095. `/automod rule modify [rule_id] [...]` - Modify an existing Discord AutoMod rule.
1096. `/modalert [message]` - Send an urgent alert to online moderators.
1097. `/security audit` - Run a comprehensive check for common server security misconfigurations.
1098. `/privacy audit` - Run a check for potential privacy concerns in server settings/roles.
1099. `/token revoke [application_id]` - Revoke access for a specific application/bot integration (admin).
1100. `/role reachability [role]` - Check which channels a role can read/send messages in.
1101. `/channel visibility [channel] [user]` - Check if a specific user can see and access a channel.
1102. `/permission conflicts [user]` - Identify potential permission conflicts for a user.
1103. `/temp role [user] [role] <duration> [reason]` - Assign a role temporarily.
1104. `/temprole list [user]` - List active temporary roles for a user.
1105. `/temprole remove [user] [role]` - Remove a temporary role assignment early.
1106. `/lockdown exempt [role|user]` - Exempt roles/users from server lockdown.
1107. `/nickname policy [enforce|disable] [regex_pattern]` - Enforce nickname standards.
1108. `/avatar policy [enforce|disable]` - Check for default avatars or enforce specific rules (difficult).
1109. `/massdm [role] <message>` - DM all users with a specific role (use with extreme caution, potential ToS violation).
1110. `/report system config [channel] [review_role]` - Configure the user reporting system.
1111. `/jira issue create <project> <summary> <description>` - Create an issue in Jira.
1112. `/jira issue view <issue_key>` - View details of a Jira issue.
1113. `/trello card create <board> <list> <name> [description]` - Create a Trello card.
1114. `/trello card view <card_id_or_url>` - View details of a Trello card.
1115. `/gitlab issue create <project_id> <title> [description]` - Create an issue on GitLab.
1116. `/gitlab repo info <owner/repo>` - Show info about a GitLab repository.
1117. `/bitbucket issue create <workspace/repo> <title> [description]` - Create an issue on Bitbucket.
1118. `/bitbucket repo info <workspace/repo>` - Show info about a Bitbucket repository.
1119. `/asana task create <workspace> <project> <name> [notes]` - Create a task in Asana.
1120. `/asana task view <task_id>` - View details of an Asana task.
1121. `/googlecalendar events list [calendar_id]` - List upcoming events from a Google Calendar.
1122. `/googlecalendar event create <summary> <start_time> <end_time> [description]` - Add an event to Google Calendar.
1123. `/googledrive file find <query>` - Search for files in Google Drive.
1124. `/googledrive file info <file_id>` - Get info about a file in Google Drive.
1125. `/dropbox file find <query>` - Search for files in Dropbox.
1126. `/dropbox file info <file_path>` - Get info about a file in Dropbox.
1127. `/zoom meeting create <topic> [start_time] [duration]` - Create a Zoom meeting.
1128. `/zoom meeting info <meeting_id>` - Get info about a Zoom meeting.
1129. `/microsoftteams message send <channel_id> <message>` - Send a message to a Microsoft Teams channel.
1130. `/slack message send <channel_id> <message>` - Send a message to a Slack channel.
1131. `/canvas courses list` - List your courses on Canvas LMS.
1132. `/canvas assignments list <course_id>` - List upcoming assignments for a Canvas course.
1133. `/moodle courses list` - List your courses on Moodle.
1134. `/moodle assignments list <course_id>` - List upcoming assignments for a Moodle course.
1135. `/duolingo profile [username]` - Show Duolingo learning progress.
1136. `/codecademy profile [username]` - Show Codecademy progress.
1137. `/stackoverflow user [user_id]` - Show Stack Overflow user reputation and stats.
1138. `/reddit user [username]` - Show Reddit user karma and account info.
1139. `/deviantart browse [query]` - Browse deviations on DeviantArt.
1140. `/artstation browse [query]` - Browse artwork on ArtStation.
1141. `/unsplash image [query]` - Fetch a high-quality image from Unsplash.
1142. `/pexels image [query]` - Fetch a high-quality image from Pexels.
1143. `/dataviz chart create <type> <data> [labels] [title]` - Create a chart image (bar, line, pie).
1144. `/dataviz graphviz <dot_code>` - Render a graph using Graphviz DOT language.
1145. `/file metadata [file_upload]` - Extract metadata from various file types.
1146. `/file compare text [file1] [file2]` - Show differences between two text files.
1147. `/file compare image [file1] [file2]` - Show differences between two image files.
1148. `/file checksum [file_upload] [algorithm]` - Calculate checksum (MD5, SHA1, SHA256) for a file.
1149. `/unit conversion list` - List all available unit conversion categories and units.
1150. `/physics constant <constant_name>` - Look up the value of a physical constant.
1151. `/chemistry element <element_name_or_symbol>` - Get information about a chemical element.
1152. `/chemistry compound <formula_or_name>` - Get information about a chemical compound.
1153. `/astronomy object <object_name>` - Get information about a celestial object.
1154. `/biology taxon <species_name>` - Get information from biological taxonomy databases.
1155. `/latex render <latex_code>` - Render LaTeX code into an image.
1156. `/user preference set <key> <value>` - Set a personal preference for bot behavior (e.g., timezone, display density).
1157. `/user preference view <key>` - View a personal preference.
1158. `/user preference list` - List all available preferences.
1159. `/bot notification config [type] [enable|disable|dm|channel]` - Configure where bot sends notifications (level ups, reminders, etc).
1160. `/command alias global create <alias_name> <command_string>` - Create a server-wide command alias (admin).
1161. `/command alias global delete <alias_name>` - Delete a server-wide alias (admin).
1162. `/command alias global list` - List server-wide aliases.
1163. `/command cooldown set <command_name> <duration> [role_or_channel]` - Set custom cooldowns for commands (admin).
1164. `/command cooldown view <command_name>` - View cooldown settings for a command.
1165. `/chess analyze [fen_string_or_pgn]` - Analyze a chess position or game.
1166. `/connect4 analyze [board_state]` - Analyze a Connect Four position.
1167. `/hangman custom [word] [guesses]` - Start a Hangman game with a custom word.
1168. `/trivia categories` - List available trivia categories.
1169. `/trivia leaderboard clear` - Clear the trivia leaderboard.
1170. `/wordle stats [user]` - Show Wordle play statistics.
1171. `/numberguess [range]` - Start a number guessing game.
1172. `/typingtest leaderboard` - Show the typing test leaderboard.
1173. `/fishing leaderboard` - Show the fishing leaderboard (economy).
1174. `/hunting leaderboard` - Show the hunting leaderboard (economy).
1175. `/pets adopt <type> [name]` - Adopt a virtual pet.
1176. `/pets feed [name]` - Feed your virtual pet.
1177. `/pets play [name]` - Play with your virtual pet.
1178. `/pets status [name]` - Check your virtual pet's status.
1179. `/pets list` - List your virtual pets.
1180. `/ai explain <concept>` - Explain a complex concept simply using AI.
1181. `/ai prosandcons <topic>` - List pros and cons for a topic using AI.
1182. `/ai brainstorm <topic>` - Brainstorm ideas related to a topic using AI.
1183. `/ai generate quiz <topic> [questions]` - Generate a quiz on a topic using AI.
1184. `/ai generate recipe <ingredients_or_dish>` - Generate a recipe using AI.
1185. `/ai sentiment analysis <text>` - Analyze the sentiment of a piece of text using AI.
1186. `/ai keyword extraction <text>` - Extract keywords from text using AI.
1187. `/ai text readability <text>` - Analyze the readability score of text.
1188. `/ai meeting summary <transcript>` - Summarize meeting notes or transcript using AI.
1189. `/accessibility check image [image_url]` - Check image for common accessibility issues (e.g., alt text).
1190. `/accessibility check contrast <color1> <color2>` - Check color contrast ratio.
1191. `/accessibility read aloud <text>` - Read text aloud using TTS (Text-to-Speech).
1192. `/accessibility config [tts_voice] [speed]` - Configure TTS settings.
1193. `/event rsvp <event_id> [yes|no|maybe]` - RSVP to a server scheduled event.
1194. `/event remindme <event_id>` - Set a reminder for a specific scheduled event.
1195. `/event export <event_id> [ical|google]` - Export event details to a calendar format.
1196. `/icebreaker question` - Get a random icebreaker question.
1197. `/icebreaker game [type]` - Start a simple icebreaker game (e.g., Two Truths and a Lie).
1198. `/qanda session start <topic>` - Start a Q&A session channel/thread.
1199. `/qanda ask <question>` - Ask a question during a Q&A session.
1200. `/qanda answer <question_id> <answer>` - Answer a question during a Q&A session (host).
1201. `/role tree` - Display the role hierarchy as a tree structure.
1202. `/role orphans` - List roles that have no members.
1203. `/role permissions compare [role1] [role2]` - Show differences in permissions between two roles.
1204. `/role permissions neededfor <permission_name>` - List roles that grant a specific permission.
1205. `/channel template save <channel> <template_name>` - Save a channel's settings and permissions as a template.
1206. `/channel template apply <template_name> <new_channel_name>` - Create a channel from a template.
1207. `/channel template list` - List saved channel templates.
1208. `/channel cleanup config [channel] [keep_pinned] [ignore_users]` - Configure automatic message cleanup rules.
1209. `/channel cleanup run [channel]` - Manually trigger a channel cleanup based on rules.
1210. `/archive search <query>` - Search within previously archived channel logs (if stored).
1211. `/server stats export [csv|json]` - Export server statistics data.
1212. `/user stats export [user] [csv|json]` - Export user statistics data.
1213. `/medical dictionary [term]` - Look up medical terms (provide disclaimer).
1214. `/legal dictionary [term]` - Look up legal terms (provide disclaimer).
1215. `/doi lookup <doi_number>` - Look up scientific papers by DOI.
1216. `/arxiv search <query>` - Search for papers on arXiv.
1217. `/pubmed search <query>` - Search for papers on PubMed Central.
1218. `/collaborative write start <document_name>` - Start a collaborative writing document/pad.
1219. `/collaborative write join <document_name>` - Join a writing session.
1220. `/drawing board start` - Create a collaborative drawing board link/instance.
1221. `/music compose helper [key] [scale]` - Provide music theory aids (scales, chords).
1222. `/data breach check email <email>` - Check an email against Have I Been Pwned.
1223. `/data breach check domain <domain>` - Check if a domain has appeared in breaches (associated emails).
1224. `/permission audit roles` - Audit roles for potentially dangerous permission combinations.
1225. `/permission audit users` - Audit users with high privilege levels.
1226. `/server invite security check` - Check invite settings for potential abuse vectors.
1227. `/webhook security check` - Check webhooks for overly broad permissions or exposure.
1228. `/git log [repo_url] [branch]` - Show recent commit history for a public repository.
1229. `/git blame [repo_url] [file_path] [line_number]` - Show who last modified a line in a file (public repo).
1230. `/dockerhub info [image_name]` - Show information about a Docker Hub image.
1231. `/currency history <from_currency> <to_currency> [range]` - Show historical exchange rate graph.
1232. `/stock history <symbol> [range]` - Show historical stock price graph.
1233. `/crypto history <symbol> [range]` - Show historical crypto price graph.
1234. `/wikipedia diff <article_title> [revision1] [revision2]` - Show changes between Wikipedia article revisions.
1235. `/vote anonymous <question> | <option1> | ...` - Create a poll where votes are anonymous even to the bot admin.
1236. `/reactionrole removeall [message_id]` - Remove all reaction role configurations from a message.
1237. `/selfrole description [role] <description>` - Add a description to a self-assignable role.
1238. `/timezone abbreviation <tz_abbreviation>` - Explain a timezone abbreviation (e.g., EST, PDT).
1239. `/weather alerts [location]` - Show active weather alerts for a location.
1240. `/airquality forecast [location]` - Show the AQI forecast.
1241. `/package manager search <query>` - Search across multiple package managers (PyPI, NPM, RubyGems, etc.).
1242. `/soundboard search <query>` - Search available soundboard sounds by name.
1243. `/ai conversation <start_prompt>` - Start a persistent conversation thread with an AI.
1244. `/ai conversation continue <message>` - Continue the AI conversation.
1245. `/ai conversation history` - Show the history of the current AI conversation.
1246. `/ai conversation end` - End the current AI conversation.
1247. `/image generate variations [image_url]` - Generate AI variations of an existing image.
1248. `/image generate edit [image_url] <prompt>` - Edit parts of an image using AI based on a text prompt.
1249. `/emoji combine <emoji1> <emoji2>` - Attempt to combine two emojis (using Google's Emoji Kitchen API if available).
1250. `/pomodoro stats` - Show your Pomodoro session statistics.
1251. `/movie watchlist [add|remove|view] <movie_title>` - Manage your personal movie watchlist.
1252. `/tv watchlist [add|remove|view] <show_title>` - Manage your personal TV show watchlist.
1253. `/game backlog [add|remove|view] <game_title>` - Manage your personal game backlog.
1254. `/book readinglist [add|remove|view] <book_title>` - Manage your personal reading list.
1255. `/server settings history` - Show a log of changes to major server settings (if logged).
1256. `/role permissionlog [role]` - Show a log of permission changes specifically for one role (if logged).
1257. `/message pin <message_id>` - Pin a message via bot command.
1258. `/message unpin <message_id>` - Unpin a message via bot command.
1259. `/message pins list [channel]` - List pinned messages in a channel.
1260. `/thread frommessage <message_id> <name>` - Create a thread starting from a specific message.
1161. `/thread rename <thread> <new_name>` - Rename a thread.
1162. `/thread members [thread]` - List members currently in a private thread.
1163. `/forum search <forum_channel> <query>` - Search for posts within a specific forum channel.
1164. `/forum pin <post_id>` - Pin a post within a forum channel.
1165. `/forum unpin <post_id>` - Unpin a forum post.
1166. `/forum lock <post_id>` - Lock a forum post (prevent replies).
1167. `/forum unlock <post_id>` - Unlock a forum post.
1168. `/forum tag post <post_id> [add|remove] <tag>` - Add or remove tags from a forum post.
1169. `/activity stats [activity_name]` - Show usage statistics for voice channel activities.
1170. `/sticky message edit <channel> <new_message>` - Edit the content of a sticky message.
1171. `/sticky message embed <channel> <json_or_builder>` - Use an embed for the sticky message.
1172. `/autoresponse list` - List currently configured autoresponses.
1173. `/autoresponse view <trigger>` - View the details of a specific autoresponse.
1174. `/autoresponse stats [trigger]` - Show usage stats for an autoresponse.
1175. `/customcommand view <name>` - View the script/actions for a custom command.
1176. `/customcommand permissions <name> [role|user] [allow|deny]` - Set permissions for a custom command.
1177. `/backup download [id]` - Download a server backup file (admin).
1178. `/backup compare [id1] [id2]` - Show a diff between two server backups.
1179. `/voicelog search <user> [timeframe]` - Search voice join/leave logs.
1180. `/messagelog search <user> [keyword] [timeframe]` - Search message edit/delete logs.
1181. `/modlog search <user|moderator|action> [timeframe]` - Search moderation action logs.
1182. `/ticket transcript format [html|txt]` - Set the format for ticket transcripts.
1183. `/ticket priority [set|view] <level>` - Set or view the priority of a ticket.
1184. `/ticket tag [add|remove|list] <tag>` - Add tags to categorize tickets.
1185. `/ticket list [status|user|assignee|tag]` - Filter the list of tickets.
1186. `/starboard blacklist user [user] [add|remove]` - Prevent a user's messages from appearing on the starboard.
1187. `/starboard minimum stars <count>` - Set the minimum stars required for a message to appear.
1188. `/starboard autostar [enable|disable]` - Automatically star messages from specific users/roles (use carefully).
1189. `/translate language detect <text>` - Detect the language of a piece of text.
1190. `/image steganalysis [image]` - Attempt to detect hidden data (steganography) in an image.
1191. `/audio steganalysis [audio]` - Attempt to detect hidden data in audio.
1192. `/filetype identify [file]` - Identify the type of a file based on its signature.
1193. `/password dump check <password>` - Check if a password appears in known credential dumps (use secure API).
1194. `/twofactor status` - Check if 2FA is enabled for the bot's account (informational).
1195. `/server rules view` - Display the server's rules channel content directly.
1196. `/role reaction limit [role] <count>` - Limit how many reaction roles a user with a specific role can have.
1197. `/message require reaction <message_id> [role] [emoji]` - Require users with a role to react to a message.
1198. `/channel slowmode duration <channel>` - Show how long slowmode has been active in a channel.
1199. `/timeout user [user] <duration> [reason]` - Use Discord's built-in Timeout feature.
1200. `/timeout list` - List users currently timed out.
1201. `/emoji usage [emoji]` - Show how often a custom emoji is used (requires logging).
1202. `/sticker usage [sticker]` - Show how often a custom sticker is used (requires logging).
1203. `/invite usage [invite_code]` - Show usage stats for a specific invite code over time.
1204. `/command usage graph [command_name] [timeframe]` - Show a graph of command usage over time.
1205. `/feature usage graph <feature_name> [timeframe]` - Show usage graph for a bot feature (e.g., leveling, economy).
1206. `/ai prompt library [list|add|use] <name> [prompt]` - Manage a library of prompts for AI generation.
1207. `/ai image style <style_preset> <prompt>` - Generate an image using a specific preset style (e.g., anime, photorealistic).
1208. `/ai image upscale [image]` - Upscale the resolution of an AI-generated or other image.
1209. `/ai text adventure start [genre]` - Start a text adventure game powered by AI.
1210. `/ai text adventure action <action>` - Perform an action in the AI text adventure.
1211. `/music playlist import [youtube|spotify] <url>` - Import a playlist directly from a URL.
1212. `/music playlist export <name> [format]` - Export a bot playlist.
1213. `/music playlist collaborate [add|remove] [user] <name>` - Allow others to add/remove songs from a playlist.
1214. `/music lyrics find <query>` - Search for lyrics without playing a song.
1215. `/music recommendations [genre|artist|song]` - Get music recommendations based on input.
1216. `/system resource graph [cpu|mem|disk|net] [timeframe]` - Show graphs of system resource usage over time.
1217. `/github release watch [owner/repo] [channel]` - Announce new releases for a GitHub repository.
1218. `/rss feed filter [url] [include_keywords|exclude_keywords]` - Filter RSS feed entries before posting.
1219. `/server event log` - Show a log of server scheduled events (created, started, cancelled).
1220. `/user note private [user] <note>` - Add a private note about a user visible only to you.
1221. `/user note list [user]` - List your private notes for a user.
1222. `/server group [create|delete|add|remove|list] <group_name> [channel|role]` - Group channels/roles for easier management.
1223. `/server group broadcast <group_name> <message>` - Send a message to all channels in a group.
1224. `/server group permission <group_name> [role] [allow|deny] [permissions]` - Apply permissions to all channels in a group.
1225. `/role request autoapprove [role] [toggle]` - Toggle auto-approval for specific role requests.
1226. `/economy stocks watchlist [add|remove|view] [symbol]` - Manage your stock watchlist.
1227. `/economy crypto watchlist [add|remove|view] [symbol]` - Manage your crypto watchlist.
1228. `/profile badge create <name> <icon> [description]` - Create custom badges for profiles (admin).
1229. `/profile badge delete <name>` - Delete a custom badge (admin).
1230. `/profile badge list` - List available profile badges.
1231. `/pet battle [user_pet] [opponent_pet]` - Start a simple battle between virtual pets.
1232. `/pet trade [user1] [pet1] [user2] [pet2]` - Initiate a trade of virtual pets.
1233. `/interaction create button <label> [style] [custom_id|url] [emoji]` - Create a message with buttons.
1234. `/interaction create selectmenu <placeholder> [custom_id] <options...>` - Create a message with a dropdown select menu.
1235. `/interaction respond modal <interaction_id> <title> <components...>` - Respond to an interaction with a modal form.
1236. `/interaction respond defer <interaction_id> [ephemeral]` - Acknowledge an interaction to respond later.
1237. `/interaction respond edit <interaction_id> <new_content>` - Edit the initial response to an interaction.
1238. `/debug interaction <interaction_id>` - Get debug info for a specific interaction event.
1239. `/debug gateway events [filter]` - Show recent gateway events received by the bot.
1240. `/debug cache stats [object_type]` - Show statistics about the bot's internal cache.
1241. `/server boost perks list` - List the perks currently active from server boosts.
1242. `/server boost goal [set|view] <level>` - Set or view a server boost goal.
1243. `/member list [role] [status] [activity]` - Advanced member listing with multiple filters.
1244. `/member prune simulate [days] [role]` - Simulate pruning members without actually kicking.
1245. `/channel nuke simulate [channel]` - Simulate nuking a channel (shows what would be deleted/created).
1246. `/role permissions effective [role]` - Show the final calculated permissions including hierarchy.
1247. `/user permissions effective [user] [channel]` - Show the final calculated permissions for a user in a specific channel.
1248. `/invite analytics [invite_code]` - Show analytics for an invite code (joins over time, conversion rate, if tracked).
1249. `/level leaderboard relative [user]` - Show the leaderboard centered around a specific user.
1250. `/level role rewards list` - List all configured level role rewards.
1251. `/economy lottery history` - Show history of past lottery winners and jackpots.
1252. `/image caption contest [start|submit|vote|end]` - Run a caption contest for an image.
1253. `/ai story continue <story_id> <prompt>` - Continue a collaboratively written AI story.
1254. `/ai image describe [image]` - Have AI describe the contents of an image.
1255. `/ai image question [image] <question>` - Ask a question about the contents of an image.
1256. `/soundboard play random` - Play a random sound from the soundboard.
1257. `/voicemod list effects` - List available voice modification effects.
1258. `/remind recurring list` - List your active recurring reminders.
1259. `/birthday upcoming [days]` - Show birthdays coming up within a specific number of days.
1260. `/wolframalpha image <query>` - Get an image result from WolframAlpha.
1261. `/wolframalpha stepbystep <query>` - Get step-by-step solutions from WolframAlpha (requires API plan).
1262. `/google image search <query>` - Perform a Google Image search.
1263. `/google scholar search <query>` - Perform a Google Scholar search.
1264. `/duckduckgo search <query>` - Perform a DuckDuckGo search.
1265. `/duckduckgo image search <query>` - Perform a DuckDuckGo image search.
1266. `/spotify playlist create <name>` - Create a new empty Spotify playlist (requires scope).
1267. `/spotify playlist add <playlist_id> <track_url_or_uri>` - Add a track to a Spotify playlist.
1268. `/steam achievement check [user] [game]` - Check a user's achievement progress for a Steam game.
1269. `/github issue search [repo] <query>` - Search for issues in a GitHub repository.
1270. `/github pullrequest search [repo] <query>` - Search for pull requests in a GitHub repository.
1271. `/server welcome message variables` - List available variables for welcome messages.
1272. `/server leave message variables` - List available variables for leave messages.
1273. `/server boost message variables` - List available variables for boost messages.
1274. `/purge regex <regex_pattern> [channel] [limit]` - Purge messages matching a regex pattern.
1275. `/purge unique [channel] [limit]` - Purge leaving only unique messages (based on content).
1276. `/channel permission sync [source_channel] [target_channels...]` - Sync permissions from one channel to multiple others.
1277. `/role permission copy [source_role] [target_roles...]` - Copy permissions from one role to multiple others.
1278. `/forum default tags [forum_channel] [add|remove|list] <tag>` - Set default tags applied to new forum posts.
1279. `/thread autopin [enable|disable] [thread]` - Automatically pin the first message in a thread.
1280. `/activity watchtogether invite [user]` - Invite a user to the current Watch Together activity.
1281. `/tag stats [name]` - Show usage statistics for a specific tag.
1282. `/tag export [format]` - Export all server tags.
1283. `/tag import [format] [file]` - Import tags from a file.
1284. `/image mosaic [images...]` - Create a mosaic from several images.
1285. `/image grid [images...] [columns]` - Arrange images into a grid.
1286. `/music queue save <name>` - Save the current music queue as a playlist.
1287. `/music playlist shuffle <name>` - Shuffle a saved playlist.
1288. `/confession config [channel] [anonymous_posting]` - Configure the confession system.
1289. `/ask config [channel] [anonymous_questions]` - Configure the anonymous question system.
1290. `/profile sync role <role> <badge_or_background>` - Automatically grant profile items based on roles.
1291. `/marry stats` - Show statistics about marriages in the server.
1292. `/leaderboard games [game_name]` - Show leaderboards for specific bot games.
1293. `/soundboard volume <name> <level>` - Set default volume for a specific soundboard sound.
1294. `/gpt model list` - List available GPT models for `/gpt query`.
1295. `/gpt config [model] [temperature] [max_tokens]` - Configure default GPT parameters.
1296. `/user presence history [user]` - Show a user's status/activity history (if logged).
1297. `/server feature flags` - Show enabled/disabled Discord features for the server.
1298. `/webhook execute <url> <json_payload>` - Send a raw JSON payload to a webhook.
1299. `/message raw <message_id>` - Show the raw JSON data for a message object.
1300. `/user raw <user_id>` - Show the raw JSON data for a user object.
1301. `/role raw <role_id>` - Show the raw JSON data for a role object.
1302. `/channel raw <channel_id>` - Show the raw JSON data for a channel object.
1303. `/guild raw <guild_id>` - Show the raw JSON data for a guild object.
1304. `/permission explain <permission_name>` - Explain what a specific Discord permission allows.
1305. `/intent explain <intent_name>` - Explain what data a specific gateway intent provides.
1306. `/color contrast checker` - Open an interactive color contrast checker.
1307. `/unicode properties <character>` - Show detailed Unicode properties for a character.
1308. `/timezone map <timezone_name>` - Show a map highlighting a specific timezone.
1309. `/member join position [user]` - Show a user's join position (e.g., "You are the 100th member").
1310. `/member role history [user]` - Show the history of roles added/removed for a user (if logged).
1311. `/purge attachments type <file_extension> [channel] [limit]` - Purge messages with specific attachment types.
1312. `/invite vanity uses` - Show how many times the vanity URL has been used.
1313. `/level xp needed [user]` - Show how much XP a user needs for the next level.
1314. `/level rank card customize [bg_image|color|font]` - Customize your rank card appearance.
1315. `/economy tax rate [set|view] <rate>` - Set a server-wide tax rate for transactions.
1316. `/economy interest rate [set|view] <rate>` - Set an interest rate for banked currency.
1317. `/image generate prompt assist <keywords>` - Get help generating a good prompt for AI image generation.
1318. `/image meme search <query>` - Search for meme templates by keyword.
1319. `/music history clear` - Clear your personal music playback history.
1320. `/music scrobble [enable|disable] [lastfm_username]` - Scrobble played tracks to Last.fm.
1321. `/server rules sign <message_id>` - Require users to react to the rules message to gain access (requires setup).
1322. `/auditlog stream [enable|disable] [channel]` - Stream audit log events live to a channel.
1323. `/dynamic vc template [set|view] [name_format|limit|bitrate]` - Configure the template for dynamic voice channels.
1324. `/role group manage [add|remove|list] <group_name> [role]` - Manage roles within logical groups (for organization).
1325. `/role group permissions <group_name> [allow|deny] [permissions]` - Apply permission changes to all roles in a group.
1326. `/ticket close reason [add|remove|list] <reason_text>` - Manage predefined reasons for closing tickets.
1327. `/ticket auto close [enable|disable] [inactive_duration]` - Automatically close inactive tickets.
1328. `/starboard star threshold random [min] [max]` - Set a random star threshold within a range.
1329. `/ai chatbot persona [set|view] <persona_description>` - Set a specific persona for the AI chatbot.
1330. `/ai image negative prompt <prompt>` - Specify things the AI should *avoid* generating in images.
1331. `/command shortcut create <shortcut> <command_string>` - Create simple shortcuts (e.g., `?` for `/help`).
1332. `/command shortcut delete <shortcut>` - Delete a command shortcut.
1333. `/command shortcut list` - List active command shortcuts.
1334. `/user color [user]` - Show the user's highest role color or accent color.
1335. `/server color palette` - Show the dominant colors used in server roles.
1336. `/message wordcount <message_id>` - Count words in a specific message.
1337. `/channel wordcount [channel] [limit]` - Count total words sent in a channel recently.
1338. `/translate stats` - Show statistics on translation usage.
1339. `/voicetime leaderboard [timeframe]` - Show the leaderboard for time spent in voice channels.
1340. `/command stats detailed [command]` - Show detailed usage stats (users, channels, times).
1341. `/error rate` - Show the bot's command error rate over time.
1342. `/suggestion implementer <suggestion_id> [user]` - Mark who implemented a suggestion.
1343. `/bugreport duplicate <bug_id_1> <bug_id_2>` - Mark a bug report as a duplicate of another.
1344. `/application comment <app_id> <comment>` - Add internal comments to a staff application.
1345. `/purge pinned [channel]` - Unpin and delete pinned messages in a channel.
1346. `/prune roles [roles_to_require] [days_inactive]` - Prune members who don't have certain roles and are inactive.
1347. `/channel permissions reset [channel] [role_or_user]` - Reset permissions for a specific overwrite.
1348. `/role members remove [role] [users...]` - Remove specific users from a role.
1349. `/emoji steal pack [message_link]` - Add all emojis from a message to the server.
1350. `/thread activity digest <thread>` - Get an AI-generated summary of recent thread activity.
1351. `/server rules edit` - Interactively edit the server rules channel message.
1352. `/channel default slowmode [category|channel] <seconds>` - Set default slowmode for new channels in a category.
1353. `/channel default permissions [category] [role] [allow|deny] [permissions]` - Set default permissions for new channels in a category.
1354. `/role add multiple [users...] [roles...]` - Add multiple roles to multiple users at once.
1355. `/role remove multiple [users...] [roles...]` - Remove multiple roles from multiple users.
1356. `/user data export [user]` - Export data the bot stores about a specific user (admin).
1357. `/user data delete [user]` - Delete data the bot stores about a specific user (admin).
1358. `/server data export` - Export all data the bot stores for the current server (admin).
1359. `/server data delete` - Delete all data the bot stores for the current server (admin).
1360. `/privacy policy update <new_policy_text>` - Update the bot's privacy policy link/text (owner).
1361. `/terms of service update <new_terms_text>` - Update the bot's terms of service link/text (owner).
1362. `/command disable user [command] [user]` - Disable a specific command for a specific user.
1363. `/command enable user [command] [user]` - Re-enable a disabled command for a user.
1364. `/command disable role [command] [role]` - Disable a command for users with a specific role.
1365. `/command enable role [command] [role]` - Re-enable a command for users with a specific role.
1366. `/command disable channel [command] [channel]` - Disable a command in a specific channel.
1367. `/command enable channel [command] [channel]` - Re-enable a command in a specific channel.
1368. `/rate limit status [command|module]` - Check the current rate limit status for specific commands/modules.
1369. `/shard reallocate [shard_id] [new_process]` - Move a shard to a different process (owner, advanced).
1370. `/shard broadcast eval <code>` - Run code across all shards (owner, extremely dangerous).
1371. `/message relay setup [channel1] [channel2]` - Relay messages between two channels (can be cross-server if bot architecture supports).
1372. `/message relay stop [channel1] [channel2]` - Stop relaying messages.
1373. `/message relay list` - List active message relays.
1374. `/reaction copy recent <count> <channel>` - Copy reactions from the last X messages in a channel.
1375. `/embed generator tool` - Link to an external embed generator website.
1376. `/webhook permissions simulator [url]` - Simulate sending different payloads to check webhook permissions.
1377. `/moderation heatmap [timeframe]` - Show a heatmap of moderation actions over time/day.
1378. `/activity correlation [activity1] [activity2]` - Check for correlation between two types of server activities (e.g., messages and voice).
1379. `/snipe config [enabled|disabled|timeout]` - Configure snipe command behavior.
1380. `/editsnipe config [enabled|disabled|timeout]` - Configure editsnipe command behavior.
1381. `/role persistence log [user]` - Show a log of roles reapplied to a user upon rejoin.
1382. `/nickname persistence log [user]` - Show a log of nicknames reapplied to a user upon rejoin.
1383. `/raidmode triggers [list|set] [joins_per_minute|new_accounts_per_hour]` - Configure triggers for automatic raid mode.
1384. `/automod exempt duration [rule_id] [user] <duration>` - Temporarily exempt a user from an AutoMod rule.
1385. `/backup compare with server [backup_id]` - Compare a backup state with the current live server state.
1386. `/channel stats compare [channel1] [channel2]` - Compare activity stats between two channels.
1387. `/role stats compare [role1] [role2]` - Compare stats between two roles.
1388. `/server growth prediction [days]` - Attempt to predict server growth based on recent trends (statistical guess).
1389. `/github webhook events [url] [add|remove] [event_type]` - Configure specific event types for GitHub webhooks.
1390. `/dynamic vc region [template] <region>` - Set a specific voice region for dynamically created VCs.
1391. `/purge before date <date> [channel]` - Purge messages before a specific date.
1392. `/purge after date <date> [channel]` - Purge messages after a specific date.
1393. `/purge contains filetype <extension> [channel] [limit]` - Purge messages containing specific file types.
1394. `/channel voice activity [channel]` - Show who is currently speaking in a voice channel (requires specific intents/permissions).
1395. `/role permissions unused [role]` - Check for permissions granted to a role that might be unused or unnecessary.
1396. `/server invites tracking url <url>` - Generate an invite URL that tracks clicks/source (requires external service/setup).
1397. `/thread participants [thread]` - List users who have participated (sent messages) in a thread.
1398. `/forum participants [post_id]` - List users who have replied to a forum post.
1399. `/activity launcher <activity_name>` - Launch a voice channel activity directly by name.
1400. `/remind on role add <user> <role> <message>` - Remind you when a user gains a specific role.
1401. `/tag execute <name>` - If tag content is a command string, execute it (risky, needs config).
1402. `/image steganography encode [image] <text_or_file>` - Hide data within an image (steganography).
1403. `/image steganography decode [image]` - Attempt to extract hidden data from an image.
1404. `/music queue stats` - Show stats about the current queue (total duration, number of songs, unique artists).
1405. `/music playlist stats <name>` - Show stats about a saved playlist.
1406. `/confession stats` - Show statistics about confessions (total submitted, approved, rejected).
1407. `/ask stats` - Show statistics about anonymous questions (total asked, answered).
1408. `/profile leaderboard <field>` - Show leaderboards based on profile fields (e.g., reputation, marriage duration).
1409. `/marry proposal list` - List pending marriage proposals.
1410. `/marry accept [user]` - Accept a marriage proposal.
1411. `/marry reject [user]` - Reject a marriage proposal.
1412. `/leaderboard custom <metric_name>` - Show leaderboards for custom tracked metrics (if bot supports).
1413. `/soundboard play sequence [sounds...]` - Play a sequence of soundboard sounds.
1414. `/gpt summarize chat [channel] [limit]` - Use GPT to summarize recent chat messages.
1415. `/gpt analyze sentiment chat [channel] [limit]` - Use GPT to analyze the overall sentiment of recent chat.
1416. `/system health check` - Run a self-check on bot system resources and API connectivity.
1417. `/user avatar steal <user>` - Get the URL of a user's avatar.
1418. `/guild icon steal <guild_id>` - Get the URL of another server's icon (if bot is in it).
1419. `/webhook clone <url> [new_channel] [new_name]` - Clone a webhook's settings to a new channel/name.
1420. `/message format markdown <text>` - Show text formatted as Discord markdown.
1421. `/role permissions neededby [user]` - List permissions a user needs to perform an action (hypothetical).
1422. `/intent checker [command]` - Check which intents are required for a specific command.
1423. `/color harmonies <hex_color> [type]` - Generate color harmonies (complementary, analogous, etc.).
1424. `/unicode block list <block_name>` - List characters within a specific Unicode block.
1425. `/timezone guess [location_name]` - Try to guess the timezone for a location name.
1426. `/member list no_roles` - List members who have no roles.
1427. `/member list bot_added` - List members who were added by bots.
1428. `/purge edited [channel] [limit]` - Purge messages that have been edited.
1429. `/invite link checker <invite_code>` - Check if an invite link is valid and get basic info.
1430. `/level xp decay config [enable|disable] [rate] [inactive_days]` - Configure XP decay for inactivity.
1431. `/level prestige system [enable|disable] [levels_per_prestige] [rewards]` - Configure a prestige system for leveling.
1432. `/economy rob user [user] <amount>` - Attempt to steal currency (minigame, high risk).
1433. `/economy crime [type]` - Commit a virtual crime for a chance of reward or penalty (minigame).
1434. `/image generate style transfer [content_image] [style_image]` - Transfer the style of one image onto another.
1435. `/image generate interpolate [image1] [image2] [steps]` - Generate intermediate frames between two images.
1436. `/music sync playback [user]` - Attempt to sync music playback time with another user (requires external service support).
1437. `/music share current` - Share the currently playing song to the chat.
1438. `/server rules history` - Show the edit history of the server rules (if logged).
1439. `/auditlog suspicious activity report` - Generate a report highlighting potentially suspicious audit log entries.
1440. `/dynamic vc claim orphaned` - Allow users to claim dynamic VCs whose owner left.
1441. `/role membership graph [role]` - Show a graph of how many members had a role over time.
1442. `/ticket statistics [category|support_role]` - Show ticket resolution times, volume by category, etc.
1443. `/starboard random` - Show a random message from the starboard.
1444. `/ai chatbot memory [view|clear]` - View or clear the short-term memory of the AI chatbot.
1445. `/ai image generator settings [view|set] [model|resolution|steps]` - Configure the AI image generator.
1446. `/command cost view [command]` - Show the resource cost (e.g., API calls, processing time) of a command (if tracked).
1447. `/user accent color [user]` - Show a user's profile accent color.
1448. `/server locale distribution` - Show a chart of preferred language settings among server members (if available).
1449. `/message character count <message_id>` - Count characters in a specific message.
1450. `/channel message density [channel] [timeframe]` - Analyze the density of messages (messages per minute/hour).
1451. `/translate auto config [channel] [target_language] [ignored_users|roles]` - Configure auto-translation settings.
1452. `/voice leaderboard active` - Show leaderboard based on current voice activity duration.
1453. `/command permission check [command] [user] [channel]` - Check if a user can run a command in a specific context.
1454. `/error traceback <error_id>` - Show the full traceback for a logged error (owner/admin).
1455. `/suggestion deadline <suggestion_id> <date>` - Set a deadline for feedback on a suggestion.
1456. `/bugreport priority <bug_id> <level>` - Set the priority level for a bug report.
1457. `/application template create [position] [questions...]` - Create a template for staff applications.
1458. `/application template use [template_name]` - Start an application using a template.
1459. `/purge include pinned [channel] [limit]` - Purge messages *including* pinned messages.
1460. `/prune reason <reason>` - Set a default reason for pruning members.
1461. `/channel permission visualizer [channel]` - Show a visual representation of permission overwrites.
1462. `/role member export [role] [csv|json]` - Export a list of members with a specific role.
1463. `/emoji pack export <pack_name>` - Export an emoji pack definition.
1464. `/sticker pack import <pack_name> [file]` - Import a sticker pack from a definition file.
1465. `/thread templates [create|use|list] <name> [channel]` - Create templates for starting threads.
1466. `/forum post template [create|use|list] <name> [forum]` - Create templates for forum posts.
1467. `/activity scheduler [activity_name] <time> <channel>` - Schedule a voice channel activity to be announced/started.
1468. `/tag placeholders list` - List available placeholders (like username, channel) usable in tags.
1469. `/image palette swap [image] [color_map]` - Swap colors in an image based on a mapping.
1470. `/music playlist recommend <playlist_name>` - Recommend songs to add to a playlist based on its content.
1471. `/confession anonymous reply <confession_id> <reply>` - Allow users to anonymously reply to a posted confession.
1472. `/profile commend [user] <reason>` - Give a special commendation visible on a user's profile.
1473. `/pet accessories [list|buy|equip] [item_name]` - Equip accessories on virtual pets.
1474. `/leaderboard activity score [timeframe]` - Show leaderboard based on a combined activity score (messages, voice, reactions).
1475. `/soundboard tag [sound_name] [add|remove|list] <tag>` - Add tags to organize soundboard sounds.
1476. `/gpt code review <code>` - Ask GPT to review a piece of code for potential issues.
1477. `/gpt generate documentation <code>` - Ask GPT to generate documentation comments for code.
1478. `/system info` - Show detailed host system information (OS, CPU, RAM).
1479. `/user banner [user]` - Display a user's profile banner.
1480. `/guild banner steal <guild_id>` - Get the URL of another server's banner (if bot is in it and boosted).
1481. `/webhook relay [source_url] [target_urls...]` - Relay messages from one webhook to others.
1482. `/message format codeblock <language> <text>` - Format text into a code block.
1483. `/role permissions visualizer [role]` - Visualize a role's permissions in a user-friendly way.
1484. `/intent simulator [event_type] [data]` - Simulate receiving a gateway event for testing.
1485. `/color schemes generate [keyword]` - Generate color schemes based on a keyword or theme.
1486. `/unicode font support <character> [font_name]` - Check if a font supports a specific character.
1487. `/timezone events [timezone]` - List upcoming world events (holidays, observances) in a timezone.
1488. `/member list by join date [date_range]` - List members who joined within a specific date range.
1489. `/member list by account age [age_range]` - List members whose accounts were created within a specific age range.
1490. `/purge until <message_id> [channel]` - Purge messages *up to* (and including) a specific message.
1491. `/invite leaderboard weekly` - Show the invite leaderboard for the past week.
1492. `/level role rewards remove <level> [role]` - Remove a role reward for a specific level.
1493. `/level leaderboard server` - Show the server-specific leveling leaderboard (if bot supports global levels).
1494. `/economy bank transfer [user] <amount>` - Transfer currency to another user's bank account.
1495. `/economy bank balance [user]` - Check a user's bank balance.
1496. `/economy deposit <amount>` - Deposit currency into your bank.
1497. `/economy withdraw <amount>` - Withdraw currency from your bank.
1498. `/image generate inpaint [image] [mask_image] <prompt>` - Replace a masked area of an image using AI.
1499. `/image generate outpaint [image] <prompt>` - Extend an image beyond its borders using AI.
1500. `/music history graph [timeframe]` - Show a graph of your music listening history.
1501. `/music genre stats [timeframe]` - Show stats about the genres of music you've listened to.
1502. `/server rules accept log` - Show a log of users who accepted the server rules (if tracked).
1503. `/auditlog alert config [action_type] [channel]` - Configure alerts for specific audit log actions.
1504. `/dynamic vc log` - Show a log of dynamic voice channels being created/deleted.
1505. `/role membership log [role]` - Show a log of users joining/leaving a specific role (if tracked).
1506. `/ticket feedback request [ticket_id]` - Request feedback from the user after a ticket is closed.
1507. `/starboard delete entry [message_id]` - Manually remove a message from the starboard (admin).
1508. `/ai chatbot context [set|view] <context_string>` - Provide persistent context for the AI chatbot's conversations.
1509. `/ai image compare models <prompt>` - Generate an image using the same prompt with different AI models.
1510. `/command dependencies [command]` - List other commands or modules required by a specific command.
1511. `/user banner history [user]` - Show previous profile banners of a user (if logged).
1512. `/server preferred locale set <locale>` - Change the server's preferred language setting.
1513. `/message character frequency [channel] [limit]` - Analyze the frequency of characters used in messages.
1514. `/channel voice user stats [channel]` - Show statistics about users in a voice channel (join/leave times, duration).
1515. `/translate glossary [add|remove|list] <term> <translation>` - Manage a custom glossary for translations.
1516. `/voice activity summary [user] [timeframe]` - Generate a summary report of a user's voice activity.
1517. `/command permission override [command] [role|user|channel] [allow|deny]` - Create specific overrides for command permissions.
1518. `/error details <error_id>` - Show detailed context and variables associated with a logged error (owner).
1519. `/suggestion vote <suggestion_id> [up|down|neutral]` - Vote on a suggestion.
1520. `/bugreport link issue <bug_id> <issue_tracker_url>` - Link a bug report to an external issue tracker.
1521. `/application withdraw <app_id>` - Withdraw your own staff application.
1522. `/purge keep reactions [channel] [limit]` - Purge messages without specific reactions.
1523. `/prune notify [enable|disable]` - Notify users before they are pruned for inactivity.
1524. `/channel permission inheritance [channel]` - Show how permissions are inherited from category/server settings.
1525. `/role member import [role] [file]` - Add members to a role from a list in a file.
1526. `/emoji pack update <pack_name> [file]` - Update an existing emoji pack from a definition file.
1527. `/sticker pack gallery search <query>` - Search public galleries for sticker packs.
1528. `/thread auto archive [thread] <duration>` - Set a custom auto-archive duration for a thread.
1529. `/forum default sort [forum_channel] [latest|creation]` - Set the default sort order for posts in a forum.
1530. `/activity config [activity_name] [setting] [value]` - Configure settings for specific voice channel activities (if applicable).
1531. `/tag group [create|delete|add|remove|list] <group_name> [tag_name]` - Organize tags into groups.
1532. `/image color search [hex_color]` - Search for images dominated by a specific color.
1533. `/music lyrics quiz [song]` - Start a quiz based on song lyrics.
1534. `/confession search <query>` - Search through posted confessions (admin).
1535. `/profile relationship status [set|clear]` - Set a fun relationship status on your profile.
1536. `/pet park [interact]` - Interact with other users' pets in a virtual park.
1537. `/leaderboard command usage [command]` - Show the leaderboard for usage of a specific command.
1538. `/soundboard upload multiple [files...]` - Upload multiple sounds to the soundboard at once.
1539. `/gpt code debugger <code>` - Ask GPT to help debug a piece of code.
1540. `/gpt translate code <source_language> <target_language> <code>` - Ask GPT to translate code between languages.
1541. `/system database stats` - Show statistics about the bot's database (size, query times).
1542. `/user avatar default check [role]` - Check users with a role for default avatars.
1543. `/guild splash steal <guild_id>` - Get the URL of another server's invite splash image.
1544. `/webhook test send [url]` - Send a predefined test message to a webhook.
1545. `/message format table [data]` - Format data into a Discord-friendly markdown table.
1546. `/role permissions matrix` - Display a matrix showing which roles have which key permissions.
1547. `/api endpoint status [endpoint]` - Check the status and latency of a specific Discord API endpoint.
1548. `/color name <hex_color>` - Get the closest matching name for a hex color code.
1549. `/unicode confusables <character>` - List characters that look similar to the input character (confusables).
1550. `/timezone current DST <timezone>` - Check if Daylight Saving Time is currently active for a timezone.
1551. `/member list by game [game_name]` - List members currently playing a specific game.
1552. `/member list by status [status]` - List members with a specific status (online, idle, dnd).
1553. `/purge from user list [users...] [channel] [limit]` - Purge messages from a list of specified users.
1554. `/invite analytics compare [codes...]` - Compare analytics between multiple invite codes.
1555. `/level leaderboard compare [user1] [user2]` - Compare the level/XP progress between two users.
1556. `/level role rewards check [user]` - Check which level role rewards a user is eligible for/has.
1557. `/economy stocks portfolio value [user]` - Show the current total value of a user's stock portfolio.
1558. `/economy crypto portfolio value [user]` - Show the current total value of a user's crypto portfolio.
1559. `/image generate batch <prompt> [count]` - Generate multiple images from the same prompt.
1560. `/image search reverse engine [google|tineye|yandex] [image]` - Perform reverse image search using a specific engine.
1561. `/music sync start session` - Start a listening party session where playback is synced.
1562. `/music sync join session <session_id>` - Join a music sync session.
1563. `/server rules language [add|remove|set] <language> <rules_text>` - Set server rules in multiple languages.
1564. `/auditlog export [format] [filters]` - Export audit log entries to a file.
1565. `/dynamic vc naming scheme [set|view] <scheme>` - Customize the naming scheme for dynamic voice channels (e.g., using game name).
1566. `/role mention graph [role]` - Show a graph of how often a role has been mentioned over time.
1567. `/ticket feedback view [ticket_id]` - View feedback submitted for a closed ticket.
1568. `/starboard leaderboard [timeframe]` - Show users whose messages have received the most stars.
1569. `/ai chatbot personality gallery [browse|set] <name>` - Choose a predefined personality for the AI chatbot.
1570. `/ai image checkpoint list` - List available models/checkpoints for the AI image generator.
1571. `/command execution log [command] [limit]` - Show a log of recent executions for a specific command.
1572. `/user banner steal <user>` - Get the URL of a user's profile banner image.
1573. `/server locale setting <locale>` - Change the server's primary language setting.
1574. `/message reaction stats <message_id>` - Show detailed statistics about reactions on a message.
1575. `/channel category stats [category]` - Show aggregated stats for all channels within a category.
1576. `/translate language support` - List all languages supported by the translation command.
1577. `/voice user mute log [user]` - Show a log of when a user was server muted/unmuted in voice.
1578. `/command permission hierarchy` - Explain the hierarchy for command permission overrides (e.g., user > role > channel).
1579. `/error report template` - Provide a template for users reporting bot errors.
1580. `/suggestion merge <suggestion_id_1> <suggestion_id_2>` - Merge two similar suggestions.
1581. `/bugreport severity <bug_id> <level>` - Set the severity level for a bug report (e.g., critical, minor).
1582. `/application edit <app_id> [answers...]` - Edit your submitted staff application (if allowed).
1583. `/purge keep user [user] [channel] [limit]` - Purge messages *except* those from a specific user.
1584. `/prune list roles [roles...]` - List members who would be pruned based on having specific roles (or lack thereof).
1585. `/channel permission check all [permission]` - Check all channels to see where a specific permission is granted/denied.
1586. `/role member log [role]` - Show a log of members being added/removed from a role (if tracked).
1587. `/emoji pack gallery [submit|browse]` - Submit or browse user-created emoji packs.
1588. `/sticker pack creator [sticker]` - Show who created a specific server sticker.
1589. `/thread starter [thread]` - Show who started a specific thread.
1590. `/forum post creator [post_id]` - Show who created a specific forum post.
1591. `/activity game stats [game_name] [user]` - Show a user's stats for a specific voice channel game (e.g., Poker wins).
1592. `/tag search content <query>` - Search within the content of tags.
1593. `/image color extractor [image] [count]` - Extract the most dominant colors from an image.
1594. `/music lyrics translate <language> [song]` - Translate lyrics to another language.
1595. `/confession block user [user]` - Prevent a user from submitting confessions (admin).
1596. `/profile visitor log [view|clear]` - See who has recently viewed your profile (optional, privacy).
1597. `/pet marketplace [list|buy|sell]` - A player-driven marketplace for virtual pets/items.
1598. `/leaderboard timezones` - Show leaderboard based on user timezone diversity (just for fun).
1599. `/soundboard queue [add|view|clear] [sound]` - Queue up soundboard sounds to play sequentially.
1600. `/gpt rewrite email <email_text> [tone]` - Rewrite an email draft with a different tone (professional, casual, etc.).
1601. `/gpt generate meeting agenda <topic> [points...]` - Generate a meeting agenda based on a topic.
1602. `/system maintenance schedule [set|view] [time] [message]` - Schedule planned maintenance mode (owner).
1603. `/user nickname history [user]` - Show a user's past nicknames in the server (if logged).
1604. `/guild discovery splash steal <guild_id>` - Get the URL of another server's discovery splash.
1605. `/webhook format message <json_payload>` - Preview how a webhook payload will look in Discord.
1606. `/message format diff <text1> <text2>` - Show the differences between two blocks of text.
1607. `/role permissions common [roles...]` - Find common permissions shared between multiple roles.
1608. `/api request raw <method> <endpoint> [json_body]` - Make a raw authenticated Discord API request (owner, dangerous).
1609. `/colorblind simulator [image] [type]` - Simulate how an image looks to users with different types of colorblindness.
1610. `/unicode normalize <text> [form]` - Normalize Unicode text (NFC, NFD, etc.).
1611. `/timezone offset <timezone>` - Show the current UTC offset for a timezone.
1612. `/member list pending verification` - List members who haven't passed server verification checks (if applicable).
1613. `/member list suspicious [criteria]` - List members matching potentially suspicious criteria (e.g., new account, no avatar, recent join).
1614. `/purge urls [domains...] [channel] [limit]` - Purge messages containing links to specific domains.
1615. `/invite creator check [invite_code]` - See who created a specific invite.
1616. `/level xp curve [view|set] [formula]` - Configure the XP formula needed for each level.
1617. `/level leaderboard role [role]` - Show the leveling leaderboard filtered by users with a specific role.
1618. `/economy item shop [list|buy|sell] [item]` - View or interact with the server's item shop.
1619. `/economy item info [item]` - Show details and price of a shop item.
1620. `/image generate controlnet [image] [control_image] <prompt>` - Guide AI image generation using ControlNet models.
1621. `/image search similar [image]` - Find visually similar images online.
1622. `/music autoplay config [genre_bias|playlist_source]` - Configure how autoplay selects songs.
1623. `/music queue duration` - Show the total duration of the current music queue.
1624. `/server rules diff [revision1] [revision2]` - Show changes between versions of server rules (if logged).
1625. `/auditlog anomaly detection [enable|disable]` - Enable automatic detection of unusual audit log patterns.
1626. `/dynamic vc idle cleanup [enable|disable] [duration]` - Automatically delete empty dynamic VCs after a period.
1627. `/role permission grant temp [role] [permission] <duration>` - Temporarily grant a permission to a role.
1628. `/ticket survey config [enable|disable] [questions...]` - Configure post-ticket surveys.
1629. `/starboard message context <message_id>` - Show messages sent before and after a starred message.
1630. `/ai chatbot forget <topic>` - Instruct the AI chatbot to try and forget about a specific topic.
1631. `/ai image style list` - List available preset styles for AI image generation.
1632. `/command usage heatmap [command]` - Show a heatmap of when a command is most frequently used.
1633. `/user profile card [user]` - Generate an image card summarizing a user's profile.
1634. `/server banner generator [template] [text]` - Generate a simple server banner image from a template.
1635. `/message reaction roles summary [message_id]` - Show a summary of configured reaction roles on a message.
1636. `/channel topic history [channel]` - Show the history of topic changes for a channel (if logged).
1637. `/translate clipboard <language>` - Translate text currently on your clipboard (requires client integration/permissions).
1638. `/voice user deafen log [user]` - Show log of when a user was server deafened/undeafened.
1639. `/command permission check multiple [commands...] [user]` - Check permissions for multiple commands at once.
1640. `/error statistics [type|command]` - Show statistics about errors (frequency, types, commands involved).
1641. `/suggestion subscribe <suggestion_id>` - Get notified about updates to a specific suggestion.
1642. `/bugreport subscribe <bug_id>` - Get notified about updates to a specific bug report.
1643. `/application review [start|next|previous] <app_id>` - Start an interactive review process for applications.
1644. `/purge keep role [role] [channel] [limit]` - Purge messages *except* those from users with a specific role.
1645. `/prune export list [days] [role]` - Export a list of members who *would* be pruned.
1646. `/channel permission check role [role] [permission]` - Check all channels for where a role has a specific permission overwrite.
1647. `/role member history [role]` - Show the history of members joining/leaving a role (if tracked).
1648. `/emoji pack suggest [emoji]` - Suggest an emoji to be added to a server pack.
1649. `/sticker pack usage stats [pack_name]` - Show usage statistics for a sticker pack.
1650. `/thread owner [thread]` - Show the owner/creator of a thread.
1651. `/forum stats [forum_channel]` - Show statistics for a forum channel (post count, reply count, active users).
1652. `/activity leaderboard session [activity_name]` - Show leaderboard for the current session of a voice activity.
1653. `/tag ownership transfer request [tag] [user]` - Request ownership transfer of a tag you created.
1654. `/image average color [image]` - Calculate the average color of an image.
1655. `/music lyrics game` - Start a game where users guess the song from lyrics snippets.
1656. `/confession reply view <confession_id>` - View anonymous replies to a confession (admin).
1657. `/profile background suggest <image_url>` - Suggest a background image for admin approval.
1658. `/pet daycare [checkin|checkout]` - Check pets into a daycare to gain passive benefits (economy).
1659. `/leaderboard top messages [timeframe]` - Show users who sent the most messages.
1660. `/soundboard record [start|stop]` - Record audio in a voice channel to create a soundboard clip (requires consent/config).
1661. `/gpt generate summary url <url>` - Ask GPT to summarize the content of a webpage.
1662. `/gpt generate code comments <code>` - Alias for `/gpt generate documentation`.
1663. `/system update check` - Check if a new version of the bot software is available (owner).
1664. `/user avatar history compare [user] [index1] [index2]` - Compare two previous avatars of a user.
1665. `/guild widget image [guild_id]` - Get the server widget image URL.
1666. `/webhook delete multiple [urls...]` - Delete multiple webhooks at once.
1667. `/message format timestamp <datetime_string> [style]` - Format a date/time string into various Discord timestamp styles.
1668. `/role permissions difference [role1] [role2]` - Show permissions role1 has but role2 doesn't, and vice-versa.
1669. `/api status history` - Show historical uptime/status for the Discord API.
1670. `/color blend <color1> <color2> [ratio]` - Blend two colors together.
1671. `/unicode emoji source <emoji>` - Show the Unicode code points that make up a complex emoji.
1672. `/timezone map compare [tz1] [tz2]` - Show a map highlighting two timezones and their difference.
1673. `/member list missing role [role]` - List members who *do not* have a specific role.
1674. `/member list nickname [regex_pattern]` - List members whose nicknames match a regex pattern.
1675. `/purge reactions specific <emoji> [channel] [limit]` - Purge messages containing a specific reaction.
1676. `/invite usage graph [invite_code] [timeframe]` - Show a graph of invite usage over time.
1677. `/level xp modifier temp [user] <multiplier> <duration>` - Grant a temporary XP multiplier to a user.
1678. `/level leaderboard weekly` - Show the leveling leaderboard for the current week.
1679. `/economy stocks buy limit <symbol> <price> <amount>` - Place a limit buy order for stocks.
1680. `/economy crypto sell stoploss <symbol> <price> <amount>` - Place a stop-loss sell order for crypto.
1681. `/image generate restore faces [image]` - Attempt to fix distorted faces in AI-generated images.
1682. `/image ocr translate [image] <language>` - Extract text from an image and translate it.
1683. `/music queue analyze` - Analyze the current queue for genre diversity, average song length, etc.
1684. `/music skip ratio [set|view] <ratio>` - Set the ratio of votes needed to skip a song.
1685. `/server rules translate <language>` - Display the server rules translated into a specific language.
1686. `/auditlog user summary [user] [timeframe]` - Summarize a user's actions recorded in the audit log.
1687. `/dynamic vc transfer ownership [channel] [user]` - Transfer ownership of a dynamic VC.
1688. `/role permissions optimize [role]` - Suggest removing potentially redundant permissions from a role.
1689. `/ticket merge [ticket_id_1] [ticket_id_2]` - Merge two related tickets together.
1690. `/starboard ignore message <message_id>` - Prevent a specific message from ever appearing on the starboard.
1691. `/ai chatbot rate limit [set|view] [limit] [duration]` - Set rate limits for AI chatbot usage.
1692. `/ai image rate limit [set|view]` - Set rate limits for AI image generation.
1693. `/command cooldown bypass [role|user]` - Allow specific roles/users to bypass command cooldowns.
1694. `/user avatar dominant color [user]` - Get the dominant color of a user's avatar.
1695. `/server banner dominant color` - Get the dominant color of the server banner.
1696. `/message reaction role cleanup` - Remove reaction role entries for deleted messages or roles.
1697. `/channel name history [channel]` - Show the history of name changes for a channel (if logged).
1698. `/translate suggestion <source_text> <language> <suggested_translation>` - Suggest an improvement for a translation.
1699. `/voice user activity graph [user] [timeframe]` - Show a graph of a user's voice activity over time.
1700. `/command permission simulator [user] [channel] [command]` - Simulate running a command to see if permissions pass.
1701. `/error subscribe [type|command]` - Get notified when specific errors occur (admin).
1702. `/suggestion deadline notify <suggestion_id>` - Notify users about an upcoming feedback deadline.
1703. `/bugreport reproduce steps <bug_id> <steps>` - Add steps to reproduce a bug.
1704. `/application scoring [app_id] [criteria] <score>` - Score applications based on predefined criteria.
1705. `/purge keep filetype <extension> [channel] [limit]` - Purge messages *except* those with specific file types.
1706. `/prune message user [user]` - Send a custom message to users before pruning them.
1707. `/channel permission check category [category] [permission]` - Check all channels in a category for a permission overwrite.
1708. `/role mention check [role]` - Check if a role is currently mentionable.
1709. `/emoji pack install <pack_name>` - Add all emojis from a known pack to the server.
1710. `/sticker pack install <pack_name>` - Add all stickers from a known pack.
1711. `/thread notification settings [thread] [all|mentions|none]` - Change your notification settings for a specific thread.
1712. `/forum notification settings [forum] [all|mentions|none]` - Change notification settings for a forum channel.
1713. `/activity stats leaderboard [activity_name]` - Show the leaderboard for a specific voice activity.
1714. `/tag info detailed [tag]` - Show detailed info including creation date, last used, total uses.
1715. `/image histogram [image]` - Show the color histogram of an image.
1716. `/music quiz leaderboard` - Show the leaderboard for the lyrics quiz game.
1717. `/confession anonymous report <confession_id> [reason]` - Allow users to anonymously report a problematic confession.
1718. `/profile relationship goals [set|view] <text>` - Set fun relationship goals on your profile.
1719. `/pet hospital [heal|revive]` - Heal or revive injured virtual pets (economy).
1720. `/leaderboard server age` - Show leaderboard based on how long users have been in the server.
1721. `/soundboard play loop <sound_name> [count]` - Loop a soundboard sound a specific number of times.
1722. `/gpt analyze writing <text>` - Ask GPT to analyze writing style, tone, and suggest improvements.
1723. `/gpt generate test cases <code>` - Ask GPT to generate test cases for a piece of code.
1724. `/system network latency [destination]` - Measure network latency to a specific host/IP.
1725. `/user avatar check animated [role]` - Check users with a role for animated avatars.
1726. `/guild template apply simulate <code>` - Simulate applying a server template without making changes.
1727. `/webhook list all` - List all webhooks created by the bot in the server.
1728. `/message format spoiler <text>` - Format text as a spoiler.
1729. `/role permissions template create <name> [permissions...]` - Create a template for a set of permissions.
1730. `/role permissions template apply <name> [role]` - Apply a permission template to a role.
1731. `/api rate limit simulator [count] [duration]` - Simulate hitting API rate limits for testing.
1732. `/color info <hex|rgb|hsl|name>` - Get detailed information about a color (conversions, name, etc.).
1733. `/unicode block info <block_name>` - Show information about a Unicode block (range, characters).
1734. `/timezone world map` - Show a world map with current time zones overlaid.
1735. `/member list joined today` - List members who joined the server today.
1736. `/member list account age new <days>` - List members whose Discord accounts are newer than X days.
1737. `/purge has link [channel] [limit]` - Purge messages that contain any URL/link.
1738. `/invite summary` - Show a summary of server invites (total uses, active invites, top inviters).
1739. `/level xp boost server [multiplier] <duration> [reason]` - Apply a server-wide XP boost event.
1740. `/level leaderboard inactive [days]` - Show users who haven't gained XP recently.
1741. `/economy leaderboard networth [user]` - Show leaderboard based on combined balance + item value.
1742. `/economy audit log [user] [action]` - View a log of a user's economic transactions (admin).
1743. `/image generate remix [image1] [image2] [prompt]` - Remix elements of two images based on a prompt.
1744. `/image search filter [license|size|type] <query>` - Filter image search results by license, size, or type.
1745. `/music autoplay next` - Show which song autoplay will play next.
1746. `/music queue vote [add|remove] <query>` - Allow users to vote on songs to add to the queue.
1747. `/server rules review request` - Request moderators to review updated server rules.
1748. `/auditlog revert action <action_id>` - Attempt to revert an action recorded in the audit log (very risky, limited support).
1749. `/dynamic vc size adjust [enable|disable]` - Automatically adjust dynamic VC user limits based on usage.
1750. `/role permissions history compare [role] [date1] [date2]` - Compare role permissions between two points in time (if logged).
1751. `/ticket priority auto assign [keywords] <level>` - Automatically assign ticket priority based on keywords.
1752. `/starboard pin message <message_id>` - Pin a message when it reaches the starboard threshold.
1753. `/ai chatbot thread create <topic>` - Create a dedicated thread for a conversation with the AI chatbot.
1754. `/ai image generator queue [view|clear]` - View or clear the queue for AI image generation jobs.
1755. `/command execution time [command]` - Show average execution time for a command.
1756. `/user nickname check duplicates` - Find users with the same nickname.
1757. `/server boost message config [channel|message|image]` - Configure messages sent when server gains/loses boost levels.
1758. `/message reaction role limit [message_id] <limit>` - Set a max number of reaction roles users can pick from a message.
1759. `/channel activity report [channel] [timeframe]` - Generate a report summarizing channel activity.
1760. `/translate custom engine [add|remove|set] <name> <api_details>` - Configure use of custom translation engines.
1761. `/voice user microphone check [user]` - Ask bot to check if it can detect audio from a user (requires listening permissions).
1762. `/command permission debug [user] [channel] [command]` - Step-by-step debug of why a user can/cannot run a command.
1763. `/error report external <error_id> [url]` - Link an internal error report to an external tracker.
1764. `/suggestion discussion thread <suggestion_id>` - Create a dedicated thread for discussing a suggestion.
1765. `/bugreport link commit <bug_id> <commit_hash>` - Link a bug report to the commit that fixed it.
1766. `/application template list` - List available staff application templates.
1767. `/purge keep pattern <regex> [channel] [limit]` - Purge messages *except* those matching a regex.
1768. `/prune simulate detailed [days] [role]` - Show exactly which users would be pruned.
1769. `/channel permission check user [user] [permission]` - Check all channels for where a user has a specific permission overwrite.
1770. `/role hoist check` - Check which roles are currently set to be hoisted.
1771. `/emoji search external <query>` - Search external emoji galleries (e.g., emoji.gg).
1772. `/sticker search external <query>` - Search external sticker galleries.
1773. `/thread auto add users [thread] [role]` - Automatically add users with a role to new threads.
1774. `/forum auto tag [forum_channel] [keywords] <tag>` - Automatically tag new posts based on keywords.
1775. `/activity user stats [user]` - Show a user's overall stats across different voice activities.
1776. `/tag backup [create|load]` - Backup or load server tags from a file.
1777. `/image glitch art [image] [options]` - Create glitch art with specific parameters.
1778. `/music lyrics analyze <song>` - Analyze lyrics for sentiment, word frequency, etc.
1779. `/confession schedule post <confession_id> <time>` - Schedule an approved confession to be posted later.
1780. `/profile status emoji [set|clear] <emoji>` - Set a status emoji on your profile.
1781. `/pet fusion [pet1] [pet2]` - Attempt to fuse two pets into a new one (minigame).
1782. `/leaderboard reaction score [timeframe]` - Show leaderboard based on combined reactions given/received.
1783. `/soundboard play private [sound_name]` - Play a soundboard sound only you can hear.
1784. `/gpt generate presentation outline <topic> [slides]` - Generate an outline for a presentation.
1785. `/gpt generate email subject <email_body>` - Suggest email subject lines based on the body text.
1786. `/system process kill <pid>` - Kill a specific process on the bot host (owner, dangerous).
1787. `/user status history [user] [timeframe]` - Show user status changes over a specific period.
1788. `/guild features list` - List all available Discord guild features and server's status.
1789. `/webhook modify <url> [name|avatar|channel]` - Modify an existing webhook's properties.
1790. `/message format embed visualizer [json]` - Visualize an embed JSON as it would appear in Discord.
1791. `/role permissions missing [role] [permissions...]` - List specified permissions that a role *lacks*.
1792. `/api debug request <request_id>` - Get debug information for a specific outgoing API request made by the bot.
1793. `/color palette generate [image|keyword]` - Generate a color palette from an image or keyword.
1794. `/unicode text tools [upsidedown|reverse|zalgo]` - Apply various fun Unicode text transformations.
1795. `/timezone city <city_name>` - Find the timezone for a specific city.
1796. `/member list booster` - List all current server boosters.
1797. `/member list recent leave [count]` - List the last X members who left the server.
1798. `/purge has attachment [channel] [limit]` - Purge messages that contain any attachment.
1799. `/invite settings view` - View current server invite settings (e.g., max age, max uses defaults).
1800. `/level xp leaderboard [channel]` - Show XP leaderboard specifically for activity within a channel.
1801. `/level reset server` - Reset all level/XP data for the server (admin, dangerous).
1802. `/economy shop log` - View a log of transactions from the server shop (admin).
1803. `/economy gambling stats [user]` - Show a user's overall gambling statistics (wins, losses, net).
1804. `/image generate interpolate gif [image1] [image2] [steps]` - Create a GIF interpolating between two images.
1805. `/image caption bulk [images...] <caption_template>` - Add captions to multiple images using a template.
1806. `/music radio stations [list|add|remove] <name> <url>` - Manage custom internet radio stations.
1807. `/music queue import spotify <playlist_url>` - Import a Spotify playlist into the queue.
1808. `/server rules accept role [role]` - Assign a role to users who accept the rules.
1809. `/auditlog webhook filter [url] [action_types]` - Filter which audit log events get sent to a webhook.
1810. `/dynamic vc prefix [set|view] <prefix>` - Set a prefix for the names of dynamic voice channels.
1811. `/role permissions remove temp [role] [permission]` - Remove a temporarily granted permission early.
1812. `/ticket export [format] [filters]` - Export ticket data (metadata, transcripts) based on filters.
1813. `/starboard halloffame [count]` - Show messages with the highest star counts ever.
1814. `/ai chatbot training data [add|remove|view] <text>` - Add/remove custom training data snippets (advanced).
1815. `/ai image model manager [list|load|unload] <model_name>` - Manage loaded AI image generation models (owner).
1816. `/command alias check <alias>` - Check if an alias is already taken (globally or personally).
1817. `/user banner dominant color [user]` - Get the dominant color of a user's profile banner.
1818. `/server splash dominant color` - Get the dominant color of the server invite splash.
1819. `/message reaction role sync [message_id]` - Check and fix users who have roles inconsistent with reactions.
1820. `/channel slowmode schedule [channel] <cron_time> <seconds>` - Schedule slowmode to turn on/off at specific times.
1821. `/translate engine status` - Check the status of the configured translation engine/API.
1822. `/voice channel status [channel]` - Show status of a voice channel (bitrate, user limit, region, connected users).
1823. `/command permission export` - Export the bot's command permission configuration.
1824. `/command permission import [file]` - Import command permissions from a configuration file.
1825. `/error log rotation config [size|time]` - Configure automatic rotation/pruning of error logs.
1826. `/suggestion link issue <suggestion_id> <issue_url>` - Link a suggestion to an external issue tracker item.
1827. `/bugreport unresolve <bug_id>` - Reopen a previously resolved bug report.
1828. `/application archive <app_id>` - Archive an old staff application.
1829. `/purge keep pinned only [channel] [limit]` - Purge all messages *except* pinned ones.
1830. `/prune list exempt` - List users/roles currently exempt from pruning.
1831. `/channel permission compare [channel1] [channel2]` - Compare permission overwrites between two channels.
1832. `/role hierarchy position [role]` - Show the numerical position of a role in the hierarchy.
1833. `/emoji upload multiple [files...] [names...]` - Upload multiple emoji images at once.
1834. `/sticker upload multiple [files...] [names...]` - Upload multiple sticker files at once.
1835. `/thread list user [user]` - List threads a user is currently participating in.
1836. `/forum post stats [post_id]` - Show stats for a forum post (views, replies, reactions).
1837. `/activity recommend` - Recommend a voice channel activity based on currently connected users.
1838. `/tag execute permission [tag_name] [role|user]` - Set who can execute a tag (if runnable).
1839. `/image text outline [image] [text] [color] [outline_color]` - Add text with an outline.
1840. `/music lyrics source [song]` - Show the source/provider of the lyrics.
1841. `/confession edit <confession_id> <new_text>` - Edit a confession before it's posted (admin).
1842. `/profile field custom create <name> <type>` - Create custom fields for user profiles (admin).
1843. `/profile field custom set <field_name> <value>` - Set a value for a custom profile field.
1844. `/pet training [pet_name] [skill]` - Train virtual pets in different skills.
1845. `/leaderboard custom metric [metric_name]` - Show leaderboard for a specific custom metric.
1846. `/soundboard download <sound_name>` - Download the audio file for a soundboard sound.
1847. `/gpt dialogue generate <characters> <scenario>` - Generate dialogue between characters in a scenario.
1848. `/gpt code optimize <code>` - Ask GPT for suggestions on optimizing code performance or readability.
1849. `/system disk io stats` - Show disk read/write statistics.
1850. `/user avatar animated check [role]` - Check users with a role for animated avatars.
1851. `/guild roles export [format]` - Export all server roles and their permissions.
1852. `/webhook permissions check [url]` - Verify if the bot has permissions to send messages via a webhook URL.
1853. `/message format quote <text>` - Format text as a Discord block quote.
1854. `/role permissions effective user [user] [role]` - Show the effective permissions a user gets *from* a specific role.
1855. `/api latency graph [endpoint] [timeframe]` - Graph the latency to a Discord API endpoint over time.
1856. `/color gradient generate [color1] [color2] [steps]` - Generate a color gradient between two colors.
1857. `/unicode emoji combinations [emoji]` - Show valid ZWJ sequences or combinations for an emoji.
1858. `/timezone location <lat> <lon>` - Find the timezone for a specific latitude/longitude.
1859. `/member list roleless` - Alias for `/member list no_roles`.
1860. `/member list timeout` - List members currently in timeout.
1861. `/purge has sticker [channel] [limit]` - Purge messages containing stickers.
1862. `/invite prune simulate [min_uses] [max_age]` - Simulate pruning invites without actually deleting them.
1863. `/level xp curve graph` - Show a graph of the XP required per level.
1864. `/level leaderboard monthly` - Show the leveling leaderboard for the current month.
1865. `/economy stocks order book <symbol>` - Show the current order book (bids/asks) for a stock.
1866. `/economy crypto price alert list` - List your active crypto price alerts.
1867. `/image generate diffusers list` - List available diffusion models/schedulers.
1868. `/image search google lens [image]` - Perform a Google Lens search on an image.
1869. `/music queue suggest [count]` - Suggest songs to add to the queue based on current content.
1870. `/music dj mode [enable|disable]` - Enable DJ mode where only specific roles can control music.
1871. `/server rules last updated` - Show when the server rules were last updated (if tracked).
1872. `/auditlog ip lookup [ip_address]` - Look up geolocation info for an IP found in audit logs.
1873. `/dynamic vc category [set|view] <category>` - Set the category where new dynamic VCs are created.
1874. `/role permissions log search <role> <permission> [timeframe]` - Search permission change logs for a role.
1875. `/ticket close survey results [ticket_id]` - View results of a post-ticket survey.
1876. `/starboard leaderboard user [user]` - Show how many stars a specific user's messages have received.
1877. `/ai chatbot interaction log [limit]` - View a log of recent interactions with the AI chatbot.
1878. `/ai image generation history [user] [limit]` - View a user's AI image generation history.
1879. `/command popularity list` - List commands sorted by recent popularity/usage.
1880. `/user profile background history [user]` - Show previous profile backgrounds used by a user (if logged).
1881. `/server welcome message test [user]` - Test the welcome message using a specific user's details.
1882. `/message reaction roles check [message_id]` - Check the status and configuration of reaction roles on a message.
1883. `/channel lock schedule [channel] <cron_time> [duration]` - Schedule channel locking/unlocking.
1884. `/translate language name <language_code>` - Get the common name for a language code (e.g., 'en' -> 'English').
1885. `/voice channel recording [start|stop] [channel]` - Record audio in a voice channel (requires significant setup, consent, storage).
1886. `/command permission list roles [command]` - List roles that have explicit allow/deny permissions for a command.
1887. `/error log search <query>` - Search the error log for specific keywords or error types.
1888. `/suggestion anonymous [toggle]` - Allow submitting suggestions anonymously.
1889. `/bugreport anonymous [toggle]` - Allow submitting bug reports anonymously.
1890. `/application view anonymous [app_id]` - View an application with applicant info anonymized (if supported).
1891. `/purge keep link domain [domain] [channel] [limit]` - Purge messages *except* those linking to a specific domain.
1892. `/prune inactivity threshold [set|view] <days>` - Set the number of days of inactivity before pruning.
1893. `/channel permission list templates` - List available channel permission templates.
1894. `/role hierarchy check loops` - Check for potential loops or inconsistencies in the role hierarchy.
1895. `/emoji usage stats [emoji] [timeframe]` - Show emoji usage statistics over a specific period.
1896. `/sticker usage stats [sticker] [timeframe]` - Show sticker usage statistics over a specific period.
1897. `/thread list inactive <days>` - List threads that have been inactive for a certain number of days.
1898. `/forum activity heatmap [forum_channel] [timeframe]` - Show a heatmap of post/reply activity in a forum.
1899. `/activity lottery` - Start a lottery activity where users can buy tickets.
1900. `/tag search owner <user>` - Search for tags created by a specific user.
1901. `/image deepdream [image]` - Apply a DeepDream effect to an image.
1902. `/music volume default [set|view] <level>` - Set the default music volume for the server.
1903. `/confession keywords filter [add|remove|list] <word>` - Filter confessions containing specific keywords before posting.
1904. `/profile field custom list` - List all custom profile fields configured for the server.
1905. `/pet leaderboard [skill|level]` - Show leaderboards for virtual pet skills or levels.
1906. `/leaderboard most active day` - Show which day of the week is typically most active.
1907. `/soundboard permissions [sound_name] [role|user]` - Set permissions for who can play a specific soundboard sound.
1908. `/gpt generate code explanation <language> <code>` - Ask GPT to explain code in a specific language.
1909. `/gpt analyze text complexity <text>` - Analyze the complexity (e.g., Flesch reading ease) of text.
1910. `/system resource limits` - Show configured resource limits for the bot process (e.g., memory, CPU).
1911. `/user avatar source <user>` - Get the source image file for a user's avatar.
1912. `/guild integrations list [type]` - List server integrations filtered by type (webhook, bot, twitch).
1913. `/webhook rate limit info [url]` - Check rate limit information specifically for a webhook URL.
1914. `/message format list <items...>` - Format items into a Discord markdown list (bulleted or numbered).
1915. `/role permissions check user [user] [role]` - Check if a user actually has a specific role.
1916. `/api request history [limit]` - Show a history of recent API requests made by the bot.
1917. `/color contrast ratio [color1] [color2]` - Calculate the WCAG contrast ratio between two colors.
1918. `/unicode text direction <text>` - Check/force the text direction (LTR/RTL) using Unicode markers.
1919. `/timezone difference <tz1> <tz2>` - Calculate the time difference between two timezones.
1920. `/member list platform [desktop|mobile|web]` - List members currently using a specific platform.
1921. `/member list activity type [playing|streaming|listening|watching]` - List members by their current activity type.
1922. `/purge has embed [channel] [limit]` - Purge messages that contain any embed.
1923. `/invite delete code <code>` - Delete a specific server invite by its code.
1924. `/level role rewards stack [enable|disable]` - Configure if level role rewards stack or replace lower level roles.
1925. `/level leaderboard change [timeframe]` - Show who gained the most levels/XP in a timeframe.
1926. `/economy item create [name] [price] [description] [role_requirement]` - Create a shop item requiring a specific role to buy.
1927. `/economy pay anonymous [user] <amount>` - Anonymously transfer currency to another user.
1928. `/image generate segmentation [image]` - Perform image segmentation to identify different objects.
1929. `/image search metadata <key:value> <query>` - Search images based on metadata tags (if available).
1930. `/music queue mode [normal|dynamic]` - Set queue mode (normal=play added songs, dynamic=autoplay related songs).
1931. `/music queue history` - Show the history of songs played in the current session.
1932. `/server rules accept reset [user]` - Reset the rules acceptance status for a user.
1933. `/auditlog retention policy [view|set] <days>` - Configure how long audit logs are kept by the bot (if stored locally).
1934. `/dynamic vc bitrate default [set|view] <bitrate>` - Set the default bitrate for new dynamic VCs.
1935. `/role permissions audit log [role]` - Show audit log entries related to changes in a role's permissions.
1936. `/ticket user history [user]` - Show history of tickets created by or involving a user.
1937. `/starboard threshold dynamic [enable|disable] [base_stars] [member_ratio]` - Dynamically adjust star threshold based on server size.
1938. `/ai chatbot usage stats [user]` - Show AI chatbot usage statistics for a specific user.
1939. `/ai image usage stats [user]` - Show AI image generation usage statistics for a user.
1940. `/command disable reason [command] <reason>` - Provide a reason when disabling a command.
1941. `/user profile comment [user] <comment>` - Leave a public comment on another user's profile (if enabled).
1942. `/server boost leaderboard current` - Show leaderboard of current server boosters.
1943. `/message reaction role list [message_id]` - List configured reaction roles on a message.
1944. `/channel lock message [channel] <message>` - Set a custom message displayed when a channel is locked.
1945. `/translate provider status` - Check the status of the underlying translation service API.
1946. `/voice user stream check [user]` - Check if a user is currently streaming/screensharing in voice.
1947. `/command permission list groups` - List all defined command permission groups.
1948. `/error frequency graph [timeframe]` - Show a graph of error frequency over time.
1949. `/suggestion status set <suggestion_id> <status_text>` - Set a custom status for a suggestion.
1950. `/bugreport tag [bug_id] [add|remove] <tag>` - Add tags to categorize bug reports.
1951. `/application status set <app_id> <status_text>` - Set a custom status for an application (e.g., 'Interviewing').
1952. `/purge interactive` - Start an interactive purge wizard to select options.
1953. `/prune exempt add [user|role]` - Add a user or role to the prune exemption list.
1954. `/prune exempt remove [user|role]` - Remove a user or role from the prune exemption list.
1955. `/channel permission list groups` - List channel permission templates/groups.
1956. `/role check unused` - List roles that have no permissions and no members (potentially safe to delete).
1957. `/emoji sync server [server_id]` - Attempt to sync emojis from another server the bot is in (admin, needs perms).
1958. `/sticker sync server [server_id]` - Attempt to sync stickers from another server.
1959. `/thread list active [min_participants]` - List active threads with a minimum number of participants.
1960. `/forum prune posts <forum_channel> [inactive_days] [min_replies]` - Prune old or inactive forum posts.
1961. `/activity create custom <name> <url>` - Add a custom link/URL as a voice channel activity.
1962. `/tag execute context <name> [channel] [user]` - Execute a tag providing specific channel/user context.
1963. `/image caption font [list|set] <font_name>` - Set the default font for image captions.
1964. `/music lyrics save <song>` - Save the lyrics of the current or specified song locally.
1965. `/confession block anonymous` - Block all anonymous confessions temporarily.
1966. `/profile field custom delete <name>` - Delete a custom profile field (admin).
1967. `/pet rename <old_name> <new_name>` - Rename your virtual pet.
1968. `/leaderboard command errors` - Show users who encounter the most command errors.
1969. `/soundboard play overlay [sound1] [sound2]` - Play two sounds simultaneously.
1970. `/gpt brainstorm alternatives <idea>` - Ask GPT to brainstorm alternatives to a given idea.
1971. `/gpt create poll <topic> [options_count]` - Ask GPT to generate poll questions and options.
1972. `/system restart shard <shard_id>` - Restart a specific shard process (owner).
1973. `/user avatar generate pattern [user]` - Generate a pattern image based on a user's avatar colors.
1974. `/guild auditlog retention` - View Discord's default audit log retention period for the server.
1975. `/webhook list permissions [url]` - List permissions required by a specific webhook URL.
1976. `/message format header <level> <text>` - Format text as a Discord markdown header (using #).
1977. `/role permissions granted by [permission]` - List roles that directly grant a specific permission.
1978. `/api response inspector <request_id>` - Inspect the raw response body for a previous API request.
1979. `/colorblind simulate text <color1> <color2> <text>` - Show how text looks with specific foreground/background colors under simulation.
1980. `/unicode regional indicators <text>` - Convert text to regional indicator flag emojis (e.g., US -> 🇺🇸).
1981. `/timezone location lookup <location_name>` - Find latitude/longitude for a location name.
1982. `/member list moderator` - List all members identified as moderators (via role config).
1983. `/member list admin` - List all members with Administrator permission.
1984. `/purge reactions count <min_count> [channel] [limit]` - Purge messages with fewer than a minimum number of reactions.
1985. `/invite revoke code <code>` - Revoke a specific invite code.
1986. `/level role rewards temporary <level> <role> <duration>` - Grant a temporary role reward upon reaching a level.
1987. `/level leaderboard server rank [user]` - Show a user's global rank across all servers (if supported).
1988. `/economy item gift [user] <item_name>` - Gift an item from the shop to another user.
1989. `/economy sell all [item_name]` - Sell all instances of a specific item from your inventory.
1990. `/image generate prompt from image [image]` - Generate a text prompt describing an image using AI.
1991. `/image search licensed [cc0|commercial] <query>` - Search for images with specific licenses.
1992. `/music queue priority [add|view|clear] <query>` - Add songs to a priority queue that plays next.
1993. `/music autoplay whitelist [add|remove|list] [artist|genre]` - Whitelist artists/genres for autoplay.
1994. `/server rules timestamp` - Add timestamps to different sections of the server rules.
1995. `/auditlog webhook status [url]` - Check the status and error rate of an audit log webhook.
1996. `/dynamic vc user limit default [set|view] <limit>` - Set the default user limit for new dynamic VCs.
1997. `/role permissions check redundant [role]` - Check for permissions that are implicitly granted by others (e.g., Admin implies all).
1998. `/ticket custom fields [add|remove|list] <name> <type>` - Add custom fields to tickets (e.g., product area, urgency).
1999. `/starboard channel topic [set|clear] <text>` - Set the topic for the starboard channel.
2000. `/ai chatbot feedback <message_id> [good|bad] [comment]` - Provide feedback on a specific AI chatbot response.
