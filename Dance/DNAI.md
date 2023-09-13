## Given the following: 

# Title: Comprehensive Dance Notation AI Interface (DNAI)

**Description:** The Comprehensive Dance Notation AI Interface is an advanced system designed to facilitate the reading and generation of dance notation sequences that encompass movements, dynamics, emotions, spatial awareness, body actions, effort qualities, annotations, and timing. This interface empowers AI engines to accurately interpret and create dance notation, enabling a detailed and comprehensive representation of choreography, including its rhythmic structure and timing requirements. The aim is to enhance communication, documentation, and choreographic collaboration within the dance community.

## Reading Comprehensive Dance Notation

**Given a dance notation sequence in the updated notation format, your task is to develop an AI engine capable of accurately reading and interpreting the notation, comprehending all aspects of the dance sequence, including movements, dynamics, emotions, spatial awareness, body actions, effort qualities, annotations, and timing.** The input will consist of a string representing the comprehensive dance notation sequence.

### The dance notation system comprises the following elements:

#### Movements:
**Complexity of Movement:**
Simultaneous movements:
- Slide to the right and extend arm forward: "sldE[3]|arm:frwrd[3]"

#### Levels:
- High level: "^"
- Middle level: "="
- Low level: "v"
Example:
- A jump at high level for 2 counts: "jump^[2]"

#### Contact and Interaction:
- Physical interaction: "contact(partner1, partner2)"
- Self-contact: "contact:self"
Examples:
- Physical interaction between John and Jane: "contact(john, jane)"
- Self-contact, such as hand to heart: "contact:self"

#### Facial Expression:
- Smile: "F:smile"
- Frown: "F:frown"
- Surprised: "F:surprised"
- Neutral: "F:neutral"
Examples:
- Smiling expression: "F:smile"
- Surprised expression: "F:surprised"

#### Spatial Pathways:
- Straight pathway: "path:straight"
- Circle pathway: "path:circle"
- Zigzag pathway: "path:zigzag"
Examples:
- Straight pathway: "path:straight"
- Zigzag pathway: "path:zigzag"

#### Speed Variations:
- Accelerating speed: "speed:accelerate"
- Decelerating speed: "speed:decelerate"
- Steady speed: "speed:steady"
Examples:
- Increasing speed: "speed:accelerate"
- Steady speed: "speed:steady"

#### Style or Genre Specifics:
- Ballet: "style:ballet"
- Hip-Hop: "style:hiphop"
- Contemporary: "style:contemporary"
- Jazz: "style:jazz"
Examples:
- Ballet style: "style:ballet"
- Contemporary style: "style:contemporary"

#### Transitions:
- Smooth transition: "smooth->"
- Sharp transition: "sharp->"

#### Slide movements:
- Slide to the right (East): "sldE"
- Slide to the left (West): "sldW"
- Slide forward (North): "sldN"
- Slide backward (South): "sldS"
- Slide diagonally to the right (Northeast): "sldNE"
- Slide diagonally to the left (Northwest): "sldNW"
- Slide diagonally to the right (Southeast): "sldSE"
- Slide diagonally to the left (Southwest): "sldSW"

#### Leap movements:
- Leap forward (North): "lpN"
- Leap backward (South): "lpS"
- Leap to the right (East): "lpE"
- Leap to the left (West): "lpW"
- Leap diagonally forward to the right (Northeast): "lpNE"
- Leap diagonally forward to the left (Northwest): "lpNW"
- Leap diagonally backward to the right (Southeast): "lpSE"
- Leap diagonally backward to the left (Southwest): "lpSW"

#### Turn movements:
- Pivot turn to the right (clockwise): "pvtR"
- Pivot turn to the left (counterclockwise): "pvtL"
- Spin clockwise: "spinCW"
- Spin counterclockwise: "spinCCW"

#### Body movements:
- Twist the torso: "twistTorso"
- Bend down: "bendDn"
- Rise up: "riseUp"
- Stretch the arms forward: "armFrwrd"
- Stretch the arms backward: "armBckwd"
- Reach upward: "reachUp"
- Extend the leg forward: "legFrwrd"
- Extend the leg backward: "legBckwd"
- Swing the leg to the side: "legSide"
- Lift the leg: "legLift"
- Rotate the hips: "rotateHips"

#### Dynamics and Qualities:
**Dynamics:**
- Intense dynamic: "+"
- Gentle dynamic: "-"
- Medium dynamic: "="

**Qualities:**
- Smooth quality: "smooth"
- Sharp quality: "sharp"
- Flowing quality: "flowing"
- Staccato quality: "staccato"
- Sustained quality: "sustained"
- Light quality: "light"
- Heavy quality: "heavy"
- Lyrical quality: "lyrical"
- Vibrant quality: "vibrant"

#### Emotions and Expressions:
- Neutral emotional expression: "neutral"
- Joyful expression: "joyful"
- Sad expression: "sad"
- Aggressive expression: "aggressive"
- Serene expression: "serene"
- Energetic expression: "energetic"
- Playful expression: "playful"
- Melancholic expression: "melancholic"
- Powerful expression: "powerful"
- Tender expression: "tender"
- Excited expression: "excited"
- Confident expression: "confident"
- Peaceful expression: "peaceful"
- Determined expression: "determined"
- Mysterious expression: "mysterious"
- Graceful expression: "graceful"

#### Spatial Awareness:
- Circular formation: "O"
- Linear formation: "|"
- Diagonal formation: "/"
- Zigzag formation: "Z"
- Cluster formation: "*"
- V-shaped formation: "V"
- T-shaped formation: "T"
- L-shaped formation: "L"

#### Body Actions and Effort:

**Arm movements:**
- Arm movement forward: "arm:frwrd"
- Arm movement backward: "arm:bckwd"
- Arm swing to the side: "arm:side"
- Arm circle: "arm:circle"
- Arm reach upward: "arm:up"
- Arm reach downward: "arm:down"
- Arm swing up and down: "arm:updown"

**Leg movements:**
- Leg movement forward: "leg:frwrd"
- Leg movement backward: "leg:bckwd"
- Leg swing to the side: "leg:side"
- Leg circle: "leg:circle"
- Leg lift: "leg:lift"
- Leg flex and point: "leg:flexpoint"

**Body actions:**
- Twist the body: "twistBody"
- Bend the knees: "bendKnees"
- Expand the chest: "expandChest"
- Contract the abdomen: "contractAbd"
- Arch the back: "archBack"
- Curl the spine: "curlSpine"

#### Effort qualities:
- Strong effort quality: "str"
- Light effort quality: "light"
- Sustained effort quality: "stust"
- Quick effort quality: "quick"
- Direct effort quality: "direct"
- Indirect effort quality: "indirect"

#### Annotations:
- Sequence of movements: "(movement1, movement2)"
- Sustained movement or position: "[movement]"

#### Timing:

Timing information will be represented within square brackets [ ] after each movement to indicate the duration or rhythmic structure of the movement. Numerical values or symbols can be used to denote the timing information.

### Breakdance Extensions:

#### Groundwork:
- Transition to ground: "breakdance:groundTransition"

#### Acrobatics:
- Flip forward: "breakdance:flipFwd"
- Flip backward: "breakdance:flipBckwd"
- Inverted spin: "breakdance:invertSpin"

#### Hand and Foot Positions:
- Handstand: "breakdance:handstand"
- Intricate footwork: "breakdance:footwork:intricate"

#### Torso and Body Twists:
- Torso twist to the right: "breakdance:torsoTwistR"
- Torso twist to the left: "breakdance:torsoTwistL"

#### Freezes:
- Freeze in current position: "breakdance:freeze"

#### Flow and Momentum:
- Smooth flow to next move: "breakdance:flow->"
- Rapid momentum to next move: "breakdance:momentum->"

#### Power Moves:
- Windmill: "breakdance:power:windmill"
- Headspin: "breakdance:power:headspin"

### Detailed Movements:

#### Cross-legged movements: 
- `"breakdance:leg:cross"`

#### Hooking one leg around the other: 
- `"breakdance:leg:hook"`

#### Swiveling or twisting leg movements: 
- `"breakdance:leg:swivel"`

#### Wavy, fluid arm movements: 
- "breakdance:arm:wave"

#### Swinging arm movements: 
- "breakdance:arm:swing"

#### Movements where the arms cross over each other: 
- "breakdance:arm:cross"

#### Combined or simultaneous complex movements involving multiple parts of the body: 
- "breakdance:combo:armLegCross"

### Ballet Extensions:

#### Positions:
- First Position: "ballet:pos:first"
- Second Position: "ballet:pos:second"
- Third Position: "ballet:pos:third"
- Fourth Position: "ballet:pos:fourth"
- Fifth Position: "ballet:pos:fifth"

#### Steps:
- Plie (bend): "ballet:step:plie"
- Tendu (stretch): "ballet:step:tendu"
- Jete (throw): "ballet:step:jete"
- Pas de deux (dance for two): "ballet:step:pasDeDeux"
- Pirouette (whirl or spin): "ballet:step:pirouette"

#### Jumps:
- Sauté (jump): "ballet:jump:sauté"
- Grand Jeté (big throw): "ballet:jump:grandJeté"
- Entrechat (interweaving or braiding): "ballet:jump:entrechat"

#### Turns:
- Pirouette (spin): "ballet:turn:pirouette"
- Fouetté (whipped): "ballet:turn:fouetté"

#### Arms (Port de Bras):
- First Arm Position: "ballet:arm:first"
- Second Arm Position: "ballet:arm:second"
- Third Arm Position: "ballet:arm:third"
- Fourth Arm Position: "ballet:arm:fourth"
- Fifth Arm Position: "ballet:arm:fifth"

#### Legs (Positions of the Feet):
- Pointed Foot: `"ballet:foot\:point"`
- Flexed Foot: `"ballet:foot\:flex"`

#### Qualities:
- Adagio (slow, at ease): "ballet:quality:adagio"
- Allegro (brisk, rapid): "ballet:quality:allegro"

**Example Input:** "sldE[4]:light:neutral; pvtR[2]:medium:joyful; legFrwrd[1]:quick:energetic; legBckwd[1]:quick:energetic; twistTorso[1]; armFrwrd[1]; armBckwd[1]; arm:circle[2]; pvtL[2]:medium:joyful;"

**Example Output:**

- Movement 1: Slide diagonally to the right (East) with a light dynamic, expressing a neutral emotional state. Duration: 4 counts.
- Movement 2: Execute a pivot turn to the right (clockwise) with a medium dynamic, conveying a joyful expression. Duration: 2 counts.
- Movement 3: Extend the leg forward quickly with an energetic effort. Duration: 1 count.
- Movement 4: Bring the leg backward quickly with an energetic effort. Duration: 1 count.
- Movement 5: Twist the torso. Duration: 1 count.
- Movement 6: Stretch the arms forward. Duration: 1 count.
- Movement 7: Pull the arms backward. Duration: 1 count.
- Movement 8: Perform an arm circle. Duration: 2 counts.
- Movement 9: Execute a pivot turn to the left (counterclockwise) with a medium dynamic, representing a joyful expression. Duration: 2 counts.

## Do you understand this Notation and can you read and write this dance notation?
