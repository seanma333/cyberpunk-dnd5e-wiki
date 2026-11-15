---
title: "Hacking"
---

While some might dip their toes in the pool of the internet, others embrace it as a tool, a career, or a weapon. Hackers are skilled at computer programming and traveling the data streams of the telecommunications grid. They use their hacking tools to search for important files, control remote computer systems, and tap phone calls.

With **Hacker's Tools**, a hacker can attempt to hack an electronic device (such as a digital lock, a computer terminal, a camera, or a server) within 5 feet of them as an action if they are able to connect to it either wirelessly or through a data port. If the hacker also has a **[[Gear|Wireless Transceiver]]**, they can wirelessly connect to the device from 60 feet away, as long as they can see it.

## Security Layers

Most systems worth hacking are protected by one or more **security layers**, much like the multi-factor authentication on a corporate account. To gain access to a system, you must get past each of its layers, one at a time and in order.

Gaining access to a system gives you control of **that system only**. Facilities split their security into separate systems, so the lobby doors, the camera grid, the elevators, and the vault are each their own system, with their own layers. Looping the cameras doesn't open the vault.

Each layer has a **type** and a **DC**, which the DM sets based on the quality of the security. Getting past a layer with Hacker's Tools requires a successful check against its DC, which takes an action in combat, or about a minute otherwise.

| Layer Quality | DC | Typical Systems |
| :---- | :---- | :---- |
| Weak | 10 | Cheap consumer tech, old terminals |
| Standard | 15 | Businesses, apartment buildings, city services |
| Hardened | 20 | Corporate offices, security firms, gang data vaults |
| Military | 25 | Megacorp black sites, military networks |

### Layer Types

Instead of hacking a layer, you can bypass it without a check by getting your hands on whatever it's checking for. This is where the rest of the crew comes in.

| Layer Type | What It Checks | Bypass |
| :---- | :---- | :---- |
| **Passcode** | Something you know | Learn the passcode from a person, a note, or a file |
| **Token** | Something you have | Steal, copy, or forge the keycard or authenticator |
| **Biometric** | Something you are | Bring a fingerprint, a retina scan, or the authorized person |
| **Firewall** | Where you're connecting from | Connect from inside the network, such as through a terminal or data port inside the facility, or with a trusted device |

Firewalls are built to keep outsiders out. When you hack a Firewall from outside the network, such as wirelessly from across the street, its DC is 5 higher than normal for its quality. Getting someone inside to plug in is often the safer option, if the crew can get them there.

### Air-Gapped Systems

Some systems, usually the most sensitive ones, aren't connected to any outside network at all. An **air-gapped** system can't be hacked wirelessly or from outside the facility, no matter how skilled the hacker is: you must connect directly through one of its terminals or data ports.

### Example Systems

Some example systems (Firewall DCs shown for hacking from outside):

- **Apartment Door:** Passcode (DC 10)
- **Office Server:** Passcode (DC 15), Firewall (DC 20)
- **Corporate Vault:** Token (DC 20), Biometric (DC 20), Firewall (DC 25)
- **Black Site:** Passcode (DC 20), Token (DC 25), Biometric (DC 25), Firewall (DC 30)

## Trace

Each time you fail a check to get past a layer, the system's **Trace** increases by 1, or by 2 if you fail by 5 or more. All of the systems in the same facility share a single Trace, so a failed check against any of them brings the whole facility closer to raising the alarm. As Trace increases, the facility's security becomes aware of your intrusion and responds:

- **Trace 1 (Alert).** The DCs of all remaining layers in the facility increase by 2.
- **Trace 2 (Alarm).** The system alerts its security to the intrusion and its physical location.
- **Trace 3 (Lockout).** You are locked out of the system until it resets, usually after about an hour. If the system is protected by **ICE** (*Intrusion Countermeasures Electronics*, security software built to actively attack intruders), it also strikes back: you must make a Constitution saving throw against the DC of the layer you failed, taking lightning damage on a failed save, or half as much on a successful one. The damage depends on the layer's quality: 2d10 for Standard, 4d10 for Hardened, or 6d10 for Military.

## Ping

While you have Hacker's Tools and a Wireless Transceiver, you can use an action to ping the devices and implants around you. You learn the location of each humanoid and construct within 60 feet of you, even through walls, until the end of your turn.

Pinging a secured network is noisy. If you ping while inside an area monitored by a secured system, such as a corporate building, that facility's Trace increases by 1, as if you had failed a check against it.
