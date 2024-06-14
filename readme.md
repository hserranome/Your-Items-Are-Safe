<h2>Your Items Are Safe</h2>
<p><a href="https://github.com/Serilum/Your-Items-Are-Safe"><img src="https://serilum.com/assets/data/logo/your-items-are-safe.png"></a></p><h2>Download</h2>
<p>You can download Your Items Are Safe on CurseForge and Modrinth:</p><p>&nbsp;&nbsp;CurseForge: &nbsp;&nbsp;<a href="https://curseforge.com/minecraft/mc-mods/your-items-are-safe">https://curseforge.com/minecraft/mc-mods/your-items-are-safe</a><br>&nbsp;&nbsp;Modrinth: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://modrinth.com/mod/your-items-are-safe">https://modrinth.com/mod/your-items-are-safe</a></p>
<h2>Issue Tracker</h2>
<p>To keep a better overview of all mods, the issue tracker is located in a separate repository.<br>&nbsp;&nbsp;For issues, ideas, suggestions or anything else, please follow this link:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;-> <a href="https://serilum.com/url/issue-tracker">Issue Tracker</a></p>
<h2>Pull Requests</h2>
<p>Because of the way mod loader files are bundled into one jar, some extra information is needed to do a PR.<br>&nbsp;&nbsp;A wiki page entry about it is available here:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;-> <a href="https://serilum.com/url/pull-requests">Pull Request Information</a></p>
<h2>Mod Description</h2>
<p style="text-align:center"><a href="https://serilum.com/" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/header/header.png" alt="" width="838" height="400"></a></p>
<p style="text-align:center"><a href="https://curseforge.com/members/serilum/projects" rel="nofollow"><img src="https://raw.githubusercontent.com/Serilum/.data-workflow/main/badges/svg/curseforge.svg" width="200"></a> <a href="https://modrinth.com/user/Serilum" rel="nofollow"><img src="https://raw.githubusercontent.com/Serilum/.data-workflow/main/badges/svg/modrinth.svg" width="200"></a> <a href="https://patreon.com/serilum" rel="nofollow"><img src="https://raw.githubusercontent.com/Serilum/.data-workflow/main/badges/svg/patreon.svg" width="200"></a> <a href="https://youtube.com/@serilum" rel="nofollow"><img src="https://raw.githubusercontent.com/Serilum/.data-workflow/main/badges/svg/youtube.svg" width="200"></a></p>
<p><strong><span style="font-size:24px">Requires the library mod&nbsp;<a style="font-size:24px" href="https://curseforge.com/minecraft/mc-mods/collective" rel="nofollow">Collective</a>.</span></strong><strong>&nbsp;<br><br> &nbsp; &nbsp;This mod is part of <span style="color:#008000"><a style="color:#008000" href="https://curseforge.com/minecraft/modpacks/the-vanilla-experience" rel="nofollow">The Vanilla Experience</a></span>.</strong><br><span style="font-size:18px">Your Items Are Safe is a mod which can function as an alternative to the existing gravestone mods, by using only vanilla blocks. When a player dies, it will keep their items from despawning. It does this by creating an armor stand with equiped gear and a chest with the items from the inventory. A sign will be placed on the chest with the player's name. If the inventory does not fit into one chest, another one above it is generated. The armor stand stands above the chest. All features can be turned on/off via the config. If a player dies in the void, the chest will be placed above the death coordinates.<br><br>To keep it balanced the chests and armor stand can only be created if the player has enough wood in its inventory. A chest requires either 2 logs, 8 planks or an actual chest. The armor stand requires 1 log or 3 planks. The mod searches for logs first, then planks, then chests. If it can't find the raw material needed, the chest and armor stand is&nbsp;<span style="text-decoration:underline;font-size:18px"><strong>not</strong></span> generated. If you'd like to always generate them, even without raw materials, this can be set in the config file as well.<br><br>The mod also contains the functionality to generate a player head and put it on the armor stand. This makes it easier to identify which player has died where. If the player had a helmet equiped, it is placed inside the chest. Enabled by default. But again, this can be disabled in the config.<br></span><br><br><strong><span style="font-size:20px">Configurable:</span> <span style="color:#008000;font-size:14px"><a style="color:#008000" href="https://github.com/Serilum/.information/wiki/how-to-configure-mods" rel="nofollow">(&nbsp;how do I configure?&nbsp;)</a></span><br></strong><span style="font-size:12px"><strong>mustHaveItemsInInventoryForCreation</strong>&nbsp;(default = true): When enabled and a player dies without any items in their inventory, no chest or armor stand is generated.</span><br><span style="font-size:12px"><strong>addPlayerHeadToArmorStand</strong>&nbsp;(default = true): If a player head should be added to the armor stand. If a helmet is worn, this will be placed into the chest.</span><br><span style="font-size:12px"><strong>createArmorStand</strong>&nbsp;(default = true): Whether an armor stand should be created on death. If disabled, the player's gear will be placed inside the chest.</span><br><span style="font-size:12px"><strong>createSignWithPlayerName</strong>&nbsp;(default = true): Whether a sign should be placed on the chest with the name of the player who died there.<br></span><br><span style="font-size:12px"><strong>needChestMaterials</strong>&nbsp;(default = true): Whether materials are needed for the chest which spawns on death. This can be the actual chest or the costs in raw materials.</span><br><span style="font-size:12px"><strong>needArmorStandMaterials</strong>&nbsp;(default = true): Whether materials are needed for the armor stand to spawn on death. This can be the actual armor stand or the costs in raw materials.</span><br><span style="font-size:12px"><strong>needSignMaterials</strong>&nbsp;(default = false): Whether materials are needed for the creation of the sign when 'createSignWithPlayerName' is enabled.</span><br><span style="font-size:12px"><strong>ignoreStoneMaterialNeed</strong>&nbsp;(default = true): Only relevant if 'needChestAndArmorStandMaterials' is enabled. An armor stand needs 1 stone slab to be created, but I think it's alright to ignore that requirement. If enabled, no stone is needed in the inventory on death.</span><br><br><span style="font-size:12px"><strong>createChestAboveVoid</strong>&nbsp;(default = true): If a chest should be placed right above the minimum build height when a player dies in the void.</span><br><span style="font-size:12px"><strong>createVoidPlatform</strong>&nbsp;(default = true): If a 3x3 platform should be created below the chest above the void. 'createChestAboveVoid' must be enabled.<br></span><br><span style="font-size:12px"><strong>sendMessageOnCreationFailure</strong>&nbsp;(default = true): If a message should be sent if the chest or armor stand can't be created due to missing materials.</span><br><span style="font-size:12px"><strong>sendMessageOnCreationSuccess</strong>&nbsp;(default = true): If a message should be sent on successful creation of the chest(s) and armor stand.</span><br><span style="font-size:12px"><strong>sendDeathCoordinatesInChat</strong>&nbsp;(default = true): If the player's death coordinates should be sent in the chat below the 'sendMessageOnCreationFailure'/'sendMessageOnCreationSuccess' message.<br></span><br><span style="font-size:12px"><strong>creationFailureMessage</strong>&nbsp;(default = "Your items are not safe due to having insufficient materials. Missing: %plankamount% planks."): The message sent on creation failure with 'sendMessageOnCreationFailure' enabled. Possible replacement values: %plankamount%, %stoneamount%.</span><br><span style="font-size:12px"><strong>creationSuccessMessage</strong>&nbsp;(default = "Your items are safe at your death location."): The message sent on creation success with 'sendMessageOnCreationSuccess' enabled.</span><br><br><br><span style="font-size:36px"><strong>Some examples:</strong></span><br><span style="font-size:12px"><span style="font-size:18px">An armor stand and chest generated after death:</span><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/a.jpg" width="1000" height="527"></picture><br><br><span style="font-size:18px">Two chests generated after death, because the inventory didn't fit in a single one:</span><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/b.jpg" width="1000" height="527"></picture><br><br><br><span style="font-size:18px">One chest and an armor stand created after death:</span></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/c.gif" width="952" height="530"></picture></p>
</div>
<p>&nbsp;<br><span style="font-size:18px">The previous death results in the following:</span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/d.gif"></picture></p>
</div>
<p>&nbsp;<br><span style="font-size:18px">Here the player has no wood in its inventory. The chest/armor stand is not generated:</span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/e.gif"></picture></p>
</div>
<p>&nbsp;<br><span style="font-size:18px">The player does have some planks in its inventory, but not enough. This is shown in the chat via a message:</span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/f.gif" width="952" height="532"></picture></p>
</div>
<p>&nbsp;<br><span style="font-size:18px">The inventory is completely full, so 2 chests are needed to store everything. Luckily the player has more than 19 planks:</span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/g.gif"></picture></p>
</div>
<p><br><br><span style="font-size:18px">When a player dies in the void, the chest is placed on the initial position above it with a cobblestone platform.</span><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/h.png"></picture><br><br><span style="font-size:18px">Death coordinates are sent in the chat. Can be disabled in the config.</span><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/your-items-are-safe/i.png"></picture><br><br><br>------------------<br><br><span style="font-size:24px"><strong>You may freely use this mod in any modpack, as long as the download remains hosted within the CurseForge or Modrinth ecosystem.</strong></span><br><br><span style="font-size:18px"><a style="font-size:18px;color:#008000" href="https://serilum.com/" rel="nofollow">Serilum.com</a> contains an overview and more information on all mods available.</span><br><br><span style="font-size:14px">Comments are disabled as I'm unable to keep track of all the separate pages on each mod.</span><span style="font-size:14px"><br>For issues, ideas, suggestions or anything else there is the&nbsp;<a style="font-size:14px;color:#008000" href="https://github.com/Serilum/.issue-tracker" rel="nofollow">Github repo</a>. Thanks!</span><span style="font-size:6px"><br><br></span></p>
<p style="text-align:center"><a href="https://serilum.com/donate" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/projects/support.svg" alt="" width="306" height="50"></a></p>