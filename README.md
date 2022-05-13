# Ecosystem
  ### A Unity engine built ecosystem simulating reinforcement machine learning capabilites through rabbit, bush, and grassland assets
  
  ### All Unity assets are custom made for this project in blender and can be found in Ecosystem\Assets\Ecosystem
  
  #### **The current state of the project:**
  
  At the current state of the project the model only has one rabbit that goes around the grassland asset to retrieve berries from the bush asset with the shortest time possible. The machine learning nueral network would be the rabbits brain in this simulation as it is eventually able to find the most optimal way to the berries.

### Current simulatioin images

**Early rabbit finding berries**

![Rabbit train GIF](https://user-images.githubusercontent.com/34993121/146284361-d1f2ca19-678d-44c2-8522-535876dcb77b.gif)

Although the rabbit sometimes finds a berry bush, it is mostly luck as it mindlessly goes in circles not understanding the assignment.

**Resulting rabbit after many simulations**

![Rabbit GIF](https://user-images.githubusercontent.com/34993121/146282895-7390ef6a-b13f-487f-b689-32b452257f6c.gif)

The behavior of the rabbit developed once the AI learned a clear path to the berries in the bush therefore allowinf the rabbit to quiclky scan a wider area compared to early simulations. This was done by creting a point system based on the time it took for the rabbit to find the berries which taught the rabbit the goal of the simulation based on the resulting score.
