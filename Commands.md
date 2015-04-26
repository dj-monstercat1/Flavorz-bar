Commands:
2	=========
3	
4	X specifies a number
5	arguments between ( ) are optional
6	
7	
8	Manager
9	-------
10	
11	|Command | Arguments |  Description |
12	|:------:|:---------:|:--------------------------------------:|
13	|!afklimit | X | sets the maximum afk time |
14	|!clearchat | |clears the chat |
15	|!cycle | | toggle DJ cycle |
16	|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |
17	|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
18	|!refresh | | refreshes the browser of whoever runs the bot |
19	|!usercmdcd | X | set the cooldown on commands by grey users |
20	|!usercommands | | toggle user commands |
21	|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit. |
22	
23	Bouncer+
24	--------
25	
26	|Command | Arguments |  Description |
27	|:------:|:---------:|:--------------------------------------:|
28	|!add | @user | add user to the waitlist |
29	|!afkremoval | | toggles the afk check |
30	|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) |
31	|!bouncer+ | | disable bouncer+ |
32	|!deletechat | @user | delete all the chats by a certain user |
33	|!lock | | lock the waitlist |
34	|!lockdown | | lock down the room: only staff can chat |
35	|!maxlength | X | specify the maximum length a song can be when timeguard is enabled |
36	|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
37	|!remove | @user | remove user from the waitlist |
38	|!roulette | | start a roulette |
39	|!songstats | | toggle song statistics |
40	|!unlock | | unlock the waitlist |
41	|!welcome | | toggle the welcome message on user join |
42	
43	Bouncer
44	-------
45	
46	|Command | Arguments |  Description |
47	|:------:|:---------:|:--------------------------------------:|
48	|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
49	|!afkreset | @user | resets the afk time of user |
50	|!afktime | @user | shows how long user has been afk |
51	|!ban | @user | bans user for 1 day |
52	|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
53	|!blinfo | | get information required to blacklist a song |
54	|!cycleguard | | toggles the cycleguard |
55	|!dclookup / !dc | (@user) | do dclookup for user |
56	|!english | @user | ask user to speak english (asked in the language they set plug to) |
57	|!eta | (@user) | shows when user will reach the booth |
58	|!filter | | toggles the chat filter |
59	|!jointime | @user | shows how long the user has been in the room |
60	|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
61	|!kill | | shut down the bot |
62	|!lockguard | | toggle the lockguard |
63	|!lockskip | (reason) | skip the song and move the dj back up (the position can be set with !lockskippos) |
64	|!lockskippos | X | set the position to which lockskip moves the dj |
65	|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
66	|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
67	|!reload | | reload the bot |
68	|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
69	|!sessionstats | | display stats for the current session |
70	|!skip | | skip the current song |
71	|!status | | display the bot's status and some settings |
72	|!timeguard | | toggle the timeguard |
73	|!togglebl | | toggle the blacklist |
74	|!togglemotd | | toggle the motd |
75	|!togglevoteskip | | toggle the voteskip |
76	|!unban | @user | unban user |
77	|!unmute | | unmute user |
78	|!voteratio | @user | display the vote statistic for a user |
79	
80	Resident DJ
81	-----------
82	
83	|Command | Arguments |  Description |
84	|:------:|:---------:|:--------------------------------------:|
85	|!link | | give a link to the current song
86	
87	
88	
89	User
90	----
91	
92	|Command | Arguments |  Description |
93	|:------:|:---------:|:--------------------------------------:|
94	|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
95	|!ba | | explains the Brand Ambassador rank |
96	|!commands | | gives a link to the commands |
97	|!cookie | (@user) | give a cookie to user |
98	|!dclookup / !dc | | use dclookup on yourself |
99	|!emoji | | a link to a list with emoji's |
100	|!eta | | shows how long before you reach the booth |
101	|!fb | | links to the room's Facebook page (if set in the settings) |
102	|!help | | links to an image to help get people started on plug |
103	|!join | | join the roulette if it's up |
104	|!leave | | leave the roulette if you joined |
105	|!link | | when the user is the DJ, give a link to the current song |
106	|!op | | links to the OverPlayed list (if set in the settings) |
107	|!ping | | pong! |
108	|!rules | | links to the rules (if set in the settings) |
109	|!theme | | links to the room's theme (if set in the settings) |
110	|!website | | links to the room's website (if set in the settings) |
111	|!youtube | | links to the room's youtube page (if set in the settings) |
