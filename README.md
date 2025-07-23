# **eutrophia**

![Eutrophia title sceen](eutrophia.gif "Eutrophia title sceen")
[Watch pitch trailer here](https://www.youtube.com/watch?v=1u6rPjjJoxo)

*The term "**eutrophication**" comes from the Greek **eutrophos**, meaning "**well-nourished**", [7] because the waterway has had an excessive amount of nutrients [such as nitrogen] for growth [...] it eventually strangulates the oxygen out [...]*

THE OLD WORLD IS DYING. THE NEW WORLD IS STRUGGLING TO BE BORN.
SHED YOUR SKIN AND MEET IT.

## **Deliverables:**
- Complete Game Design Document (3000-4000 words)
- Visual mockups/concept art (minimum 5 images)
- Technical specification document

## **GDD Structure**
### **Executive Summary**
An unknown beam shot from the heart of Andromeda turned the seas to blood and made the buildings of man come alive and spiral downward into the Earth. Air on the surface is no longer livable, owing to the blood-red bloom of a xenoalgae that's aggressively colonized the oceans and turned the rains acidic, off-gassing nitrogen and carbon monoxide. After two centuries under these conditions, a new sort of society has emerged in the living bowels of the Earth. 

Within the increasingly-organic subterranean cathedrals, offices, and houses that you call home, a theory has begun to emerge that the wall-eyes - strange teratoma-like growths that have begun developing inside the walls - are becoming decidedly more human as one approaches the suffocating surface. You escaped the last expedition meant to document this, a group of four-turned-three armed with re-breathers,  sledgehammers, and body-bags. You will not escape this one.


 Your assignment: to trudge alone armed only with an ultrasound tool, a scapel, and a journal. Head towards the surface. Solve Blockages. Excise Wall-Eyes. Document their features. Do not return until you have found the reason for the failure of the expedition you abandoned.

### Target audience
Ages 16+, with a particular pull towards marginalized gender identities.

This is a caving puzzle/exploration game, and the work is intended to play on anxieties about the body as an object and the identities that emerge from it; as such, I imagine it would appeal particularly well to young women and members of the transgender community who are horror fans. Anyone who'd ever click on a video essay titled 'Visceral Femininity in Bloodborne' - this one's for you.

Comparative works of media with similar themes and audience draws are Mouthwashing by Wrong Organ (game), Anatomy by Kitty Horrorshow (game), Pathologic 2 by Icepick Lodge (game), BLAME! by Tsutomu Nihei (manga), The Southern Reach book series by Jeff Vandermeer (book series), and The Haunting of Hill House by Shirley Jackson (book). Puzzles are meant to be inspired by the Myst (game) series. 

### Platform and technical requirements
Windows. It should be able to run on an average gaming laptop (8-16GB RAM; dedicated graphics card of the Nvidia 10 series or later). Maximum 20GB in size.
### Development timeline estimate

### **Game Overview**
#### Core gameplay mechanics
**Puzzles:** Called 'Blockages' in-universe. Solving grown Blockages is the only way to press forward. Blockages often resemble man-made structures, though no man ever made them, and it is difficult to discern what - if any - practical use they provide other than to delay one's ascent to the surface. Examples of documented Blockages include turning dials to align shifting plates on a clock's face to reveal a gap that can be crawled through and placing stone spheres in the correct order on a series of scales so their balances align to allow a person to walk across them.

**Ultrasounding:** In soft spots in the walls, you should use your portable ultrasound pack to check for wall-eyes. Switch to this tool using the [3] key, and then left-click on the wall.

**Scapel:** Used on exposed soft areas in walls to cut them open, bring a Wall-Eye into the world.

**Oxygen:** %SpO2. A measurement of your blood oxygen. Exerting yourself by moving heavy objects or running uses up Oxygen and can leave you choking for air. Critically low levels of Oxygen will blur and darken the screen; a Game Over can be triggered by suffocation. Try moving deeper into the Earth to catch your breath; the closer to the surface you get, the less replenishing your breaths will be - and the more the high CO will trigger Panic...

**Panic:** Panic increases your rate of respiration and can shrink the Oxygen bar at high levels. Panic increases in tight spaces, in high CO areas, in the dark, and during certain scripted events. Completing puzzles decreases Panic. Excising Wall-Eyes can decrease or increase Panic.

**Journal:** Press [J] to open. Document your findings thusfar. Takes notes on the puzzles. Journalling usually decreases Panic; note that you can't Journal in tight spaces. Who's been writing all these extra pages of notes?

**Exploration:** Exploration should be rewarding by delivering novel visuals to players and new clues about the story.

### Genre and style
This is a sci-fi horror game, and is intended to be horror *without* jumpscares or enemies to chase you. Just you, the caves, and what lurks within you.
### Unique selling points
### Player experience goals
 I imagine this effectively as an 'art puzzle' game along similar lines to the Myst series. While the themes, some mechanics, and art direction will push it in more of a 'horror' direction, there should be no (or minimal) jump scares, and no monsters chasing you. Just you, the living caves, and the ascent to a poisoned world.
### **Gameplay Mechanics:**
#### Core game loop
The player moves forward through a linear route to complete puzzles and avoid situations that may increase their Panic and decrease their Oxygen. As they complete puzzles, they will uncover new leavings 
#### Player actions and controls
#### Game systems and interactions
#### Progression and rewards

### **Technical Design:**
#### Engine choice (Unreal Engine 5.6 or Godot 4.4) and justification
Unreal Engine 5.6; for VR capacity and semi-realistic graphics. 
Part of what made Myst and Riven so striking was the strong art direction and the incredible visuals for the time period. Unreal's dedication to realistic rendering would help contribute to this for Eutrophia.
#### Technical requirements and architecture
#### Performance targets and optimization considerations
#### Platform considerations and deployment strategy

### **Art and Audio Direction:**
#### Visual style and art direction
Biopunk / steampunk / fantasy / real-world architecture; 'realism', but within the restrictions of PS2-era graphics to keep asset scope smaller. [Myst managed to be beautiful while being visibly low-res to modern eyes.](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimg.atlasobscura.com%2F6EuWxWPJMKwvB49ZS7eSBYwV3Ztsik3oNJ4MCFBZVyw%2Frt%3Afit%2Fw%3A1280%2Fq%3A81%2Fsm%3A1%2Fscp%3A1%2Far%3A1%2FaHR0cHM6Ly9hdGxh%2Fcy1kZXYuczMuYW1h%2Fem9uYXdzLmNvbS91%2FcGxvYWRzL2Fzc2V0%2Fcy80YWU3ZTljNS1h%2FNDZhLTRmZWUtYTU0%2FMS1hOGQ3ODQ5ZDQ1%2FMTQ5ODM0NTljNjJi%2FNjg5ODEyYzBfbXlz%2FdHBpYzMuUE5H.png&f=1&nofb=1&ipt=53b72157a4c3798da5f2573bd95abd07f3216c28f42ed843136f6edfd62ca42b)

While some aesthetic sensibilities such as pulsing buildings and veined walls will understandably overlap with Scorn (2022, Ebb Software), the world of Eutrophia is meant to feel 'grounded' in the real world much in the same way that Myst's world - despite the fantastical elements - felt like a 'real' place one could walk around in that made a certain amount of intuitive sense.

While, yes, aliens shot a giant terraforming laser at Earth that turned the seas to blood and made every human-made building into a living structure that endlessly grows downwards (the fantastical elements are there) the way objects, puzzles, and physics itself interact should draw more from our present world than from 'aliens did it'. There might be a giant living clock in the center of a room, but you still need to interact with physical, weighty gears to turn the plates on its face. The interfaces that make themselves apparent to you should remain recognizably human and even 'old-fashioned'.
#### Audio design and music style
*Synth notes billowed from a vast windpipe carrying dead air and pre-language vocalizations.* 

The best musical touch-stones are Thierry Zabolitzeff's Promethee and Anna Holmer's work with Breadwoman & Other Tales. Ideally, music should echo and sound 'airy', with a focus on instruments that convey breath such as members of the woodwind family; experimentation with billows and whatever else is encouraged, we're looking for wind and echoes through empty space. 

A musical moodboard can be found [here](https://www.youtube.com/watch?v=QTLFzly4ifU&list=PLIecGGweOsQwA9z2NpJIv-4ILti6Watai).
#### UI/UX design principles
As the story itself is heavily based in pregnancy horror and the fear of medical exploitation and becoming a colonized body, all UI elements should draw from the visual language of medical UIs. 


Blood oxygen should look like the UI of an oximeter, opening the Inventory should pull up a full-body MRI of a person. Panic could be represented as a an EKG UI. The UI should have a glossy, 'glassy' feel and use Sans serif, ALL-CAPITAL fonts. A combination of modern imaging and old medical UIs such as the THERAC-25 would be particularly ideal, as it would echo the hodgepodge of 'old' and 'modern' architecture throughout the caves.


The sound of interacting with the UI should be surprisingly 'retro', similar to the somewhat harsh/ominous SFX noises of [LSD Dream Emulator](https://www.youtube.com/watch?v=e5oBPsPIG7E) - simultaneously 'crunchy' and audibly synthetic, yet breathy. It's almost as if this medical envisioning of your body is rejecting you, somehow...

### **Level Design**
#### Game world structure
The game world will be almost entirely linear, with small choices given throughout to allow a player to manage their Panic and Oxygen. 

The player should start underneath a rope off a tongue-like ledge and progress forward through various tunnels that will lead them to a Blockage that they will need to resolve before they can continue forward to search for Wall-Eyes. There should be 3-5 Blockages, depending on time and development constraints. 

The player must collect a minimum of 10 Wall-Eyes for their expedition to be allowed back into the settlement; Wall-Eyes are usually found right before or in the chamber of a Blockage, meaning that the player must keep solving puzzles in order to collect the Wall-Eyes they need to finish the game.
#### Level progression
Each blockage should be more complex, as a puzzle, than the last one. Player access to Oxygen will decrease as they progress through each level, and player Panic will increase as they ascend due to the increase in CO displacing Oxygen the closer a player gets to the surface. 
Later puzzles should include physically taxing tasks, such as moving heavy objects or needing the player to run quickly from one spot to another. If we're incorporating VR, the tasks should involve large, fast, repetitive arm movements, such as cranking a wheel to generate electricity, so the character's struggle for breath is echoed in the player's. Tunnels between puzzles should also get narrower to increase character Panic.
#### Environmental storytelling
As the player progresses through the world, they should find small keepsakes and off-sheds from the expedition they abandoned. The player character should comment on these and collect them throughout, prompting the player to open the Journal so the character can take notes on what occurred previously. 

It should be implied late in the game that the character has kept secret that they are two months pregnant out of fear of being forced into motherhood, and had made the mistake of disclosing their discovery to their partner, who was the head scientist leading the expedition. While the player character still hasn't decided what to do about it, their partner's insistence that they tell the council and force an exit from scientific life and become permanently domestic - an insistence that happened against the backdrop of an expedition where they cut the Earth open to collect the meat inside - caused the player character to run off into the depths of the Earth to wander alone. Hunger eventually drove them back to the settlement, which drove them back out on a last expedition as punishment.
### **Production Plan**
#### Development phases and milestones
#### Resource requirements and team structure
#### Risk assessment and mitigation strategies
#### Version control and project management strategy
#### Testing and quality assurance approach

### **Market Analysis (optional)**
#### Competitive analysis
This piece was not designed to be competitive, aside from adding to the conversation within the realm of interactive media regarding pregnancy horror. Mouthwashing focused on the experiences of the men around Anya but still conveyed her story with tact; however, I feel there's a missing link with regards to media that focuses pregnancy horror and *depicting it from the perspective of the person carrying the pregnancy*.
#### Target market research
#### Monetization strategy (if applicable)
This is an art game. It's intended to be bought once and played as an art and conversation piece. While I am aware of other games with similar themes that then monetized the characters into cute plushies, stickers, etc, I would like to avoid that with Eutrophia. At most, perhaps 3D print figurines of the more iconic architectural Blockages could be sold for people to use as they'd like or keep as keepsakes.
