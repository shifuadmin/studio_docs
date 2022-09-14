# Player rules

Player rulezzzzz!!!! :facepunch:

---

## GetMyTerraPlayerReference

?>![Hover text](player/GetMyTerraPlayerReference.png ':size=80%')

```markdown

Input
- None
Output 
- Reference to the local terra player controller (Each client can get their own player)

```

---

## GetITerraPlayerReference

?>![Hover text](player/GetITerraPlayerReference.png ':size=80%')

```markdown

Input
- Connection ID (comes from Terra client player)
Output 
- Reference to the terra player controller attached to the input connection ID

```

---

## GetPlayerProperties

?>![Hover text](player/GetPlayerProperties.png ':size=80%')

```markdown

Input
- ITerraPlayerController Reference
Outputs
- All changeable properties of the players

In the above example we are getting the referenece to the local player and accesing player velocity
```

---

## GetPlayerSyncProperty

?>![Hover text](player/GetPlayerSyncProperty.png ':size=80%')

```markdown

Inputs 
- ITerraPlayerController Reference
- Property Key (Unique identifier)

Output
- Fetched property

Note : Errors out when the specified key is not present on the player properties
```

!>Check for the log `Found for key = your_key_value and value = fetched_value`


---

## SetPlayerSyncProperty

?>![Hover text](player/SetPlayerSyncProperty.png ':size=80%')

```markdown

Input
- ITerraPlayerController Reference
Output
- All changeable properties of the players

In the above example we are getting the referenece to the local player and accesing player velocity
```

---