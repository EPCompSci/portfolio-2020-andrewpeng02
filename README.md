# iOS-Portfolio
I'm Andrew Peng, and this is my portfolio of all the apps I created as part of my high school iOS App Development class (Fall 2020). I learned about how to create a basic user interface with animations, as well as creating games using Apple's SpriteKit framework. This was mainly a self-taught class, and I learned through online resources such as Apple tutorials or developer blogs/tutorials. I also learned about good git workflows with teams, such as forks, pull requests, and branches.

# iOS Apps
## [Stratagem](https://github.com/Stratagem-Studios/Stratagem)
An alpha game built with SwiftUI, collaberating with Niraj Amin (also developer), Martin Zhou (art), and Jacob Peterson (marketing/music). This game can best be described as a real-time-stratagy game that's easy to learn and fun with friends.

I mainly worked on the city view and database synchronization with Firebase. One of my biggest challenges was deciding how to synchronize player data using a database, and I ended up letting the owner of the city/planets be the singular source of truth. For an actual project, I would've chosen a server-client model next time because player data won't be lost on disconnect, the games are less prone to modification, and it's more clear what data is shared with the different clients. 

I also modified the [SKTiled](https://github.com/mfessenden/SKTiled) framework, which I used to create the city itself. Players can build and destroy buildings on their owned cities, giving them more resources and units. I ended up learning how to navigate an unfamilier framework and learned a lot more about SpriteKit this way. I modified SKTiled to lock the camera on the tilemap boundaries, and I also added an alpha layer to each tile so you can properly tap on the right tile. This is where I spent most of my time coding.


![Menu screen](Stratagem%20screenshots/galaxy.png)
Galaxy view, where you can view all the planets.


![Menu screen](Stratagem%20screenshots/planet.png)
Planet view, where you can drag the planet around and view the cities on that planet.


![Menu screen](Stratagem%20screenshots/city.png)
City view, where you can view your city and build/destroy special buildings. We used the [SKTiled](https://github.com/mfessenden/SKTiled) framework to handle the tilemap. 

![Menu screen](Stratagem%20screenshots/queue.png)
You can create military units in this building, which has a unique responsive UI.


## [Task Manager](https://github.com/andrewpeng02/task-manager-swiftUI/)
![](https://github.com/EPCompSci/portfolio-2020-andrewpeng02/blob/master/Task%20Manager.png)

A basic task manager that supports adding, deleting, and finishing tasks with deadlines. I learned about basic animations and SwiftUI views in this project. Animations were the most challenging because it was not clear when a view would animate, but I eventually figured it out with some trial and error. 

# Other
## [GPU Monitor](https://github.com/andrewpeng02/gpu-monitor-plugin)
![](https://github.com/andrewpeng02/gpu-monitor-plugin/blob/master/gpu-monitor-graphs.png)
A simple plugin for IntelliJ IDEs that shows gpu usage, temperature, and more. Coded in Java. 

# Programming Experience
- Java (2015-)
- Python (2017-)
- Swift (2020-)
