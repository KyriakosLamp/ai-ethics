## Exercise 4 — AI as a Learning Amplifier

# Phase 1: Build Foundation (My Own Thinking First)
```
Devices in a wireless network need a way to pass messages between each other.If two devices 
can’t reach each other directly, messages may “hop” through other devices.Routing protocols decide 
which path the message takes.Some protocols constantly update pathways (faster but uses battery).Others 
find a pathway only when needed (slower but saves battery).

My scenario:
6 smart-home devices in an apartment:
Device	Type
4	small gadgets like lamps or switches
1	home wifi-router (plugged into wall)
1	smartphone 

gadgets don’t send much data → want something quiet and power-saving.
wifi: can handle the “brain work.”
smartphone: it’s mobile but connects strongly to router → no need for complex routing.
```

# Phase 2: Strategic Use of AI (Now I Ask Questions)
```
“What kinds of routing protocols are usually used for low-power sensors?”
“Is there a protocol that works well for devices powered by batteries?”
“What protocol works best when devices don’t move a lot?”
“What protocol is good for fast-moving devices like cars?”

Low-power sensors often use protocols designed to save battery and tolerate weak signals.
Fixed devices (like my home router or traffic lights) can use more stable “always-on” routing.
Moving devices (like vehicles) need special routing that updates quickly.

Iportant lesson:
I realized routing is about power + mobility + stability.
This helped me understand the basics without memorizing complicated protocol names.
```

# Phase 3: Real Application (Smart-City Example)
```
The network I need to design:

1,000 IoT sensors across a city
50 traffic lights
10 emergency vehicles

I approached this with simple everyday logic:
1. 1,000 IoT sensors (tiny, simple, low battery)
    My reasoning:
    They mostly send small pieces of data.
    They sit still (on lampposts, walls, etc.).
    They must last a long time on battery.
    So I choose:
    A low-power, slow-but-steady routing type.
    Why:
    They don’t need speed — they need battery life and just enough reliability.

2. 50 traffic lights (plugged into power)
    My reasoning:
    Traffic lights can’t afford delays (they affect public safety!).
    They have full electrical power.
    They need to talk to each other fast.

    So I choose:
    A routing type that is fast and always maintains good paths.
    Why:
    Fast reactions > energy savings.
    They must stay synchronized.

3. 10 emergency vehicles (move fast)
    My reasoning:
    Cars move quickly → routes must update quickly.
    They need accurate info in real time.
    They can’t rely on slow recalculations.
    So I choose:
    A location-based routing style that uses GPS-like information.
    Why:
    It fits the everyday intuition:
    “Route data based on where the car currently is.”
```
# AI Feedback (Summarized at Beginner Level)
```
    After showing the design to AI, it told me:
    Good that I matched routing choices to battery life, mobility, and speed.
    I should also think about backup plans if GPS fails.
    For 1,000 sensors, the system needs a way to avoid message overload.
    For traffic lights, having redundant paths improves safety.
    This helped refine my thinking without overwhelming me.
```

# Reflection
```
Human judgment vs AI contribution
Human: ~60% (initial reasoning, structure, choices)
AI: ~40% (names of protocols, deeper clarification, identifying issues)
Could I defend my choices without AI?
    yes — because my choices came from logic I understood:
    low power → energy-saving
    fast movement → fast-updating
    safety-critical → stable/fast

Even without protocol names, the reasoning holds.
What will I remember in 6 months?
Choose routing based on power + motion + reliability needs.
Not all networks need the same kind of routing.
Emergency vehicles need fast-updating paths.
Sensors need low-power communication.
```
```
Did AI make me sharper or think for me?
AI helped me by:
Filling in gaps
Giving realistic names
Suggesting failure risks
But I created the logic first, which made the learning stick.
So AI made me sharper, not dependent.
```