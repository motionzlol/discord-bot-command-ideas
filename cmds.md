# Bot Command Ideas

Here is a list of potential command ideas for the Discord bots.

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
