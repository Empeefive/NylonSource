# Nylon 4.5.2
*Created in 2016*
**I am the original developer and first to find these server-sided exploits for Snapchat.**
# Understanding The API

# Bitmoji-Token
The bitmoji token method is a faster and simple method. <br>
Works better with normal item spawning or script use. <br>
*Most common mods/tools use this method* <br>
**Has rights to:** <br>
```
Snapchat API (Avatar/SDK/Marketplace)
Bitmoji API (Avatar/SDK)

CONTROLS ONLY AVATAR DATA AT BITMOJI AND SNAPCHAT
```
# Authorization Bearer
The authorization bearer method is a stronger method and more reliable and stable. <br>
Works best with normal item spawning or custom/paid spawning and script use.
<br>
**Has rights to:** <br>
```
Snapchat API (Avatar/SDK/Marketplace)
Bitmoji API (Avatar/SDK)
Snapchat Account (Login/Logout/Path/Data/Services)
Snapchat Data (Chats/Settings/Binary)

CONTROLS ALL ACCOUNT DATA AND IS SUPER DANGEROUS IF GIVEN OUT
```
# JSON Class Methods
**The class method in Snapchat is *CRUCIAL*, This allows you to actually create changes to the Avatar, This is also the only way to bypass spawning paid items.** <br>
<br>
**Edit**
<br>
**Edit is the simplest form of changing the Snapchat Avatar, It works only with changing items from Bitmoji. Does not work well with paid items. Some items such as Hats or Glasses can be done using the Edit Method since their classes are built using the Edit Method.** <br>
```json
"mode": "edit"
```

**Create**
<br>
**The Create Method is used primarily when you create a brand new Snapchat Avatar. This will put automatic values and traits onto your Avatar and follows a semi-strict rule set. This can work well with normal Avatar edits and with paid/custom edits.** <br>
```json
"mode": "create"
```

**Reset**
<br>
**The Reset Method is the most effective method for bypassing the Snapchat Marketplace. This allows you to Reset your avatar before the marketplace can verify anything. You can reset your avatar to a custom avatar and the system will think it's the generic reset, This is a bad method when it comes to simple or small edits, Should be only used for custom/paid item spawning.** <br>
```json
"mode": "reset"
```
