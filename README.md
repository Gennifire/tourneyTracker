# tourneyTracker

////////////////////////

- Think about design pattern that this could benefit from
- Think about  ui / ux in initial build.
- progress to wpf or website


Design phase 1: Requirements.

- number of players: 
    - variable? 
    - if not complete / even, over players skips to next round.
    - Randomise players to brackets.
    
 - Brackets
    - schedule games?
       - whats system will we use for scheduling?
    - Are rounds able to be played out of order (round 2 finished before round 1, can round 3 begin?)
    - points for winning bracket (0/1: win lose?) (points earned in comp: greater or less than)
 
 - prize option
    - top 3?
    - points based?
    - best sportman etc. 
    - extend to fee option in future.

- FrontEnd Structure: 
    - windows forms for now. (extend to web in future)


- Data storage: 
    - sql 
    - Print to textfile (optional).
    - printable forms.
    - printable brackets

    
- Users: 
    - team for now 
    - extendable:
      - Game admin
      - Team Coach (for team sign ups)
      - individual user (for solo tournament sign ups) 
      
- contact: future extension
    - email/text about tournament.
        - timetable
        - brackets
        
- BIG PICTURE:
    - Concepts:
      - Email
      - Sql
      - interface
      - Custom events
      - Error handling
      - Random Order
      - Sending information
      
      
/////////////////////////

Design phase 2:UI development


- Main Tournament view form
    - Select team / player from matchups
    - view players in tournament.
- Create tournament form
    - Select Team to add to tournament
    - Delete team from tournament.
- Create Team form
    - Add new team
    - Add players to team
    - Delete players from team
    - Read current teams.
- Create Prize form
    - Create prize type (G,S,B, monetary etc.)

////////

Design phase 3: Database design

Basic Uml design

![UML tournament tracker](https://user-images.githubusercontent.com/72698786/200116925-347c7eb6-6eaf-4feb-9988-4c7618b2dd89.png)
