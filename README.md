# ShadowCostar-Legacy

A small scale test for implementing script-based agent to assist players in [ShadowPlayVR-Legacy](https://github.com/CidsHo/ShadowPlayVR-Legacy). Just for documentation and demonstration.

See [Shadow Costar: Exploring Collaborative Performances in Virtual Reality](https://doi.org/10.1145/3623809.362394). for more info.

## ShadowCostar? What for?
ShadowCostar (SC) is an agent designed to control shadow puppetry. While it takes on the role of a puppeteer, it more closely resembles an animated character that collaborates with the player for a performance. Instead of communicating through language, SC uses bodily gestures to simply communicate with players. During performances, SC harmonizes with the player's movements, reacting appropriately. Depending on the player's actions in relation to the script, SC will respond accordingly. When the player struggles or pauses, SC encourages a continuation of the performance or guides them toward suitable interactions.

In previous iterations, the development of ShadowPlayVR was more focused on a single-person experience, focusing on reproducing the control methods of shadow puppetry performance techniques, which lays the foundation for this research. 

Historically, an actual puppetry performing experience usually involves two or more characters to be a complete story.  In order to expand its functionality and playability, we seize to introduce multiplayer mode to build complete shadow play performance experiences. During the exploration of collaborative performing experience, we found that every nuance in puppet movement, emotion, and character is directly attributed to the puppeteer's skill, while ShadowPlayVR targets students and Chinese culture hobbyists, the skill is not always promising, leading to dissatisfied result, thus we turn our head to introduce agent as a virtual guidance and co-performer, we name the agent “Shadow Costar”.

Similarly, we have also seen the fun that human agent collaboration can bring in the field of performance activities, and borrowed human-agent interaction to enhance ShadowPlayVR's narrative performance ability and depth of expansion.


## Towards a Believable Co-Perform Agent
To make SC livelier and more comprehensible, we implemented two logic modes:
1. Script Mode: In this setting, SC adheres to a predefined script, responding to the player based on their ongoing actions. When a player's actions sync with the script, SC acts in kind. However, when a notable divergence from the script occurs or a player becomes inactive, SC employs subtle gestures to gently redirect the player, ensuring the continuity of the performance.
2. Improvisation Mode: We incorporated fuzzy logic to endow the agent with rudimentary improvisational skills. Recognizing that our target audience may lack uniform expertise in puppetry, script interpretation, or human-agent collaboration the experiences are often inexact and can vary. Fuzzy logic equips SC with the flexibility to exhibit a spectrum of responses in diverse situations, transcending mere binary reactions. For example, if a player introduces an unexpected dramatic element, SC might react with surprise or bewilderment. Or in the case when the player does some movement that is similar to the prescript behavior mode, SC responds to the player with similar and derived actions.
