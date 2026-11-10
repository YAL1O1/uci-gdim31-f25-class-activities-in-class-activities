# in-class-activities
## Devlogs
### W1
1. When the camera is no longer a child of the cat, it does not move along the cat. Because the script only moves the cat.
2. [ItchLink](https://pdu31.itch.io/week1activity)

### W2
1. Because they represent the intensity of each color, which is a continuous value.  
2. Because it represents the number of times the ball bounces, and the number of bounces is always an integer.  
3. The error showed that the syntax was incorrect because a semicolon was missing at the end of the statement.

### W3
Table 16
#### Activity1
1. input int and bool, return string
2. input float, return void
3. input float, return bool
#### Activity2
I think of a class as a person: a complete profile of traits and abilities that exists only on paper. A Component is the job that person gets hired for — the moment they are hired (instantiated), the profile becomes a working barista, cashier, or guard. Member variables are the person's traits, like charm or stamina. Methods are the full abilities they can perform, like making latte art or operating the register.
#### Activity3
1. Because the color is repeatedly multiplied by 1.5f until it reaches white. However, if the ball's original color is black, it won't get brighter because it remains black even when multiplied by 1.5f.

### W4
1. I added Rigidbodies to Cat and SoccerBall because they need physics simulation. And I checked Goal's Is Trigger so that the soccer ball can pass through it while triggering an event.
2. I realized that I accidentally assigned _timeText to _pointText. So I fixed the mistake.

### W6
We need to hold a Transform so that we can make the deer follow its position even if it moves. And then we need to call methods on the NavMeshAgent component every frame in the Update() method, so we'd better hold it as a member variable, avoiding getting the component every frame. In the Update() method, we would need to update the destination to the target's current position.

### W7
#### Activity1:
I was responsible for the "General C# coding" category and collaborated with Jelena Song.
[GoogleDoc Link](https://docs.google.com/document/d/1W83E18EwXXSdkScO6OmRU6EeHu7ACjFLijvjSUNB8QA/edit?usp=sharing)
#### Activity2:
Member variables:
- A serialized float variable to store the speed.
- A serialized Cat component as the chase target, which can be assigned in the Inspector.

Methods and what they do:
- Update(): Move toward the Cat every frame.
- public Stop(): Set enabled to false to stop running Update().
- public StartChasing(): Set enabled to true to resume running Update().
- Start(): Call StartChasing() to make the bat start chasing immediately when the game begins.

Partners：Patrick Du, Xiangyi Li, Xingyue Zhang

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
