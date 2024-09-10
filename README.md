The Blocker Mod aims to deepen and expand the game's planetary colonization and development loop.

With the mod, colonizing planets will be harder but also more rewarding. Your Colonists will take on the role of heroic explorers and bring knowledge, bounty, and renown to your empire.

But they will face significant challenges as you settle and expand new worlds. In The Blocker Mod, all planetary features take up space even as they provide districts and bonuses. A Searing Desert will remain a good source of energy, but no one wants to live there. And you don't mess with Toxic Kelp.

Almost all features can be cleared, and many more will swap, so it iwll be up to you to explore and shape your planet's geography as you tame its pristine wilderness to your needs. Will you nurture an idyllic farming world of Nutritious Mudlands and rolling Green Hills where xeno-melons grow as big as your head? Or will you pave paradise with Industrial Wasteland in the name of progress?


--- Planetary Features ---

The Blocker Mod adds approximately 60 new features and reworks most existing features. It does not alter event-based features or features added by other mods.

Almost all features now behave as "blockers" and take up space. All can be cleared, but the cost in time and price varies with feasibility. Once they're gone, they're gone -- along with any resource districts provided.

When you first settle on a new world, it will have very little if any space for development. You will need to make use of buildings, decisions, and the features themselves to get a colony up and running. Don't expect this to happen quickly because these features will eat into your planet's natural carrying capacity -- it's hard to raise kids when Dangerous Wildlife is lurking in the Fungal Forest.

Feature placement has also been reworked. Tropical Islands can only spawn where there's actually water and Desert worlds will be hard to inhabit and farm. Planet can have different biomes. Existing blocker technologies have been reworked and many features have more complex costs and clearance requirements. It is no longer possible to bulldoze Impassable Mountains ina few months.

In general, the mod reduces the volume of resource districts in favor of increasing their efficiency. Larger worlds will struggle to be self-sufficient while carefully-planned rural colonies can form the backbone of an empire.


--- Dynamic Planets & Events ---

As you explore the final frontier, you'll discover the pitfalls and possibilities of alien worlds. Many features can fire events, and your choices can powerfully shape the worlds around you.

So tread lightly. While your colonists can adapt to Moisture Farming, over-use or clear-cutting may lead to the creation of Floodplains, Dustbowls, or even whole regions lost to Barren.

You'll also need to handle crime and amenities. Hot Springs and Rushing Waterfalls can be a great source of unity, but Hydro Plants have a way of ruining a view no matter which sensory organs you possess. The occasional Sprawling Slum might be situationally useful, but an authoritarian dystopia may see happiness penalties stack up faster than it can clear them.

If you find yourself in a spot of ecological bother, terraforming a world will reroll its planetary features.


The AI will make choices about which features to clear based on its personality and its planet designations, which should lead to more varied, interesting galaxies.


--- Colonists ---

These courageous and skilled champions of civilization have given up everything to forge a new life on alien worlds far from home. In keeping, this formerly banal job can now provide massive bonuses on new worlds, especially early on.

Most features provide an additive bonus to Colonist output -- often in the form of food, minerals, or research. While the early colonization period may require some patience, it'll also be a boon for your scientists back home who get to study all those new specimens.

Due to the way features are spawned, the occasional "outlier" planet may spawn with negative district space. In severe cases, these get the Wild World modifier and give an additional boost to colonists as well as a discount on clearance cost/time. The Environmental Engineer trait can also be taken from game start, and is generally a lot more useful.

New colonial buildings allow you to add extra colonists, specialize them, and keep them around until a Planetary Capital is established. As your population floods to a developing world, you'll also see colonial features like Frontier Farmland and Pioneer Settlements appear to help ease bottlenecks and shape the world for generations to come.

While powerful, too many of these buildings and features can strain your national unity, and an empire that's over-reliant on colonies will soon find it hard to enforce edicts, traditions, and even public order.


--- Homeworlds & Difficulty ---

The Blocker Mod doesn't aim to make the game more difficult so much as make your interactions with planetary features more meaningful.

By way of tutorial, you'll have a completely unique set of features on your homeworld chronicling the past 150 years of your history. Many of these features are origin or empire-dependent, so should you conquer a Determined Exterminator you can expect to spend some time deprogramming Battery Farms and shutting down the Central Power Nexus. Or use them for yourself -- it's up to you. Advanced Start empires even have some special bonus features for you to find.

Most homeworld features are pretty tame -- a product more of corruption and failure, and so easily overcome with a bit of space-age investment. But as you clear them, you'll slowly lose resource districts and become more reliant on colonies to fuel homeworld industry. (Life-Seeded and Ocean Paradise empires get a slightly different set of challenges related to managing space on a large planet.)


--- Compatibility ---

The Blocker Mod is made with compatibility in mind, but it goes without saying that it may behave oddly with other mods that affect or rely on planetary features, and you should probably pick only one major feature mod. If you prefer variety, WP's excellent Planetary Features Expanded is a great add. For extra content, Guilliman's Planetary Modifiers & Features is always a good standby. The Blocker Mod will be more focused on emergent story and system play.

TBM doesn't overwrite any event features or limit the ability to add more, but it does overwrite deposit_categories to enable clearing all features. One-off features should retain their effects, but you will want to be extra careful not to clear your Local Production stockpile or origin-unique features. But you should be careful about clearing features anyway!

For the mod to function properly, it is also necessary to overwrite the scripted effect generate_start_deposits_and_blockers. This will create a conflict with Planetary Diversity. I enjoy PD myself and am hopeful of developing a patch, but PD is a complicated mod and there's a lot of work involved before that happens.

It is a good idea to load TBM after any other mod that adds features. It's also possible that any mod that adds uniquely scripted planets via initializer may not function properly, but only if that initializer sets deposit_blockers = none, and those are generally easy to patch.

Two blocker-related defines are overwritten, MIN_UNBLOCKED_DEPOSITS and COLONY_DEPOSITS_FIXED_FROM_SIZE.

The Colonist job is overwritten but the file can be easily patched by switching Colonists to the planet_colonist economic category, which is added by TBM.

It should be compatible with most UI mods. It will disable achievements.


--- Bugs ---

The beta version of this mod is fully playable but some content is still WIP and there may be unfixed bugs, especially in edge cases. A list of Known Issues is included in the mod directory, and bug reports are encouraged in the appropriate area.

Enjoy!
