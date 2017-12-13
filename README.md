# Marine Rescue Description:

In this minimap, your mission is to locate marines and order them to load a medivac for evacuation. Banelings are wandering on the map randomly looking for marine to kill. Dodge those banelings and get as many marines rescued as possible. 10 difficulty levels are available for beginner and experienced player. With higher level, there will be more marines and banelings appeared simultaneously on the map. Keep an eye on the minimap for banelings and, if necessary, use the stimpack for marine to gain a speed advantage. Stimpack is only available once for each marine, make it count.

Medivac will automatic launch after it is fully loaded and you will get reward for that. At same time, another empty medivac will enter battle field to the designated location. It beneficial to load single medivac instead of load them seperately but you have to risk longer travel time of your marines on the map. So, plan carefully.

# Score:

 * each marine loaded medivac, score plus 1
 
 * each marine killed by baneling, score minus 1
 
 * each medivac fully loaded and escaped, score plus 8
 
 # Time Available:
 
  * 180 seconds
 
 # Intended Machine Learning Objective:
 
 Observe the minimap, locate marines spawning on the map. Since medivac location are pre-determined, it should be easy to find marine location from minimap. This simulate, in real game-play, distinguish between location of friendly buildings and units. Buildings will have determined location and unable to move (normally) and unit require constant observe and micro.
 
 Give simple order to marine to move to desired location.
 
 Locate friendly and hostile encounter and give appropriate maneuver. Move camera to encounter of marine and baneling. Since marine sight are slightly longer than the distance of triggering attack of baneling, there are certain range of reaction time possible. Move properly to dodge banelings in a timely efficient manner. In real game play, this mean move your camera to potential combat area.
 
 Use skill to increase chance of survival. Use marine skill (stimpack) when it is chased by baneling. Baneling speed is slightly higher than marine speed without stim. Use stimpack will give marine speed advantage. Keep in mind that each marine only have one chance to use their stimpack. Also, when speed increases, there are less time to react. This is similar to access battle field situation and give right order to unit.
 
 Multi-tasking. In higher difficulty, it is necessary to control multiple marines at same time. Select the right marine for your micro. Basically, marine without encountering baneling need no micro (move to point); marine encountering baneling but not been spotted need some maneuvering (shift + move); marine get spotted by baneling need to use stimpack .... 
