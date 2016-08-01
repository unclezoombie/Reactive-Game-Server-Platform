# Reactive-Game-Server-Platform

### Requirements
Where does an idea to build a Reactive Game Server Platform come from? It comes from a bunch of realworld requirements.
- To build a scalabe, robust, resilient game server with quick response in any cases of load is hard. Even to big companies/studios. Small team/studio can't invest more into this. But they really need a game server for their game with the capabilities mentioned above, because in current stage, a game with weak server side support means weak competitive force. Social has been one of the most important system in a game. I can't imagine a game can be success without Social. The thing is the Social system in a game need strong push from game server. To support millions of players needs a strong game server as well.
- Indie gameers don't have adequate development power on game server. This heavy limited their game features and services.
  Normally indie games don't have a server or have a simple server. They normally go to single player game or be placed in the middle area between single player game and multiplayer game.
- Small team with very few server developer. That means less development force on game server. so the server should be simple and easy to build.
- Server guys in indie team or small studio normally are short and weak. They usually familiar with php, javascript or ROR, seldom they know JEE, rarely they are skilled on enterprise level server development. Almost non of them can built a game server with easy scalability, robustness, reselience. Almost non of them can build a server in reactive way. 

To satisfy above requirements, here I set the goals for Reactive Game Server Platform.
### Golas

- A Big Data ready game server
  * Covered full Big Data pipeline which include data acquision, transformation, analysis, decision/visualization. 
  * Lambda architecture: Fast Data + Batched Data
  * Injection sensor on Client side and Server side.
- Game server built in Reactive way.
  * Support high massive amount of Online Player
  * Good response time
  * High Availability
  * High Scalability
  * Automatic Failover and Self-Healing
  * Naturely Cload ready
  * Non-blocking and asynchronous 
  * Built on Reactive Stream
- A Lambda style game server
  * Scalable Functions
  * Simple API
  * Simple Function Life-cycle
  * built on IOC
- Microservices with Lambda Functions
- Application level load balancing.
  * No dummy network level load balancing
- Extremely developer friendly.
  * No enigmatic concept ( Resilient, Elastic, Asynchronize, Non-blocking etc.)
  * Fill in the blank: a skeleton/frame/structure onto which game developer put "flesh".


### Let's running to the future, hAkker gamers!
