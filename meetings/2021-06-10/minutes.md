# Meeting Minutes - Reactive Foundation TOC

Location: Teleconference
Date:     Thursday, June 10th
Time:     1500 UTC

## Attendance
 - Board
   - James (Acting as secretary) 
   - Roland
   - Oleh
   - Mark
   - Sergei
   - Jonas (Chair)
   - Ben
   - Simon
 - Notable Guests
   - Violeta Georgieva
   - Clement 
   - Sergey
   - Rossen Stoyanchev
   - Micheal Minella (Board Chair)

## Agenda Items
1. Election of a new chair of TOC
1. Report from Education / Support
    - Messanging changes and website change lightbend freelancer will do work with the website changes. See: https://docs.google.com/document/d/19lBWwMI7ZIv1hT9tP00YPEAm-_DxTPUO1zuaMS5atLI/edit#
1. Report from Community / Stewardship
    - Still needs leader.
    - Ben has a document at: https://docs.google.com/document/d/1-VZ9983sGFeCvqCloT-S32bAJxQwx-WB00ajd-Kv1N0/edit?ts=607e98dd
      - Syn Meeting for coediting with James and others. 
1. Rossen on Spring framework change and potential synergies with Reactive Foundation
    - Reactive Streams bridge for servlet containers
    - Oleh: Rsocket could benifit 
    - Clement: We (Quarkus http) have implemented servlets on top of netty
    - Oleh: Helidon (Oracle) would benifit from this as well
    - Current goal is seeking feedback
    - Mark: (Devils advocate) How about having Servlet API and WebSocket specs implement a Reactive Streams-based interface.
    - Ben: Any docs on this? 
1. Will reactive steams ever be depricated? (Important for new spring framework verison (6))
    - Mark: R2DBC is very affected by this but wants to keep using reactive streams
    - Ben: The goals was to make this part of JDK. 
    - Rossen: Java versions in new framework will be higher then Java9
    - Ben: What is the adoption on Flow API?
      - Simon: Very little adoption
      - Clement: Confirmed this
      - Flow is not used in the JDK
      - Sergei: https://github.com/reactive-streams/reactive-streams-jvm/pull/490
      - Roland: We should see Flow as a dead API
      - Sergei: Evolution of JVM may be going to the loom direction? We would assume this will be a death nell for Flow API.
      - Michael: 3 years time from for evaluatons of spring
      - Mark: Best time to revist this is when Java 8 is gone.
1. Reactive Archetecture course for Foundation based on lightbend academy: https://academy.lightbend.com
1. Reports
    1.  Rsocket report
        - Good progress
    1.  Reactive Streams
        - Roland is now the rep
        - PR for https://github.com/reactive-streams/reactive-streams-jvm/pull/490 please have a look
    1.  Blockhound
        - Where should it go? (Offline)
        - Legal work is complete
        - Needs to move.
    1.  R2DBC
        - Wrapping up 0.9m2 (End of July) (Stored procs, display results)
        - JOOQ support up coming
1. Comments
    -  Reactive summit
       -   Needs CFP reviews
       -   Needs more submissions
       -   It runs 7am to 1pm PT , 2pm CET -> 10pm CET


## Election
  Nominations:
    - James Townley
 1. James Townley / Acclaimed 

## Motions
 1. Approval of Agenda / Mark / Simon / Uniamous / Passed
 1. Approval of Minutes / Simon / James / Uniamous / Passed
 1. Adjourn / Roland / Simon / Uniamous / Passed

## Action Items
 1. James and Ben to coedit community doc post in Slack / Responsible / Due Date

## Other Notes
